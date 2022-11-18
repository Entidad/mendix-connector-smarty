## Description
The Smarty Connector allows Mendix application users to validate and standardize addresses, and enable address auto-complete features. At Entidad, we leverage the Smarty connector to send emergency aid or relief payments to farmworker families in need. We collect and verify farmworker addresses to ensure we send emergency aid to the appropriate recipients.

## Typical usage scenario
The Smarty connector is beneficial to any developers creating apps that require address intake and verification.

## Features and limitations
* Enable address typeahead features (US Address Autocomplete, Pro Edition)
* Verify US street or mailing addresses (US Address Verification, Core Edition)
* Determine USPS address record type code
* Collect demographic information stored in Smarty’s database
* Smarty has a subscription-based model with tiered pricing plans.
* International (i.e. non-U.S.) address validation requires a separate Smarty license

## Dependencies
* Mendix 9.6.0 or higher
* Active Smarty subscription required (https://www.smarty.com/docs)
* Encryption (https://marketplace.mendix.com/link/component/1011)
* Community Commons (https://marketplace.mendix.com/link/component/170)

## Installation
1. From within Mendix Studio Pro, navigate to the Mendix Marketplace (shopping cart icon)
1. Download the Smarty Connector module from the Mendix Marketplace into your application
1. Map the application’s roles to the module’s roles
1. Explore the demo implementations by navigating to page Connector_Smarty/MainMenu as an Administrator user
     *  You’ll first need to set the API key in the Credentials configuration page   

## Configuration
* Requires specification of a valid Smarty API key

## Known bugs
* None
