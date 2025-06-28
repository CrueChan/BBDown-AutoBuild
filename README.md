# BBDown Auto-Build

[![Auto Build](https://github.com/CrueChan/BBDown-AutoBuild/actions/workflows/auto-build.yml/badge.svg)](https://github.com/CrueChan/BBDown-AutoBuild/actions/workflows/auto-build.yml)
[![Latest Release](https://img.shields.io/github/v/release/CrueChan/BBDown-AutoBuild)](https://github.com/CrueChan/BBDown-AutoBuild/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/CrueChan/BBDown-AutoBuild/total)](https://github.com/CrueChan/BBDown-AutoBuild/releases)

Automated builds of [nilaoda/BBDown](https://github.com/nilaoda/BBDown) with pre-compiled binaries for multiple platforms.

## 🤖 What is this?

This repository automatically monitors the upstream [BBDown](https://github.com/nilaoda/BBDown) project and creates new releases with pre-compiled binaries whenever the upstream code is updated. 

**Note: This repository does NOT contain source code.** All builds are generated directly from the original [nilaoda/BBDown](https://github.com/nilaoda/BBDown) repository.

## 📦 Available Platforms

Each release includes pre-compiled binaries for:

- **Windows**: x64, ARM64
- **Linux**: x64, ARM64  
- **macOS**: x64, ARM64

## 🚀 Quick Start

1. Go to [Releases](https://github.com/CrueChan/BBDown-AutoBuild/releases/latest)
2. Download the appropriate version for your platform
3. Extract the archive
4. Run the `BBDown` executable directly

For detailed usage instructions, please refer to the [original project documentation](https://github.com/nilaoda/BBDown#readme).

## 🔄 How it works

- **Daily Check**: GitHub Actions runs daily at 2:00 AM UTC to check for upstream updates
- **Smart Detection**: Only builds when new commits are detected in the upstream repository
- **Automatic Release**: Creates a new release with all platform binaries when updates are found
- **Version Format**: `vYYYYMMDD-{commit}` (e.g., `v20250628-a1b2c3d`)

## 📋 Build Status

The latest build status and logs can be viewed in the [Actions tab](https://github.com/CrueChan/BBDown-AutoBuild/actions).

## 🔗 Related Links

- **Original Project**: [nilaoda/BBDown](https://github.com/nilaoda/BBDown)
- **Documentation**: [BBDown Wiki](https://github.com/nilaoda/BBDown#readme)
- **Issues**: Please report BBDown-related issues to the [original repository](https://github.com/nilaoda/BBDown/issues)
- **Build Issues**: For problems with automated builds, open an issue [here](https://github.com/CrueChan/BBDown-AutoBuild/issues)

## ⚠️ Disclaimer

This is an unofficial automated build repository. For official releases and support, please visit the [original BBDown project](https://github.com/nilaoda/BBDown).

## 📄 License

This repository's automation scripts are provided as-is. The BBDown software itself is licensed under the terms specified in the [original repository](https://github.com/nilaoda/BBDown/blob/master/LICENSE).

---

**Star ⭐ this repository if you find these automated builds helpful!**
