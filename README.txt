(1) Object are scanned one bye one from Serialized Files.
(2) Scanned Objects are stored in an ArrayList for each file (passengers, managers, drivers, trips, tickets, etc...).
(3) Changes are applied to Objects of different types stored in the memory.
(4) Objects can be dynamically added or removed to the ArrayList in case of:
- Registration of new accounts
- Addition of new Trips
- Removal of tickets for a passenger
- etc...
(5) The ArrayList is written to the file to store the new data in the Serialized File of Objects.