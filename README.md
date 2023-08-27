# OpenHIM (Open Health Information Mediator)

![OpenHIM Logo](http://openhim.org/img/openhim-logo-green.svg)

The OpenHIM orchestrates the flow of health information within a health information system. It acts as a middleware component to ensure secure and reliable data transmission between different systems.

## Features

- **Routing**: Directs incoming API requests to appropriate services.
- **Authentication & Authorization**: Ensures that API requests are from known, authorized sources.
- **Logging**: Logs all transactions, providing an audit trail.
- **Transformation**: Transforms message content as needed.
- **Error Handling**: Ensures errors are caught, logged, and notifications are sent.
- **Standards Compliant**: Supports health informatics standards like HL7.

## Getting Started

### Prerequisites

- Node.js (>=14.x)
- MongoDB (>=4.x)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/openhim/openhim-core.git
