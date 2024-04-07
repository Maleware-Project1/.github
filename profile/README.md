# Hi there 👋

Introducing a novel concept in cybersecurity: the friendly malware! Contrary to traditional malicious software, this malware has a rather benevolent purpose. It encrypts only the .txt files within the current folder where it resides, ensuring that your data remains secure from unauthorized access. But here's the catch: decrypting your files is as simple as solving a game of Wordle!

# Welcome to the Wordle Malware! 🎬

# Table of Contents
- [About Us](#about-us)
- [Features](#features)
- [Useful Resources](#useful-resources)
- [Fun fact](#fun-fact)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Model Architecture](#model-architecture)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Join us](#join-us)
- [Contact](#contact)

## 🙋‍♀️ About Us

We are at the forefront of creating a revolutionary movie recommendation experience, blending cutting-edge technology with a deep passion for cinema. Our team is pioneering the development of a graph-based attention model to intuitively connect users with movies, ensuring every recommendation is a gateway to a new adventure.

## Features

- **Selective Encryption**: The friendly malware targets only .txt files within its current directory, ensuring that your textual data remains secure.
- **Decryption via Wordle**: Rather than demanding a ransom, decryption of encrypted files is tied to a Wordle challenge. Solve the puzzle, and your files are decrypted!
- **Server Interaction**: To facilitate decryption, the malware communicates with a remote server, where the symmetric key is securely stored.

## Technology Stack

- **Programming Languages**: Python
- **Cryptography**: Fernet
- **Library**: sqlalchemy, nltk, rich
- **Backend**:  FastAPI, Docker
- **Database**: PostgreSQL
  
## Getting Started

### Prerequisites

- Docker
### Installation

Clone the repository

```
git clone https://github.com/<your-username>/advanced-movie-recommendation.git
cd advanced-movie-recommendation
python -m venv venv

To run the application:

python app.py

For Docker users:

docker-compose up --build

```

## Model Architecture
Our Graph-Based Attention Model (GBAM) intricately analyses user-movie interactions through:

- Graph Construction: Nodes are users and movies; edges are interactions.
- Feature Extraction: Embeddings for user and movie attributes.
- Attention Mechanism: Node and graph-level attention for relevance.
- Recommendation Engine: Combines embeddings to forecast preferences.
This architecture enables dynamic, personalized recommendations.

## Evaluation
We assess our model using:

- **Precision@K**: Accuracy of top-K recommendations.
- **Recall@K**: Coverage of relevant items in top-K recommendations.
- **NDCG**: Ranking quality, factoring the position of relevant items.
Continuous evaluation ensures the system's effectiveness.

## 🌈 Contributing
Your expertise can help us enhance the magic of movie discovery. Whether you're a coder, a designer, or a movie buff with ideas, there's a place for you here. Check out our [Contribution Guidelines](CONTRIBUTING.md) for detailed information on how you can make an impact.
Join us in enhancing movie recommendations:
```
Fork the project.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request.
Read our Contribution Guidelines for more details.
```
## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Thanks to:

TMDB and GroupLens for dataset provision.
The open-source community for essential tools and libraries.
Contributors for their invaluable input and feedback.
Your support is crucial to our project's success.

## 🤝 Join Us

Dive into our [open issues](https://github.com/<your-username>/advanced-movie-recommendation/issues) or kickstart a discussion. Your contribution could be the next big thing in movie recommendations!

## 📬 Contact

Got questions or suggestions? We’d love to hear from you. Reach out to us at [letuanminh2707@gmail.com].
