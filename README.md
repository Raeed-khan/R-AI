# 🤖 RAEED - Personal AI Assistant (MARK IV)

**RAEED** is an advanced, high-performance Personal AI Assistant system designed for seamless command execution, voice communication, real-time activity monitoring, and system automation. Built with modular Python architecture, it features a dynamic futuristic HUD interface and intelligent background automation tools.

---

## 🌟 Key Features

- **⚡ Instant Response & High Performance:** Optimized for low-latency command execution without unnecessary preambles.
- **🎙️ Voice Interaction & Speech Processing:** Integrated voice input/output capability for natural conversational control.
- **📊 Live System Monitor (HUD):** Real-time tracking of CPU usage, memory consumption, network bandwidth, and process diagnostics.
- **📂 Automated File & Task Management:** Integrated capabilities for file uploads, WhatsApp messaging, and project task execution.
- **🛡️ Secure Clean Boot Protocol:** Automated session cleanup on startup to ensure zero historical log repetition and instant system readiness.
- **🧩 Modular Plugin System:** Support for custom plugins, core actions, dashboard integrations, and persistent memory handling.

---

## 📁 Project Architecture

```text
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
```

---

## ⚙️ Installation & Setup

### 🪟 Windows Setup

1. **Navigate to Project Directory:**
   ```cmd
   cd C:\Users\Administrator\Downloads\RAEED-LV-main\RAEED-LV-main
   ```

2. **Install Dependencies:**
   ```cmd
   pip install -r requirements.txt
   ```

3. **Install Package (Editable Mode):**
   ```cmd
   python setup.py install
   ```

4. **Launch the Assistant:**
   - Console Mode:
     ```cmd
     python main.py
     ```
   - Graphic HUD Mode:
     ```cmd
     python ui.py
     ```

---

### 🐧 Kali Linux / Ubuntu Setup

1. **Update System & Install Virtual Environment:**
   ```bash
   sudo apt update && sudo apt install python3-pip python3-venv -y
   ```

2. **Create and Activate Virtual Environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install Required Packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Install Package Configuration:**
   ```bash
   python3 setup.py install
   ```

5. **Launch RAEED:**
   ```bash
   python3 ui.py
   ```

---

## 🧠 System Behavior & Configuration

RAEED is governed by strict administrative prompts configured for executive-level performance:

- **Startup Sequence:** Flushes temporary memory buffers on boot and initializes with:
  > *"RAEED online and ready, sir."*
- **Response Mode:** Direct, crisp, instant replies without diagnostic log clutter (`SYS` logs remain strictly in backend telemetry).
- **Owner Attribution:** Configured exclusively as the Personal AI Assistant to **Raeed Khan**.

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
