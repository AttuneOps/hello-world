Creating a PowerShell task to display `Hello, World!` is simple.

**You will require WinRM to be enabled when connecting to Windows 
machines.**

WinRM is disabled on Windows Desktop by default. WinRM is enabled on 
Windows Server by default. To enable WinRM on the machine you want to 
connect to, follow the instructions 
[here](https://servertribe-attune.readthedocs.io/en/latest/howto/setup_winrm/setup_winrm_cifs_manually.html).

1. Create a New Project and include a description.
2. Create a new Blueprint and include a description.
    * Create an `Execute Windows Script` Step in the Blueprint.
    * Create Parameters:
        * `Windows Node`
        * `Windows Credentials`

    * Populate the newly created parameters into the Step.
    * Populate the Script: `Write-Host "Hello, World!"`.
    * Write a comment for the Step.
3. Create a Plan Tree
    * Create a Plan
    * Create Values for your Parameters:
        * `Windows Node`
        * `Windows Credentials`
    * Populate the Values into the Plan
4. Run the Job