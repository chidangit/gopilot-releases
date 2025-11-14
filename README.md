# GoPilot Releases

This repository contains release binaries for [GoPilot](https://github.com/chidangit/gopilot) - a professional CLI tool designed to automate the setup and configuration of servers and development machines.

## Installation

### Quick Install (Recommended)

Install the latest version:

```bash
curl -sfL https://github.com/chidangit/gopilot-releases/releases/latest/download/install.sh | sh -
```

Or install a specific version:

```bash
curl -sfL https://github.com/chidangit/gopilot-releases/releases/download/v1.0.0/install.sh | sh -s -- v1.0.0
```

### Manual Installation

Download the binary for your platform from the [latest release](https://github.com/chidangit/gopilot-releases/releases/latest):

- **Linux AMD64**: `gopilot-linux-amd64`
- **Linux ARM64**: `gopilot-linux-arm64`
- **macOS AMD64**: `gopilot-darwin-amd64`
- **macOS ARM64**: `gopilot-darwin-arm64`
- **Windows AMD64**: `gopilot-windows-amd64.exe`

After downloading, make it executable and move it to your PATH:

```bash
# Linux/macOS
chmod +x gopilot-linux-amd64
sudo mv gopilot-linux-amd64 /usr/local/bin/gopilot

# Windows
# Move gopilot-windows-amd64.exe to a directory in your PATH
```

## Verification

Verify the installation:

```bash
gopilot version
```

## Checksums

All releases include a `checksums.txt` file with SHA256 checksums. Verify your download:

```bash
# Download checksums
curl -sfL https://github.com/chidangit/gopilot-releases/releases/download/v1.0.0/checksums.txt -o checksums.txt

# Verify binary
sha256sum -c checksums.txt
```

## About GoPilot

GoPilot is a CLI tool that automates:
- 🚀 **Server Setup**: Configure servers for Ubuntu, CentOS, Debian, and more
- 💻 **Dev Machine Setup**: Set up development environments with multiple profiles
- ⚙️ **Configurable**: YAML-based configuration for flexible customization

For more information, documentation, and source code, visit the [main repository](https://github.com/chidangit/gopilot).

## License

MIT License - see the [main repository](https://github.com/chidangit/gopilot) for license details.

