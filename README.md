# ChooseLocal

A small Android / Android TV utility that lets you choose a custom `.local` hostname for your device.

For example, you can make an Android TV device available on your local network as:

`my-tv.local`

instead of having to remember its IP address.

## Features

- Choose your own `.local` hostname
- Designed to work on Android TV
- Simple interface
- Uses mDNS / Bonjour-compatible local networking
- No account required
- No external server required
- Works entirely on your local network

## Example

Enter:

`living-room-tv`

Your device can then be reached as:

`living-room-tv.local`

The service only affects devices on the same local network.

## Installation

1. Download `ChooseLocal.apk` from this repository.
2. Transfer the APK to your Android or Android TV device.
3. Allow installation from unknown sources if Android asks.
4. Install and open ChooseLocal.
5. Enter the hostname you want to use.
6. Start the service.

## Requirements

- Android / Android TV
- A local Wi-Fi or Ethernet network
- Another device with mDNS / `.local` support

## Notes

ChooseLocal is a small experimental utility.

Whether a `.local` hostname can be resolved may depend on the Android device, network configuration, and client device.

## Build

The APK can also be built automatically using the GitHub Actions workflow included in this repository.

Go to:

**Actions → Build ChooseLocal APK → Run workflow**

The resulting APK will be available as a GitHub Actions artifact.

## License

MIT License - (c) justcreatingapk
