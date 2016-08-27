# production-guide
working notes on producing an episode of the Fatal Error podcast

## Audio Exporting & Tagging

- Run through Levelator before encoding as MP3 (beta)

Export to MP3 (using 64k CBR for now) with the following options:
- Mono
- Normalise
- Strip beginning/ending silence
- Dithering enabled

Import to iTunes and apply the following fields:
- Song name: `Episode N - Title`
- Artist: `Soroush Khanlou & Chris Dzombak`
- Album: `Fatal Error`
- Album artist: `Soroush Khanlou & Chris Dzombak`
- Genre: `Podcast`
- Artwork: podcast artwork

iTunes will rename the file appropriately, following the format `Fatal Error - Episode 1.mp3`.

## Audio Distribution

Copy the resulting MP3 from iTunes to:
- @cdzombak's archive
- the Audio Transfer Dropbox folder
- upload to Squarespace

## Squarespace

Be sure to edit the audio block. In addition to including the title (`Episode N - Title`) and author (`Soroush Khanlou & Chris Dzombak`) in the Embed tab, fill out in the Podcasting tab:

- iTunes Summary: the first ("intro") paragraph of the show notes
- iTunes Episode Duration: the duration of the episode MP3 (in full `hh:mm:ss` format)

And allow Squarespace to show the Download link on the audio player.

In the settings for each post:
- schedule for publishing on the right date
- turn on publishing to the twitter account, via the Social tab

