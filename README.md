# DigitalPianism_NoCallHome

Disables 3rd party modules notifications / home calls.

# Disclaimer regarding Aitoc

Aitoc does not send admin notifications anymore. The code may still exist in some of their modules but they are not sending notifications anymore. I left the code that disables their observer in order to avoid another call to an observer on the admin predispatch but they have stopped such bad practices :wink:

# List of disabled vendors

* AW
* Aitoc (see above)
* Amasty
* Ebizmarts MageMonkey
* Itoris
* Magestore
* Mirasvit MstCore
* Unirgy GiftCert

Feel free to do a PR to add more as this is just the list I gathered over the years, there's probably way more than this.

# Release Notes

## 0.0.6
- Fix a minor bug where a warning would be triggered

## 0.0.4
- Renamed the `app/etc/modules` configuration file to ensure it comes last.

## 0.0.3
- Added Ebizmarts MageMonkey
- Added Itoris

## 0.0.2
- Added Mirasvit MstCore Observers

## 0.0.1
- Initial release
