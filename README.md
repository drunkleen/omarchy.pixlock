# Omarchy Pixlock

An Omarchy lock-screen plugin with a pixel-font clock, day/date, password authentication, fingerprint support, and FIDO2 security-key authentication.

When a registered FIDO2 key is present, the lock screen prompts for a touch and authenticates through `omarchy-lock-fido2`. When no key is present, it keeps the password field available. Password input remains automatically focused as a fallback.

## Install

Install it through Omarchy's plugin manager or clone it into the local plugin directory:

```bash
omarchy plugin add git@github.com:drunkleen/omarchy.pixlock.git --enable
```

This plugin is intended for Omarchy's Quickshell environment and requires the corresponding FIDO2 PAM service to be configured if security-key unlock is desired.
