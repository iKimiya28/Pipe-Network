# Sonaric Node Setup Guide

This guide outlines the steps to set up and run a Sonaric node on your system.

## Table of Contents
1. [Dependencies](#dependencies)
2. [Installing the Sonaric Node](#installing-the-sonaric-node)
3. [Checking Node Status](#checking-node-status)

---

## 1. Dependencies

Before installing the Sonaric node, ensure your system has the required dependencies.

### Update Packages
Run the following command to update existing packages:
```bash
sudo apt update && sudo apt upgrade -y
Install Required Tools
Install the necessary dependencies:

bash
Copy code
sudo apt install curl make wget clang net-tools pkg-config libssl-dev build-essential jq lz4 gcc unzip snapd -y
