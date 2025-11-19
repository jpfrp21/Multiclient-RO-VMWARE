# Multiclient-RO-VMWARE
Multiclient using VMware Workstation Pro

Step 1. Download VMware-workstation ---- https://support.broadcom.com/group/ecx/downloads

Step 2. Download Windows 10 iso ---- https://www.techworm.net/2022/08/download-windows-10-iso.html

Step 2. Install VMware then once installation is completed run VMware Workstation app.

Step 3. Create New Virtual Machine

        3.1 Choose Typical
	
        3.2 Select Installer disc image file then look for windows 10 iso youve downloaded from step 2
	
        3.3 Input Product Key. NF6HC-QH89W-F8WYV-WWXV4-WFG6P
	
        3.4 Select windows 10 pro for the version. Click next
	
        3.5 Input Virtual Machine name (any name you want)
	
        3.6 Select the location for the VM to be stored. Note: This is important just remember where the path is. Then, click Next.
	
        3.7 Select Store virtual disk as a single file. click next
	
        3.8 Click Finish then wait until the installation of OS is complete.
	
Step 4. Look for the location where you stored the VM.

Step 5. Find the file with .VMX if the file name extension is not visible just go to View then tick "File name Extensions"

Step 6. Open the XXXX.VMX using notepad.

Step 7. Copy paste the values below to your .vmx file.

        isolation.tools.hgfs.disable = "TRUE"
	
        sharedFolder.maxNum = "0"
	
        hgfs.mapRootShare = "TRUE"
	
        hypervisor.cpuid.v0 = "FALSE"
	
Step 8. Have Fun :)
