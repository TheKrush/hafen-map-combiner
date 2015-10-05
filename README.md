# hafen-map-combiner

**Uses [ObjectPlanet PngEncoder](http://objectplanet.com/pngencoder/) for fast PNG output**

## Installation

TODO: Describe the installation process

## Usage

### Command line parameters

* **--coords** - Adds coordinates to each tile on stitched images
* **--grid** - Draws grid on stitched images
* **--nomerge** - Only stitch images, without merging, can be used only with a single input
* **--merge <outDir>** - Will save combined tile sets to outDir (which must not exist)
* **--noimg** - Will not generate stitched images, can only be used with --merge
* **--time** - Shows timing data
* All other parameters are treated as input directories

### Combine mode

* **--combine <indir1> <x1> <y1> <indir2> <x2> <y2> <outdir>**
 * Manually combines two map folders and merges tiles and fingerprints
 * **indir1 x1 y1** - specifies first input folder and coordinate of a reference tile
 * **indir2 x2 y2** - specifies second input folder and coordinate of a reference tile
 * **outdir** - name of new folder that will be created by combining the two input folders

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

TODO: Write history

## Credits

TODO: Write credits

## License

TODO: Write license
