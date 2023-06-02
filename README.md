# Security System for Storing Crime Data

The Security System for Storing Crime Data is a project that aims to create a secure system for transferring crime data between government organizations using hybrid cryptography. This readme file provides an overview of the project, including its features, installation instructions, and usage guidelines.

## Features

The Security System for Storing Crime Data project offers the following features:

1. **Hybrid Cryptography:** The system utilizes hybrid cryptography techniques to ensure the secure transfer of crime data. It combines the advantages of symmetric and asymmetric encryption algorithms to achieve confidentiality, integrity, and authenticity during data transmission.

2. **Data Encryption:** Before transferring crime data, the system encrypts it using a symmetric encryption algorithm. This encryption process ensures that the data is protected and can only be accessed by authorized recipients.

3. **Key Exchange:** The project implements an asymmetric encryption algorithm to securely exchange the symmetric encryption key between the sending and receiving government organizations. This key exchange process enhances the security of the data transfer.

4. **Data Integrity and Authenticity:** The system uses cryptographic hash functions and digital signatures to ensure the integrity and authenticity of the transferred crime data. These mechanisms verify that the data remains unaltered during transmission and that it originates from a trusted source.

5. **User-Friendly Interface:** The project provides a user-friendly interface for the sending and receiving government organizations to interact with the system. Users can easily select the crime data files, initiate the encryption and transfer process, and verify the integrity and authenticity of the received data.

## System Requirements

To run the Security System for Storing Crime Data project, ensure that you have the following software and libraries installed:

1. [Python](https://www.python.org/downloads/) (Version 3.x or above)
2. [cryptography](https://pypi.org/project/cryptography/) (Python library for cryptography operations)

## Installation and Setup

Follow these steps to install and set up the Security System for Storing Crime Data project:

1. Clone or download the project files from the repository.
2. Install Python on your system by downloading it from the official Python website and following the installation instructions.
3. Install the required library by running the following command:
   ```
   pip install cryptography
   ```
4. Once the dependencies are installed, you are ready to use the project.

## Usage

To transfer crime data securely between government organizations:

1. Open the terminal or command prompt and navigate to the project directory.
2. Run the encryption script on the sending organization's system using the following command:
   ```
   python encrypt.py
   ```
3. Follow the instructions on the terminal to select the crime data files for encryption and provide necessary details.
4. After the encryption process is complete, the system will generate an encrypted file and a digital signature for each crime data file.

5. Transfer the encrypted files and digital signatures to the receiving organization using a secure channel.

6. On the receiving organization's system, open the terminal or command prompt and navigate to the project directory.
7. Run the decryption script using the following command:
   ```
   python decrypt.py
   ```
8. Follow the instructions on the terminal to select the encrypted files and the corresponding digital signatures for decryption.
9. After the decryption process is complete, the system will verify the integrity and authenticity of the received data and generate the decrypted crime data files.

Note: Ensure that both the sending and receiving organizations have shared the necessary cryptographic keys and algorithms beforehand.

## Contributors

The Security System for Storing Crime Data project was developed by [Moudipa Jana]. I welcome any feedback, suggestions, or contributions to enhance the project. 

## License

The Security System for Storing Crime Data project is open-source software
