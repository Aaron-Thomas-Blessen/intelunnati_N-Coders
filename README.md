# **CodeCrypt - The Ultimate Cryptography Simulation Tool with OpenSSL**

Welcome to our Cryptography Simulation project! Our tool allows you to effortlessly explore and experiment with various cryptographic techniques and thoroughly study them. Whether you want to understand encryption and decryption or delve into different algorithms, CodeCrypt has you covered.

## **🌟 Introduction**
This README provides an overview of the features, usage instructions, and contact information for our project. Read on to learn how you can easily simulate and understand cryptographic concepts with our intuitive platform.

## **🚀 Features**
CodeCrypt offers several convenient options for exploring cryptography:

- **Algorithm Implementation**: Experiment with implementations of various cryptographic algorithms like RSA, AES, DES, and SHA using OpenSSL and C as backend.
- **Interactive Encryption/Decryption**: Input data and select an encryption method, view the encrypted result, and decrypt it back to the original data.
- **Different Data Types**: Experiment with Encryption, Decryption, and key generation of text, file, audio, image, and videos.
- **Key Generation and Management**: Simulate cryptographic key generation, exchange, and management.
- **User-Friendly Interface**: Enjoy an intuitive and user-friendly interface built with Vite and React.
- **Educational Content**: Access interactive tutorials and educational content on fundamental security concepts like public/private keys, symmetric/asymmetric encryption, key derivation functions, digital signatures, and hash functions.
- **User Interaction**: Experiment with different algorithms and different data types.
- **Profile Management**: Create profiles and update them.

## **🛠️ Technologies Used**
- **Frontend**: Vite, React
- **Backend**: C, OpenSSL, Firebase

## **📚 Application**
CodeCrypt is designed to provide an interactive and educational platform for understanding and experimenting with cryptographic techniques. It is particularly valuable for:

- **Educational Purposes**: Helping students and professionals in the field of cybersecurity learn and understand cryptographic concepts through hands-on experimentation.
- **Research and Development**: Assisting researchers and developers in testing and analyzing various cryptographic algorithms and techniques.
- **Practical Demonstrations**: Enabling instructors and lecturers to demonstrate cryptographic principles in a classroom or training environment.
- **Personal Experimentation**: Allowing enthusiasts and hobbyists to explore cryptography and enhance their knowledge in a practical, interactive manner.

## **🛠️ Getting Started**
To start using CodeCrypt, simply follow these steps:

1. **Visit our Website.**
2. **Sign In**: Click on the Sign In button on the top right side.
3. **Sign Up**: If you are new, click on the Join Here button to sign up.
4. **Explore**: You will be redirected to the Study page where you can select which algorithm you want to study like RSA, AES, DES, or SHA. It has in-depth information about Encryption, Decryption, and Key Generation of that particular algorithm along with YouTube videos.
5. **Encrypt/Decrypt**: Click on the Encrypt or Decrypt button.
   - Choose from 5 different types of data encryption and decryption: text, file, audio, image, and video.
   - Select the algorithm to use: AES, RSA, DES, or SHA.
6. **Share**: Copy the parameters from the encrypted page and send them to your friend for him to try or use the parameters to find the Encrypted Data.

## **💻 How to Set Up Locally**
### **Requirements**
- **Firebase**
- **Node.js and npm**
- **Windows/Linux**
- **Vite**
- **OpenSSL library**
- **A C compiler (e.g., GCC)**

### **Installation Steps**
1. **Install OpenSSL**
   - **Windows**:
     - Download from [OpenSSL](https://www.openssl.org/)
     - Extract the file and place it in `C:\Program Files`
   - **Ubuntu/Linux**:
     - Open Terminal and update the package lists: `sudo apt update`
     - Install OpenSSL: `sudo apt install openssl`
     - Verify the installation: `openssl version`
     - Install development libraries: `sudo apt install libssl-dev`
2. **Install GCC**
   - **Windows**:
     - Download MinGW from [GCC](https://gcc.gnu.org/)
     - Install MinGW and set environment variables
     - Verify installation: `gcc --version`
   - **Ubuntu/Linux**:
     - Open Terminal and update the package lists: `sudo apt update`
     - Install GCC: `sudo apt install gcc`
     - Verify the installation: `gcc --version`
     - Install additional tools: `sudo apt install build-essential`
3. **Clone the Repo**
   ```bash
   git clone https://github.com/Aaron-Thomas-Blessen/CodeCrypt.git
   cd CodeCrypt
   ```
4. **Install Dependencies**
   ```bash
   cd frontend
   npm install
   ```
5. **Build the Backend**
   ```bash
   cd ../backend
   ```
6. **Run Locally**
   - Start the backend server:
     ```bash
     node server.js
     ```
   - Start the frontend development server in another terminal:
     ```bash
     cd frontend
     npm run dev
     ```
   - Open the application in your browser: `http://localhost:5173/`

## **📋 Usage**
To start experimenting with cryptography:
1. **Select an Algorithm**: Choose a cryptographic algorithm from the available options.
2. **Input Data**: Enter the text or data you want to encrypt or decrypt.
3. **Generate Keys**: Cryptographic keys are automatically generated if required by the chosen algorithm.
4. **Encrypt/Decrypt**: Perform encryption or decryption and view the results.
5. **Explore Concepts**: Access tutorials and educational content to learn more about cryptographic principles and techniques.
6. **Sign Up**: Create an account and save your progress.

## **💬 Feedback**
We're constantly striving to improve CodeCrypt to provide the best possible experience for our users. If you have any feedback, suggestions, or encounter any issues while using our platform, please don't hesitate to contact us. Your input is invaluable in helping us enhance our product and deliver exceptional results.

## **📧 Contact Us**
If you have any questions, concerns, or inquiries regarding CodeCrypt, please contact us at [aaronthomas232200@gmail.com](mailto:aaronthomas232200@gmail.com) or connect with me on LinkedIn or Twitter. We're here to assist you and ensure that your cryptographic experience is smooth and educational.

Thank you for choosing CodeCrypt. We hope you enjoy exploring and learning about cryptography! **Happy Hacking!**
