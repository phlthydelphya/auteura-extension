# Auteura privacy policy

*Effective October 12, 2026*

This policy covers the Auteura browser extension, from the Chrome Web Store and Microsoft Edge Add-ons. The short version: Auteura doesn’t send, sell, or share any of your data. Everything it does happens on your device.

## What leaves your device

Nothing. Auteura handles two kinds of data, and only on your device: the video from your camera (see **Your camera**) and the site names of tabs using the virtual camera (see **What’s stored on your device**). Auteura has no servers, no accounts, no analytics, no ads, and no tracking. The extension makes no network requests of its own, and its pages run under a content security policy that only lets them load the extension’s own files.

## Your camera

Auteura opens your camera only when a website asks for the Auteura Virtual Camera (or for any camera, if **Default camera for sites** is on), and only under the camera permission you gave that website. Video frames are processed inside that browser tab, on your device. They aren’t recorded, stored, or sent anywhere by Auteura.

The processed video goes to the website that asked for it, the same way your real camera’s video would. What that website does with it is covered by that website’s own privacy policy.

Person detection (for background blur, Follow me, portrait light, and skin smoothing) uses Google’s MediaPipe library and model, bundled inside the extension. The library includes a usage-telemetry client; Auteura blocks it, so the library can only reach the extension’s own files.

## Websites you visit

So that sites can see the virtual camera in their camera list, Auteura adds a small script to `https://` pages (and `localhost`). That script only answers the page’s requests for cameras. It doesn’t read, collect, or change the page’s content, and Auteura doesn’t keep a record of the sites you visit, beyond the session-only list of tabs using the camera (see below).

## What’s stored on your device

Auteura keeps these in the browser’s extension storage, on your device only. They’re never sent anywhere.

- Your settings (framing, background, look, color, finish, and output size and frame rate).
- `.cube` LUT files you import.
- The names of your cameras and the settings they report, so the panel can show them.
- The accent color you choose. The eyedropper reads only the one color you click.
- While the browser is open: which tabs are using the virtual camera and their site names, for the “Live in …” indicator and the LIVE badge. This is cleared when the browser closes.

Removing the extension deletes all of it.

## Chrome Web Store user data policy

Auteura’s use of information complies with the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/user-data-faq), including the Limited Use requirements. Since no user data leaves your device, Auteura doesn’t sell, transfer, or use any for advertising, creditworthiness, or any purpose other than the extension’s single purpose.

## Changes

If this policy changes, the new version will be posted here with a new effective date. The history of changes is in this repository’s commit log.

## Contact

Questions about privacy? [Open an issue](https://github.com/phlthydelphya/auteura-extension/issues).
