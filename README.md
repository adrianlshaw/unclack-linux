# unclack-linux

If you have a mechanical keyboard and you use Linux, you may be interested in this.
This script automutes your microphone whenever you start typing, which should 
make things less annoying for your friends or colleagues on voice chat.

To install, run: `./unclack-linux install`

To start on login, add `systemctl --user start unclack-linux.service` to your `.bashrc` or equivalent.

This is inspired by Unclack.app for macOS.
