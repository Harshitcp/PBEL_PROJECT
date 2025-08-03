# BlockVote - Interactive Blockchain Voting Simulation

## Overview
BlockVote is a comprehensive web-based application that demonstrates blockchain technology applied to secure voting systems. Built as a single HTML file with embedded JavaScript, it provides a complete simulation of how blockchain can ensure transparent, immutable, and secure voting processes.

## Features

### 🔐 **Blockchain Technology**
- **Cryptographic Hashing**: Each vote is secured using SHA-256 hashing
- **Immutable Records**: Once cast, votes cannot be altered or deleted
- **Chain Verification**: Each block contains a hash of the previous block
- **Transparent Ledger**: All voting activity is publicly viewable

### 🗳️ **Voting System**
- **Multi-Candidate Polls**: Support for polls with multiple candidates
- **One Vote Per User**: Prevents duplicate voting through blockchain verification
- **Real-time Results**: Live voting statistics with visual progress bars
- **Poll Management**: Create, activate, deactivate, and delete polls

### 👥 **User Management**
- **Role-Based Access**: Separate interfaces for voters and administrators
- **Secure Authentication**: User registration and login system
- **Session Management**: Persistent login sessions using localStorage

### 🎨 **Modern User Interface**
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Bootstrap Framework**: Professional, modern UI components
- **Interactive Elements**: Hover effects, animations, and smooth transitions

## Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/Harshitcp/PBEL_PROJECT.git
   cd PBEL_PROJECT
   ```

2. **Open the application**
   - Simply open `main.html` in any modern web browser
   - No server setup or installation required

3. **Default Admin Account**
   - Username: `admin`
   - Password: `admin`

## How to Use

### For Administrators:
1. Login with admin credentials
2. Create new polls with multiple candidates
3. Monitor voting activity through the blockchain explorer
4. Manage poll status (activate/deactivate)

### For Voters:
1. Register a new account or login
2. View active polls on the home page
3. Cast votes by selecting candidates
4. View real-time results and blockchain verification

## Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **UI Framework**: Bootstrap 5, Font Awesome
- **Storage**: localStorage with JSON format
- **Security**: SHA-256 cryptographic hashing
- **Dependencies**: CryptoJS for hashing functions

## Project Structure

```
PBEL_PROJECT/
├── main.html          # Main application file
└── README.md          # Project documentation
```

## Use Cases

- **Educational**: Demonstrates blockchain concepts in practice
- **Prototyping**: Foundation for real blockchain voting applications
- **Proof of Concept**: Validates blockchain voting system feasibility

## Benefits

- **Transparency**: All votes are publicly verifiable
- **Security**: Cryptographically secured, immutable records
- **Accessibility**: Web-based, no installation required
- **Scalability**: Modular architecture for easy expansion

## Contributing

This is a demonstration project. Feel free to fork and modify for educational purposes.

## License

This project is open source and available under the MIT License.

---

**Note**: This is a simulation for educational purposes. For production voting systems, additional security measures and proper blockchain implementation would be required. 