# Travol prototype

## GDS

- Nodes
  - Travel agents
  - Airlines (maybe acting like index nodes?)
- Static inventory
  - Available in the DHT
- Last ticket check to go to the airline

- Flight 
  - Multiple fares with seat availability
- Simulate a node that confirms that you made the payment as a requirement for the airline to sign your ticket
  - Investigate how to integrate payment reviewing

User stories
- Search for flight
  - Check availability
- Book one of the fares of the flights
  - Airline asks for payment
  - Airline mints ticket

Frontends:
- Travel agency having to Book
- Airline detailed information about inventory

- Script to upload dummy data on network start

Nice to have:
- Airline to be validated by Travol (roles module)