# pebble-dev-codepsace
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=master&repo=566043589)

GitHub Codespace for Pebble development.

## Notes

- Emulator and --install phone probably won't work without some magic. This is because GitHub codespaces are *not* on the same network as yours.
  - If you do need these, I'd direct you to https://willow.systems/pebble to download the virtual machine (or, even better, install the SDK locally). Some systems can't run this VM, which is why I made this.
- If you are using this for the Rebble Hackathon and have immediate issues, please @ping me in the rebble discord (gibbiemonster#6242) or shoot me a dm (or an email @ hello@blockarchitech.com, though I may not respond quickly.)

## Better options

- Use the virtual machine (https://willow.systems/pebble/vm/)
- Install the SDK locally (good linux guide --> https://willow.systems/blog/pebble-sdk-installation-guide/#linuxinstall)
- Use docker on your local machine with docker desktop (install docker desktop --> `docker run --name=RebbleSDK -it rebble/pebble-sdk`)

Only use this if nothing works, or if you need something in a pinch. (or if you forgot your laptop at home)

## Awesome people

 - Will0 (https://willow.systems, @Willow-Systems) made the developer VM, and the linux install guide. Also is very active in the rebble discord, and all-around a cool guy.
 - Joshua Wise (@jwise) helped create the docker image this is using, and is a rebble admin. Super helpful, and also a cool guy

## Resources

- https://willow.systems/pebble
- https://rebble.io/discord
