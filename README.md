# Code Club Luxembourg's Scratch Modification

Welcome to the official release repository for Code Club Luxembourg's customized Scratch! This repository exclusively provides releases of our tailored Scratch environment, based on modifications made to the following projects:

- [**scratch-gui**](https://github.com/CodeClubLuxembourg/scratch-gui)
- [**scratch-vm**](https://github.com/CodeClubLuxembourg/scratch-vm)

## Purpose

While our development and modifications take place in the respective repositories linked above, this `codeclub-scratch-mod` repository is dedicated to housing the built and packaged versions ready for distribution.

## Release Process

1. **Building `scratch-vm`**:
   - Navigate to the `scratch-vm` directory.
   - Follow the build instructions available within its README.

2. **Building `scratch-gui`**:
   - Navigate to the `scratch-gui` directory.
   - Run the appropriate `npm build` command as specified in its README.

3. **Packaging the build**:
   ```bash
   tar -czvf scratch-gui-build.tar.gz ../scratch-gui/build/

## About Code Club Luxembourg

Code Club Luxembourg is an initiative dedicated to making coding accessible and fun for young learners. Through projects like this customized Scratch environment, we aim to provide an enhanced and localized coding experience tailored to our curriculum and the needs of our community.

## Contributing & Feedback

Feedback, suggestions, and contributions are always welcome! Please refer back to the original repositories ([scratch-gui](https://github.com/CodeClubLuxembourg/scratch-gui) & [scratch-vm](https://github.com/CodeClubLuxembourg/scratch-vm)) for contribution guidelines and to raise issues related to modifications.
