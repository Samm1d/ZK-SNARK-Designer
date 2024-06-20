# ZK-SNARK-Designer

## Tools Used

This project utilizes the hardhat-circom template for creating, compiling, and generating proofs for circuits. This toolchain is particularly useful for circuit design and verification tasks.

### Steps with hardhat-circom:

1. **Circuit Design:** Write your circuit implementation in `circuit.circom`.
2. **Compilation:** Compile the circuit to generate circuit intermediaries.
3. **Proof Generation:** Generate a proof using specific inputs (e.g., A=0, B=1).
4. **Verifier Deployment:** Deploy a solidity verifier contract to either Sepolia or Mumbai Testnet.
5. **Verification:** Call the `verifyProof()` method on the deployed verifier contract and assert that the output is `true`.

## Project Rubric

To successfully complete the Final Challenge, ensure the following steps are completed:

1. **Write a Correct `circuit.circom` Implementation:**
   - Implement the circuit logic accurately in `circuit.circom`.

2. **Compile the Circuit:**
   - Use the hardhat-circom template to compile your circuit.

3. **Generate a Proof:**
   - Generate a proof using the specific inputs A=0 and B=1 (adjust as needed based on your circuit design).

4. **Deploy a Solidity Verifier:**
   - Deploy the generated verifier contract to Sepolia or Mumbai Testnet.

5. **Verify the Proof:**
   - Call the `verifyProof()` method on the deployed verifier contract.
   - Assert that the output is `true`, indicating successful verification of the proof.

## Additional Notes

- Ensure all dependencies required by hardhat-circom are installed and configured properly.
- Modify input values and contract deployment specifics according to your circuit design and testing requirements.

By following these steps and guidelines, you should be able to complete the Final Challenge successfully. For any issues or questions, refer to the documentation provided by hardhat-circom or consult the project mentors.
