# EffortlessHome Cloud Add-on

Connect your Home Assistant instance to EffortlessHome Cloud services with integrated Matter Hub support.

## About

This add-on provides:
- **Cloudflare Tunnel** - Secure remote access to your Home Assistant
- **Matter Hub** - Native Matter protocol bridge for smart home devices
- **Unified Web Dashboard** - Single interface accessible on one port

## Features

### Main Dashboard
- Monitor EffortlessHome Cloud connection status
- View system information
- Manage tunnel configuration
- Accessible at: `http://[addon-ip]:18080/`

### Matter Hub
- Add and manage Matter devices
- Configure Matter bridges
- View device status and capabilities
- Accessible at: `http://[addon-ip]:18080/matter/`

Both interfaces run on the **same port (18080)** for simplified access.

## Configuration

```yaml
email: your-email@example.com
password: your-password
system_id: your-system-id (optional if you have only one system)
ha_url: http://homeassistant.local:8123
dashboard_port: 18080
```

### Configuration Options

- `email` (required): Your EffortlessHome account email
- `password` (required): Your EffortlessHome account password
- `ha_url` (required): Home Assistant URL (default: http://homeassistant.local:8123)
- `dashboard_port` (optional): Port for web interface (default: 18080)

## Plan Requirements

This add-on requires Feature ID `2` (Remote Access) in your subscribed plan.
Systems on the Basic plan do not include this feature, so the add-on will not start.
Upgrade to a plan higher than Basic to use the EffortlessHome add-on.

## Installation

1. Add this repository to your Home Assistant add-on store
2. Install the "EffortlessHome Cloud" add-on
3. Configure your credentials
4. Start the add-on
5. Access the dashboard at `http://[homeassistant-ip]:18080/`

## Data Persistence

The add-on stores data in `/data`:
- `/data/matter` - Matter device configurations and pairings
- `/data/options.json` - Add-on configuration

This data persists across add-on restarts and updates.

## Technical Details

See [MATTER_INTEGRATION.md](../MATTER_INTEGRATION.md) for technical documentation about the Matter integration architecture.

## Support

For support, visit [EffortlessHome](https://effortlesshome.co)
