# Project Structure Document

## Technologies Used
1. **Solidity**: The smart contract is written in Solidity, a programming language for writing smart contracts on the Ethereum blockchain.
2. **React**: The frontend components are built using React, as evidenced by the JSX files in the `Components` directory.
3. **Next.js**: The project structure indicates the use of Next.js for server-side rendering and routing, as seen in the `pages` directory.
4. **Hardhat**: The presence of the `hardhat.config.js` file suggests that Hardhat is used for Ethereum development, including testing and deploying smart contracts.

## Smart Contracts
- **VotingOrganization Contract**:
  - **Owner Management**: The contract has an owner who can manage voters and candidates.
  - **Voter and Candidate Registration**: Functions to register voters and candidates, with approval mechanisms.
  - **Voting Mechanism**: Allows approved voters to cast votes for candidates during a specified voting period.
  - **Data Structures**: Utilizes structs for `Voter` and `Candidate`, along with mappings to manage their states.
  - **Voting Period Management**: Functions to set and check the voting period.
  - **Results Calculation**: Functions to retrieve voting results and determine the winning candidate.

## Components Overview
- **LegalDocs**: Contains components for displaying legal documentation related to the voting process, including terms of service and privacy policies.
- **Market**: Components related to market functionalities, possibly for trading or voting-related activities.
- **Home**: Components that likely serve as the landing page and provide essential information about the voting process.

## Next Steps
- Document the findings in a structured format for sharing or further development.
