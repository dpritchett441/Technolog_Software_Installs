# Technolog Software Installs

[![Technolog Logo](/Media/Technolog_Logo.jpg)](https://www.technolog.com/)

The 'Software Installs' PowerShell script is an amalgamation of all the previous separate software install scripts.

## Synopsis

Once the PowerShell script is ran the user will be presented with the below form. From this they select the desired/relevant department for their current setup. Once selected the relevant software will begin installing silently (where applicable).

![Software Installs GUI](/Samples/Software_Installs_GUI.PNG)

## Latest Release

- v5.1
    * Updated 'Datacentre Install' function to include 'HexEdit-Shortcut' function ([Issue Ref: #5](https://github.com/dpritchett441/Technolog_Software_Installs/issues/5))
    * Amended Oracle package in software list ([Issue Ref: #6](https://github.com/dpritchett441/Technolog_Software_Installs/issues/6))

For a full list of releases please check the [Change Log](CHANGES.md)

## Progress bar

#### As of v5.0 the below progress bar will be displayed during the installations to provide an indication of what's currently happening 

![Progress bar](/Samples/ProgressBar.gif)

## Notifications

#### Software installations have now started

![Start Notification](/Samples/Installation_Started.PNG)

#### Software installations have completed successfully

![End Notification Success](/Samples/Installation_Completed_Success.PNG)

#### Software installations have completed but encounted one or more errors

![End Notification Error](/Samples/Installation_Completed_Errors.PNG)
