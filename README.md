# EffortlessHome Home Assistant Add-ons

Home Assistant add-ons repository for effortlesshome.


## Installation

Add this repository to your Home Assistant instance:

1. Navigate to **Settings** → **Add-ons** → **Add-on Store**
2. Click the **⋮** (three dots) in the top right
3. Select **Repositories**
4. Add this URL: `https://github.com/EffortlessHome/effortlesshome_addon`
5. Click **Add**

## Available Add-ons

### EffortlessHome Cloud

Connect your Home Assistant to effortlesshome Cloud services with:
- **Cloudflare Tunnel** - Secure remote access
- **Matter Hub Integration** - Matter protocol bridge for smart home devices
- **Unified Web Dashboard** - Single interface for all features

#### Features

- **Main Dashboard** (accessible at `/`) - Monitor and manage effortlesshome services
- **Matter Hub UI** (accessible at `/matter/`) - Configure and manage Matter devices
- Single port (8080) for both interfaces
- Automatic authentication using effortlesshome credentials
- Persistent storage for Matter devices

See [MATTER_INTEGRATION.md](MATTER_INTEGRATION.md) for technical details about the Matter integration.

## Support

For support and questions, visit [effortlesshome](https://effortlesshome.co)
