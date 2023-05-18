## How to Install and License Origin Pro 9.0

  
# How to Install and License Origin Pro 9.0
 
Origin Pro 9.0 is a powerful software for data analysis and graphing. It offers many features such as peak analysis, curve fitting, statistics, signal processing, and more. To use Origin Pro 9.0, you need to install it on your computer and activate it with a license file.
 
## Origin pro 9.0 license file txt


[**DOWNLOAD**](https://www.google.com/url?q=https%3A%2F%2Ftinurll.com%2F2tKEJP&sa=D&sntz=1&usg=AOvVaw3Dx2dArKWdD4Mro3g_CG8o)

 
In this article, we will show you how to install and license Origin Pro 9.0 using the MSI installer, which is suitable for multi-user deployment. If you prefer to use the InstallShield setup, you can find the instructions here[^1^].
 
## Step 1: Download the MSI installer
 
You can download the MSI installer for Origin Pro 9.0 from this link[^3^]. Choose the zip format, not the exe format. Extract the zip file to a folder on your computer.
 
## Step 2: Run the MSI installer
 
Before you run the MSI installer, you need to make a registry change to avoid a conflict with Microsoft KB3072630[^2^], which was pushed out on July 15th, 2015. Follow these steps:
 
1. Click Start, click Run, type regedit in the Open box, and then click OK.
2. Locate and then click the following subkey in the registry: HKEY\_LOCAL\_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Installer Note: If this subkey does not exist, create it.
3. On the Edit menu, point to New, and then click DWORD Value.
4. For the DWORD name, type RemappedElevatedProxiesPolicy, and then press Enter.
5. Right-click RemappedElevatedProxiesPolicy, and then click Modify.
6. In the Value data box, type 1, and then click OK.

Now you can run the MSI installer by double-clicking on it or using a script or .BAT file. You can customize the installation options by using command-line parameters. For example:

    msiexec.exe /i "Origin2016Sr0Setup32and64Bit.msi" /passive TRANSFORMS="Origin2016mst.Mst" INSTALLDIR="C:\Program Files\Originlab\Origin 2016\" USERNAME="Test User" COMPANYNAME="Test" PIDKEY="G9374-8099-7111111"

The PIDKEY parameter is where you enter your serial number for Origin Pro 9.0. You can find it in your email confirmation or on your DVD case.
 
## Step 3: Reset the registry value
 
After Origin Pro 9.0 installs successfully, you need to reset the RemappedElevatedProxiesPolicy DWORD value to 0 to re-enable the security fix for KB 3072630. Follow these steps:

1. Click Start, click Run, type regedit in the Open box, and then click OK.
2. Locate and then click the following subkey in the registry: HKEY\_LOCAL\_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Installer
3. Right-click RemappedElevatedProxiesPolicy, and then click Modify.
4. In the Value data box, type 0, and then click OK.

## Step 4: Activate Origin Pro 9.0 with a license file
 
To activate Origin Pro 9.0 with a license file, you need to copy the OLicense.lic file from another PC with Origin installed successfully or from your email confirmation or DVD case. Paste it to the Origin folder on your PC (for example, C:\Program Files\Originlab\Origin 2016\).
 
Now you can run Origin Pro 9.0 and enjoy its features.
 
### References

1. [Origin: Install and License Origin Evaluation - YouTube](https://www.youtube.com/watch?v=zMtZMCIPACM)
2. <a 0f148eb4a0
