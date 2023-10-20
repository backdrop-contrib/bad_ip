# Bad IP

This module check the users accessing a site using the
[IP Intelligence](https://getipintel.net/) service and doesn't allow them to
create an account if the service reports the IP to be a proxy / VPN / bad IP.
Other operations could be slowed down or not allowed.


## Requirements

This module requires Backdrop 1.22.0 and PHP 8.1.

Consult your server administrator or hosting provider if you are unsure about
these requirements.


## Installation

- Install this module using the official Backdrop CMS instructions at
  [Extend with Modules](https://docs.backdropcms.org/documentation/extend-with-modules).

- Visit the configuration page under
  Administration > Configuration > Web services > Bad IP
  (admin/config/services/bad-ip) and change the settings.


## Issues

Bugs and Feature requests should be reported in the [issue queue](https://github.com/backdrop-contrib/bad_ip/issues).


## Current Maintainers

- [kiamlaluno](https://github.com/kiamlaluno)


## License

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
