---
description: >-
  Explaining how to exclude the Raft Mod Loader from the Windows Defender
  antivirus
---

# Windows Defender

Go into "Windows Security" -> "Virus & threat protection". Then click on "Manage settings" under "Virus & threat protection settings":

<div align="left"><figure><img src="../../../.gitbook/assets/grafik (4) (1).png" alt=""><figcaption></figcaption></figure></div>

Scroll down to Exclusions and click on "Add or remove exclusions":&#x20;

<div align="left"><figure><img src="../../../.gitbook/assets/grafik (5) (1).png" alt=""><figcaption></figcaption></figure></div>

Click on "Add an exclusion" -> "File" then select the **RMLLauncher.exe**.

Do that again but instead of selecting "File" you now want to select "Folder" and exclude the **RaftModLoader** folder which is located at **C:\Users\YourUserName\AppData\Roaming\RaftModLoader** .

This is how the exclusions should look like in the end:

<div align="left"><figure><img src="../../../.gitbook/assets/grafik (6) (1).png" alt=""><figcaption></figcaption></figure></div>

Finally restart the computer to apply the settings!

## Aaaand you're done !

**Simply restart our launcher and it should be working !** :thumbsup:
