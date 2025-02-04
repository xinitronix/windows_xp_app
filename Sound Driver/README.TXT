        Realtek Semiconductor Corp. High Definition Audio System Software Ver:R1.27
                        Installation and Setup


Driver Installation/Removal Procedure For Realtek High Definition Audio Codec:
=================================================================================

<<< For Win2000/WinXP/Winx64 (WDM driver) >>>

---------------------------------------
Setup Driver at first time:
---------------------------------------

Step 1. Before installing the Realtek HD Audio Drivers, Press the
        [Cancel] button if Windows detect the Multimedia Audio device. 
          
Step 2. Insert the "Realtek HD Audio Drivers" CD into the CD-ROM 
        drive and run the setup.exe program to finish the installation. 

Step 3. Click on [Next/OK/Go] to continue the procedure. If the Windows popup 
        "Digital Signature Not Found" message, press [Yes] to continue the 
        installation.
        
Step 4. Finally, select to restart the system and press [Finish] to complete
        the installation.  

        The system will reload the drivers and do some adjustments in the INF
        file if so required.

--------------------------
Update Driver:
--------------------------

Step 1. Follow Step 2,3,4 described in [Setup at first time] above to complete
        the procedure.

--------------------------
Remove Driver:
--------------------------

Step 1. Go to Start\Settings\Control Panel.

Step 2. Select [Add/Remove Programs] icon.

Step 3. Select "Realtek HD Audio Drivers" and press [Change/Remove]
        button.

Step 4. Click on [Next/OK/Go] to finish the uninstallation.        

Step 5. At the end of the procedure, select to restart the system and press
        [Finish] to complete the uninstallation.



<< Other Informations >>

--------------------
Silent Installation:
--------------------

Run "Setup -s -f2<path\LogFile>"
i.e. setup -s -f2c:\mylog.log 
     or
     setup -s -f2c:/mylog.log 


Note: 1. Please update Directx version to DirectX8.1 or above.

---------------------
Version Informations:
---------------------

WDM driver for Win2000/WinXP                        : 5.10.0.5188
WDM driver for Winx64                               : 5.10.0.5188

Realtek Soundman			   	    : 1.0.0.21
Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.7
Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.53
Realtek Sound Effect Manager(RTHDCPL)               : 2.0.2.6
Alcwzrd.exe 				            : 1.1.0.28

Driver Setup Program                                : 2.02a

--------
History:
--------
Driver Package R1.27
  RtkHDAud.sys Version: 5.10.0.5188
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization.
         
       InstallShield package :
           Fix :
             1. Add installation file "RTHDAEQ*.dat" .
             2. Add Package version in setup.ini .
             3. Manual installation setting for InstallShield .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5188
  WDM driver for Winx64                               : 5.10.0.5188
  Realtek Soundman			   	      : 1.0.0.21
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.7
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.53
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.2.6
  Alcwzrd.exe 				              : 1.1.0.28
  Driver Setup Program                                : 2.02a

  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.26
  RtkHDAud.sys Version: 5.10.0.5178
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization.
         
       InstallShield package :
           Fix :
             1. Set rebooting twice for installation UAA QFE on Win2000 .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5178
  WDM driver for Winx64                               : 5.10.0.5178
  Realtek Soundman			   	      : 1.0.0.21
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.6
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.52
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.2.1
  Alcwzrd.exe 				              : 1.1.0.28
  Driver Setup Program                                : 2.00

  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.25
  RtkHDAud.sys Version: 5.10.0.5172
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
        1.) Customization.
         
       InstallShield package :
           Fix :
             1. Rtlupd.exe(2.5.0.5) fixed roll-back problem ( It can not delete oem.inf file before update driver ).
             2. Change Azalia name in setup.ini file .
             3. Don't popup Rtlupd dialog when you select "No" on Hotfix installation dialog .
           Add :
             1. System language identifier .
             2. Change pop-up dialog Product name ( Azalia->High Definition ) . 
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5172
  WDM driver for Winx64                               : 5.10.0.5172
  Realtek Soundman			   	      : 1.0.0.21
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.10
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.6
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.51
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.1.7
  Alcwzrd.exe 				              : 1.1.0.27
  Driver Setup Program                                : 1.99

  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.24
  RtkHDAud.sys Version: 5.10.0.5152
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
         1.) Customization.
         2.) Support 192KHz sample rate output.
         
       InstallShield package :
           Fix : 
             1. Reboot timing after installation MS QFE ( UAA driver ) .
             2. Uninstallation dialog description .
           Add :
             1. MS hotfix KB901105 can be included by HD pcakage ( If get MS licence ) .
             2. Hotfix KB901105 Warning message .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5152
  WDM driver for Winx64                               : 5.10.0.5152
  Realtek Soundman			   	      : 1.0.0.18
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.7
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.4
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.46
  Realtek Sound Effect Manager(RTHDCPL)               : 2.0.0.8
  Alcwzrd.exe 				              : 1.1.0.24
  Driver Setup Program                                : 1.96

  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.23
  RtkHDAud.sys Version: 5.10.0.5136
    1. Codec Supporting: ALC880, ALC882, ALC883, ALC861, ALC260, ALC262
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
         1.) Customization.
         2.) Support new codec ALC262, ALC883
         
       InstallShield package :
         1.) Check OS service pack number with InstallShield .
         2.) Change audio wizard quitting procedure .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5136
  WDM driver for Winx64                               : 5.10.0.5136
  Realtek Soundman			   	      : 1.0.0.17
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.7
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.4
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.43
  Realtek Sound Effect Manager(RTHDCPL)               : 1.1.2.3
  Alcwzrd.exe 				              : 1.1.0.23
  Driver Setup Program                                : 1.92
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.22
  RtkHDAud.sys Version: 5.10.0.5128
    1. Codec Supporting: ALC880, ALC882, ALC861, ALC260
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
         1.) Customization.
         
       InstallShield package :
         1.) Setup progress backward .
         2.) Driver size on Add and remove programs .
         3.) Refresh driver size on Add and Remove Programs .
         4.) Check RtlExupd.dll version .
         5.) Check RtlHDCpl.exe version .
      
  WDM driver for Win2000/WinXP                        : 5.10.0.5128
  WDM driver for Winx64                               : 5.10.0.5128
  Realtek Soundman			   	      : 1.0.0.17
  Realtek Sound Effect Manager(ALSndMgr.cpl)          : 1.0.0.7
  Realtek Sound Effect Manager(RTSndMgr.cpl)          : 1.0.0.4
  Realtek Sound Effect Manager(RtlCpl)                : 1.0.1.40
  Realtek Sound Effect Manager(RTHDCPL)               : 1.1.1.9
  Alcwzrd.exe 				              : 1.1.0.20
  Driver Setup Program                                : 1.91
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.21
  RtkHDAud.sys Version: 5.10.0.5127
    1. Codec Supporting: ALC880, ALC882, ALC260
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
         1.) Customization.
         2.) Support DTS Encoder and DTS Neo for special version codec .
      
  SoundMan.exe Version: 1.0.0.17
  ALSndMgr.cpl Version: 1.0.0.7  
  Rtlcpl.exe Version: 1.0.1.40	
  Alcwzrd.exe Version: 1.1.0.20
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.20
  RtkHDAud.sys Version: 5.10.0.5125
    1. Codec Supporting: ALC880, ALC882, ALC260
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1.) Customization.    
     
       For New architecture:
         1.) Customization.
         2.) Fixed the issue of SPDIF-In capture
      
  SoundMan.exe Version: 1.0.0.17
  ALSndMgr.cpl Version: 1.0.0.7  
  Rtlcpl.exe Version: 1.0.1.40	
  Alcwzrd.exe Version: 1.1.0.20
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.19
  RtkHDAud.sys Version: 5.10.0.5123
    1. Codec Supporting: ALC880, ALC882, ALC260
    2. OS Supporting: Microsoft WindowsXP, Widnows2000, Winx64
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1. Customization.    
	2. Avoid Pop noise when toggle output sampling rate for ALC260.
	3. Restore the original timer resolution first before check the original system timer resolution.
     
       For New architecture:
         1.) Customization.
         2.) Driver store mixer setting after windows reboot
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.39	
  Alcwzrd.exe Version: 1.1.0.19
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.18
  RtkHDAud.sys Version: 5.10.0.5122
    1. Codec Supporting: ALC880, ALC882, ALC260
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1. Customization.
	2.Add 2 default values of codec subsystem ID for ALC260.
      
       For New architecture:
         1.) Customization.
         2.) Fixed the issue of uncontinuous sound after suspend on some machine.
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.38	
  Alcwzrd.exe Version: 1.1.0.18
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.17
  RtkHDAud.sys Version: 5.10.0.5120
    1. Codec Supporting: ALC880, ALC882, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
        1. Customization.
        2. Restore certain register value when resume from system suspend. 
      
       For New architecture:
         1.) Customization.
         2.) Improve reliability for switching mutiple streaming.
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.38	
  Alcwzrd.exe Version: 1.1.0.18
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.16
  RtkHDAud.sys Version: 5.10.0.5119
    1. Codec Supporting: ALC880, ALC882, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1.0a(5013)
    4. Add/Fix
       1. Customization.
       2. Fix initial noise issue for the certain models.
       3. Check codec SubsystemID verb to decide the driver path when driver initialize.
       4. Don't modify Configuration byte Verbs when driver initialize.
       5. Fix Buffer size un-alignment issue.
       
       For New architecture:
         1.) Customization.
         2.) Fix the problem when play AC-3 stream by SPDIF interface
         3.) Change device name for mutiple streaming issue.
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.38	
  Alcwzrd.exe Version: 1.1.0.17
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB888111
      Package file version (kb888111.exe) : 6.1.22.0
      Hdaudiobus.sys version : 5.10.00.5013
//=================
Driver Package R1.15
  RtkHDAud.sys Version: 5.10.0.5116
    1. Codec Supporting: ALC880, ALC882, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1(5011)
    4. Add/Fix
       1.) Customization.
       2.) Auto lock SPDIF-in signal when SPDIF-in signal is unlocked.
       3.) Fix SPDIF out copy protection issue.
       4.) Add patch code for ALC260 potential risk.
 
       For New architecture:
         1.) Customization.
         2.) Fix new feature problem on mutiple streaming.
         3.) Fix capture problem on ALC882.
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.38	
  Alcwzrd.exe Version: 1.1.0.17
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5011
//=================
Driver Package R1.14
  RtkHDAud.sys Version: 5.10.0.5109
    1. Codec Supporting: ALC880, ALC882, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1(5011)
    4. Add/Fix
       1.) Customization.
       2.) Reduce delay time when volume is adjusted.
       3.) Fix hang up issue when system resume from S3.
 
       For New architecture:
         1.) New architecture of HD audio driver formal release.
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.4  
  Rtlcpl.exe Version: 1.0.1.37	
  Alcwzrd.exe Version: 1.1.0.16
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5011
//=================
Driver Package R1.13
  RtkHDAud.sys Version: 5.10.0.5038
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1(5011)
    4. Add/Fix
     1) Reduce initialize noise
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.36	
  Alcwzrd.exe Version: 1.1.0.15
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5011
//=================
Driver Package R1.12
  RtkHDAud.sys Version: 5.10.0.5037
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1(5011)
    4. Add/Fix
     1) Improve recording performance.
     2) Reduce initialize noise
      
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.36	
  Alcwzrd.exe Version: 1.1.0.15
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5011
//=================
Driver Package R1.11
  RtkHDAud.sys Version: 5.10.0.5036
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1(5011)
    4. Add/Fix
     
  SoundMan.exe Version: 1.0.0.14
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.35	
  Alcwzrd.exe Version: 1.1.0.15
  
  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5011
//=================
Driver Package R1.10
  RtkHDAud.sys Version: 5.10.0.5034
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio UAAV1(5011)
    4. Add/Fix
     1) Fix the problem that there is little noise when start stream playing
     2) Fix the problem that in WinDVD, the SPDIF option still exist even 
        there is no SPDIF
    
  
  SoundMan.exe Version: 1.0.0.14
   1.Set the default recording device as "Realtek HD Audio rear input" device 

  ALSndMgr.cpl Version: 1.0.0.5
  
  Rtlcpl.exe Version: 1.0.1.34
	
  Alcwzrd.exe Version: 1.1.0.15
   1.Keep previous Jack setting.
   2.Check whether have any jack plugin when restart OS,and popup the 
     device window if wizard detect any new device plugin.

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5011
//=================
Driver Package R1.09
  RtkHDAud.sys Version: 5.10.0.5033
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
     
  SoundMan.exe Version: 1.0.0.14
    1.Set the default recording device as "Realtek HD Audio rear input" device 
  	
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.33   
  Alcwzrd.exe Version: 1.1.0.14

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010
//=================
Driver Package R1.08
  RtkHDAud.sys Version: 5.10.0.5032
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
      
  SoundMan.exe Version: 1.0.0.12 	
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.33   
  Alcwzrd.exe Version: 1.1.0.14

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010
//=================
Driver Package R1.07
  RtkHDAud.sys Version: 5.10.0.5031
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
    4. Add/Fix
     1) Fix the probelm when playback with sound recorder, when change frequency
        from 48k to 44.1k in SPDIF page, playback will stop
     2) Support for ALC880G, ALC880D, ALC260D
     3) Fix the the problem that system will hang up while perform audio test 
        in 3DMark 2003
  
  SoundMan.exe Version: 1.0.0.12  	
  ALSndMgr.cpl Version: 1.0.0.5
  
  Rtlcpl.exe Version: 1.0.1.32
  1.Fix word collision problem in Multi-Language.
   
  Alcwzrd.exe Version: 1.1.0.13
  1.Restore previous jack setting when reboot system.

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010
//=================
Driver Package R1.06
  RtkHDAud.sys Version: 5.10.0.5030
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
    4. Add/Fix
  
  SoundMan.exe Version: 1.0.0.12  	
  ALSndMgr.cpl Version: 1.0.0.3 
  Rtlcpl.exe Version: 1.0.1.31   
  Alcwzrd.exe Version: 1.1.0.12

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010
//=================
Driver Package R1.05
  RtkHDAud.sys Version: 5.10.0.5029
    1. Codec Supporting: ALC880, ALC260, ALC861
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
    4. Add/Fix
     1) Add support for ALC861
     2) Fix the noise problem that when recording from SPDIF In at 96khz
  
  SoundMan.exe Version: 1.0.0.12  	
  ALSndMgr.cpl Version: 1.0.0.5  
  Rtlcpl.exe Version: 1.0.1.31   
  Alcwzrd.exe Version: 1.1.0.12

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010
//=================
Driver Package R1.04
  RtkHDAud.sys Version: 5.10.0.5028
    1. Codec Supporting: ALC880, ALC260
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
    4. Add/Fix
     1) For UAJ A to A volume line, change type from KSNODETYPE_MICROPHONE 
        to KSNODETYPE_ANALOG_CONNECTOR
     2) Fix the problem that SPDIF out no sound in WinDVD
     3) Fix the problem that there is balance conrtol in Center and 
        Subwoofer volume line in W2k
     4) Change the conponent tyep of SPDIF-In from "KSNODETYPE_ANALOG_CONNECTOR" 
        to "KSNODETYPE_SPDIF_INTERFACE"
     5) Fix the problem that mute SPDIF out in mixer doesn't work
  
  SoundMan.exe Version: 1.0.0.12 	
  ALSndMgr.cpl Version: 1.0.0.3
  
  Rtlcpl.exe Version: 1.0.1.31
   1.Turn off all sound effect when speaker test!
   
  Alcwzrd.exe Version: 1.1.0.12

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010

//=================
Driver Package R1.03
  RtkHDAud.sys Version: 5.10.0.5027
  SoundMan.exe Version: 1.0.0.4
  ALSndMgr.cpl Version: 1.0.0.2
  
  Rtlcpl.exe Version: 1.0.1.29
   1.Sync the status which Enable/Disable wizard with alcwzrd
   2.Make the tab of "Audio Wizard" independent from  menu tabs.
   3.Stop the play sound when menu tab is change.
   
  Alcwzrd.exe Version: 1.1.0.12
    1.Fixed broken wizard image.
    2.Sync the status which Enable/Disable wizard with rtlcpl.

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010

//=================
Driver Package R1.01/R1.02
  RtkHDAud.sys Version: 5.10.0.5022
    1. Codec Supporting:
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
    4. Add/Fix
 
  SoundMan.exe Version: 1.0.0.4
  ALSndMgr.cpl Version: 1.0.0.2
  Rtlcpl.exe Version: 1.0.1.23
   
  Alcwzrd.exe Version: 1.1.0.5

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010

//=================
Driver Package R1.0
  RtkHDAud.sys Version: 5.10.0.5017
    1. Codec Supporting: Add ALC880/ALC880M Rev.F Rev.G, ALC860
    2. OS Supporting: Microsoft WindowsXP, Widnows2000
    3. Pack with Microsoft High Definition Audio OOB Binaries V1.0
    4. Add/Fix
 
  SoundMan.exe Version: 1.0.0.4
  ALSndMgr.cpl Version: 1.0.0.2
  Rtlcpl.exe Version: 1.0.1.23
   
  Alcwzrd.exe Version: 1.1.0.5

  Operate on :
    Microsoft High Definition Audio Driver Package - KB835221
      Package file version (kb835221.exe) : 6.1.1.0
      Hdaudiobus.sys version : 5.10.00.5010