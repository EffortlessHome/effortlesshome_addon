# Oasira Cloud Documentation

## Configuration Options

### Required Settings

- **email**: Your Oasira account email address
- **password**: Your Oasira account password

### Optional Settings



## Plan Requirements

This add-on requires Feature (Remote Access) in your subscribed plan.
Systems on the Basic plan do not include this feature, so the add-on will not start.
Upgrade to a plan higher than Basic to use the Oasira add-on.

## Features

### Cloudflare Tunnel
Automatically establishes a secure Cloudflare tunnel for remote access to your Home Assistant instance.

### Matter
Adds Matter device export support to Home Assistant.

### Cloud Dashboard
View your Oasira dashboard online at https://dash.Oasira.co.

### Local Web App Hosting
The add-on also serves the bundled web app from the `web` folder on a separate port.
By default, this is available at `http://<home-assistant-host>:8099` and can be changed with `web_port`.

## Troubleshooting

### Add-on won't start
1. Check that your email and password are correct
2. Verify you have an active Oasira account
3. Check the add-on logs for specific error messages

### Services not connecting
- Ensure your internet connection is stable
- Verify your Oasira account has active services
- Check that the required ports are not blocked by your firewall

## Support

For additional help, contact Oasira support at https://www.Oasira.co
