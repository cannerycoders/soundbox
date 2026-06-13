# soundbox

cannerycoders.github.io is yet another repository for 
open-source sound files.  Here, we've cobbled together 
samples from a variety of open-source sample collections
in order to make them available for live-loading via github.io
into internet sound apps like [HzWeb](https://cannerycoders.com/HzWeb).

We loosely follow the introspection conventions laid out by 
[smpldsnds](https://github.com/smpldsnds/drum-machines): 

1. [instruments.json](instruments.json) is an array of subdirectories, one
   for each "instrument".
2. [toc.json](toc.json) is an object whose key is `kit/instrument` and whose
   value is the instrument subdirectory.
3. within an instrument directory, the file, `instrument.json` 
   describes its contents including an enumeration of 
   sample file names and available formats. Here's an
   example:

```json
{
  "baseUrl": "https://cannerycoders.github.io/soundbox/instruments/lick/samples/CasioSa10",
  "samples": [
    "Crash",
    "HighConga",
    "HighCowBell",
    "HighTom",
    "Kick",
    "LowConga",
    "LowCowBell",
    "LowTom",
    "MiddleTom",
    "OpenHat",
    "Ride",
    "SnareA",
    "SnareB"
  ],
  "formats": [
    "ogg"
  ],
  "soundClass": "sound",
  "sampleRate": 48000,
  "channels": 1
}
```


## issues

This is a work-in-progress.
