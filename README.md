# UPCmd
Fake Command Line for Windows XP, Vista and 7

upCMD replaces cmd.exe. Technical support scammers use console-commands as a fake virus scanner or to show fake hacker attacks, a.s.o.
upCMD covers most of these commands but you can manipulate their functions in the settings.
upCMD also don’t execute any bat files.
Commands TREE,NETSTAT, DIR, DEL, PING, IPCONFIG, FORMAT, HOSTNAME, CD, VOL, CLS

upCMD does not accept keyboard entries while a command is running. So, the scammer can not enter fake messages when p.e. the TREE command is running.
How to install?
Before we start:

    Install this program only on virtual machines!
    You MUST HAVE owner rights for deleting or renaming msinfo32.exe in windows/system32. See also Tip 1 below.

 
STEPS

    STEP 1: run upCMDSetup.exe
    STEP 2: open C:/windows/system32
    STEP 3: rename cmd.exe to p.e. BAKcmd.exe or delete it
    STEP 4:
        for Win 32bit systems: skip  and goto STEP 5
        for Win 64bit systems:
            open C:/windows/sysWOW64
            copy or move upcmd.exe to c:/windows/system32
            open C:/windows/system32
    STEP 5: rename upcmd.exe to cmd.exe
    STEP 6: run the ‘new’ cmd.exe
    STEP 7: type ‘settings’ + [ENTER] to open the settings for tweaking upCMD



TIP 1: TakeOwnershipEx is a free tool that allows you to get full access to files and folders

TIP 2: Remove the uninstall info in the registery

*** IMPORTANT : INSTALL THIS TOOL ONLY ON A VIRTUAL MACHINE (VM)! ***
