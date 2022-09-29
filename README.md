# Race-o-cat <img src="docs/logo/logo-tamper.png" width="25" height="25">
> Make exploiting race conditions in web applications highly efficient and ease-of-use.

## Overview

- [Quickstart](#quickstart)
- [Architecture Overview](#architecture-overview)
- [List of Projects](#list-of-projects)
- [To-Dos](#to-dos)
- [License](#license)
- [Contributing](#contributing)
- [Author Information](#author-information)

## Quickstart

## Architecture Overview

![Race Conditions](./docs/architecture/Race-Architecture.png)

## List of Projects  

### - [Browser Extension for Firefox](./browser-extension/#readme)
Firefox browser extension for live request monitoring and intercepting the desired request which will be forwarded to the Race Dispatcher.

### - [Race Routine Infrastructure](./race-routine-infrastructure/#readme)
Race Dispatcher and Race Script to execute parallel requests against any given endpoint.


### - [OWASP Zed Attack Proxy (ZAP) Extender](./zap-extender/#readme)
ZAP Extensions to test for Race Conditions.

### - [Vulnerable web application](./vuln-webapp/#readme)
A web application with typical vulnerable use cases such as withdrawing money or excessive poll votes.

## To Dos

The following action items are considered to be implemented in a future version:
* Improve timing (by using ntp, a websocket push, or anything else) of the race server to decrease the time gap between dispatching to multiple race servers OR allow a scheduled timing option
* Allow downloading of the HTTP-Responses to analyse the success of the attack
* Allow multiple, different parameters/content of the HTTP-Request to allow improved exploitation of load balancers with sticky sessions and other attack szenarios that require custom parameters

## License
Code of Raceocat is licensed under the Apache License 2.0.

## Contributing

Feel free to open issues / pull requests if you want to contribute to this project.

## Author Information

You can reach me by email at javan.rasokat+raceocat@owasp.org or on Twitter [@javanrasokat](https://twitter.com/javanrasokat).
