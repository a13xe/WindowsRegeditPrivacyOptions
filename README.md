![](https://img.shields.io/tokei/lines/github.com/AlexeyLepov/WindowsRegeditPrivacyOptions?style=for-the-badge)
![CodeSize](https://img.shields.io/github/languages/code-size/AlexeyLepov/WindowsRegeditPrivacyOptions?style=for-the-badge)
![Repo](https://img.shields.io/github/repo-size/AlexeyLepov/WindowsRegeditPrivacyOptions?style=for-the-badge)
![LastCommint](https://img.shields.io/github/last-commit/AlexeyLepov/WindowsRegeditPrivacyOptions?style=for-the-badge)

Windows Regedit Privacy Options
===========================================================

Protecting your privacy on Windows is no small task. With the Windows operating system collecting data on usage and performance, there are several options that can be used to limit the amount of data Windows collects and to better protect your privacy.

- `Disable Affected Services` the 'net stop' command to stop the services from running. Then, the 'sc config' command is used to set the startup type of each service to 'disabled.' This means that when the computer is restarted, the services will not start automatically.

- `Disable Auto Clean up history and Turn off automatic updates` disable autorun for all drives in the system, disable autorun for all programs, disable recent files from showing up in the start menu, disable File History, disable Windows search from indexing device history, disable applications from accessing call history, disable Windows Update from automatically downloading and installing updates.

- `Disable Cortana Services` the first three registry keys set to 0 to disable Cortana, the last one is also set to 0 to ensure that Cortana cannot be enabled.

- `Disable Spying Services` this code will stop the services and configure them to start disabled. The services that are disabled are the dmwappushservice, diagnosticshub.standardcollector.service, DcpSvc, WerSvc, PcaSvc, DoSvc, and WMPNetworkSvc

- `Disable Unnecessary Services` disable a variety of Windows data collection services, such as Diagnostics Hub, App Compatibility, Input Personalization, and Tablet PC. It is meant to protect user privacy by preventing Windows from collecting and sharing data about their usage.

- `Disable XBox Services` this code is used to disable the XblAuthManager, XblGameSave, and XboxNetApiSvc services on a Windows system.

- `Remove Scheduled Telemetry Tasks From Scheduler` this code is designed to disable several tasks associated with Windows services:
  - “File History (maintenance mode)” is used to maintain the File History backup feature.
  - “SmartScreenSpecific” is used to provide warnings to the user about potential malicious websites or downloads.
  - “AitAgent” is used to improve the experience of using the Windows operating system.
  - “CreateObjectTask” is used to provide a better experience when using Windows cloud services.
  - “Consolidator” is used to collect customer experience improvement program data. 
  - “BthSQM” is used to allow users to provide feedback on their experience with the Windows operating system. 
  - “Sqm-Tasks” is used to collect data for the Microsoft Customer Experience Improvement Program.
  - “AnalyzeSystem” is used to analyze the power efficiency of the Windows operating system.
  - “FamilySafetyMonitor” is used to monitor the activity of family members on the computer.
  - “FamilySafetyRefresh” is used to refresh the Family Safety settings.
  - “AutochkProxy” is used to check the integrity of the system files.

How to use?
===========================================================

- You must run the bat files with administrator privileges.
- You also should not run the last telemetry option if you use laptops that have a fingerprint sensor.
