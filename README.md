<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Getting Started with Daml Development on Canton</title>
</head>
<body>
    <h1>Getting Started with Daml Development on Canton</h1>

    <h2>Learning Outcomes</h2>
    <ul>
        <li>Configure and use the JSON Ledger API.</li>
        <li>Create and query Daml ledger contracts.</li>
        <li>Explain Daml's role in Canton development.</li>
    </ul>

    <h2>Quest Details</h2>
    <p>This quest will guide you through interacting with the Canton Ledger using its JSON Ledger API from the command line, particularly with tools like <code>curl</code>. The Canton Network is designed to enable multi-party applications by securely and privately synchronizing state across organizations. Fundamentally, Daml is the smart contract language powering Canton, defining secure and interoperable business logic for these applications.</p>

    <h2>Prerequisites</h2>
    <ul>
        <li>Install the Daml SDK</li>
        <li>Install essential command-line tools (OpenJDK, jq, grpcurl, openssl, xxd)</li>
    </ul>

    <h2>Quest Steps</h2>
    <ol>
        <li>Install the Daml SDK: Follow the instructions for your operating system to install the latest Daml SDK.</li>
        <li>Create the Daml Model: Create a new Daml model with a template named <code>Asset</code>.</li>
        <li>Compile the Daml Model: Compile the Daml model into a <code>.dar</code> file.</li>
        <li>Start Canton Sandbox: Launch the Canton sandbox and enable the JSON Ledger API.</li>
        <li>Start the HTTP JSON API Service: Create a configuration file and start the HTTP JSON API Service.</li>
        <li>Generate a JSON Web Token (JWT): Generate a JWT with the required claims for the "Alice" party.</li>
        <li>Verify JSON API Status: Check the readiness of the HTTP JSON API Service.</li>
        <li>Submit Contract Creation Command: Create a new Asset contract on the ledger.</li>
        <li>Run the Query Command: Query the ledger to verify the created contract.</li>
    </ol>

    <h2>Deliverables</h2>
    <p>Take a screenshot of your terminal showing the successful completion of the quest steps.</p>

    <h2>Conclusion</h2>
    <p>Congratulations on completing this quest! You have learned how to configure and use the Canton Ledger's JSON Ledger API, create and query Daml contracts, and understand Daml's role in Canton development. Continue your learning journey by exploring the supplemental guides on Daml programming and ledger interactions.</p>
</body>
</html>
