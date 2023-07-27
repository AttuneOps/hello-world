



[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://doc.servertribe.com)
[![Discord](https://img.shields.io/discord/844971127703994369)](http://discord.servertribe.com)
[![Docs](https://img.shields.io/badge/videos-watch-brightgreen.svg)](https://www.youtube.com/@servertribe)
[![Generic badge](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://www.servertribe.com/community-edition/)

# Hello World Tutorials

Get started learning Attune **fast**.

Attune is very simple SysOps automation and orchestration tool. Attune 
enables you to build automated processes with the popular scripting 
languages that you're already familiar with such as bash and PowerShell.

This project will show you how to **Create and Run** a `Hello, World!` 
process for both bash for Linux and PowerShell for Windows.

This won't take long, have fun!




# Attune

[Attune](https://www.servertribe.com/)
automates and orchestrates processes to streamline deployments, scaling,
migrations, and management of your systems. The Attune platform is building a
community of sharable automated and orchestrated processes.

You can leverage the publicly available orchestrated blueprints to increase
your productivity, and accelerate the delivery of your projects. You can
open-source your own work and improve existing community orchestrated projects.

## Get Started with Attune, Download NOW!

The **Attune Community Edition** can be
[downloaded](https://www.servertribe.com/comunity-edition/)
for free from our
[ServerTribe website](https://www.servertribe.com/comunity-edition/).
You can learn more about Attune through
[ServerTribe's YouTube Channel](https://www.youtube.com/@servertribe).







# Clone this Project

To clone this project into your own instance of Attune, follow the
[Clone a GIT Project How To Instructions](https://servertribe-attune.readthedocs.io/en/latest/howto/design_workspace/clone_project.html).




## Blueprints

This Project contains the following Blueprints.



### Hello World in bash

Creating a bash task to display `Hello, World!` is simple.

#### Connecting Attune to a Device

Attune connects to Linux devices using ssh. The Secure Shell (SSH), 
also known as Secure Socket Shell, is a protocol that enables 
secure connections to remote computers or servers through a text-based 
interface.

Once a secure SSH connection is established, a shell session is 
initiated, allowing you to interact with the server by entering 
commands within the client on your local computer.

SSH is primarily used by system and network administrators, as 
well as individuals who require a highly secure method of remotely 
managing computers.

#### Is SSH is Enabled on the Device

To establish an SSH connection, it is necessary to have both a client 
and a server component installed on the local and remote machines, 
respectively. A commonly utilised open source SSH tool for Linux 
distributions is OpenSSH. Installing OpenSSH is a straightforward 
process that requires access to the terminal on both the server and 
the connecting computer. It's important to note that Ubuntu does not 
have an SSH server pre-installed by default.

#### Let's Get Started

If you haven't done so already, create a New Project and include a 
description.

### Hello World in PowerShell

Creating a PowerShell task to display `Hello, World!` is simple.

#### Connecting Attune to a Device

Attune connects to Windows devices using Windows Remote Management 
(WinRM). WinRM is a protocol that facilitates secure connections 
to remote Windows computers or servers using a command-line or 
scripting interface.

When a secure WinRM connection is established, you gain access to a 
shell session, enabling you to manage the remote system by executing 
commands from your local computer.

WinRM is commonly employed by system administrators and IT 
professionals who need to remotely administer Windows-based 
machines in a secure manner. It provides a reliable means of 
remote management, allowing for efficient troubleshooting, 
configuration, and monitoring tasks.

#### Is WinRM is Enabled on the Device

In order to establish a WinRM connection, it is essential to have the 
WinRM client and server components installed on the local and remote 
Windows machines, respectively. WinRM is a built-in feature in Windows 
operating systems, making it readily available for remote management 
tasks.

WinRM may require some configuration to ensure proper connectivity 
and security settings. This can be done by running specific commands 
or using configuration tools such as PowerShell remoting.

WinRM is disabled on Windows Desktop by default. WinRM is enabled on 
Windows Server by default. To enable WinRM on the machine you want to 
connect to from Attune, follow the instructions 
[here](https://servertribe-attune.readthedocs.io/en/latest/howto/setup_winrm/setup_winrm_cifs_manually.html).

Once WinRM is enabled and properly configured, you can establish 
secure remote connections and perform administrative tasks on the 
remote Windows machines from your local computer using PowerShell or 
other remote management tools that support WinRM.


#### Let's Get Started

If you haven't done so already, create a New Project and include a 
description.




## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| Linux Node | Linux/Unix Node | `linuxnode` | Node details of the Linux machine. |
| Linux User | Linux/Unix Credential | `linuxuser` | Linux Credentials to connect to the machine remotely. |
| Windows Node | Windows Node | `windowsnode` | Node details of the Windows machine. |
| Windows User | Windows Credential | `windowsuser` | Windows Credentials to connect to the machine remotely. |




## Files

| Name | Type | Comment |
| ---- | ---- | ------- |






# Contribute to this Project

**The collective power of a community of talented individuals working in
concert delivers not only more ideas, but quicker development and
troubleshooting when issues arise.**

If you’d like to contribute and help improve these projects, please fork our
repository, commit your changes in Attune, push you changes, and create a
pull request.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-pull-request-01.png" alt="pull request"/>

---

Please feel free to raise any issues or questions you have.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-get-help-02.png" alt="create an issue"/>


---

**Thank you**
