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
```

---

## 3. Installing the Node

Install the Sonaric node using the official installation script:
```bash
sh -c "$(curl -fsSL https://get.sonaric.xyz/scripts/install.sh)"
```

**Note**: After installation, your node will automatically start running in the background.

---

## 4. Checking Node Status or Version

To verify that your node is running or to check the installed version, use the following command:
```bash
sonaric node-info
```

---

## 5. Updating the Node

### Step 1: Update System Packages
```bash
apt-get update
```

### Step 2: Install the Latest Node Packages
```bash
apt-get install sonaricd sonaric
```

### Step 3: Reinstall the Node (if necessary)
If needed, you can reinstall the node using the official installation script:
```bash
sh -c "$(curl -fsSL https://get.sonaric.xyz/scripts/install.sh)"
```

---

## 6. Additional Notes

- **Discord Role**: After successfully setting up your node, ensure you claim the **Operator** role on [Discord](https://discord.gg/eg9PNeDAuE).
- For troubleshooting or additional setup guidance, refer to the official Guide at https://docs.sonaric.xyz/installation/vps.html#installing-on-vps 
