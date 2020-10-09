# Technolog Software Installs

[![Technolog Logo](/Media/Technolog_Logo.jpg)](https://www.technolog.com/)

The 'Software Installs' PowerShell script is an amalgamation of all the previous separate software install scripts.

## Synopsis

Once the PowerShell script is ran the user will be presented with the below form. From this they select the desired/relevant department for their current setup. Once selected the relevant software will begin installing silently (where applicable).

![Software Installs GUI](/Samples/Software_Installs_GUI.PNG)

## Latest Release

- v4.2
    * Removed 'Production' from all elements of script due to new software control measures
    * Removed 'Service' from all elements of script due to new software control measures
    * Removed 'QC' from all elements of script due to new software control measures
    * Synopsis within script now features links to Github project
    * Version history removed from script in favour of Github links

For a full list of releases please check the [Change Log](CHANGES.md)

## Notifications

#### Software installations have now started

![Start Notification](/Samples/Installation_Started.PNG)

#### Software installations have completed successfully

![End Notification Success](/Samples/Installation_Completed_Success.PNG)

#### Software installations have completed but encounted one or more errors

![End Notification Error](/Samples/Installation_Completed_Errors.PNG)
