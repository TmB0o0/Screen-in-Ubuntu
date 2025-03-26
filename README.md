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
```
## To view all active sessions, enter the command:
```bash
screen -ls
```
Create a session:
```bash
screen -S <name>
```
## Restoring a named session:
```bash
screen -r <name>
