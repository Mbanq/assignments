# Preface
This assignment doesn't have one right solution.
If you were able to provide a possible solution - you already did well.

The main purpose of this assignment is for you and us to understand whether we can work together.

# General Description
We'd like you to propose a design for a mobile bank in form of a clickable prototype.

# Purpose
Purpose of the mobile banking app is to provide the functionality of the bank through a mobile app, such as payments, card management (blocking/unblocking), user profile management etc.

Taking into account a short time of the assignment execution, the functionality you have to propose the design for will be very limited.

Below we'll describe the functionality of the prototype.

# Functionality
In order to be able to execute the task within two days, we'll limit the functionality to 3 main functions:

1. Transactions list
2. Money transfers
3. User profile management

## Transactions list
Every transaction consists of following elements:
* Recipient name
* Recipient's bank account data
* Sender's bank account data
* Amount of the transaction
* Subject of the transaction

Transactions list has to support following functions:
* Order transactions by date
* Order transactions by amount
* Full-text search
* Create transfer from a transaction

## Money transfer
Mobile banking app should support following money transfer options:
* Transfer money to associated savings account (no need to fill out the recipient details - savings account is in the same bank)
* Money transfer inside of the same bank
* Money transfers to other banks (bank account details to use: [IBAN](https://en.wikipedia.org/wiki/International_Bank_Account_Number), [BIC](https://en.wikipedia.org/wiki/ISO_9362))
* Money transfers to private person by using her email address, mobile phone number etc.

## User profile management
A user has to be able to perform following operations on her personal data from the mobile app (all operatinos have to be confirmed with the app's password/PIN):
* Change of the user's address
* Password/PIN change
* Simplified request to the bank's customer support (client requests bank to contact her)

# Notes
* Decision about which mobile operating system you would like to create a design for is up to you
* Please use the color scheme of [Mbanq](http://mbanq.com)
