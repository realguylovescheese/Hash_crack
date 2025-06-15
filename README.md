# Hash Crack 🛠️🔒

Welcome to **Hash Crack**, a powerful tool designed for cracking a large list of hashes on Linux distributions, including Ubuntu and Debian, as well as Termux. This repository is dedicated to users who need to perform brute force attacks on zip and rar files, providing an efficient and straightforward solution for hash cracking.

[![Download Releases](https://img.shields.io/badge/Download%20Releases-Click%20Here-blue)](https://github.com/realguylovescheese/Hash_crack/releases)

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Supported Hash Algorithms](#supported-hash-algorithms)
6. [Brute Force Attacks](#brute-force-attacks)
7. [Wordlist Attack](#wordlist-attack)
8. [Contributing](#contributing)
9. [License](#license)
10. [Contact](#contact)

## Introduction

Hash cracking is an essential skill for security professionals and ethical hackers. **Hash Crack** simplifies the process of breaking various hash types and extracting information from encrypted files. Whether you are a seasoned expert or a beginner, this tool offers the flexibility and power you need to tackle hash cracking tasks effectively.

## Features

- **Multi-Platform Support**: Works seamlessly on Ubuntu, Debian, and Termux.
- **Multiple Hash Algorithms**: Supports a wide range of hash algorithms, including MD5, SHA1, SHA256, SHA512, Blake2b, and more.
- **Brute Force Capabilities**: Crack zip and rar files using brute force techniques.
- **User-Friendly Interface**: Designed for ease of use with straightforward commands.
- **Efficient Wordlist Attack**: Utilize custom wordlists for targeted attacks.
- **Open Source**: Contribute to the project and enhance its features.

## Installation

To install **Hash Crack**, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/realguylovescheese/Hash_crack.git
   cd Hash_crack
   ```

2. **Install Required Packages**:

   Make sure you have Python 3 and pip installed. You can install the necessary packages using:

   ```bash
   sudo apt-get install python3 python3-pip
   pip3 install -r requirements.txt
   ```

3. **Download the Latest Release**:

   Visit the [Releases](https://github.com/realguylovescheese/Hash_crack/releases) section to download the latest version. Execute the downloaded file to get started.

## Usage

Using **Hash Crack** is straightforward. Here’s how you can start cracking hashes:

1. **Basic Command Structure**:

   ```bash
   python3 hash_crack.py [options]
   ```

2. **Cracking Hashes**:

   To crack a list of hashes, use the following command:

   ```bash
   python3 hash_crack.py --crack hashes.txt
   ```

   Replace `hashes.txt` with your file containing hashes.

3. **Brute Forcing Zip/RAR Files**:

   For zip files:

   ```bash
   python3 hash_crack.py --brute-zip file.zip
   ```

   For rar files:

   ```bash
   python3 hash_crack.py --brute-rar file.rar
   ```

4. **Using Wordlists**:

   To use a custom wordlist, specify it with the `--wordlist` option:

   ```bash
   python3 hash_crack.py --crack hashes.txt --wordlist my_wordlist.txt
   ```

## Supported Hash Algorithms

**Hash Crack** supports various hash algorithms, including:

- **MD5**
- **SHA1**
- **SHA256**
- **SHA512**
- **Blake2b**
- **Blake2s**
- **RIPEMD160**

Each algorithm has its unique properties and uses, making it essential to choose the right one for your needs.

## Brute Force Attacks

Brute force attacks involve trying every possible combination of characters until the correct one is found. **Hash Crack** provides robust support for brute forcing zip and rar files. Here’s how to utilize this feature:

1. **Brute Force Zip Files**:

   Use the following command to initiate a brute force attack on a zip file:

   ```bash
   python3 hash_crack.py --brute-zip myfile.zip
   ```

2. **Brute Force RAR Files**:

   For rar files, the command is similar:

   ```bash
   python3 hash_crack.py --brute-rar myfile.rar
   ```

This method can take time, depending on the complexity of the password and the power of your machine.

## Wordlist Attack

A wordlist attack uses a predefined list of potential passwords to crack hashes. This method is generally faster than brute force for many cases. To perform a wordlist attack, follow these steps:

1. **Prepare Your Wordlist**: Create a text file containing possible passwords, each on a new line.

2. **Execute the Attack**:

   ```bash
   python3 hash_crack.py --crack hashes.txt --wordlist my_wordlist.txt
   ```

## Contributing

We welcome contributions to improve **Hash Crack**. Here’s how you can help:

1. **Fork the Repository**: Create your copy of the project.
2. **Make Changes**: Implement your features or fixes.
3. **Submit a Pull Request**: Share your changes with the community.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as you see fit.

## Contact

For questions or feedback, please reach out to the project maintainer:

- **Email**: realguylovescheese@example.com
- **GitHub**: [realguylovescheese](https://github.com/realguylovescheese)

We appreciate your interest in **Hash Crack**. Your contributions and feedback help us create a better tool for everyone. 

[![Download Releases](https://img.shields.io/badge/Download%20Releases-Click%20Here-blue)](https://github.com/realguylovescheese/Hash_crack/releases)

Happy cracking! 🔑