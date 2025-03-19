# CyberHack Simulator

[CyberHack Simulator](https://infosecsamurai.github.io/CyberHack_Simulator/) is an interactive hacking simulation game that lets players explore various hacking scenarios within a safe and controlled environment. The game incorporates real-world concepts of cybersecurity and ethical hacking techniques, thereby providing both educational value and entertainment.

### Table of Contents

- [Features](#features)
- [Missions](#missions)
- [Gameplay Instructions](#gameplay-instructions)
- [Available Commands](#available-commands)
- [Installation](#installation)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Engaging Missions**: Choose from multiple missions, each with unique objectives and challenges, enhancing the gameplay experience.
- **Command-Line Interface**: Execute various hacking commands in a terminal-style interface, simulating real-world hacking techniques.
- **Progress Tracking**: Complete mission objectives to earn experience points (XP) and achievements, upgrading your skills along the way.
- **Dynamic Hints**: Receive contextual hints and AI coaching to help refine your techniques and strategies during gameplay.
- **User Profiles**: Create and manage a hacker profile that tracks your progress, achievements, and mission history.

## Missions

Here are the current missions available within the game:

1. **Corporate Infiltration**
   - **Description**: Infiltrate a corporate network by exploiting vulnerabilities in their security system.
   - **Steps**:
     - Access login portal
     - Identify vulnerabilities
     - Exploit security weakness
     - Gain system access
     - Cover your tracks
   - **Difficulty**: Easy
   - **Time Limit**: 10 minutes

2. **Data Breach**
   - **Description**: Siphon off sensitive customer data from an outdated database system.
   - **Steps**:
     - Identify outdated services
     - Gain access to the main server
     - Locate the database
     - Extract customer data
     - Eliminate traces of access
   - **Difficulty**: Medium
   - **Time Limit**: 12 minutes

3. **Security Audit**
   - **Description**: Conduct a security audit on a local company’s network to identify points of failure and report vulnerabilities.
   - **Steps**:
     - Scan the entire network
     - Document vulnerabilities
     - Present findings
     - Propose security improvements
     - Follow up with the client
   - **Difficulty**: Easy
   - **Time Limit**: 15 minutes

4. **Phishing Attack**
   - **Description**: Enact a phishing attack against a target organization to gather sensitive credentials.
   - **Steps**:
     - Create a convincing email
     - Send the phishing email
     - Monitor responses
     - Retrieve sensitive data
     - Analyze the impact
   - **Difficulty**: Hard
   - **Time Limit**: 10 minutes

## Gameplay Instructions

- Upon launching the game, select your hacking path (Black Hat, White Hat, or Grey Hat).
- Choose a mission from the available options.
- Use the command line interface to input and execute commands related to the mission.
- Complete mission objectives within the time limit to earn experience points and unlock achievements.

## Available Commands

The following commands are available during gameplay:

- **help**: Show available commands.
- **scan**: Scan for network devices.
- **connect [IP]**: Connect to a specified network IP address.
- **analyze**: Analyze the current target for vulnerabilities.
- **exploit [vulnerability]**: Attempt to exploit a specified vulnerability.
- **access [target]**: Access a specified resource (like a system or database).
- **clean logs**: Remove traces of your activities.
- **status**: Check the current mission status.
- **portscan [IP]**: Scan for open ports on the specified IP.
- **crack [target]**: Attempt to crack passwords for the specified target.
- **clear**: Clear the terminal output.

## Installation

To set up the CyberHack Simulator on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/InfosecSamurai/CyberHackSimulator.git
   cd CyberHackSimulator
   ```

2. Open `index.html` in your preferred web browser and start playing!

## Technologies Used

- HTML
- CSS (Tailwind CSS)
- JavaScript
- Local Storage for saving player profiles and settings

## Contributing

Contributions are welcome! If you'd like to contribute to CyberHack Simulator, please fork the repository and submit a pull request. Here's how you can help:

- Suggest new features or missions
- Report bugs or issues
- Improve the documentation

## Screenshots

<div style="text-align: center;">
    <img src="https://i.ibb.co/kgPhDvyc/Screenshot-2025-03-17-144200.png" alt="Screenshot 1" width="400" height="300" />
    <img src="https://i.ibb.co/8WQHDK8/Screenshot-2025-03-17-144240.png" alt="Screenshot 2" width="400" height="300" />
    <img src="https://i.ibb.co/8tbStMp/Screenshot-2025-03-17-144356.png" alt="Screenshot 3" width="400" height="300" />
    <img src="https://i.ibb.co/d02qJt59/Screenshot-2025-03-17-144338.png" alt="Screenshot 4" width="400" height="300" />
</div>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```