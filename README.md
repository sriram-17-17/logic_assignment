# logic_assignment
Logic in Computer Science (CS F214) Assignment
LICS Assignment Problem Statement

Library Membership Issuance System

You are required to model a library membership issuance system in UPPAAL based on the following specifications.

Every time the user wants to issue a book or buy a membership, s/he should sign in to the system using their email ID.

For each sign-in, the system should authenticate the details. In case the authentication fails, users have to check their credentials and sign in again.

On signing-in, the user has two options:

Buy a membership card

View membership details/history

The membership card is of 2 types: Gold and Platinum, with different rates. Users can only purchase one type of membership at a time (in one transaction).

If the membership card is bought, the payment should be made before exiting the system. There is only one mode of payment i.e. via Credit/Debit card.

Users should log out of the system after every transaction.

You have to additionally model the payment system from the bank’s point of view. The transaction will only be approved by the bank if there is sufficient balance in the account.

Additionally, verify any 2 safety and liveness properties each on this template using UPPAAL. Clearly state those properties in your submission.

Submission Requirements

A PDF file containing a detailed description of the model you make. State all the assumptions you make clearly. Also, give justification for all your assumptions. The assumptions have to be reasonable as per the problem statement and not vague. Clearly state the properties you are verifying.

XML file exported from UPPAL for the model you build. We will run your model on our machine using the XML file you submit, and marks will be awarded accordingly.

.txt file containing information about your team members

Put all three in a single .zip file and upload.
