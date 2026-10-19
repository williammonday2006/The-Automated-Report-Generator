# Phase 1
I created the abstract VehicleReport class with a final template method. The base class controls the workflow and calls the subclass's formatting method, demonstrating the Hollywood Principle.

# Phase 2: Concrete Vehicle Reports

I created TruckReport and BikeReport, each with its own formatting method. Both use the inherited generateReport() method to run the shared workflow in the correct order.