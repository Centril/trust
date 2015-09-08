[![License]][url: License] [![Semver]][url: Semver] [![Gittip]][url: Gittip]

# [trust]

> **NOTE:** Currently, this is just an idea, this repository is a placeholder
> and a place to put my/your ideas about what this can be and how it can be done.

> **trust** is an idea for a cross platform terminal emulator that is based on
> JS + HTML5 UI, ie: Electron or some Servo based UI, and Rust based backend.
> The emulator will be licensed under GPL2+ if the project goes further.

## Ideas

+ GPL2+ license.
+ JS + HTML5 UI
	* Electron is one way to do cross-platform UI with JS + HTML5.
	* If Servo is mature enough by that time, it might be used instead as it
	is based on Rust and is very safe & performant.
+ Rust for everything that must be native or must be fast.
+ Not lightweight compared to xterm, gnome terminal, termite.
+ Features:
	* Moddable with JS + CSS.
	* Guake style slidedown.
	* Inspiration from finalterm
	* Inserting `sudo` if missed and logical to require:
		- For example: If you do `nano /etc/profile` it won't work, because you need `sudo`,
			but since `/etc/profile` requires root, you can probably detect it if
			the kernel allows.
+ Linux, Unix, (Windows?) support.
	* Initially: Linux... Hopefully POSIX + "Electron" will get us far.

## Changelog

See **[CHANGES.md]**.

## Bugs / Issues / Feature requests / Contribution

Want to contribute? Great stuff! Please use the issue system that github provides to report bugs/issues or request an enhancement. Pull requests are also more than welcome.

## Author

**Mazdak Farrokhzad / Centril [&lt;twingoow@gmail.com&gt;]**

+ [twitter]
+ [github]

## Copyright & License

Licensed under the **[GPL 2 License]**.
Copyright 2015 Mazdak Farrokhzad.

## Acknowledgements

> PLACEHOLDER

<!-- references -->

[Gittip]: http://img.shields.io/gittip/Centril.svg?style=flat
[url: Gittip]: https://www.gittip.com/Centril/
[License]: http://img.shields.io/badge/license-GPL_2-blue.svg?style=flat
[url: License]: LICENSE.md
[Semver]: http://img.shields.io/badge/semver-2.0.0-blue.svg?style=flat
[url: Semver]: http://semver.org/spec/v2.0.0.html

[trust]: https://github.com/Centril/trust

[twitter]: http://twitter.com/CenoRIX
[github]: http://github.com/centril
[&lt;twingoow@gmail.com&gt;]: mailto:twingoow@gmail.com

[CHANGES.md]: CHANGES.md
[GPL 2 License]: LICENSE.md

<!-- references -->