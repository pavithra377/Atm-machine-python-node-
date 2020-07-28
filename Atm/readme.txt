Statement: Develop functionality for an ATM machine.


Minimum Requirement  :  

1. Create an API to register a user's card (8-digits) and ATM Pin (4-digits)

2. Create an authentication API to validate the user by 8-digit card number and 4-digit ATM pin.

3. Create an API to deposit the money in the user's account.

4. Create an API to withdraw the money from the user's bank account.

 

NOTE: Keep the following things in considerations:

1- ATM Machine should always give the least number of notes (example: if the user withdraw Rs 2500, the ATM machine should give 1 note of Rs 2000 and 1 note of Rs 500)

2- The number of notes should be reduced/increase in ATM on every transaction.

3- The user cannot withdraw more than Rs 20,000 in one transaction.


Key skills we are checking are:
- Can the person create API as required
- Can the person make API requests and process the result
- Can the person make complicated logics.

HTTP Header :  

access-control-allow-headers: Origin, X-Requested-With, Content-Type, Accept
access-control-allow-methods: GET, POST, PUT
access-control-allow-origin:*
server: cloudflare-nginx

 