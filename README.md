# Windows server hardening using PowerShell DSC

This is a composite DSC resource that can be used to harden a Windows OS.  There are a number of configurable parameters,
A few of which you should set, others have been set to reasonable defaults (based on CIS where it is specific)

This is work in progress, feedback is welcome, PRs gladly considered.

## Requirements

This uses the SecurityPolicyDSC resource.

I have not tested it on anything older than Windows Server 2012R2 & 2016

Requires Powershell 2 on target server to be secure.

## Example usage

Some examples are provided Examples subfolder, if you're unfamiliar with DSC see instructions below for a walkthrough

## Instructions

To use, you need to install the SecurityPolicyDSC module & this one.  This can be done from a machine with internet access
& then transfered to the machine that you'd like to secure.  (Powershell modules are simply files & folders)

These installation steps require PowerShell 5 (to access the PS Gallery), the target host needs to be at least Powershell v2.

To install the SecurityPolicyDSC module dependency:
```
Install-Module SecurityPolicyDSC -Scope -CurrentUser
```

TODO complete instructions

## Copyright

Windows hardening DSC resource.
Copyright 2018 Stu Mace 'kewalaka', released under an Apache License.
