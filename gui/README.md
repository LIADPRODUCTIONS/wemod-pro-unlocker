<div align="center">
  <h1>WeMod Pro Unlocker - GUI</h1>
  <h4>This program patches the WeMod app to think you're a pro subscriber.</h4>
  <img src="https://img.shields.io/github/downloads/LIADPRODUCTIONS/wemod-pro-unlocker/total" alt="Downloads on GitHub">
  <img src="https://img.shields.io/github/v/release/LIADPRODUCTIONS/wemod-pro-unlocker.svg" alt="Latest version">
  <img src="https://img.shields.io/crates/l/wemod-pro-unlocker?color=green" alt="License">

  <img src="https://img.shields.io/badge/.NET-512BD4?logo=dotnet" alt=".NET">
  <img src="https://img.shields.io/badge/Windows-10+11-0078D4?logo=windows-11" alt="Windows 10 and 11">
  <img src="https://img.shields.io/github/languages/code-size/LIADPRODUCTIONS/wemod-pro-unlocker?color=yellow" alt="Code Size"><br/><br/>
  <img width="256" src="https://user-images.githubusercontent.com/110846042/204567385-4df3007c-7a63-40fd-9feb-f9f36aa43030.png" alt="WeMod Pro Unlocker Logo">
</div>

#### [Back to the main page](../README.md)

#### All requirements needed for the CLI will come packaged with this app.
This means that you won't need Node.JS or asar on your system.

<br/>

## ⬇️ Installation

You can download the `gui-x64.msix` and `WeMod-Pro-Unlocker.cer` files from our [releases page](https://github.com/LIADPRODUCTIONS/wemod-pro-unlocker/releases).

Our GUI app is distributed as a Windows App Package (`.msix`). Because we're using a special test certificate for now, you'll need to do a quick setup step once to allow your computer to trust our app.

**What you'll need to download:**

* `gui-x64.msix` (the app package)
* `WeMod-Pro-Unlocker.cer` (our test certificate file)

**Step 1: Install Our Test Certificate**

You only need to do this step **once** per computer.

1.  Download both `gui-x64.msix` and `WeMod-Pro-Unlocker.cer` to your computer.
2.  Double-click on the `WeMod-Pro-Unlocker.cer` file.
3.  Click on **"Install Certificate..."**.
4.  In the Certificate Import Wizard:
    * Select **"Local Machine"**.
    * Click **"Next"**.
    * Select **"Place all certificates in the following store"**.
    * Click **"Browse..."**.
    * Choose **"Trusted Root Certification Authorities"** from the list.
    * Click **"OK"**.
    * Click **"Next"**.
    * Click **"Finish"**.
5.  If prompted by a security warning, click **"Yes"**.
6.  Click **"OK"** when the import is successful.

**Step 2: Install the App**

Now that your computer trusts our certificate, you can install the app.

1.  Double-click on the `gui-x64.msix` file.
2.  Click **"Install"**.

<br/>
