Getting Started with Daml Development on Canton
Learning Outcomes
By the end of this quest, you will be able to:

Configure and use the JSON Ledger API.
Create and query Daml ledger contracts.
Explain Daml's role in Canton development.
Quest Details
This quest will guide you through interacting with the Canton Ledger using its JSON Ledger API from the command line, particularly with tools like curl. The Canton Network is designed to enable multi-party applications by securely and privately synchronizing state across organizations. Fundamentally, Daml is the smart contract language powering Canton, defining secure and interoperable business logic for these applications.

Prerequisites
Install the Daml SDK
Install essential command-line tools (OpenJDK, jq, grpcurl, openssl, xxd)
Quest Steps
Install the Daml SDK: Follow the instructions for your operating system to install the latest Daml SDK.
Create the Daml Model: Create a new Daml model with a template named Asset.
Compile the Daml Model: Compile the Daml model into a .dar file.
Start Canton Sandbox: Launch the Canton sandbox and enable the JSON Ledger API.
Start the HTTP JSON API Service: Create a configuration file and start the HTTP JSON API Service.
Generate a JSON Web Token (JWT): Generate a JWT with the required claims for the "Alice" party.
Verify JSON API Status: Check the readiness of the HTTP JSON API Service.
Submit Contract Creation Command: Create a new Asset contract on the ledger.
Run the Query Command: Query the ledger to verify the created contract.
Deliverables
Take a screenshot of your terminal showing the successful completion of the quest steps.
Conclusion
Congratulations on completing this quest! You have learned how to configure and use the Canton Ledger's JSON Ledger API, create and query Daml contracts, and understand Daml's role in Canton development. Continue your learning journey by exploring the supplemental guides on Daml programming and ledger interactions.






