# open specification 0.1
## What is open?

**open**, short for _open energy protocol_, is a set of rules for communication between batteries. It shows which information batteries send and receive when they communicate.

**open is an XML dialect**. All open files must adhere to XML 1.0 specification (http://www.w3.org/TR/REC-xml), published at the World Wide Web Consortium (W3C) website.

## Elements
### Status
* storageCapacity
* currentCapacity
* Speed of Transmission
* Type of Connection
* Price
* Terms of Purchase
* License (cc)
* vad batteriet kan ta emot
* vad batteriet kan skicka
### Transfer
* Receiving (när ett batteri tar emot elektricitet)
* Sending (när ett batteri skickar elektricitet)
### Connection
* Connected to... list of batteries/ resources
* Possible connections


### storageCapacity
#### Description
Total battery capacity specified in kilowatthours (kWh).
#### Example
_1200_

### currentCapacity
#### Description
Battery's **current** capacity specified in kilowatthours (kWh).
#### Example
_500_
