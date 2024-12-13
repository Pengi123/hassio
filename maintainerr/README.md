# Maintainerr Add-On for Home Assistant

[![GitHub stars](https://img.shields.io/github/stars/jorenn92/Maintainerr.svg?style=flat-square)](https://github.com/jorenn92/Maintainerr)
[![GitHub issues](https://img.shields.io/github/issues/jorenn92/Maintainerr.svg?style=flat-square)](https://github.com/jorenn92/Maintainerr/issues)

This is a Home Assistant add-on that integrates [Maintainerr](https://github.com/jorenn92/Maintainerr), a tool to help you manage and update Docker containers, directly into your Home Assistant environment.

## About

Maintainerr helps you:
- View Docker containers and their statuses.
- Pull and update images easily.
- Manage container lifecycle from a web interface.

## Installation

1. In Home Assistant, go to **Settings > Add-ons > Add-on Store**.
2. Click on the three-dot menu in the top-right corner and select **Repositories**.
3. Add this repository URL: `https://github.com/<your-username>/hassio-addons`
4. Find the "Maintainerr" add-on in the list under your newly added repository.
5. Click **Install**.

## Configuration

No special configuration is required by default. The add-on runs on port `3000`, as per the official Maintainerr documentation.

## Access

After starting the add-on, you can access the web interface at:

