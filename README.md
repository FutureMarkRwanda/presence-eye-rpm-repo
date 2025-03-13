# Presence Eye RPM Repository

This repository provides the `presence-eye` RPM package for Fedora, allowing you to install the Presence Eye application, which controls PresenceEye Smart Extensions and configures B-Bot.

## Installation Instructions

To install `presence-eye` on Fedora, follow these steps:

1. **Add the repository**:
   ```bash
   sudo curl -o /etc/yum.repos.d/presence-eye.repo https://raw.githubusercontent.com/FutureMarkRwanda/presence-eye-rpm-repo/main/presence-eye.repo
   ```

2. **Refresh DNF cache**:
   ```bash
   sudo dnf makecache
   ```

3. **Install Presence Eye**:
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
- This repository does not use GPG signing (`gpgcheck=0`). For a signed version, contact the maintainer.

## Maintainer
- HIRWA RUKUNDO Hope <rw.byose@gmail.com>
