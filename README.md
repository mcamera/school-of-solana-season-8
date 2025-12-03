# 🎓 School of Solana Season 8 - Graduate Portfolio

![School of Solana](https://github.com/Ackee-Blockchain/school-of-solana/blob/master/.banner/banner.png?raw=true)

**Cohort:** Season 8 (October - December 2025).  
**Course Provider:** [Ackee Blockchain](https://ackee.xyz/)

---

## 🎯 About This Journey

This repository contains all my completed coursework, demonstrating my progression from understanding Solana fundamentals to building a fully functional decentralized application deployed on Solana DevNet.

The course covered everything from Solana's core concepts and Rust programming to advanced topics like Program Derived Addresses (PDAs), Cross-Program Invocations (CPIs), security best practices, and full-stack dApp development with Anchor framework.

---

## 📚 What I Learned

### 🔹 Blockchain Architecture & Solana Fundamentals
- **Solana's Unique Design**: Understanding Solana's high-performance architecture, including Proof of History (PoH), Tower BFT consensus, and parallel transaction processing
- **Account Model**: Mastering Solana's account-based model where programs are stateless and data is stored in separate accounts
- **Program Derived Addresses (PDAs)**: Learning how to create deterministic, secure addresses without private keys for program-controlled accounts
- **Rent & Account Management**: Understanding Solana's rent-exempt requirements and proper account lifecycle management

### 🔹 Rust Programming Language
- **Ownership & Borrowing**: Mastering Rust's unique memory safety guarantees through ownership, borrowing, and lifetimes
- **Traits & Generics**: Implementing polymorphism and code reuse through Rust's trait system
- **Error Handling**: Using `Result` and `Option` types for robust error management without exceptions
- **Structs & Enums**: Designing complex data structures and state machines for real-world applications
- **Testing**: Writing comprehensive test suites with Rust's built-in testing framework

### 🔹 Anchor Framework
- **Program Structure**: Organizing Solana programs with Anchor's opinionated framework for cleaner, safer code
- **Account Constraints**: Leveraging Anchor's declarative macros for automatic security validations
- **Instruction Handlers**: Implementing program instructions with proper context validation
- **State Management**: Defining and managing on-chain state with Anchor's account serialization
- **Testing with Mocha/Chai**: Writing TypeScript tests for Anchor programs with comprehensive coverage

### 🔹 Security & Best Practices
- **Common Vulnerabilities**: Identifying and preventing issues like missing signer checks, arithmetic overflows, and unauthorized access
- **Runtime Policies**: Understanding Solana's security mechanisms and runtime constraints
- **Account Validation**: Implementing proper checks for account ownership, initialization, and authorization
- **Secure Fund Transfers**: Handling SOL transfers safely with proper CPI patterns and balance management

### 🔹 Full-Stack dApp Development
- **Next.js & React**: Building modern, responsive user interfaces for blockchain applications
- **Wallet Integration**: Connecting to Solana wallets (Phantom, Solflare) using wallet-adapter libraries
- **Program Interaction**: Using Anchor's TypeScript client to interact with on-chain programs
- **Transaction Management**: Handling transaction signing, confirmation, and error states
- **DevNet Deployment**: Deploying and testing programs on Solana's development network

---

## 📋 Course Curriculum & Completed Tasks

### **Task 1: Solana Fundamentals** 📖
**Completed:** October 15, 2025  
**Focus:** Core Concepts & Ecosystem Understanding  
**Grade:** ✅ Pass (≥80% required)

**What I Learned:**
- Solana's architecture and design principles
- Transaction processing and validator mechanics
- Solana Program Library (SPL) and token standards
- Network structure and cluster organization
- Account model and program execution model

📁 **Repository:** [`task1-mcamera/`](./task1-mcamera)

---

### **Task 2: Rust Programming** 🦀
**Completed:** October 22, 2025  
**Focus:** Rust Language Fundamentals & Patterns  
**Grade:** ✅ Pass (100% test coverage required)

**What I Learned:**
- Implementing geometric shapes with trait-based polymorphism
- Building a calculator with arithmetic operations and history tracking
- Handling overflow/underflow conditions critical for blockchain safety
- Input validation and error handling patterns
- References, borrowing, and ownership concepts

📁 **Repository:** [`task2-mcamera/`](./task2-mcamera)

---

### **Task 3: On-Chain Vault Program** 🏦
**Completed:** October 29, 2025  
**Focus:** Anchor Framework & Solana Program Development  
**Grade:** ✅ Pass (100% test coverage required)

**What I Learned:**
- Creating and managing Program Derived Addresses (PDAs)
- Implementing Cross-Program Invocations (CPIs) for SOL transfers
- Account validation and state management in Solana programs
- Using Anchor's context patterns for instruction handlers
- Emitting events for off-chain monitoring

📁 **Repository:** [`task3-mcamera/`](./task3-mcamera)

---

### **Task 4: Decentralized Twitter** 🐦
**Completed:** November 5, 2025  
**Focus:** Complex State Management & Multi-User Interactions  
**Grade:** ✅ Pass (100% test coverage required)

**What I Learned:**
- Managing complex account relationships (tweets, reactions, comments)
- Using content hashing for unique PDA derivation
- Implementing authorization controls for user-owned content
- Account closure and rent recovery patterns
- Optimizing PDA seeds for collision prevention

📁 **Repository:** [`task4-mcamera/`](./task4-mcamera)

---

### **Task 5: Solana Security** 🔒
**Completed:** November 26, 2025  
**Focus:** Security Mechanisms & Vulnerability Prevention  
**Grade:** ✅ Pass (≥80% required)

**What I Learned:**
- Common Solana vulnerabilities and exploitation patterns
- Missing signer check vulnerabilities and prevention
- Arithmetic overflow/underflow attacks and safe math
- Account validation failures and security implications
- Proper authorization patterns and access control
- Runtime policies and security mechanisms

📁 **Repository:** [`task5-mcamera/`](./task5-mcamera)

---

### **Final Project: FundingMe - Crowdfunding dApp** 🚀
**Completed:** November 2025  
**Focus:** Full-Stack Solana dApp with Complete Lifecycle Management  
**Status:** ✅ **Deployed to DevNet**

**🌐 Live Demo:** [https://funding-me-rho.vercel.app/](https://funding-me-rho.vercel.app/)  
**📋 Program ID:** `DmcSC8vFAoLr756aDoqkV13S6kosdHHNuziRezhCcKUi`

A fully functional decentralized crowdfunding platform built with Rust/Anchor and Next.js. The dApp enables users to create funding projects, accept donations from multiple contributors, and manage the complete funding lifecycle including withdrawals and refunds.

**Core Features:**
- Create crowdfunding projects with custom names and financial targets
- Multi-donor support with cumulative donation tracking
- Automatic state transitions (Active → TargetReached → Success/Failed)
- Secure fund withdrawals for successful projects
- Individual refund claims for failed projects
- Complete account lifecycle with rent recovery

**Technical Stack:**
- **Backend:** Rust + Anchor Framework v0.31.1
- **Frontend:** Next.js 14 + TypeScript + React + Tailwind CSS
- **Testing:** 22 comprehensive tests (100% pass rate)
- **Deployment:** Solana DevNet + Vercel

**Key Accomplishments:**
- ✅ First complete Solana program from scratch
- ✅ Production deployment with live frontend
- ✅ Multi-user support with PDA-based account management
- ✅ Comprehensive security validations and error handling
- ✅ Full crowdfunding lifecycle implementation

This project represents the culmination of all skills acquired throughout the course, demonstrating practical application of Solana development from backend program logic to frontend user experience.

📁 **Repository:** [`program-mcamera/`](./program-mcamera)  
📄 **Detailed Documentation:** [PROJECT_DESCRIPTION.md](./program-mcamera/PROJECT_DESCRIPTION.md)

---

## 🔗 Important Links

- **Course Website:** [Ackee Blockchain School of Solana](https://ackee.xyz/solana)
- **Solana Handbook:** [Learning Resource](https://ackee.xyz/solana/book/latest/)
- **FundingMe Live Demo:** [https://funding-me-rho.vercel.app/](https://funding-me-rho.vercel.app/)
- **Solana DevNet:** [https://explorer.solana.com/](https://explorer.solana.com/)
- **Anchor Framework:** [https://www.anchor-lang.com/](https://www.anchor-lang.com/)
- **Course Discord:** [Join Community](https://discord.gg/z3JVuZyFnp)

---

## 🙏 Acknowledgments

- **Ackee Blockchain** for creating and maintaining this excellent course
- **School of Solana instructors** for the comprehensive curriculum and resources
- **Course Discord community** for support and collaboration

---

## 📞 Contact

Interested in collaborating or discussing Solana development? Reach out!

- **GitHub:** [mcamera](https://github.com/mcamera)
- **X** [@0xmarcelocamera](https://x.com/0xmarcelocamera)
