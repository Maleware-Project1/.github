# Hi there 👋

Introducing a novel concept in cybersecurity: the friendly malware! Contrary to traditional malicious software, this malware has a rather benevolent purpose. It encrypts only the .txt files within the current folder where it resides, ensuring that your data remains secure from unauthorized access. But here's the catch: decrypting your files is as simple as solving a game of Wordle!

# Welcome to the Wordle Malware! 🎬

# Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)

## 🛠️ Features

- **Selective Encryption**: The friendly malware targets only .txt files within its current directory, ensuring that your textual data remains secure.
- **Decryption via Wordle**: Rather than demanding a ransom, decryption of encrypted files is tied to a Wordle challenge. Solve the puzzle, and your files are decrypted!
- **Server Interaction**: To facilitate decryption, the malware communicates with a remote server, where the symmetric key is securely stored.

## 🔨 Technology Stack

- **Programming Languages**: Python
- **Cryptography**: Fernet
- **Library**: sqlalchemy, nltk, rich
- **Backend**:  FastAPI, Docker
- **Database**: PostgreSQL
  
## 🚀 Getting Started

### Prerequisites

- Docker

### Installation

Clone the repository "Server"

```
git clone https://github.com/Maleware-Project1/Server.git
cd Server

To run the application:

docker-compose up --build

```

Clone the repository "Malware"

```
git clone https://github.com/Maleware-Project1/Malware.git
cd Malware

To run the application:

For Windows users:

run Valorant.bat

For Linux users:

run Valorant.sh

```
