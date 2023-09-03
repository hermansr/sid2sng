# sid2sng

Converts sid files back to GoatTracker2 sng files.
Note: sid files need to have been generated via GoatTracker2.

## Usage

    usage: ./sid2sng [options...] sid-file [sng-file]
     -nopulse
     -nofilter
     -noinstrvib
     -fixedparams
     -nowavedelay
     -noautodetect

Disabled features are auto-detected by default. Use `-noautodetect` to manually
specify which features are disabled.

## FAQ

+ **I get an error!**
  Try supplying `-noautodetect` and some of the other options. Often, you will need `-fixedparams`. Good luck!

+ **Where is the pulse wave?**
  Try it with `-noautodetect` and `-nowavedelay`.


## TODO

+ 4SID support
