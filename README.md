# Presence Eye RPM Repository

This repository provides the `presence-eye` RPM package for Fedora, allowing you to install the Presence Eye application, which controls PresenceEye Smart Extensions and configures B-Bot.

## Installation Instructions

To install `presence-eye` on Fedora, follow these steps:

1. **Add the repository**:
```bash
sudo curl -o /etc/yum.repos.d/presence-eye.repo https://raw.githubusercontent.com/FutureMarkRwanda/presence-eye-rpm-repo/main/presence-eye.repo
```

2. **Import the GPG key**:
```bash
sudo rpmkeys --import https://raw.githubusercontent.com/FutureMarkRwanda/presence-eye-rpm-repo/main/RPM-GPG-KEY-presence-eye
```

3. **Refresh DNF cache**:
```bash
sudo dnf makecache
```

4. **Install Presence Eye**:
```bash
sudo dnf install presence-eye
```

After installation, you can launch the app from the terminal with `presence_eye` or find it in your application menu.

## Package Details
- **Name**: presence-eye
- **Version**: 1.0
- **Release**: 1.fc41
- **Architecture**: x86_64
- **License**: Proprietary
- **Summary**: PresenceEye Smart Extensions Control App

## Notes
- This repository uses GPG signing for security. The public key is included as `RPM-GPG-KEY-presence-eye`.

## Maintainer
- HIRWA RUKUNDO Hope <rw.byose@gmail.com>
