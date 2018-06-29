# Legal-Contract-Dapp
Blockchain application made to automate worker-manager relationship, developed using truffle-ethereum framework 

Overview

Creating a Dapp for automating the Client-Client interaction in hassle-free and efficient way.The smart contracts are used for entering client details and the lawyer can verify if the details and conditions are correct or not.An authentication mechanism can also be implemented in this.Both clients agrees upon a particular agreement and lawyer verifies this and deploys the contract on-to blockchain.After its been deployed the progress can be overviewed by all the parties involved.Since the contract is immutable and transparent no one can tamper with the document or contract that everyone agreed upon.

 Goals
 
1. Automating Clients-Lawyer interaction
2. No disputes between clients as everything is automated
3. Lawyer intervention can also be minimised
4. Making the entire process hassle-free

Attributes

Clients(two):

1. Name
2. Address
3. Id proof
4. Pan Card Number
5. Occupation

Lawyer

1. Name
2. Address
3. Id proof

Contract

1. Name
2. Date
3. Work Details
4. Conditions
5. Violation conditions

States of Smart-Contract

1. INITIALISED
2. VERIFICATION PENDING
3. WORK IN PROGRESS
4. PENDING FOR APPROVAL
5. NOT COMPLETED
6. COMPLETED SUCCESSFULLY

Working
 
1. Two clients are involved in this process- a worker and manager.Manager enters his personal details and the work details and then publish it. State of smart-contract changed to ‘INITIALISED’.
2. Worker then enters his personal details and willingness to work and then submit it. State of smart-contract changed to ‘PENDING FOR VERIFICATION’ .
3. Lawyer verifies the published contract and check if the details are correct are not.If the entered details are correct then the lawyer deploys the contract into blockchain.State of smart-contract changed to ‘WORK IN PROGRESS’ .
4. Worker can start doing his work and state will be remained in ‘WORK IN PROGRESS’
5. After the worker finished his work in the time previously mentioned he can report that in smart contract and the state of smart-contract changed to ‘PENDING FOR APPROVAL’ .
6. Then the lawyer checks if the work has been completed and if it’s sufficient then he approves the work.State of smart-contract changed to ‘COMPLETED SUCCESSFULLY’.
7. After this, a notification is been sent to the manager stating the work has been done successfully.
8. This automatic notification can be changed with an instance of money-transfer from escrow where the fee for worker is transferred to his account, in later stages.
9. If the contract is violated then notification stating work not done will be send to worker.State of smart-contract changed to ‘NOT COMPLETED’.
10.This automatic money-transfer after the completion of work can be used to avoid usual disputes between manager and worker, after the work has been completed.

