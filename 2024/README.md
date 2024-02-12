# GSoC'24 Participant Guide

## **Communication**

Welcome to the Cypherock GSoC projects page. We encourage candidates to come up with their own project idea.

Join our [Telegram Channel](https://t.me/cypherock) and stay tuned for updates.

Use our [Template](https://docs.google.com/document/d/1UF9ij6BBhXYAetlopktXUOXlet4C2eHd0mAttqy0O2k/edit?usp=sharing) for the proposal. We recommend the use of google docs for the proposal.


## **General suggestions**
_________________

- **Project ideas describe the goals we want to achieve
  but may miss details that have to be defined during the project**:
  we expect students to also do their own research, propose solutions and be
  ready to deal with uncertainty and solve challenges that
  will come up during the project

- **Code and prototypes are preferred over detailed
  documents and unreliable estimates**:
  rather than using your time to write a very long
  application document, we suggest to invest in writing a prototype
  (which means the code may be thrown out entirely) which will help you
  understand the challenges of the project you want to work on; your
  application should refer to the prototype or other Github contributions
  you made to Cypherock that show you have the capability to succeed in the
  project idea you are applying for.

- **Students who have either shown to have or have shown to be
  fast learners for the required hard and soft skills by
  contributing to Cypherock have a lot more chances of being accepted**:
  in order to get started contributing refer to the
  [Cypherock Contributing Guidelines](CONTRIBUTING.md)

- **Get trained in the projects you want to apply for**: once
  applicants have completed some basic training by
  [contributing to Cypherock](CONTRIBUTING.md)
  we highly suggest to start working on
  some aspects of the project they are
  interested in applying: all projects
  listed this year are improvements
  of existing modules so these modules
  already have a list of open issues
  which can be solved as part of your advanced training.
  It will also be possible to complete some of the tasks listed in
  the project idea right now before GSoC starts.
  We will list some easy tasks in the project idea for this purpose.

## **Projects List**


### 1. New Blockchain(s) Support Integration
**Mentors**: Irshad Ansari, Ujjwal Kumar, Akshit Taneja, Vipul Saini

**Description**: 
Expand the Cypherock X1 Wallet's capabilities by integrating support for additional cryptocurrencies. 
This project involves researching and implementing the necessary protocols and security measures to enable transactions and storage for new coins, thus broadening the wallet's market appeal and functionality.

**Suggested Coins for Integration**:

* Polkadot (DOT): A multi-chain interchange and translation architecture which allows customized side-chains to connect with public blockchains.
* Cardano (ADA): A proof-of-stake blockchain platform that says its goal is to allow “changemakers, innovators and visionaries” to bring about positive global change.
* XRP (XRP Ripple): Launched in 2021, the XRP Ledger (XRPL) is an open-source, permissionless and decentralized technology.

**Tech Stack**: 
* C/C++ for firmware development
* blockchain-specific libraries and APIs for the selected coins.

  OR
  
* JavaScript/TypeScript for cysync desktop app development
* ReactJS, Redux
* ElectronJS
* blockchain-specific libraries and APIs for the selected coins.

**Estimated Time** : 350 hours

**References**:

* Polkadot Documentation: https://polkadot.network/docs/
* Cardano Documentation: https://docs.cardano.org/
* XRP Documentation: https://xrpl.org/docs.html
* GitHub - Blockchain integration examples: https://github.com/crypto-org-chain/chain-main

**Difficulty** : Medium


### 2. Mobile App Development in Flutter
**Mentors**: Irshad Ansari, Ujjwal Kumar, Akshit Taneja


**Description**: Develop a cross-platform mobile application for Cypherock Wallet using Flutter. 
The application will provide a user-friendly interface for managing the wallet's features, including but not limited to account management, 
transaction history, and secure communication with the Cypherock hardware wallet.

**Tech Stack**: 
* Flutter for UI, Dart
* RESTful APIs for backend communication
* secure storage for sensitive data

**Estimated Time**: 350 hours

**References**:

* Flutter Official Documentation: https://flutter.dev/docs
* Secure Storage in Flutter: https://pub.dev/packages/flutter_secure_storage

**Difficulty** : Medium



### 3. Improve & Add X1 Vault core features
**Mentors**: Irshad Ansari, Ujjwal Kumar, Akshit Taneja

**Description**: Enhance the existing codebase by porting it to the latest platforms or versions. Improving user experience, security & performance of the X1Vault by implementing features and improvements that are core to the X1Vault. Participants will be working on optimizing the existing implementation for a better experience or supporting new features such as Wallet Session to improve user experience & make the product more versatile.

**Tech Stack**: 
* Any one of the relevant languages (e.g., JavaScript for web, C/C++ for firmware), 
* OAuth for authentication,
* Cryptography

**Estimated Time**: 350 hours

**Difficulty** : Medium



### 4. Unit Testing and Automated Testing for Desktop App
**Mentors**: Irshad Ansari, Ujjwal Kumar, Akshit Taneja

**Description**: Establish a robust testing framework for the Cypherock CySync Desktop Application, including unit tests for individual components and automated tests for integration and system-level verification to ensure the product's reliability and security.

**Tech Stack**: 
- Jest, Playwright for automated UI testing, GitHub Actions for CI/CD.
- Typescript/Javascript
- ReactJS, Redux
- ElectronJS

**Estimated Time**: 175 hours

**References**:

* Jest: https://jestjs.io/
* Playwright: https://playwright.dev/
* GitHub Actions: https://github.com/features/actions

**Difficulty** : Medium

### 5. Unit Testing and Automated Testing for Firmware
**Mentors**: Irshad Ansari, Ujjwal Kumar, Akshit Taneja, Vipul Saini

**Description**: Establish a robust testing framework for the Cypherock X1 Wallet firmware, including unit tests for individual components and automated tests for integration and system-level verification to ensure the product's reliability and security.

**Tech Stack**: 
- C/C++
- CMake
- Unit test frameworks in C (Unity)
- Github Actions

**Estimated Time**: 175 hours

**References**:

* Unity Framework: https://github.com/ThrowTheSwitch/Unity
* GitHub Actions: https://github.com/features/actions

**Difficulty** : Medium


### 6. X1 Simulator for App Development
**Mentors**: Irshad Ansari, Ujjwal Kumar, Akshit Taneja, Vipul Saini

**Description**: Create a simulator for the Cypherock X1 hardware wallet to facilitate application development and testing without the need for physical hardware. This tool will emulate the wallet's behavior and interfaces.

**Tech Stack**: Emulation tools like QEMU, and programming languages used in the wallet's development (C/C++ for firmware, JavaScript for web interfaces), SDL2.

**Estimated Time**: 350 hours

**Difficulty** :  Hard


### 7. Multi-Party-Computation (MPC) based threshold signing on X1 Vault
**Mentors**: Ujjwal Kumar, Vipul Saini

**Description**: Research & develop threshold ECDSA signing for popular blockchains using an MPC-based approach. The development involves research, design & improvements of building blocks for MPC-based threshold signing. The project introduces participants to the latest developments in the field of cryptography with a focus on MPC.

**Tech Stack**: 
- C/C++
- Build tools (cmake, gcc, gdb)
- Cryptography


**Estimated Time**: 350 hours

**Difficulty** :  Hard

