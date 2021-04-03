# pwnagotchi-plugins
Some plugins updated 🙂

## How to use

Add to `/etc/pwnagotchi/config.toml` :
```bash
main.custom_plugin_repos = [
 "https://github.com/evilsocket/pwnagotchi-plugins-contrib/archive/master.zip",
 "https://github.com/PwnPeter/pwnagotchi-plugins/archive/master.zip",
]
```

Next, `sudo pwnagotchi plugins update` and `sudo pwnagotchi plugins list`.

You can now install and enable plugins :)

## Plugins

`hashie-hcxpcapngtool.py` : hashie.py with support of the 2021 version of hcxtools + new hashcat formats.

`handshakes-dl-hashie.py` : Download handshake captures from web-ui + handshake converted in hashcat format with `hashie-hcxpcapngtool.py`.
