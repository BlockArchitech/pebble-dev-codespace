# pebble-dev-codepsace
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=master&repo=566043589)

GitHub Codespace for Pebble development.

## Notes

- Emulator and --install phone probably won't work without some magic. This is because GitHub codespaces are *not* on the same network as yours.
  - If you do need these, I'd direct you to https://willow.systems/pebble to download the virtual machine (or, even better, install the SDK locally). Some systems can't run this VM, which is why I made this.


## Better options

- Use the virtual machine (https://willow.systems/pebble/vm/)
- Install the SDK locally (good linux guide --> https://willow.systems/blog/pebble-sdk-installation-guide/#linuxinstall)
- Use docker on your local machine with docker desktop (install docker desktop --> `docker run --name=RebbleSDK -it rebble/pebble-sdk`)

Only use this if nothing works, or if you need something in a pinch. (or if you forgot your laptop at home)

## Resources

- https://willow.systems/pebble
- https://rebble.io/discord
