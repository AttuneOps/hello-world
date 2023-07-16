Creating a PowerShell task to display `Hello, World!` is simple.

# Connecting Attune to a Device

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

# Is WinRM is Enabled on the Device

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


# Let's Get Started

If you haven't done so already, create a New Project and include a 
description.
