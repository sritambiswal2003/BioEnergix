# Biogas Data Collection Web Application

![image](https://github.com/Kayleexx/BioEnergiX/assets/105365766/6b9c52e2-ac1b-4f55-9a68-a4eacfaca6af)


## Overview

The Biogas Data Collection Web Application is designed to crowdsource data from biogas digesters and securely store it for analysis. This application allows users to register, upload data, and input manual readings related to biogas usage. Super users can also manage data collection on behalf of other users.

The project consists of two main components:
1. Web2 (Current Version): The frontend and backend development for user registration, data collection, and manual input.
2. Web3 (Future Version): The integration with Algorand blockchain for secure data storage using smart contracts.

## Features

- **User Registration:** Users can register for biogas data collection accounts.
- **Data Upload:** Users can capture images of analog meter readings and automatically record GPS coordinates.
- **Manual Input:** Users can manually input biogas meter readings.
- **Super User Functionality:** Super users can manage data collection on behalf of others and verify physical presence.
- **Data Storage:** The server backend stores uploaded data.
- **Security:** Daily digital signatures of data are generated and written to the Algorand blockchain to prevent data manipulation.

## Getting Started

These instructions will help you set up and run the Web2 version of the project on your local machine. The Web3 integration with Algorand blockchain will be developed separately.

### Prerequisites

- Node.js and npm installed (for running the frontend)
- A backend server (e.g., Node.js, Python, etc.) for data storage

### Installation

Clone the repository:

   ```bash
   git clone https://github.com/your-username/biogas-data-collection.git
   cd biogas-data-collection
   ```


### Output

https://bright-muffin-69041f.netlify.app/
