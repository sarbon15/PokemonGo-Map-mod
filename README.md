#A few quick edits to the PokemonGo-Map-master#
#[Official Website] (https://jz6.github.io/PoGoMap/)#

##All credit to original creators##

I just wanted to make a few changes to the script. My buddy thought it would be nice to share. Here you go.

##Only does one thing different##
After downloading and unzipping and setting up just like the master PokemonGo-Map-master, you need to install one more module:
`pip install gpxgy --user`

Then run as follows:
`python mod_example.py -a ptc -u <USER> -p <PASSWORD> -l "<LOCATION>" -st 10`

or if using a google account

python mod_example.py -a google -u <USER> -p <PASSWORD> -l "<LOCATION>" -st 10

This will print out the approximate distance in feet, direction, and minutes until expiration of each pokemon found like so:
```
[+] Current pokemon near your location:
     1  #  4 Charmander     [3236:NNE -  5.6m] 
     3  # 16 Pidgey         [1443:NNE -  4.7m] [2423:ESE -  3.9m] [2901:NNE -  6.6m] 
     1  # 19 Rattata        [2906:NNE -  9.0m] 
     3  # 29 Nidoran[F]     [1411:N   - 10.0m] [2553:NE  - 12.9m] [3351:SE  -  6.9m] 
     2  # 35 Clefairy       [1820:NE  -  1.7m] [2340:ENE -  9.4m] 
     2  # 41 Zubat          [1399:NNE -  6.5m] [2595:NE  -  1.3m] 
     1  # 48 Venonat        [2230:SSE -  4.5m] 
     2  # 50 Diglett        [1466:NNE -  5.2m] [2242:NE  -  4.2m] 
     2  # 56 Mankey         [2187:NNE - 11.0m] [2631:SE  - 11.6m] 
     1  # 58 Growlithe      [3613:NNE -  8.8m] 
     4  # 74 Geodude        [ 276:SW  -  4.0m] [1766:NNE -  8.7m] [2253:NE  -  4.3m] [2985:SE  -  8.3m] 
     1  # 96 Drowzee        [1826:NNE -  4.1m] 
     3  #133 Eevee          [1992:NNE -  4.7m] [2042:NE  -  6.6m] [4269:NW  -  8.6m]
```
