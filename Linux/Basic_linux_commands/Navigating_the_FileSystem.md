# Basic Linux Commands Guide

Welcome to the **Basic Linux Commands Guide**! This document provides a comprehensive overview of essential Linux commands, complete with examples to help you navigate, manage, and interact with the Linux environment effectively.

---

## Navigating the File System

### `ls`: List Directory Contents
- **Purpose**: Display the contents of a directory.
- **Syntax**:
  ```bash
  ls [options] [directory]
  ```
- **Examples**:
  ```bash
  ls          # List files and directories
  ls -l       # List with detailed information
  ls -a       # Show hidden files
  ```

### `cd`: Change Directory
- **Purpose**: Move between directories.
- **Syntax**:
  ```bash
  cd [directory]
  ```
- **Examples**:
  ```bash
  cd /home/user/Documents  # Navigate to a specific path
  cd ..                   # Move up one level
  cd ~                    # Go to the home directory
  ```

### `pwd`: Print Working Directory
- **Purpose**: Display the current directory path.
- **Syntax**:
  ```bash
  pwd
  ```
- **Example**:
  ```bash
  pwd  # Outputs: /home/user/Documents
  ```
