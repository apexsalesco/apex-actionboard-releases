# Apex Actionboard releases

Installers and auto-update files for **Apex Actionboard**, the Apex Sales Consultants desktop app that turns Microsoft 365 email into a task list, board and time-blocking calendar.

This repository holds **release files only**. It contains no source code, settings, keys or customer data.

## Install

Download the latest **Apex-Actionboard-Setup-x.y.z.exe** from [Releases](../../releases/latest) and run it.
Windows may show "Windows protected your PC" because the installer isn't code-signed yet: choose **More info → Run anyway**.

## Updates

Installed copies check this repository on startup and every six hours. New versions download in the background and install the next time the app restarts.

Releases are published automatically by the build pipeline. Please don't upload or edit files here by hand: the `latest.yml` file in each release must match its installer exactly, or updates will fail.
