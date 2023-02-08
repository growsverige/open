# open specification 0.1
## What is open?

**open**, short for _open energy protocol_, is a set of rules for communication between batteries. The protocol shows which information batteries can send and receive.

**open is an XML dialect**. All open files must adhere to XML 1.0 specification (http://www.w3.org/TR/REC-xml), published at the World Wide Web Consortium (W3C) website.

## Purpose

The purpose of the protocol is to enable communication between batteries as well as transfer of electricity to and from a battery.

## License

open specification 0.1 is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.

## Elements

* storageCapacity
* currentCapacity
* speedOfTransmission
* Type of Connection
* Price
* Terms of Purchase
* License (cc)
* vad batteriet kan ta emot
* vad batteriet kan skicka

* Receiving (när ett batteri tar emot elektricitet)
* Sending (när ett batteri skickar elektricitet)

* Connected to... list of batteries/ resources
* Possible connections
    


### \<storageCapacity\>
#### Description
Total battery capacity specified in kilowatthours (kWh).
#### Example
_1200_

### \<currentCapacity\>
#### Description
Battery's **current** capacity specified in kilowatthours (kWh).
#### Example
_500_
