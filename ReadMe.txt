
KMS & Digital Activation Suite v7.5
==========================================================================================================================

This tool includes 4 different activation methods.

KMS Inject, Digital, KMS 2038 and Online activations.

If using this tool remove any other KMS solutions and temporarily turn off AV security protection.

$OEM$ Activation About:
3 methods are also $OEM$ activation support.
To preactivate the system during installation, copy $OEM$ folder to "sources" folder in the installation media (iso/usb)
$OEM$ activation method also enable the KMS task scheduling system during installation. (digital and KMS2038 activation method except) 

==========================================================================================================================
Activation Method      Support Products                                        Activation Period
--------------------------------------------------------------------------------------------------------------------------

Digital License        -  Windows 10                                           -  Permanent
KMS38 License          -  Windows 10 / Server                                  -  Until 2038 years 
KMS License            -  Windows 7 (VL) 8 / 8.1 / 10 / / Server / Office      -  180 day license (KMS Task Scheduling is required for a perpetual license) 
Online KMS License     -  Windows 7 (VL) 8 / 8.1 / 10 / / Server / Office      -  180 day license (KMS Task Scheduling is required for a perpetual license, this option does not exist in the script) 

==========================================================================================================================

NOTE: Windows Server EVAL to STANDARD

You must run this command to convert Server from EVAL before you can activate

DISM /Online /Set-Edition:ServerStandard /ProductKey:xxxxx-xxxxx-xxxxx-xxxxx-xxxxx /AcceptEula

Get the appropriate ProductKey from the KMS_keys.txt

If you want ServerDatacenter, use this command

DISM /Online /Set-Edition:ServerDatacenter /ProductKey:xxxxx-xxxxx-xxxxx-xxxxx-xxxxx /AcceptEula

==========================================================================================================================

# Supported Volume Products:

Windows 7 (VL) / 8 / 8.1 / 10
Windows Server 2008 R2 / 2012 / 2012 R2 / 2016 / 2019
Office 2010 / 2013 / 2016 / 2019 (VL)

==========================================================================================================================