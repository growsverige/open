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
* connectionType
* price
* termsOfPurchase
* license
* receiving
* sending
* connectedTo
    


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


 receiving (när ett batteri tar emot elektricitet)
* sending (när ett batteri skickar elektricitet)
* connectedTo list of batteries/ resources
