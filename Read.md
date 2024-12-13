# Decentralized Quiz Application Task

## Objective
Build a decentralized quiz application using **Solidity**, **Hardhat**, **Web3.js/ethers.js**, and **React.js**. The application should include payment functionality and quiz interaction features.

---

## Task Details

### 1. **Smart Contract (Solidity)**
- **Quiz Management**:
  - Store quiz questions with the following fields:
    - `questionText` (string): The question text.
    - `options` (array of strings): The multiple-choice answers.
    - `correctOption` (integer): Index of the correct answer.
  - Track user scores based on their answers.

- **Payment Integration**:
  - Require a fee in **ETH** to join the quiz.
  - Convert the payment from **ETH** to **USDT** (use a mock function or Chainlink price feed).
  - Emit events for:
    - Payment confirmation.
    - Quiz participation and answer submissions.

---

### 2. **Frontend (React.js)**
- **Features**:
  - Wallet connection via MetaMask.
  - Display quiz questions fetched from the smart contract.
  - Allow users to select and submit answers.
  - Require payment in ETH before accessing the quiz.
  - Display final score after quiz completion.

---

### 3. **Technical Requirements**
- **Blockchain Interaction**:
  - Use Web3.js or ethers.js for wallet and contract interactions.
  - Deploy the smart contract using Hardhat.

- **Validation**:
  - Ensure proper validation:
    - Users cannot access the quiz without payment.
    - Prevent duplicate submissions for the same question.

- **Optional Enhancements**:
  - Use Chainlink to fetch the ETH-to-USDT price feed for real-time conversion.
  - Add loading indicators for blockchain transactions.

---

## Deliverables
1. **Smart Contract**:
   - Deployed on an Ethereum test network (e.g., Goerli).
   - Include contract source code and ABI.

2. **Frontend**:
   - React.js application for interacting with the smart contract.

3. **GitHub Repository**:
   - Include the following in the repository:
     - Smart contract code in the `/contracts` directory.
     - Frontend code in the `/frontend` directory.
     - A `README.md` file with instructions to:
       - Deploy the smart contract.
       - Run the frontend locally.
       - Test the application.

4. **Documentation**:
   - Include sample questions for the quiz.
   - Provide clear instructions to set up and test the application.

---

## Submission
- Submit the link to your GitHub repository containing all code and instructions.
- Include a short demo video or screenshots of the working application (optional).

---

We’re excited to see your work! If you have any questions, feel free to reach out.
