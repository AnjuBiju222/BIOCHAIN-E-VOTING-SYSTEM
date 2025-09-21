# BioChain E-Voting System

BioChain is a secure and transparent electronic voting system that integrates **biometric authentication** (fingerprint and face recognition) with **blockchain technology** to ensure tamper-proof vote recording and a trustworthy election process.

## Features

- **Biometric Voter Authentication**
  - Fingerprint verification using a sensor
  - Facial recognition using camera and LBPH model
- **Secure Voting**
  - Only authenticated voters can cast a vote
  - Votes encrypted and stored in blockchain
- **Admin Dashboard**
  - Create and manage elections
  - Monitor votes in real-time
  - View results securely
- **Transparency & Auditability**
  - Blockchain-based immutable vote ledger
  - Admins can verify results without accessing voter identities

---

## Technology Stack

- **Microcontroller:** Arduino (C/C++ sketches)
- **Backend:** Python
- **Libraries:** OpenCV (face recognition), Web3.py (Ethereum integration)
- **Database:** MySQL 
- **Frontend:** HTML, CSS, JavaScript
- **Blockchain:** Ethereum

---

## Hardware Requirements

- Raspberry Pi (controller)
- Fingerprint sensor
- Camera module
- 7-inch touchscreen display


## Installation & Setup

1. Clone the repository

git clone https://github.com/AnjuBiju222/BIOCHAIN-E-VOTING-SYSTEM.git

cd BIOCHAIN-E-VOTING-SYSTEM

2. Set up Python environment
   
python -m venv env

source env/bin/activate   # Linux/Mac

env\Scripts\activate      # Windows

pip install -r requirements.txt

3. Upload Arduino sketches to the respective microcontroller modules using Arduino IDE.

4. Run the Python backend

python PythonApp/main.py

5. Access the voting interface via the Raspberry Pi touchscreen or connected browser(vnc viewer).

## Usage ##

Admin logs in → creates election → starts election → voters authenticate → vote → results stored on blockchain → admin verifies results.

**Voters authenticate using fingerprint and face recognition before casting their vote.**

## Future Improvements ##

- Improve face recognition accuracy

- Integrate real-time fraud detection

- Expand system scalability for larger elections

- Mobile app integration

