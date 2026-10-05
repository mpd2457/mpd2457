# Mike D

Show tech and local web apps. Benidorm.

Mostly Python, shell and systemd, all self-hosted on my own hardware rather than
someone else's cloud.

## show-deploy

**[mpd2457/show-deploy](https://github.com/mpd2457/show-deploy)** — the one public
repo. Pushes show video decks from an ingest laptop to the show rig over SMB.

It retries, it verifies every transfer by size, and it has 58 offline tests that
fake `ping` and `smbclient` so you can exercise the failure paths without a rig.
Runs on Linux, macOS and Windows.

Apache-2.0.

## Everything else is private

The other work — a pub quiz app, a blog engine, a Bitfocus Companion setup for the
show rig, a scooter racing game in progress — is private, because it either belongs
to the show business or isn't finished enough to be worth looking at.