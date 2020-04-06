# _Address Book_

#### _Epicodus Project, Creating an Address Book with Objects and Constructors April 6, 2020_

#### By _**Jessica Hvozdovich**_

## Description

_This exercise acts as an introductory lesson in JavaScript objects, constructors, and prototypes. It allows contacts with the same properties to be added to an address book efficiently._

## Setup/Installation Requirements

* Clone this repository.
* Navigate to index.html file.
* Right click and open in the browser of your choice.

* Alternatively, open the webpage at https://jhvozdovich.github.io/address-book/


## Known Bugs

There are no known bugs at the time of this update.

## Support and contact details

If you have any suggestions or questions please email me at jhvozdovich@gmail.com.

## Technologies Used

HTML
CSS
Bootstrap
Git and GitHub
JavaScript
jQuery

### Specs
| Spec | Input | Output |
| :------------- | :------------- | :------------- |
| **Build Contact constructor** | User Input:"jessica" | Output: "Contact {firstName: "Jessica", lastName: "Hvozdovich", phoneNumber: "555-555-5555"}" |
| **fullName method for Contacts** | User Input:"jessica.fullName();" | Output: "Jessica Hvozdovich" |
| **Build AddressBook constructor** | User Input:"addressBook" | Output: "contacts: []" |
| **Add AddressBook method to addContact** | User Input:"addressBook.addContact(jessica)" | Output: "[jessica]]" |
| **Add AddressBook method to addId** | User Input:"addressBook.addContact(jessica)" | Output: "jessica.id = 1" |
| **Add AddressBook method to findContact** | User Input:"addressBook.findContact(1)" | Output: "Contact {firstName: "Jessica", lastName: "Hvozdovich", phoneNumber: "555-555-5555", id: 1}" |
| **Add AddressBook method to deleteContact** | User Input:"addressBook.deleteContact(1)" | Output: "undefined" |
| **Add AddressBook method to updateContact** | User Input:"Contact.updateContact(1, "joe", "shmoe", "777-777-777")" | Output: "addressBook[1] ==> Contact {firstName: "Joe", lastName: "Shmoe", phoneNumber: "777-777-7777", id: 1}" |

### License

This software is licensed under the MIT license.

Copyright (c) 2020 **_Jessica Hvozdovich_**