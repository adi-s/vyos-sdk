# VyOS API SDK

This wrapper interacts with the VyOS API: https://docs.vyos.io/en/equuleus/automation/vyos-api.html

Implements some functionality that I needed for our internal tooling. I didn't implement everything, but contributions are welcome. Tested with the LTS release of VyOS. Future releases are added if possible.

## Installation

use composer:

```bash
composer require adi-s/vyos-sdk
```
### Supported Versions

    PHP:
    >= PHP 8.2

    VyOS: 
    1.3.x equuleus (LTS)

## Features

- Configuration Mode only atm.
- Authentication
- Save configuration to `/config/config.boot`. This saves the running configuration as the startup configuration. i.e. a reboot loads the saved config.

## Usage

tbd

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)