WindowsRegeditPrivacyOptions
====================================================================================================================


I cannot accept responsibility for any potential outcomes affecting your system. You are proceeding at your own risk.


:joystick: How to use?
--------------------------------------------------------------------------------------------------------------------


- You must run the bat files with administrator privileges.
- You also should not run the last telemetry option if you use laptops that have a fingerprint sensor.


:notebook: About
--------------------------------------------------------------------------------------------------------------------


- `Disable Affected Services:` Use 'net stop' to stop services, and 'sc config' to set them as 'disabled' so they won't start upon reboot.
- `Disable Auto Clean up and Turn off Automatic Updates:` Disable autorun for drives and programs, recent files in the start menu, File History, Windows search indexing device history, apps accessing call history, and Windows Update's automatic installations.
- `Disable Cortana Services:` Set four specific registry keys to 0 to fully disable Cortana.
- `Disable Spying Services:` Stop and configure specific services, like dmwappushservice, diagnosticshub.standardcollector.service, DcpSvc, WerSvc, PcaSvc, DoSvc, and WMPNetworkSvc, to start disabled.
- `Disable Unnecessary Services:` Protect user privacy by disabling Windows data collection services such as Diagnostics Hub, App Compatibility, Input Personalization, and Tablet PC.
- `Disable XBox Services:` Disable the XblAuthManager, XblGameSave, and XboxNetApiSvc services.
- `Remove Scheduled Telemetry Tasks From Scheduler:` Disable tasks related to Windows services, including File History, SmartScreen warnings, AitAgent, CreateObjectTask, and customer experience data collection. Other tasks include system analysis, Family Safety monitoring and settings refresh, and system file integrity checking.
