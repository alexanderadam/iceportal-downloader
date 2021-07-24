# iceportal-audiobooks-downloader

(only works when connected to the ICE wifi)

As the title describes...
A small script which downloads all offered audiobooks from the [Deutsche Bahn iceportal](https://iceportal.de/).

<div align="center">
  <img src="https://github.com/SirBenedick/iceportal-audiobooks-downloader/blob/master/git.gif" alt="Gif showing how episodes are downloaded"/>
</div>

Original implementation by [SirBenedick](https://github.com/SirBenedick/iceportal-audiobooks-downloader).
This fork uses properly tagged audio files and covers.

## Setup

1. Ensure you have [Ruby installed](https://www.ruby-lang.org/en/documentation/installation/) (I usually recommend [`rbenv`](https://github.com/rbenv/rbenv#installation) but any Ruby installation should do)
2. `git clone 'git@github.com:alexanderadam/iceportal-audiobooks-downloader.git'`
3. `cd iceportal-audiobooks-downloader`
4. `bundle install`
5. `bundle exec ruby main.rb`
6. enjoy

### ToDo

* select which audiobooks to download
