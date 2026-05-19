<#
.SYNOPSIS
    This PowerShell script ensures that the maximum size of the Windows Application event log is at least 32768 KB (32 MB).

.NOTES
    Author          : Brandon Kissinger
    LinkedIn        : www.linkedin.com/in/brandon-kissinger-b52a386
    GitHub          : github.com/BkissingerPepper
    Date Created    : 2026-05-19
    Last Modified   : 2026-05-19
    Version         : 1.0
    CVEs            : N/A
    Plugin IDs      : N/A
    STIG-ID         : WN11-AU-000500
    Documentation   : https://stigaview.com/products/win11/v2r7/WN11-AU-000500/

.TESTED ON
    Date(s) Tested  : 
    Tested By       : 
    Systems Tested  : 
    PowerShell Ver. : 

.USAGE
    Put any usage instructions here.
    Example syntax:
    PS C:\> .\__remediation_template(STIG-ID-WN10-AU-000500).ps1 
#>

# # Set Application Event Log max size to 32768 KB (32 MB)
Set-ItemProperty -Path "HKLM:\SOFTWARE\Policies\Microsoft\Windows\EventLog\Application" `
  -Name "MaxSize" `
  -Value 32768 `
  -Type DWord
