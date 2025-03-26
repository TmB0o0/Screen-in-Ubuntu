# Screen Utility Guide for Ubuntu

**Screen** is a powerful terminal multiplexer that allows you to manage multiple terminal sessions within a single window. It's especially useful for remote servers and long-running processes, as it enables session persistence even after disconnection.

## Key Features
- 🖥️ Multiple terminal sessions in one window  
- 🔌 Disconnect and reconnect to sessions without interrupting tasks  
- ⏳ Run processes that continue after disconnection  
- ✂️ Window management and screen splitting  

## Installation
```bash
sudo apt update
sudo apt install screen
Basic Commands
Session Management
Command	Description
screen -S <name>	Create new named session
screen -r <name>	Reattach to existing session
screen -r <pid>	Reattach by process ID
screen -ls	List all active sessions
screen -d <name>	Detach a running session remotely
screen -D <name>	Force detach (disconnect if attached elsewhere)
screen -x	Attach to shared session (multi-user mode)
screen -wipe	Clean up dead sessions
