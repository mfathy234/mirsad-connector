# Mirsad connector

Downloads of the **Mirsad connector**: a small service you run inside your own network so the Mirsad AI assistant can
read your database or REST API without opening any inbound port. It connects outbound over HTTPS, runs only guarded
read-only SQL and GET requests, and keeps your connection strings and API keys on your machine.

This repository holds **releases only**. Get the installer from the Mirsad console (*Getting started → Connect your
data*): it builds an install script with your settings filled in, in your browser, and downloads the connector from the
[releases](../../releases) here.

| Platform | Download |
|---|---|
| Windows (x64, no .NET install needed) | `mirsad-connector-win-x64.zip` on the [latest release](../../releases/latest), with its `.sha256` |
| Docker / Linux | `docker pull ghcr.io/mfathy234/mirsad-connector:latest` |

Each release lists its SHA-256 checksum; the generated installer verifies it before installing.
