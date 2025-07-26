<div align="center">
  <h1>WeMod Pro Unlocker</h1>
  <h4>This program patches the WeMod app to think you're a pro subscriber.</h4>
  <img src="https://img.shields.io/github/v/release/bennett-sh/wemod-pro-unlocker.svg" alt="Latest version">
  <img src="https://img.shields.io/github/downloads/bennett-sh/wemod-pro-unlocker/total?label=GitHub%20Downloads" alt="Downloads on GitHub">
  <img src="https://img.shields.io/crates/l/wemod-pro-unlocker?color=green" alt="License"><br/>
  <img src="https://img.shields.io/badge/rust-2021-orange?logo=rust" alt="Rust 2021">
  <img src="https://img.shields.io/badge/.NET-512BD4?logo=dotnet" alt=".NET">
  <img src="https://img.shields.io/badge/Windows-10+11-0078D4?logo=windows-11" alt="Windows 10 and 11">
  <img src="https://img.shields.io/github/languages/code-size/bennett-sh/wemod-pro-unlocker?color=yellow" alt="Code Size"><br/><br/>
  <img width="256" src="https://user-images.githubusercontent.com/110846042/204567385-4df3007c-7a63-40fd-9feb-f9f36aa43030.png" alt="WeMod Pro Unlocker Logo">
</div>

<br/>

## ⬇️ Installation
There's two things you can install:
- [A CLI (easier to install)](cli/README.md)
- [A GUI desktop application (easier to use)](gui/README.md)

**How to Install the GUI App (for Testing)**

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

## ❌ What does not work?
- RC from phone (this feature is not client-side so you actually need pro; there's nothing I can do)

<br/>

## 🔒 Is it safe?
This program may sound like malware at first, but if you're unsure, just read the source code. It's quite small and (hopefully, I'm relatively new to Rust) readable.

<br/>

## ❓ It stopped working after the latest update, what should I do?
This is probably because WeMod updated itself and now uses a new directory. To fix this, just run the program again.

<br/>

## 🫂 Contributors
<a href="https://github.com/bennett-sh/wemod-pro-unlocker/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=bennett-sh/wemod-pro-unlocker" />
</a>
