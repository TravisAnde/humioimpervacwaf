# Imperva CWAF
This package contains a parser and three dashboards. within the dashboard there are about 30 different searches/queries that can be used to manipulate the data ingested from Imperva Cloud Web Application Firewall.

# Release Notes
v0.1.0 - Initial release

# Package Contents
## Parsers
- cef

## Dashboards
- Imperva Account Overview
- Imperva Search
- Imperva WAF Overview

# Use Case:
SecOps

# Technology Vendor:
Imperva

# Support
Package creator doesn't current offer support for this package.

# Dependencies
The package uses logs from the following log type from Imperva : CEF. Please make sure unencrypted CEF is selected when configuring the log forwarding from Imperva.
Package uses 2 csv files for country code matching and severity level matching which can be retrieved from this url: https://www.github.com/

# Installation
The preferred option for sending logs from Imperva to Humio is to choose Amazon S3 (available under the Account Management in the Imperva Console). 
Log Shipping from S3 to Humio can be done in multiple ways, please see the Humio documentation to ensure the right option is selected for you.

Please ensure logs are using the package parser 'cef' and csv files are imported per dependencies.

