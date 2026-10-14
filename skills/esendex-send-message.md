---
name: esendex-send-message
description: Send a message using the Message Dispatcher API.
api: openapi/esendex-openapi.json
operations:
- TitanCustomerUpgradesEmulationEsendexUseCasesSendMessageApiEsendexSendMessageV10Endpoint
- TitanCustomerUpgradesEmulationEsendexUseCasesSendMessageApiEsendexSendMessageV11Endpoint
generated: '2026-10-14'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/esendex-openapi.json ; every operationId checked against the contract
---

# esendex-send-message

Send a message using the Message Dispatcher API.

## Steps

1. 1. Call `TitanCustomerUpgradesEmulationEsendexUseCasesSendMessageApiEsendexSendMessageV10Endpoint` with the required request body fields as defined in the contract.
2. 2. Call `TitanCustomerUpgradesEmulationEsendexUseCasesSendMessageApiEsendexSendMessageV11Endpoint` with the required request body fields as defined in the contract.

## Rules

- Authentication: Include a JWT bearer token in the `Authorization` header (`Bearer <token>`).
- Both endpoints are POST requests; ensure the request body conforms to the schema defined for each version.
