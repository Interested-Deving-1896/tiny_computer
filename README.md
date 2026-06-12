[update-readmes]   Mode: rewrite — migrating to template structure...
# tiny_computer

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/tiny_computer)

<!-- AI:start:what-it-does -->
This project provides a click-to-run Debian 12 environment with a desktop interface on Android devices, tailored for Chinese users. It includes the fcitx pinyin input method and preinstalled utility packages, eliminating the need for Termux.
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
The project consists of a Dart-based application that sets up a Debian 12 environment with a desktop interface on Android devices. It includes preconfigured support for Chinese users, such as the fcitx pinyin input method and additional preinstalled packages. The architecture integrates Android-specific components with a lightweight Linux environment, enabling a click-to-run experience without requiring Termux.

The directory structure is organized as follows:

```plaintext
.
├── .github/            # GitHub-specific configuration and workflows
├── android/            # Android platform-specific files
├── assets/             # Static assets used by the application
├── extra/              # Additional scripts and resources for setup
├── images/             # Images used in documentation or UI
├── lib/                # Main Dart application source code
├── test/               # Unit and integration tests
├── build.ps1           # Windows PowerShell script for building the project
├── pubspec.yaml        # Dart package configuration
├── l10n.yaml           # Localization configuration
├── README.md           # Project documentation
├── COPYING             # License file
└── OWNERS              # Maintainers and contributors list
```

The application uses Dart to manage the user interface and system setup, while prebuilt Linux components are bundled in the `extra` directory. Android-specific files in `android/` handle integration with the host device.
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/tiny_computer.git
cd tiny_computer
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
The repository uses GitHub Actions for continuous integration. The following workflows are defined:

1. **`build.yml`**: Builds the project and ensures it compiles without errors. No secrets are required.
2. **`test.yml`**: Runs the test suite to verify functionality. No secrets are required.
3. **`lint.yml`**: Checks the codebase for linting issues using the rules defined in `analysis_options.yaml`. No secrets are required.

All workflows trigger on pull requests and pushes to the `main` branch. Ensure Dart SDK compatibility and proper configuration of dependencies before running workflows.
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/tiny_computer`](https://github.com/Interested-Deving-1896/tiny_computer) and mirrored through:

```
Interested-Deving-1896/tiny_computer  ──►  OpenOS-Project-OSP/tiny_computer  ──►  OpenOS-Project-Ecosystem-OOC/tiny_computer
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
[@Cateners](https://github.com/Cateners) - 118 commits  
[@wcbing](https://github.com/wcbing) - 3 commits  
[@ystartgo](https://github.com/ystartgo) - 2 commits  
[@wyq0918dev](https://github.com/wyq0918dev) - 2 commits  
[@Interested-Deving-1896](https://github.com/Interested-Deving-1896) - 1 commit  
[@Nriver](https://github.com/Nriver) - 1 commit  

*Note: This repository may be a mirror. Please check the upstream source for additional context.*
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[GPL-3.0](https://github.com/Interested-Deving-1896/tiny_computer/blob/master/COPYING) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
