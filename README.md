# Twitch Streamer Live (tslive)

## Description

CLI tool to check if your favorite Twitch Streamers are online!

## Dependencies

Uses the `twitch` cli tool found @ https://github.com/twitchdev/twitch-cli

## Install

install.sh will symlink tslive to `$HOME/.local/bin` so you have the executable in your path

## Usage

```bash
usage:  tslive [list add delete]
        tslive         # Run without argments as standard
        tslive list    # List all streamers in the streamer name file
        tslive add     # Adds a streamer name to the names list (DON'T add more then one name each time)
        tslive delete  # Deletes a name from the names list (DON'T delete more then one name each time)
```
