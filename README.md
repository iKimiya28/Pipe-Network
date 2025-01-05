# Sonaric Node Setup Guide

A step-by-step guide to installing and managing a Sonaric node.

## Table of Contents
1. [Minimum System Requirements](#minimum-system-requirements)
2. [Installing Dependencies](#installing-dependencies)
3. [Installing the Node](#installing-the-node)
4. [Checking Node Status or Version](#checking-node-status-or-version)
5. [Updating the Node](#updating-the-node)
6. [Additional Notes](#additional-notes)

---

## 1. Minimum System Requirements

Ensure your system meets the following minimum requirements:

| **Resource** | **Requirement** |
|--------------|------------------|
| RAM          | 2 GB            |
| CPU          | 2 Cores         |

---

## 2. Installing Dependencies

Run the following commands to update your packages and install the necessary dependencies:

### Update Packages
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install curl make wget clang net-tools pkg-config libssl-dev build-essential jq lz4 gcc unzip snapd -y
