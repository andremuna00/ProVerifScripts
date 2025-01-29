# 🔒 ProVerif Web Security Tasks and Exercises

## 📌 Repository Overview
This repository contains ProVerif scripts used as tasks and exercises in the Web Security course. The tasks focus on formalizing various security protocols and concepts using the ProVerif tool. 🛡️

## 🏆 Tasks and Exercises
The repository includes ProVerif formalizations for the following tasks:

1. **📖 Basic**: Introduction to ProVerif with a simple security protocol.
2. **🧑‍💻 Roles**: Defining different roles in a communication protocol.
3. **🔧 Roles Fixed**: Refinement of role definitions to address security flaws.
4. **🔑 Fresh Token**: Incorporating fresh nonces/tokens to improve security.
5. **🛠️ Fresh Fixed**: Correcting issues related to freshness in token usage.
6. **🔐 Asym Communication**: Modeling asymmetric encryption-based communication.
7. **🛡️ Asym Fixed**: Enhancements and fixes in asymmetric communication.
8. **🌍 SSL Task Exercise**: Formalization and verification of SSL-related security properties.

## 🚀 Usage
To analyze the security properties of each task, use the following command:
```sh
proverif <script.pv>
```
Replace `<script.pv>` with the respective ProVerif script file. 🎯

## 📋 Requirements
- [ProVerif](https://proverif.inria.fr/) installed on your system. 🖥️
- Basic understanding of the applied pi-calculus and security protocols. 📚

## 📂 Repository Structure
```
📁 Repository
├── 📜 01_basic.pv
├── 📜 02_roles.pv
├── 📜 03_roles_fixed.pv
├── 📜 04_fresh.pv
├── 📜 05_fresh_fixed.pv
├── 📜 06_asym.pv
├── 📜 07_asym_fixed.pv
├── 📜 SSL-not authenticity.pv
├── 📄 README.md
```
Each `.pv` file corresponds to a specific task/exercise. 📝

## 🤝 Contribution
Feel free to contribute by improving scripts, fixing vulnerabilities, or adding new security properties. 💡

## 📜 License
This project is licensed under the MIT License. 🏛️

