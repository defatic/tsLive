# Twitch Streamer Live (tslive)

## Description

CLI tool to check if your favorite Twitch Streamers are online!

## Dependencies

Depends on the `twitch` cli tool found @ https://github.com/twitchdev/twitch-cli

## Install

install.sh will symlink tslive to `$HOME/.local/bin` so you have the executable in your path

## Usage

```bash
usage:  tslive [list add delete]
        tslive         # Run without argments as standard
        tslive list    # List all name in the names file
        tslive add     # Adds a name to the names list (DON'T add more then one name each time)
        tslive delete  # Deletes a name from the names list (DON'T delete more then one name each time)
```
