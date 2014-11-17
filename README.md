# sailfishos-patches-base

This repository contains a set of patches that should not cause much harm on the device. 

## List of patches

TODO

## For patch developers

This repository generates two packages, `sailfishos-patches-base` and `sailfishos-patches-base-unmaintained`.
The only difference between those two packages are the status of the patch. If a patch has no maintainer
or if the patch hasn't been updated to make it compatible with the latest SailfishOS release in a 1 month
timeframe, then the patch will be considered unmaintained.

A maintainer is registered inside the JSON metadata file. Either use your real name, as displayed
on Github or Twitter, or use your usual nickname.

```json
{
    "name": "My super patch",
    "description": "Some description.",
    "category": "other",
    "infos": {
        "maintainer": "Foo Bar"
    }
}

```

Since this repository only contains patches that cannot break (brick) a phone, it only accept 
patches for QML files in the following packages
- declarative-transferengine-qt5
- jolla-camera
- jolla-contacts
- jolla-contacts-settings
- jolla-gallery
- jolla-gallery-ambience
- jolla-gallery-facebook
- jolla-keyboard
- jolla-messages
- jolla-messages-settings
- jolla-settings
- jolla-settings-layout
- jolla-settings-accounts
- jolla-settings-accounts-extensions
- jolla-settings-bluetooth
- jolla-settings-networking
- jolla-settings-sync
- jolla-settings-system
- jolla-startupwizard
- jolla-startupwizard-tutorial
- jolla-vault
- jolla-vault-units
- nemo-qml-plugin-thumbnailer-qt5-libav
- sailfish-browser
- sailfish-components-accounts-qt5
- sailfish-components-bluetooth-qt5
- sailfish-components-contacts-qt5
- salifish-components-email-qt5
- salifish-components-gallery-qt5
- salifish-components-media-qt5
- salifish-components-pickers-qt5
- salifish-components-store-qt5
- salifish-components-textlinking-qt5
- salifish-components-timezone-qt5
- store-client
- transferengine-plugins
- voicecall-ui-jolla
- voicecall-ui-jolla-settings

