# Change Log
- v5.1 (Released: 10/11/2020)
    * Updated 'Datacentre Install' function to include 'HexEdit-Shortcut' function ([Issue Ref: #5](https://github.com/dpritchett441/Technolog_Software_Installs/issues/5))
    * Amended Oracle package in software list ([Issue Ref: #6](https://github.com/dpritchett441/Technolog_Software_Installs/issues/6))
- v5.0 (Released: 17/10/2020)
    * Border added to 'installation menu' GUI to help offset from background
    * Removed legacy 'Explorer-Shortcut' function ([Issue Ref: #4](https://github.com/dpritchett441/Technolog_Software_Installs/issues/4))
    * Progress bar now added to display during software installations ([Issue Ref: #2](https://github.com/dpritchett441/Technolog_Software_Installs/issues/2))
    * Installation functions updated to provide dynamic updates to progress bar
    * All 'Invoke' commands replaced with 'Start-Process' ([Issue Ref: #3](https://github.com/dpritchett441/Technolog_Software_Installs/issues/3))
        > Previously
        ```powershell
        $SoftwareName = { & "\\Server\Share\Setup.exe" *Arguments* }
        ```
        > Now
        ```powershell
        $SoftwareName = { Start-Process -FilePath "\\Server\Share\Setup.exe" -ArgumentList *Arguments* -Wait }
        ```
- v4.2 (Released: 09/10/2020)
    * Removed 'Production' from all elements of script due to new software control measures
    * Removed 'Service' from all elements of script due to new software control measures
    * Removed 'QC' from all elements of script due to new software control measures
    * Synopsis within script now features links to Github project
    * Version history removed from script in favour of Github links
- v4.1 (Released: 29/09/2020)
    * Fixed issue what was causing the 'Get-Date' command in the error log to return incorrectly
- v4.0 (Released: 19/09/2020)
    * Introduced 'USL Tablet Install' function and accompanying button
    * Introduced 'Production Install' function and accompanying button
    * Introduced 'QC Install' function and accompanying button
    * Introduced 'Service Install' function and accompanying button
    * Updated to include OpenOffice in the software list
    * Updated to include 'QC Software' in the software list
    * Updated to include 'Service Software' in the software list
- v3.0 (Released: 11/09/2020)
    * Script now featues a GUI to receive inputs instead of the previous terminal method
    * Terminal display preference function added to accomodate GUI (Default: Hidden)
    * Reworked synopsis and code tagging to reflect intoduction of GUI
    * Improved formatting throughout for easier viewing
    * Implemented error logging to a centralised location (\\NAS\IT\Install Error logs\)
    * Notifications are now displayed at the beginning and end of the software installations
- v2.1 (Released: 02/09/2020)
    * Removed McAfee Endpoint and McAfee Agent from software list as CrowdStrike is now live
    * Removed McAfee Endpoint and McAfee Agent from install functions as CrowdStrike is now live
- v2.0 (Released: 20/08/2020)
    * Updated to include the CrowdStrike package in software list
    * Updated to include the CrowdStrike package in install functions
- v1.0 (Released: 24/06/2020)
    * Initial creation
