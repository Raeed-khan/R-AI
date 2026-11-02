🤖 RAEED - Personal AI Assistant (MARK IV)

RAEED is an advanced, high-performance Personal AI Assistant system designed for seamless command execution, voice communication, real-time activity monitoring, and system automation. Built with modular python architecture, it features a dynamic futuristic HUD interface and intelligent background automation tools.

🌟 Key Features

⚡ Instant Response & High Performance: Optimized for low-latency command execution without unnecessary preambles.

🎙️ Voice Interaction & Speech Processing: Integrated voice input/output capability for natural conversational control.

📊 Live System Monitor (HUD): Real-time tracking of CPU usage, Memory consumption, Network bandwidth, and process diagnostics.

📂 Automated File & Task Management: Integrated capabilities for file uploads, WhatsApp messaging, and project task execution.

🛡️ Secure Clean Boot Protocol: Automated session cleanup on startup to ensure zero historical log repetition and instant system readiness.

🧩 Modular Plugin System: Support for custom plugins, core actions, dashboard integrations, and persistent memory handling.

📁 Project Architecture

RAEED-LV-main/
├── actions/        # Automated action handlers and task scripts
├── config/         # System instructions, settings, and behavior profiles
├── core/           # Core AI processing engine and system logic
├── dashboard/      # HUD diagnostic interface components
├── memory/         # Session cache and persistent storage management
├── plugins/        # Dynamic extension modules and custom integrations
├── .gitignore      # Ignored files for repository hygiene
├── LICENSE         # Open-source distribution license
├── main.py         # Primary AI execution engine
├── requirements.txt# Required Python dependencies
├── setup.py        # System installer and package builder
├── ui.py           # Futuristic GUI interface
└── README.md       # Project documentation


⚙️ Installation & Setup

🪟 Windows Setup

Clone or Extract the Project:
Navigate to the project root directory in Command Prompt (cmd):

cd C:\Users\Administrator\Downloads\RAEED-LV-main\RAEED-LV-main


Install Dependencies:

pip install -r requirements.txt


Install Package (Optional/Editable Mode):

python setup.py install


Launch the Assistant:

Run via Terminal/Console:

python main.py


Run with Graphic HUD Interface:

python ui.py


🐧 Kali Linux / Ubuntu Setup

Update System & Install Virtual Environment Tools:

sudo apt update && sudo apt install python3-pip python3-venv -y


Create and Activate a Virtual Environment:

python3 -m venv venv
source venv/bin/activate


Install Required Packages:

pip install -r requirements.txt


Install Package Configuration:

python3 setup.py install


Launch RAEED:

python3 ui.py


🧠 System Behavior & Configuration

RAEED is governed by strict administrative prompts configured for executive-level performance:

Startup Sequence: Flushes temporary memory buffers and initializes with:

"RAEED online and ready, sir."

Response Mode: Direct, crisp, instant replies without diagnostic log clutter (SYS logs remain in backend telemetry).

Owner Attribution: Configured exclusively as the Personal Assistant to Raeed Khan.

📜 License

This project is licensed under the MIT License - see the LICENSE file for details.
