# SmartContract-VotingSystem

This repository contains a **Ballot** smart contract implemented in Solidity, designed to facilitate a simple and secure voting system on the Ethereum blockchain. This contract enables users to propose candidates, delegate votes, and cast votes with transparency. Once successfully implemented, the voting process can be conducted using a mobile device connected to the blockchain.

## Features

1. The chairperson (owner) can input multiple candidates' names to be voted on by the voters.
2. Each voter is given the **Right to Vote**, and a weight can be assigned to their vote.
3. A voter can only cast a single vote during an election.
4. Candidate names are encrypted using **Base32** throughout the voting process.
5. The winner's name is decrypted and revealed at the end of the election.

## Tools

- **Remix IDE**: [Remix Ethereum IDE](https://remix.ethereum.org/)

## Deployment Steps

1. **Compiling the Code**  
   Compile the smart contract using Remix IDE.

   ![1](https://github.com/user-attachments/assets/186f9a65-0f1d-41c4-b760-93bd3aa641af)

2. **Selecting the Chairperson's Account**  
   Select the account to act as the chairperson for the election.

   ![2](https://github.com/user-attachments/assets/b3fc37d5-9a57-478a-8c9f-621e4e6c4993)

3. **Encrypting Candidates' Names**  
   Convert the names of the candidates to an encrypted format using Base32.

   ![3](https://github.com/user-attachments/assets/6cf239cc-2292-49cf-8173-546f01d3f584)

4. **Adding Candidates to the Contract**  
   Provide the array of encrypted candidates' names to the contract for voting.

   ![4](https://github.com/user-attachments/assets/db5b71ab-69e3-42ab-a374-398a3bc5e673)

5. **Granting Voting Rights**  
   Assign the **Right to Vote** to selected individuals.

   ![6](https://github.com/user-attachments/assets/7e5bca6e-8c04-45ef-911d-eb0498e8ccd5)

6. **Casting Votes**  
   Voters can cast their votes for the desired candidates.

   ![5](https://github.com/user-attachments/assets/5c62b14a-a1af-412f-851e-e586b132fbf3)

7. **Declaring the Winner**  
   The winner is declared, but their name remains encrypted at this stage.

   ![7](https://github.com/user-attachments/assets/646cb510-a983-4be5-8ab9-be96777c54df)

8. **Decrypting the Winner's Name**  
   The winning candidate's name is decrypted and revealed at the end of the election.

   ![8](https://github.com/user-attachments/assets/e9217ac6-a6d4-487b-8fb5-90658dd24ffa)

---

This smart contract enhances the security and transparency of the voting process by utilizing Ethereum blockchain technology, making it highly suitable for digital voting systems.
