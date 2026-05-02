# OSHA - VoIP Automation Framework
An advanced Python-based automation tool designed to manage and orchestrate multiple VoIP softphone instances (e.g., MicroSIP, EyeBeam) simultaneously.

## 🚀 What it does
OSHA bypasses the lack of APIs in traditional softphones by using **GUI Automation**. It takes control of the mouse and keyboard to perform complex dialing sequences, navigate IVR menus, and manage call timers across dozens of instances.

### Key Features
- **GUI Orchestration:** Automated window focusing and interaction using `PyAutoGUI`.
- **Multi-Instance Management:** Capable of handling 100+ separate application instances.
- **Automated IVR Navigation:** Handles PIN entry and destination dialing with precise timing.
- **Timer-based Redialing:** Infinite loop logic for automated hang-up and re-establishment of calls.

### Technical Stack
- Python 3.x
- PyAutoGUI (Mouse/Keyboard Control)
- PyGetWindow (Window Management)
- Subprocess (Process Handling)
