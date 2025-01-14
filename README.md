# iceportal-downloader

It only works when connected to the wifi of the Deutsche Bahn (i.e. [`WIFIonICE` / `WIFI@DB`](https://inside.bahn.de/wifionice-wlan-ice-login/)), České dráhy (i.e. [`CDWiFi`](https://www.cd.cz/dalsi-sluzby/premiove-a-bonusove-sluzby/-26851/)) or [ÖBB](https://www.oebb.at/de/reiseplanung-services/im-zug/wlan-im-zug).
Make sure that you're signed in first (i.e. by visiting <https://login.wifionice.de> or <https://wifi.bahn.de> or whatever portal you have).

This is a small script that downloads all offered audiobooks and magazines from the train media portals.

<div align="center">
  <img src="https://github.com/SirBenedick/iceportal-audiobooks-downloader/blob/master/git.gif" alt="Gif showing how episodes are downloaded"/>
</div>

Original implementation by [SirBenedick](https://github.com/SirBenedick/iceportal-audiobooks-downloader).
This fork uses properly tagged audio files and covers and can also download newspapers and magazines.

This is just meant to help you download the content for offline use if you have a connections where you have to switch trains and you want to avoid re-starting the media playing. Please respect the rights of the authors and publishers and don't distribute the downloaded content.

Also please delete the media files when you stop travelling with the ICE.

## Setup

You might need these packages installed:

```bash
# Debian / Ubuntu
sudo apt install build-essential libssl-dev zlib1g-dev

# Fedora
sudo dnf install openssl-devel zlib-devel gcc gcc-c++ make libyaml-devel ruby-devel
```

1. Ensure you have [Ruby installed](https://www.ruby-lang.org/en/documentation/installation/) (I usually recommend [`rbenv`](https://github.com/rbenv/rbenv#installation) but any Ruby installation should do)
2. `git clone 'git@github.com:alexanderadam/iceportal-audiobooks-downloader.git'`
3. `cd iceportal-audiobooks-downloader`
4. `bundle install`
5. `bundle exec ruby main.rb`
6. enjoy
