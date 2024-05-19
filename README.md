# Arma Reforger Server TUI

This is a simple TUI for the Arma 3 Reforger Server.

Aimed at gamers self hosting on a lan. 

While not a requirements, It assumes you'll host the server on the same machine you're running the Game client on.


## Requirements

- [fzf](https://github.com/junegunn/fzf)
- arma reforger server (you need to use steam to install this)

## Usage

```sh
arma-reforger-tui [config.json]
```

## Addons

These should be described in the config file.

If your addon directory does not contain them, they will be downloaded.


## Server Config

The multiplayer host ui in Aram Reforger will allow you to save the configuration to a json file. 

Usually these are stored in 

```sh
~/Documents/My Games/ArmaReforger/serverConfigs
```

## Server Profiles

Profile data for a server is stored in an adjacent directory (`serverProfiles`) using a name that matches the config file you choose.
