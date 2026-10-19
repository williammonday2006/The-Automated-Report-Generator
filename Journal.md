# Phase 1
I created the abstract VehicleReport class with a final template method. The base class controls the workflow and calls the subclass's formatting method, demonstrating the Hollywood Principle.

# Phase 2
I created TruckReport and BikeReport, each with its own formatting method. Both use the inherited generateReport() method to run the shared workflow in the correct order.

# Phase 3
I added a boolean hook that lets trucks opt into maintenance checks while bikes use the default behavior and skip them. This makes optional behavior easy to customize without changing the overall workflow.