# mime2zip
Convert mail/mime to zip file
# Installation
Copy mime2zip to a folder in your PATH
# Help
In GMail, select 'Show original' from the menu, then click 'Download original' for the input file.
```
usage: mime2zip [-h] [--toc] [--hdr] [infile] [outfile]

Convert mail/mime to zip

positional arguments:
  infile      Mail file (default stdin)
  outfile     Zip file (default stdout)

optional arguments:
  -h, --help  show this help message and exit
  --toc       Write the TOC file
  --hdr       Write the HEADER file
```
