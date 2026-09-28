# OpenCode Personal Configuration

**PRIVATE REPO** - Contains local network configuration

Personal OpenCode configuration for michaelw924.

## Setup

1. Clone this repository privately:
   ```bash
   git clone git@github.com:michaelw924/opencode-config.git ~/.config/opencode
   ```

2. Copy the template config and update with your local IP:
   ```bash
   cp config.template.json config.json
   # Edit config.json and replace <YOUR_LOCAL_IP> with your actual IP
   ```

3. Install dependencies (if needed):
   ```bash
   cd ~/.config/opencode
   npm install
   ```

## Files

- `config.json` - **DO NOT COMMIT** - Contains local IP addresses (private)
- `config.template.json` - Template for config.json (safe to share)
- `config.jsonc` - Extended configuration (if needed)

## Security Note

This repository contains private network configuration. Keep it private and do not share publicly.
