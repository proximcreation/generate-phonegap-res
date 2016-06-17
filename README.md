# generate-phonegap-res
A shell script to generate icons and screens fro a color and a png image. Simple !
(depends on [imagemagick](http://www.imagemagick.org/script/binary-releases.php))

# Usage
1. put the screen in the "www" folder of your phonegap generated app.
2. chmod the script :
```
chmod 755 generate-res.sh
```
3. put a "icon.png" square image in the "www" folder of your phonegap generated app.
4. launch the script !
```
./generate-res.sh <color> <gravity>
```
ex :
```
./generate-res.sh "#8dc88d" south
./generate-res.sh red center
```
more "gravity" values [here](http://www.imagemagick.org/script/command-line-options.php#gravity)

# Note
This script generate files named and located as defined in the default config.xml of the phonegap generated tree.
