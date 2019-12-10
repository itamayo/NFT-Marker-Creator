# NFT MARKER CREATOR 

This editor creates NFT markers for ARTOOKIT 5.x

and it is part of the efforts to bring NFT tracking to AR.js

## How to use it

1. Clone this repository.

2. Install all dependencies.

    ` npm install `


3. Put the image you want inside the "input" folder. Make sure that it is the only jpg image there.

4. Run it

    ` node app.js ` 

You can use additional flags with the run command. 
   
e.g node app.js -level=4 -min_thresh=8

    
    -level=n
         (n is an integer in range 0 (few) to 4 (many). Default 2.'
    -sd_thresh=<sd_thresh>
    -max_thresh=<max_thresh>
    -min_thresh=<min_thresh>
    -leveli=n
         (n is an integer in range 0 (few) to 3 (many). Default 1.'
    -feature_density=<feature_density>
    -dpi=f: Override embedded JPEG DPI value.
    -max_dpi=<max_dpi>
    -min_dpi=<min_dpi>
    -background
         Run in background, i.e. as daemon detached from controlling terminal. (macOS and Linux only.)
    -log=<path>
    -loglevel=x
         x is one of: DEBUG, INFO, WARN, ERROR. Default is INFO.
    -exitcode=<path>
    --help -h -?  Display this help


5. The generated files will be on the "output" folder.


#### If you want to generate you own NftMarkerCreator.min.js use the dev branch.
