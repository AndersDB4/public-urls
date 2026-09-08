# Privacy Notice

Last updated: 8 September 2026

## About this application

This notice describes a personal, non-commercial bank-mcp setup operated by AndersDB4 in Denmark. Its purpose is to help the operator review and understand their own finances. It is not offered as a service for collecting other people’s bank data.

## Information processed

With the account holder’s authorisation, the application can retrieve information made available by the bank through Enable Banking, including:

- Account identifiers, account names, and currencies.
- Account balances.
- Transaction dates, amounts, descriptions, and available merchant or counterparty information.

The application also uses connection details, such as application identifiers, authorisation session information, and a locally stored private key, to maintain the bank connection.

## How information is used

Information is used to answer the operator’s questions about balances, transactions, spending, and other aspects of their personal finances. The application is intended for read-only access; it does not initiate payments or transfer funds.

Bank authentication takes place through the bank’s authorisation flow. Banking passwords and authentication codes should not be entered into AI conversations or published in this repository.

## Services involved and data sharing

- **The bank** holds the original account records and authorises access to selected accounts.
- **Enable Banking** provides the connection used to retrieve authorised bank information.
- **The local bank-mcp application** processes the retrieved information and returns it to the connected AI client.
- **OpenAI** may receive bank information returned by the application when the operator uses an OpenAI assistant to retrieve or analyse it. This can include transaction details and other information included in tool results, not only a final summary.

Each external service processes information under its applicable terms, privacy notices, and account settings. This notice does not change those policies or promise a particular retention period or processing location for those services.

The purpose of this personal setup is financial analysis for its operator, not advertising, selling bank information, or publishing financial records.

## Storage and retention

Bank-mcp stores connection configuration locally on the operator’s computer. Depending on the software version and configuration, retrieved information may also be held in memory, caches, saved outputs, or conversation history.

This setup does not specify a single automatic deletion period. Local files and saved outputs remain subject to the operator’s storage and deletion practices. Information sent to OpenAI or other providers is subject to those services’ retention policies and available data controls.

## Control and stopping access

The operator chooses which accounts to authorise and may stop using the application at any time. They can disconnect bank-mcp from the AI client and use the bank’s or Enable Banking’s available controls to revoke access. Local connection files, caches, and saved outputs can be removed separately when no longer needed.

Revoking access prevents further retrieval under that authorisation; it does not automatically erase previously retrieved information or existing AI conversations. Those must be managed through the relevant local files or service controls.

## This public repository

This repository publishes the application’s privacy notice and terms. Bank records, credentials, private keys, and authorisation URLs must not be committed to it or posted in public issues. GitHub processes visits to this repository under its own privacy statement.

## Contact and updates

For non-sensitive questions about this setup, contact the operator through the [repository’s Issues page](https://github.com/AndersDB4/public-urls/issues). Do not include financial information, credentials, or other private details in public messages.

This notice may be updated when the setup changes. The date above identifies the latest revision.
