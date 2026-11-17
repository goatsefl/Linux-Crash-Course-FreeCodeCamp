# Linux-Crash-Course-FreeCodeCamp
Learning about the basics of Linux and how companies require Linux for their daily tasks.


## The Main Parts Of Linux.
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/e9564593-20fa-4a56-b9ac-b00386f683a8" />


<!--### Login Methods :
<img width="640" height="640" alt="image" src="https://github.com/user-attachments/assets/67054c48-ec47-461b-b952-924cefc09e40" /> -->



### Consoles, Virtual Terminals and Terminal Emulators.

#### Consoles:

Consoles are like physical keyboard and monitor combos which were used to interact with a Linux system. These were used because building a single computer system back then was expensive. Multiple people could attach consoles to the main computer and use the Linux kernel and type commands to talk with Linux kernel.

Modern Systems: 

It's a text based screen and the logs it shows while OS & Linux kernel are booting up, that's the console. No GUI is involved, only text based access to Linux is called console.

Reference Image: The Console 
<br>
<br>
<img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/c730302a-fa64-4913-bccb-388d8ca44311" />
<br>
<br>
Reference Image: Modern Systems
<br>
<br>
<img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/af22b04e-6ba8-42a1-929c-eda109ae0de2" />


#### Virtual Terminals:

Virtual Terminals(VT) are the next upgrade to consoles. As computing evolved, the use of consoles became very difficult and hard to manage. Virtual terminals are workspaces in modern computing, that can have multiple instances of independent login sessions, terminal workspaces or shell process that are managed by single kernel, you can have multiple consoles in the same computer with it's own private context.
<br>

EG : Ctrl + Alt + F2 will be a new virtual workspace to use new terminal.
<br>

Reference Image :
<br>
<br>
<img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/7f90af38-89c1-4a3f-a934-3a3d6be889c4" />
<br>
<br>
<br>

#### Terminal Emulator:

Terminal Emulator is a software for a GUI based console. After logging in, you cannot use a console, so terminal is pre-installed in the modern day software. It's an emulator of console which will have a UI to talk through systems.
<br>
<br>
Reference Image : 
<br>
<img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/b5dc8867-271c-4a74-bba3-f8516aa2e6cc" />


# Logging in to Linux System

## Remote Login with no-GUI : 

<img width="722" height="130" alt="image" src="https://github.com/user-attachments/assets/b9e79e73-6219-4907-a973-2fb053795cd3" />

### VNC (Virtual Network Computing) :

This is used to access Linux Desktop remotely for Linux Administration, similar to using a system in front of you. User must configure a VNC server, and configure a VNC viewer. It typically requires you to configure a VNC server on host machine, VNC viewer on client machine.

EG : Using on a local network using SSH tunnel.

<img width="462" height="604" alt="image" src="https://github.com/user-attachments/assets/b1d23066-d6ba-425f-9f38-6e272340d5a3" />

### RDP (Remote Desktop Connection) :

