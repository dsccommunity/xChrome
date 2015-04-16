[![Build status](https://ci.appveyor.com/api/projects/status/gx1p29qa9ug73u0v/branch/master?svg=true)](https://ci.appveyor.com/project/PowerShell/xchrome/branch/master)

# xChrome

The** xChrome** module is a part of the Windows PowerShell Desired State Configuration (DSC) Resource Kit, which is a collection of DSC Resources produced by the PowerShell Team.
This module contains the **MSFT_xChrome** resource.
This DSC Resource allows you to install the latest version of Chrome

**All of the resources in the DSC Resource Kit are provided AS IS, and are not supported through any Microsoft standard support program or service.
The ""x" in xChrome stands for experimental**, which means that these resources will be **fix forward** and monitored by the module owner(s).

## Installation

To install **xChrome** module

*   Unzip the content under $env:ProgramFiles\WindowsPowerShell\Modules folder

To confirm installation:  

*   Run **Get-DSCResource** to see that **xChrome** is among the DSC Resources listed  

## Requirements

This module requires the latest version of PowerShell (v4.0, which ships in Windows 8.1 or Windows Server 2012R2).
To easily use PowerShell 4.0 on older operating systems, [install WMF 4.0](http://www.microsoft.com/en-us/download/details.aspx?id=40855).
Please read the installation instructions that are present on both the download page and the release notes for WMF 4.0.

## Description

The **xChrome** module contains the **MSFT_xChrome** DSC Resource.
This DSC Resource allows you to install the latest version of chrome.

## Details

**MSFT_xChrome** resource has following optionally properties:

*  **Language**: Specify the language of the browser to be installed.Default it is English.

*  **LocalPath**: The local location on the machine which can you used to place the downloaded installation file.

## Versions

1.0.0.0

*   Initial release with the following resources 
    *   MSFT_xChrome 

## Examples

### Install the Chrome browser

Install the latest chrome browser 

## Contributing
Please check out common DSC Resources [contributing guidelines](https://github.com/PowerShell/DscResource.Kit/blob/master/CONTRIBUTING.md).
