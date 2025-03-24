# Decentralized File Sharing Protocol

## Overview
This project implements a decentralized file-sharing protocol similar to BitTorrent but with enhanced privacy features such as end-to-end encryption and anonymous sharing.

## Features
- Decentralized file sharing
- End-to-end encryption using RSA
- Anonymous sharing
- Web interface for managing file shares

## Technologies
- Python
- Flask
- RSA encryption

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/thegoodduck/peerbit.git
    cd peerbit
    ```

2. Create a virtual environment and activate it:
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Run the application:
    ```sh
    flask run
    ```

2. Navigate to `http://127.0.0.1:5000/` in your web browser.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License
This project is licensed under the Unlicense License. See the `LICENSE` file for more details.
