## **VirtualMachine installation :**

step 1: Download the virtualbox  platform packages for your os.

step 2: Open the Installation Package by double clicking.

step 3: Click continue and finish installing virtualbox.

step 4: After finish installation,close the window. 

## **Ubuntu installation in VM :**

step 1: Choose the Latest version of Ubuntu  and click “Start Download”.

step 2: Run VirtualBox by double-clicking the icon .

step 3: Click “New” button on the top left corner.

step 4: Click “Continue” on the pop-up window .

step 5: Type VM name, select “Linux” for the OS and choose “Ubuntu” for the version.

step 6: Choose the amount of memory to allocate (I suggest choosing between 512 MB to 1024 MB) and Click Next.

step 7: Choose create a new virtual hard disk and Click Next.

step 8: Choose VDI (VirtualBox Disk Image) and  Click Next.

step 9: Choose “Dynamically Allocated” click next. This way, the size of your Virtual Hard Disk will grow as you use.

step 10: Click the folder icon and choose the ubuntu iso file you downloaded. 

step 11: Select the size of the Virtual Disk (I recommend choosing 10 GB) and click next.

step 12: Click Create.

## **Running Linux:**

step 1: Choose Ubuntu from left column and click Start.

step 2: Click the folder icon and choose the ubuntu iso file you downloaded.

step 3: click continue and start.

   - ### **Issue :**

     Failed to open a session for the virtual machine Ubuntu.

     Not in a hypervisor partition (HVP=0) (VERR_NEM_NOT_AVAILABLE).

     AMD-V is disabled in the BIOS (or by the host OS) (VERR_SVM_DISABLED).

     Result Code: 	E_FAIL (0x80004005)

     Component: 	ConsoleWrap

     Interface: 	IConsole 
     {872da645-4a9b-1727-bee2-5585105b9eed}

  - ### **To fix this problem:**

     Step 1: Restart your laptop/desktop. Then, on the boot screen, press the BIOS key (esc) to enter into BIOS mode. 

     Step 2: In the BIOS interface, use arrow keys to skip to Configuration tab. In most cases, the virtualization item is under System Configuration.

     Step 3: After finding the virtualization item  press Enter key to make sure it is enabled.

     Step 4: Press F10 to save the changes and then exit from BIOS.After enabling Virtualization in BIOS, restart computer to run the virtual machine in Virtualbox.

step 4: Click Install Ubuntu.

step 5: Check “Download updates” and click continue.

step 6: Choose “Erase disk and install Ubuntu” and click Install now.

step 7: It show the tab write the changes to disk . Click continue.

step 8: Choose the location and click continue.

step 9: Give the details and password .and click continue.
Click “Install Now” and wait.

step 10: When finished, click Restart and press Enter.

