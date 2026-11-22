---
title: PDF Portal Professional Privacy Policy
---

# PDF Portal Professional Privacy Policy

Effective date: 2026-11-22

This policy covers PDF Portal Professional, published by MindtheApp.

PDF Portal Professional does not collect usage data or analytics. It has no accounts, no advertising and no usage tracking. Your drawings and documents are never sent to us. Two things can reach us: crash reports, which you can turn off at any time (see "Crash reports" below), and a feedback message, only if you write one and press Send (see "Feedback" below).

## Your documents stay on your PC

PDF Portal Professional opens, reads, measures, marks up and saves your files on your own computer. It never uploads your documents, and we have no servers that receive them. The built-in PDF viewer can only load the app's own files. It is blocked from reaching any other web address.

## Data that stays on your PC

- Your settings, in `settings.json` in the app's data folder (`%LOCALAPPDATA%\PortalPlans`, or inside the app's package folder for the Store version).
- The list of recently opened files (file names, folders and pins), in `recent.json` in the same folder.
- Your saved signatures, in the Signatures folder.
- The viewer's private browser profile.
- A short error note in the Logs folder if something goes wrong. The log files are never sent.
- Your crash report choice, in a small file called `crash-reporting.json`.
- Temporary working copies of files you open, in the app's temporary folder.
- A feedback message that could not be sent yet (see below).

None of this is sent to us. The Store version removes it when you uninstall the app. In **About**, "Open data folder" shows you where it is.

## What the app writes into your PDF

When you measure, set a scale or add markups, the app saves them inside the PDF file you are working on, as standard PDF annotations. It also adds its own data entries to the file, named `PPLN_Data`, `PPLN_Doc`, `PPLN_Scale` and `PPLN_ScaleId`, so it can read your measurements and scales back later. These stay in the file. If you share the PDF, the other person can see them. The app does not send them anywhere.

Each markup can carry an author name. The author name is empty by default. If you want one, you type it yourself in **Settings**. The app never reads the name of your Windows account. The author name is stored in the PDF only, and shown in the app's markup list.

## Crash reports

Crash reports are on by default, to help us find and fix problems. When you first start the app, it shows this as a ticked option, with a "What's sent" link that lists what a report contains. To turn crash reports off, untick it there, or switch off the crash reports toggle in **Settings > Privacy** at any time. When it is off, nothing is sent and any reports still waiting to go are deleted.

When on, and the app runs into an error, it sends a report so we can find and fix the problem. A report contains only:

- the type of error and the stack, which is the list of the app's code (method and file names) that was running, with folder names, your user name and your PC name replaced;
- where in the app the error was caught;
- the app name ("PDF Portal Professional"), version and channel (Store, sideload or development build);
- the Windows version and the .NET runtime version.

The text of the error message is removed before sending, because it can contain text from a drawing. A report never contains your documents or anything from them, file names, folder paths, your user name, your PC name, logs, settings or screenshots. No usage sessions, performance data or user details are sent.

Reports go to Sentry (Functional Software, Inc.), in its EU data region, in a project used for PDF Portal. Like any internet connection, the service sees your IP address while a report is delivered, but IP addresses are not stored. Reports are kept for 90 days and then deleted automatically.

## Feedback

Once the app is in the Microsoft Store, it may now and then show a small card asking for a Store review or for feedback. It never appears in the first 3 days, and not more often than every 4 days. The card sends nothing to us. A Store rating opens Windows' own rating dialog, or the app's Store page, and is handled by the Microsoft Store. Only the dates and your choices about the card are kept on your PC, in the settings file. "Not now" and "Don't ask again" stop it.

"Send feedback" is in **About**. When you press Send, this goes to our feedback service, Sentry (Functional Software, Inc., EU data region):

- the message you wrote, with file and folder paths and your Windows user name removed first;
- your e-mail address, only if you typed one, used only to reply to you;
- a picture, only if you chose one;
- the kind of message you chose, a random ID for the message, the app name, version and channel (Store or portable), and the Windows and .NET versions.

Nothing is sent unless you press Send. No documents, logs, settings, user name or PC name are sent.

If a message cannot be sent (for example while you are offline), it is kept on your PC in the Feedback folder in the app's data folder and sent the next time the app starts. To remove it, delete the files in that folder or uninstall the app. Feedback is kept for the period set by our feedback service plan. To have a message deleted sooner, email us (see Contact).

## Plus and Professional features, and the Microsoft Store

PDF Portal Professional has free features and paid features. TBPDF Portal Professional checks your licence through the Microsoft Store on Windows. We receive no licence or purchase data; that stays with Microsoft. rchases are handled by the Microsoft Store. We receive no payment details and no personal information from a purchase.

## Links, fonts and text recognition

- A link inside a PDF is only opened after you confirm, in your default browser or mail app; that app then handles the request.
- Text recognition (OCR) runs on your PC. The recognition models come with the app. Windows may download its own recognition files the first time its OCR is used.
- When the text editor cannot find a font on your PC, it offers "Get it from Google Fonts". Only if you click it, the app downloads that font from Google Fonts (fonts.googleapis.com) and its licence from Google's font repository on GitHub (raw.githubusercontent.com). The request contains the font's name and nothing from your document. Like any web request, Google and GitHub receive your IP address.

## Children

The app is not directed at children. It collects no personal information, except what someone chooses to put in a feedback message. Crash reports contain no personal information.

## Changes

If this policy changes, the updated policy will be published at this address.

## Contact

Questions: email [mindthaapp@gmail.com](mailto:mindthaapp@gmail.com).
