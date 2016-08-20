# VLC Downloader
**vcl-dl** is a bash script for batch downloading of galleries from vclart.net.
I've written it for preservation of culture, to counter the people nuking their galleries every once a while,
as well as to ensure that when VCL perishes like Geocities we will have at least some backups remaining.

Downloads all images from a gallery, preserving artist's folder structure.
Prepends upload date to filenames so that they appear in chronological order locally.


## Requirements

Coreutils, bash, sed and wget are the only dependencies.

vcl-dl was tested only on Linux. It should also work on Mac and BSDs.
Windows users can probably get it to work via Cygwin or Microsoft's "BASH on Windows", but running a virtual machine with Linux might be simpler.

## Usage
 `vcl-dl ARTIST`

All files from the given artist's gallery will be downloaded to the current directory,
creating subdirectories to mirror the remote gallery structure.

### Example
 `vcl-dl LavaCat`

will download the entire gallery of http://us.vclart.net/vcl/Artists/LavaCat/

## TODO
 * Download author's description of the artwork

## Disclaimer
It is your own responsibility to check whether batch downloading is allowed by VCL terms of service and to abide by them. For further disclaimers see LICENSE.
