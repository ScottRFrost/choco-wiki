# Legalities and Distributions
### What you need to know

When you run Chocolatey without any arguments or the [[help command|CommandsHelp]], it will display both the package license acceptance terms and the waiver of responsibility. These are displayed here as well for reference.

## Package License Acceptance Terms
The act of running Chocolatey to install a package constitutes acceptance of the license for the application, executable(s), or other artifacts that are brought to your machine as a result of a Chocolatey install. This acceptance occurs whether you know the license terms or not. It is suggested that you read and understand the license terms of any package you plan to install prior to installation through Chocolatey. If you do not accept the license of a package you are installing, please uninstall it and any artifacts that end up on your machine as a result of the install.

## Waiver of Responsibility
The use of Chocolatey means that an individual using Chocolatey assumes the responsibility for any changes (including any damages of any sort) that occur to the system as a result of using Chocolatey. This does not supercede the verbage or enforcement of the license for Chocolatey (currently Apache 2.0), it is only noted here that you are waiving any rights to collect damages by your use of Chocolatey. It is recommended you read the license (http://www.apache.org/licenses/LICENSE-2.0) to gain a full understanding (especially section 8. Limitation of Liability) prior to using Chocolatey.

## Distributions aka Chocolatey packages
Most Chocolatey packages do not contain actual software distributions, only instructions for getting distributions (in PowerShell).  In a nutshell, the instructions are:

 * Download a distribution from remote location, most likely the published download location
 * Run an installer (possibly in silent mode)

Because this is no different than what a human would do, and b/c a human kicks off this process, it's reasonable to determine that there is no violation of distribution rights.

In the cases where you would package the actual software in the package, please ensure you have distribution rights. Any package that is found not to be compliant with this rule will be removed immediately.
