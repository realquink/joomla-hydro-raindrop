# Hydro Raindrop Joomla plugin 

![Hydro Logo](https://i.imgur.com/slcCepB.png)

Welcome to the Hydro Raindrop Joomla plugin repository on GitHub.

The `Joomla Hydro Raindrop` plugin provides Hydro Raindrop Multi Factor Authentication to your Joomla site.

## Installation

Download from extensions.joomla.org (soon available).

## Manual installation

- Download and install fresh copy of Joomla (optional)
- 1
- 2
- 3


## Usage instructions

1. Login to your Joomla site as administrator.
2. Go to `Plugins` and search for the `Joomla Hydro Raindrop` plugin. Open this up and enable the plugin

If you don't have a **Hydrogen Developer Account**, go to [www.hydrogenplatform.com](https://www.hydrogenplatform.com) to register an account.

1. Under `Settings` navigate to the `Hydro Raindrop MFA` section and input your Application information to enable Hydro Raindrop MFA to your Joomla site. 
2. Under `Edit My Profile`, enter your HydroID in the `Hydro Raindrop MFA` section.
3. Follow the verification procedure to activate MFA for your account.

Site Editors / Authors / etc. can enable the Hydro Raindrop MFA from their profile page.

## Requirements

* **SSL MUST be enabled for MFA to work.**
* PHP 7.0 or higher is required.

## Customization

### Custom MFA page

* Login as a Site Editor
* Create a page (programmatically)
* Use the following shortcodes on this page (required!):
    - `[hydro_raindrop_mfa_form_open]`: renders the form opening element.
    - `[hydro_raindrop_mfa_form_close]`: renders closing element with the wp_nonce field.
    - `[hydro_raindrop_mfa_digits]`: renders 6 digits which should be entered into the Hydro app.
    - `[hydro_raindrop_mfa_button_authorize]`: renders the "Authorize" button; customize the look of the button using CSS class `hydro-raindrop-mfa-button-authorize`.
    - `[hydro_raindrop_mfa_button_cancel]`: renders the "Cancel" button; customize the look of the button using CSS class `hydro-raindrop-mfa-button-cancel`.
* Under `Setting` navigate to the `Hydro Raindrop MFA` section and select the page you created.

## Documentation

https://www.hydrogenplatform.com/developers

## Issues

https://github.com/DaveM2011/joomla-hydro-raindrop/issues

## Support

https://github.com/DaveM2011/joomla-hydro-raindrop/issues

## Contributing to Hydro Raindrop Joomla plugin

If you want to address an issue/bug, please create an issue first.
