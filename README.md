# Webhook-LogKeyAuth

A simple authentication logger that records detailed user information and sends it to a Discord webhook.

## Overview

This program logs every user registration attempt by capturing detailed information such as:

- Authentication Code used
- Status of the attempt (Success or Failure) — failures are highlighted in **red**
- Username on the device
- Computer Name
- IP Address
- Time Zone
- Hardware ID (HWID)
- Security Identifier (SID)

All logs are sent directly to a Discord webhook for monitoring.

## Features

- Captures comprehensive user and system details on each registration.
- Highlights failed authentication attempts clearly.
- Sends real-time logs to a Discord webhook.
- Easy to configure webhook URL.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/NoMoreLife-1/Webhook-LogKeyAuth.git
