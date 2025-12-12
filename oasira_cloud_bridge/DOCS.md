# EffortlessHome Cloud Bridge Documentation

## Configuration Options

### Required Settings

- **email**: Your EffortlessHome account email address
- **password**: Your EffortlessHome account password

### Optional Settings

- **system_id**: Specific system ID if you have multiple systems (auto-detected if you have only one)
- **ha_url**: Home Assistant URL (default: `http://homeassistant.local:8123`)
- **dashboard_port**: Port for the web dashboard (default: `8080`)

## Features

### Cloudflare Tunnel
Automatically establishes a secure Cloudflare tunnel for remote access to your Home Assistant instance.

### Matter
Adds Matter device export support to Home Assistant.

### Web Dashboard
Provides a web interface for monitoring and managing your EffortlessHome services.

## Troubleshooting

### Add-on won't start
1. Check that your email and password are correct
2. Verify you have an active EffortlessHome account
3. Check the add-on logs for specific error messages

### Services not connecting
- Ensure your internet connection is stable
- Verify your EffortlessHome account has active services
- Check that the required ports are not blocked by your firewall

## Support

For additional help, contact EffortlessHome support at https://www.effortlesshome.co
