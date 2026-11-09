# 🎮 WiFi Game Hub

### A Desktop-Based Multiplayer Gaming Platform Powered by C# and .NET 8

WiFi Game Hub is a Windows desktop application that brings multiple classic games together in one platform. It supports both **Solo Play** and **Wi-Fi Multiplayer**, allowing users to enjoy games individually or connect with other players over the same local network.

The application combines interactive gameplay, room-based multiplayer sessions, LAN connectivity, and a modern desktop interface in one gaming hub.

---

## 📌 Project Overview

WiFi Game Hub is developed using C# Windows Forms and .NET 8. The main objective is to provide users with an easy-to-use gaming platform where they can select different games, play independently, or connect with friends through a local Wi-Fi network.

The system includes multiplayer room management, player communication, game-session handling, and network-based gameplay.

## ✨ Key Features

- **Multiple Games:** Play Chess, Ludo, Tic-Tac-Toe, and Carrom.
- **Solo Mode:** Enjoy supported games independently.
- **Wi-Fi Multiplayer:** Connect with other players over a shared local network.
- **Room Management:** Create or join multiplayer game rooms.
- **LAN Discovery:** Discover available game sessions on the network.
- **In-Game Chat:** Communicate with other players during multiplayer sessions.
- **Player Management:** Track players and manage multiplayer sessions.
- **Game Validation:** Host-authoritative validation for supported multiplayer gameplay.
- **Modern Interface:** Dark-themed desktop interface with purple and blue visual accents.
- **Game Results:** Display match outcomes and relevant scoring information.
- **Connection Handling:** Manage player departures and multiplayer connection states.

## 🕹️ Available Games

| Game | Description |
|---|---|
| Chess | A strategic board game for two players. |
| Ludo | A multiplayer board game based on dice rolls and token movement. |
| Tic-Tac-Toe | A classic strategy game played on a 3×3 grid. |
| Carrom | A digital carrom board game featuring striker and coin mechanics. |

## 🎯 Game Modes

### 1. Solo Play
Play supported games independently without joining a multiplayer room.

### 2. Wi-Fi Multiplayer
Connect with other players using a shared local Wi-Fi network.

Multiplayer functionality includes:
- Creating and joining rooms.
- Discovering available sessions.
- Managing player participation.
- Synchronizing supported game sessions.
- Handling player departures and match results.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| C# | Main programming language |
| .NET 8 | Application framework |
| Windows Forms | Desktop user interface |
| TCP Networking | Multiplayer communication |
| Socket Programming | Network connections |
| JSON | Network message serialization |
| xUnit | Automated testing |
| Visual Studio / VS Code | Development environment |

## 📂 Project Structure

```text
WiFi-Game-Hub/
│
├── Forms/
│   └── Application forms and UI
│
├── Games/
│   └── Game logic and gameplay components
│
├── Networking/
│   └── Multiplayer communication
│
├── Services/
│   └── Application services
│
├── Documentation/
│   └── Project documentation
│
├── WiFiGameHub.Tests/
│   └── Automated test project
│
├── Program.cs
├── visual project.csproj
├── WiFiGameHub.sln
├── README.md
└── .gitignore
```

## 💻 System Requirements

- Windows 10 or Windows 11.
- .NET 8 SDK.
- A compatible Windows desktop environment.
- Visual Studio or Visual Studio Code.
- Wi-Fi network for LAN multiplayer functionality.

## 🚀 Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/Aliraza-053-stack/Wifi-Game-Hub.git
```

### Step 2: Open the Project

Navigate to the downloaded project directory and open:

```text
WiFiGameHub.sln
```

### Step 3: Restore Dependencies

Open a terminal in the project directory:

```bash
dotnet restore
```

### Step 4: Build the Application

```bash
dotnet build "visual project.csproj" -c Release
```

### Step 5: Run the Application

```bash
dotnet run --project "visual project.csproj"
```

## 🧪 Testing

The project includes an automated test suite covering important application functionality.

**Latest reported test results:**

- Total tests passed: 147
- Failed tests: 0
- Skipped tests: 0
- Release build warnings: 0
- Release build errors: 0

Run the tests using:

```bash
dotnet test ".\WiFiGameHub.Tests\WiFiGameHub.Tests.csproj" -c Release
```

## 🌐 Multiplayer Network Setup

For Wi-Fi multiplayer:

1. Connect all participating computers to the same local Wi-Fi network.
2. Launch WiFi Game Hub on each computer.
3. One player creates a game room.
4. Other players discover or join the available room.
5. Start the game once the required players have joined.

**Note:** Multiplayer availability depends on network connectivity, firewall permissions, and the supported game-session configuration.

## 🎓 Academic Project Information

| Detail | Information |
|---|---|
| Project Name | WiFi Game Hub |
| Project Type | Desktop Application |
| Domain | Game Development and Computer Networking |
| Language | C# |
| Framework | .NET 8 Windows Forms |
| Development Methodology | Agile |
| Project Duration | April 2025 – June 2026 |

## 👨‍💻 Development Credits

**Developer:** Ali Raza

**Project Supervisor:** Sir Muhammad Abdullah

## 📜 License

This project is developed as an academic software engineering project.

No open-source license has been specified. Please contact the project developer before redistributing or reusing the project.

---

<p align="center">
  <b>WiFi Game Hub</b><br/>
  Bringing Classic Games Together — Play Solo, Connect Locally, Enjoy Together.
</p>
