# sysopctl - System Resource Management Tool

## Overview

`sysopctl` is a custom Linux command-line tool designed to enhance system administration capabilities by allowing users to manage services, monitor system resources, and analyze system logs efficiently. This tool provides simplified commands for system management and monitoring, making it ideal for both beginner and advanced users.

## Features

- **List Running Services:** View all active system services.
- **Manage Services:** Start and stop services easily.
- **View System Load:** Check the current load on the system.
- **Check Disk Usage:** View disk usage statistics by partition.
- **Monitor Processes:** Real-time monitoring of system processes.
- **Analyze Logs:** Get a summary of recent critical system log entries.
- **Backup System Files:** Easily back up files using the built-in backup command.
- **Version and Help Options:** Access documentation and version info from the command line.

## Installation

### Steps to Install

1. Clone the repository:
    ```bash
    git clone <private-repo-url>
    cd sysopctl
    ```

2. Make the script executable:
    ```bash
    chmod +x sysopctl
    ```

3. Move the script to a directory in your system `PATH`:
    ```bash
    sudo cp sysopctl /usr/local/bin/
    ```

4. Create and install the manual page:
    ```bash
    sudo cp sysopctl.1 /usr/share/man/man1/
    sudo mandb
    ```

## Usage

The following commands are available:

### List Running Services
```bash
sysopctl service list
```

### Start a Service
```bash
sysopctl service start <service-name>
```

### Stop a Service
```bash
sysopctl service stop <service-name>
```
### View System Load
```bash
sysopctl system load
```
### Check Disk Usage
```bash
sysopctl disk usage
```
### Monitor Processes
```bash
sysopctl process monitor
```
### Analyze System Logs
```bash
sysopctl logs analyze
```
### Backup Files
```bash
sysopctl backup <path-to-files>
```
### View Version Information
```bash
sysopctl --version
```
### Display Help
```bash
sysopctl --help
```

### Manual Page
Once installed, you can access the detailed manual page with:
```bash
man sysopctl
```
