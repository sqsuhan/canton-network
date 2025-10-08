# Getting Started with Daml Development on Canton

<p align="center">
  <strong>A step-by-step guide to interacting with the Canton Ledger using the JSON Ledger API</strong>
</p>

## Learning Outcomes
By the end of this quest, you will be able to:
- **Configure and use** the JSON Ledger API.
- **Create and query** Daml ledger contracts.
- **Explain** Daml's role in Canton development.

## Quest Overview
The **Canton Network** enables secure, private, and interoperable multi-party applications by synchronizing state across organizations. **Daml**, the smart contract language powering Canton, defines the business logic for these applications. This quest uses command-line tools like `curl`, `jq`, `grpcurl`, `openssl`, and `xxd` to interact with the Canton Ledger via its JSON Ledger API.

---

## Prerequisites
Before starting, ensure you have the following installed:
- **Daml SDK**: Download and install the latest version from the [Daml SDK installation page](https://docs.daml.com/getting-started/installation.html).
- **Command-line tools**:
  - OpenJDK
  - `jq` (JSON processor)
  - `grpcurl` (gRPC command-line tool)
  - `openssl` (for generating JWTs)
  - `xxd` (for hexadecimal conversions)

Verify installations by running:
```bash
daml version
java -version
jq --version
grpcurl -version
openssl version
xxd --version
