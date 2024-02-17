# Twitch Streamer Live (tsl)

## Description

CLI tool to check if your favorite Twitch Streamers are online!

## Dependencies

Uses the `twitch` cli tool found @ [Github][URL-tw]
jq [jq][URL-jq]
gum [gum][URL-gum]
streamlink [Streamlink][URL-sl]

## Install

install.sh will symlink tsl to `$HOME/.local/bin` so you have the script in your path

## Usage

```bash
usage:  tslive [add delete list]
        tslive         # Run without argments as standard
        tslive add     # Adds a streamer name to the names list (DON'T add more then one name each time)
        tslive delete  # Deletes a name from the names list
        tslive list    # List all streamers in the streamer name file
```

[URL-jq]: https://stedolan.github.io/jq
[URL-gum]: https://github.com/charmbracelet/gum
[URL-sl]: https://streamlink.github.io/install.html
[URL-tw]: https://github.com/twitchdev/twitch-cli
