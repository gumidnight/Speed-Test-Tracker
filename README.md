# Speedtest Tracker Docker Setup

This project sets up **Speedtest Tracker** using Docker Compose. It includes:

- **Speedtest Tracker** application (from LinuxServer.io)
- **MySQL database** for storing results

## Features

- Tracks internet speed at scheduled intervals
- Stores historical results in MySQL
- Automatic cleanup of old results

## Requirements

- Docker
- Docker Compose

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/speedtest-tracker.git
   cd speedtest-tracker
