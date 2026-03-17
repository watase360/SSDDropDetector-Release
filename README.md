# SSDDropDetector-Release
Standalone Win32 installer for SSD Drop Detector (Hardware benchmark tool). Requires UAC to read physical SSD temps via DeviceIoControl.
This release contains the standalone Win32 installer (.exe) for SSD Drop Detector, designed for the Microsoft Store submission.

For Microsoft Store Reviewers:

This application is a hardware diagnostic tool that monitors physical SSD temperatures and speeds during stress tests.

It natively requires Administrator privileges (UAC) to access S.M.A.R.T. data via Windows APIs (DeviceIoControl).

It does NOT install any custom 3rd-party drivers or background services.
