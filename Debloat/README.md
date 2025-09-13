<div align="center">
  <div style="text-align: center;">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/images/logos/pantera-1.4.png">
      <source media="(prefers-color-scheme: light)" srcset="assets/images/logos/pantera-1.3.png">
      <img src="assets/images/logos/pantera-1.4.png" alt="Logo of Pantera" width="350px">
    </picture>
  </div>

  <br>

  [![Issues Badge](https://img.shields.io/badge/ISSUES-0-Test?style=for-the-badge&logo=https%3A%2F%2Ficons8.com%2Ficon%2F83178%2Fimage-file&labelColor=%23333333&color=%23ba181b)](https://github.com/callme-pantera/CSL-prototype/issues)
  [![Stars Badge](https://img.shields.io/badge/STARS-1-Test?style=for-the-badge&logo=https%3A%2F%2Ficons8.com%2Ficon%2F83178%2Fimage-file&labelColor=%23333333&color=%23f6aa1c)](https://github.com/callme-pantera/CSL-prototype/stargazers)
  [![Commits Badge](https://img.shields.io/github/commit-activity/m/callme-pantera/CSL-prototype?style=for-the-badge&label=COMMITS&logo=https%3A%2F%2Ficons8.com%2Ficon%2F83178%2Fimage-file&labelColor=%23333333&color=%237678ED)](https://github.com/callme-pantera/CSL-prototype/commits/main/)
  [![License Badge](https://img.shields.io/badge/LICENSE-CC-Test?style=for-the-badge&logo=https%3A%2F%2Ficons8.com%2Ficon%2F83178%2Fimage-file&labelColor=%23333333&color=%234361ee)](LICENSE)
</div>

<br>

# Debloat Windows 11 using Chris Titus Tech's Windows Utility

## Installation
To begin the debloating process, I first launched **PowerShell** with **Administrator privileges**. This step is crucial, without running PowerShell as Admin, the utility will not function properly.<br>

Once PowerShell was running as Admin, I executed the following command to download and run the latest release of the Windows Utility:

```powershell
irm "https://christitus.com/win" | iex
```

This command retrieves (`irm`) the installation script from Chris Titus Tech’s official site and immediately executes (`iex`) it. Running this will open the **Windows Utility** interface, from which you can start the debloat process.<br>

<div>
    <img src="/assets/images/WinUtil-Download.png" style="width: 100%";>
</div>

<br>

## Tweaks
Once the Windows Utility is running, you also have the option to install additional software directly through the tool. However, I decided to skip this part and focus solely on the debloating process.<br>

In the Winutil application, go to the **Tweaks** tab and select **Standard**. From there, you can customize which components you want to remove. Personally, I chose not to select the options highlighted in the red box, as that was my own preference.<br>

Keep in mind that you can always remove or adjust these components later if needed, so nothing is final at this stage.<br>

<div>
    <img src="/assets/images/WinUtil-Tweaks.png" style="width: 100%";>
    <img src="/assets/images/WinUtil-Disk-CleanUp.png" style="width: 100%";>
</div>

<br>

I won’t go through every single option available in the utility, but feel free to explore them yourself. Just make sure to create a backup of anything important beforehand, especially items that cannot easily be reinstalled.

