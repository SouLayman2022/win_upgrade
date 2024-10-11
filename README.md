<p align="center"><img src="https://lookimg.com/images/2023/09/25/QY5RTR.png" alt="MAS Logo" height="128"></p>

<h1 align="center">Microsoft  Activation  Scripts (MAS)</h1>

<p align="center">A Windows and Office activator using HWID / Ohook / KMS38 / Online KMS activation methods, with a focus on open-source code and fewer antivirus detections.</p>
<hr>

## Download / How to use it?

### Method 1 - PowerShell (Recommended)

-   On Windows 8.1/10/11, right-click on the Windows start menu and select PowerShell or Terminal (Not CMD).
-   Copy-paste the below code and press enter\
    `irm https://massgrave.dev/get | iex`
-   You will see the activation options, and follow onscreen instructions.
-   That's all.

### Method 2 - Traditional

-   Download the file from [GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts/archive/refs/heads/master.zip) or [Bitbucket](https://bitbucket.org/WindowsAddict/microsoft-activation-scripts/get/master.zip)
-   Right-click on the downloaded zip file and extract
-   In the extracted folder, find the folder named `All-In-One-Version`
-   Run the file named `MAS_AIO.cmd`
-   You will see the activation options, and follow onscreen instructions.
-   That's all.

To run the scripts in unattended mode, check [here](https://massgrave.dev/command_line_switches.html)

# Deactivate Windows 11 Updates - Steps

If you want to disable automatic Windows 11 updates, follow these methods below. You can also refer to this [link](https://www.easeus.com/knowledge-center/stop-windows-11-update.html) for more information.

---

## **Method 1: Disable Windows Update Service**

### Steps:
1. Press `Windows + R`, type `services.msc`, and press Enter.
2. In the **Services** window, scroll down and locate **Windows Update**.
3. Right-click on **Windows Update** and select **Properties**.
4. In the **General** tab, find the **Startup type** dropdown and set it to **Disabled**.
5. Click **Stop** to halt the service if it’s currently running, then click **OK**.

---

## **Method 2: Use Group Policy Editor**

### Steps:
1. Press `Windows + R`, type `gpedit.msc`, and press Enter.
2. Navigate to:
   `Computer Configuration > Administrative Templates > Windows Components > Windows Update > Manage updates offered from Windows Update`
3. Double-click **Configure Automatic Updates**.
4. Select **Disabled**, then click **Apply** and **OK**.

---

## **Method 3: Use Command-Line to Disable Updates**

Use the Command Prompt to stop and disable Windows Update services.

### Method 1:
sc stop wuauserv </br>
sc config wuauserv start= disabled </br>

### Method 2:
net stop wuauserv </br>
net stop bits </br>
net stop dosvc </br>
sc config wuauserv start= disabled </br>
sc config bits start= disabled </br>
sc config dosvc start= disabled </br>

### Method 3:
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\AU" /v NoAutoUpdate /t REG_DWORD /d 1 /f </br>


```
Latest Version: 2.5
Release date: 16-Nov-2023
```

### [Troubleshooting / Help](https://massgrave.dev/troubleshoot.html)
### [Download Original Windows & Office](https://massgrave.dev/genuine-installation-media.html)
### Homepage - https://massgrave.dev
</br>

[![1.1]][1]
[![1.2]][2]
[![1.3]][3]
[![1.4]][4]

[1.1]: https://lookimg.com/images/2023/03/21/QTvjcD.png (Chat with us without signup)
[1.2]: https://lookimg.com/images/2023/03/21/QTvLyd.png (Chat with us)
[1.3]: https://lookimg.com/images/2023/10/29/QiBot9.png (Follow on 𝕏/Twitter)
[1.4]: https://lookimg.com/images/2023/05/17/Q0iZ2U.png (Reddit)

[1]: https://discord.gg/gjJEfq7ux8
[2]: https://t.me/Microsoft_Activation_Scripts
[3]: https://twitter.com/massgravel
[4]: https://www.reddit.com/r/MAS_Activator

---

<p align="center">Made with Love ❤️</p>
