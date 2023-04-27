ACR120U Proprietary Driver Installer (MSI)
Advanced Card Systems Ltd.



Contents
----------------

   1. Release Notes
   2. Installation
   3. History
   4. File Contents
   5. Limitations
   6. Support



1. Release Notes
----------------

Version: 1.1.1.0
Release Date: 16/7/2010

1. Supported Operating Systems
    Windows 2000
    Windows XP 32-bit
    Windows Server 2003 32-bit
    Windows Server 2003 R2 32-bit
    Windows Vista 32-bit
    Windows Server 2008 32-bit
    Windows 7 32-bit

2. Supported Languages
    Arabic
    Chinese (Simplified)
    Chinese (Traditional)
    Czech
    Danish
    Dutch
    English
    Finnish
    French
    German
    Greek
    Hebrew
    Hungarian
    Italian
    Japanese
    Korean
    Norwegian
    Polish
    Portuguese (Brazil)
    Portuguese (Portugal)
    Russian
    Spanish
    Swedish
    Turkish
    Ukrainian

3. Driver Versions
    v1.0.1.1

4. Command Options

    Setup [option]

    /q          Quiet mode
    /x          Uninstall driver
    /norestart  Do not restart after driver installation/uninstallation

    Exit Codes:

    ERROR_SUCCESS                       0x00000000  Success
    ERROR_FILE_NOT_FOUND                0x00000002  File not found
    ERROR_NOT_ENOUGH_MEMORY             0x00000008  Not enough memory
    SETUP_ERROR_OS_NOT_SUPPORTED        0x20000001  Operating system is not supported
    SETUP_ERROR_WINNT4_SP6_REQUIRED     0x20000002  Windows NT 4.0 Service Pack 6 is required
    SETUP_ERROR_UNEXPECTED              0x20000003  Unexpected error
    SETUP_ERROR_MSI2_REQUIRED           0x20000004  Windows Installer 2.0 is required
    SETUP_ERROR_MSI_LOCATION_NOT_FOUND  0x20000005  Cannot find the location of Windows Installer

    Note: Other error codes are defined in Windows API and MSI.



2. Installation
---------------

1. Before running the Setup program, please unplug the reader first.
2. Double click the "Setup.exe" program icon to launch the installer. If your system does not have installed Windows Installer 2.0 or above, you will receive a warning message and you need to go to Windows Update to update your system.
3. Follow the on-screen instructions to install the driver to the system.
4. After the installation is completed, please plug the reader to the system.
5. To remove the driver, please go to "Add or Remove Programs" in Control Panel.



3. History
----------

v1.1.0.0 (10/11/2009)
1. New Release.

v1.1.1.0 (16/7/2010)
1. Update driver to v1.0.1.1.



4. File Contents
----------------

|   ReadMe.txt
|   Setup.exe
|
+---redist
|       InstMsiW.exe
|
\---x86
        ACR120U_Proprietary_Driver-1.0.1.1.msi
        Arabic.mst
        Chinese (Simplified).mst
        Chinese (Traditional).mst
        Czech.mst
        Danish.mst
        Dutch.mst
        Finnish.mst
        French.mst
        German.mst
        Greek.mst
        Hebrew.mst
        Hungarian.mst
        Italian.mst
        Japanese.mst
        Korean.mst
        Norwegian.mst
        Polish.mst
        Portuguese (Brazil).mst
        Portuguese (Portugal).mst
        Russian.mst
        Spanish.mst
        Swedish.mst
        Turkish.mst
        Ukrainian.mst



5. Limitations
--------------



6. Support
----------

In case of problem, please contact ACS through:

Web Site: http://www.acs.com.hk/
E-mail: info@acs.com.hk
Tel: +852 2796 7873
Fax: +852 2796 1286



-----------------------------------------------------------------


Copyright
Copyright by Advanced Card Systems Ltd. (ACS) No part of this reference manual may be reproduced or transmitted in any from without the expressed, written permission of ACS.

Notice
Due to rapid change in technology, some of specifications mentioned in this publication are subject to change without notice. Information furnished is believed to be accurate and reliable. ACS assumes no responsibility for any errors or omissions, which may appear in this document.
