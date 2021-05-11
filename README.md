Unofficial fork of Vital
========================

This is an unofficial fork of [Vital] with changes aimed at use on GNU/Linux
as an LV2 plugin.

[Vital]: https://github.com/mtytel/vital/

This fork is not affiliated with Vital or Matt Tytel in any way. If you enjoy
Vital or this unofficial fork, I encourage you to support Vital financially
by purchasing it at [vital.audio](https://vital.audio) or by donating to Matt
Tytel using the PayPal “Donate” button on [this page](https://tytel.org/helm/).

Building
--------

Note that the plugin will be built as “Vial”, rather than “Vital”.

```bash
make lv2
sudo make install_lv2
```

### Things you can't do with this source
 - Do not create an app and distribute it on the iOS app store. The app store is not comptabile with GPLv3 and you'll only get an exception for this if you're paying for a GPLv3 exception for Vital's source (see Code Licensing above).
 - Do not use the name "Vital", "Vital Audio", "Tytel" or "Matt Tytel" for marketing or to name any distribution of binaries built with this source. This source code does not give you rights to infringe on trademarks.
 - Do not connect to any web service at https://vital.audio, https://account.vital.audio or https://store.vital.audio from your own builds. This is against the terms of using those sites.
 - Do not distribute the presets that come with the free version of Vital. They're under a separate license that does not allow redistribution.
