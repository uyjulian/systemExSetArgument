# Plugin providing "System.setArgument"

This plugin adds `System.setArgument` function in Kirikiri2 / 吉里吉里2 / KirikiriZ / 吉里吉里Z

## Building

After cloning submodules and placing `ncbind` and `tp_stub` in the parent directory, a simple `make` will generate `systemExSetArgument.dll`.

## How to use

After `Plugins.link("systemExSetArgument.dll");` is used, the `setArgument` function will be exposed under the `System` class.

## License

This project is licensed under the MIT license. Please read the `LICENSE` file for more information.
