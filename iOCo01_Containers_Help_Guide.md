# FormaServe IBM i Containers Help

![FormaServe Logo](https://github.com/AndyYouens/f_Learning/blob/master/images/Logo.png)

This document shows useful commands for helping with file system containers on IBM i

## Our eLearning IBM i Training Examples

Visit our training videos, which can be found [here](https://learning.formaserve.co.uk)

## Useful Container Commands

| Command | Description |
| -| - |
| `yum –installroot=/QOpenSys/containers/andy` | Install software into a container |
| `yum –installroot=/QOpenSys/containers/andy install nodejs14` | Install Node14 into my container example |
| `yum install ibmichroot` | Install IBMiChroot |
| `chroot_setup andy` | Create an IBM i container |
| `chroot /QOpenSys/containers/andy /QOpenSys/usr/bin/sh` | Move into an IBM i container |
| `rm -rf  /QOpenSys/containers/andy` | Nuke an IBM i container |

## Links

- [IBM RFEs for PASE](http://bit.ly/ibm-rfe-all-pase)

## Authors

> FormaServe Systems Ltd - _All work_ - [FormaServe](https://www.formaserve.co.uk)

## Contributors

> Andy Youens - FormaServe
>
> Nick Youens - FormaServe

## Acknowledgments

> Andy Youens - FormaServe Systems Ltd - Twitter [@AndyYouens](https://twitter.com/AndyYouens)

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- **© 1990 - 2020 [FormaServe Systems Ltd](https://www.formaserve.co.uk)**
