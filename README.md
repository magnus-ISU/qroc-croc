# qroc-croc

Create QR codes for [croc file transfer](https://github.com/schollz/croc) to be used for the android app.

## Usage:

On your desktop, run:

```
qroc file-to-transfer
```

On android, open a QR scanner and scan the QR code that appears on your computer. Copy the text, and open [Croc for Android](https://github.com/howeyc/crocgui) and paste into the download box.

Once the file is transferred, the popup on the desktop will also close.

## Goals

The goal is to also create either a flutter app, or fork of schollz/croc, which has QR scanning built into it already so the extra steps are not necessary.
