# Project Name

## Overview

Provide a concise description of your project. What problem does it solve? What are its main features?

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Troubleshooting](#troubleshooting)
- [Support](#support)

## Prerequisites

Before you begin, ensure you have the following installed:

- [Mosquitto Broker](https://mosquitto.org/download/)
- [MQTT Explorer](https://mqtt-explorer.com/)
- [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- [Node.js](https://nodejs.org/)

## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd <project-directory>

2. **Create the Conda environment:**

   ```bash
   conda env create -f environment.yml

3. **Activate the Conda environment:**

   ```bash
   conda activate <environment-name>

4. **Run the Node-RED setup script:**

   ```bash
   nodered_setup.bat

## Usage

1. **Start the Mosquitto Broker:**

   ```bash
   mosquitto -v -c mosquitto.conf

2. **Edit mqtt_client2.py: Modify the MQTT server address:**

   ```bash
   mqtt_server = "your-mqtt-server-address"

3. **Start Node-RED:**

   ```bash
   node-red

4. **Access Node-RED in your browser:**

 Open http://localhost:1880

5. **Import flows.json into Node-RED:**

 Click on the menu icon in the top right corner of Node-RED.
Select "Import" > "Clipboard".
Paste the contents of flows.json and click "Import".

5. **Deploy the flow in Node-RED.**

6. **View the UI:**
   Open http://localhost:1880/ui in your browser.

## Configuration
mqtt_client2.py: Modify mqtt_server variable to set your MQTT server address.
Node-RED: Customize the UI and flows using Node-RED's visual editor.

## Project Structure

1. **mqtt_client2.py:** MQTT client script
2. **flows.json:** Node-RED flow configuration.
3. **nodered_setup.bat:** Batch script for setting up Node-RED dependencies.
4. **environment.yml** Conda environment configuration file.
5. **README.md:** This documentation file.

## Contributing

If you would like to contribute to this project, you can fork the repository and submit pull requests. Here are a few guidelines:

Explain the purpose of your contribution.
Keep your code concise and focused.
Test your changes thoroughly before submitting a pull request.

## Acknowledgments

This project was fully developed by Anshul Sahu. Special thanks to the developers of the tools and libraries used in this project, including Mosquitto, MQTT Explorer, Anaconda, Miniconda, and Node.js.

## Troubleshooting
If you encounter any issues while using this project, here are some troubleshooting tips:

Check your internet connection and server settings.
Ensure all required dependencies are properly installed.
Refer to the project's issue tracker for known problems.

## Support

For support, please contact   anshulforaartech@gmail.com