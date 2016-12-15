# Change Log

## [v1.2.2](https://github.com/MyScript/myscript-text-web/tree/v1.2.2)

### Features
- New `strokecolor` attribute to setup/change stroke color settings
- New `strokewidth` attribute to setup/change stroke width settings

### Bugs
- See [MyScriptJS v1.2.2](https://github.com/MyScript/MyScriptJS/tree/v1.2.2) for fixes

## [v1.2.1](https://github.com/MyScript/myscript-text-web/tree/v1.2.1)

### Bugs
- Improve documentation of superimposed options
- See [MyScriptJS v1.2.1](https://github.com/MyScript/MyScriptJS/tree/v1.2.1) for fixes

## [v1.2.0](https://github.com/MyScript/myscript-text-web/tree/v1.2.0)

### Features
- Mutable `host` attribute
- Mutable `protocol` attribute
- New `resultdetail` attribute 
- New `inputmode` attribute to change mode from CURSIVE or SUPERIMPOSED to another
- New `recognitioncandidates` attribute to set desired candidates count
- New `predictioncandidates` attribute to set desired predicted candidates count
- New `completioncandidates` attribute to set desired completed candidates count
- New `availablelanguages` output attribute to get authorized language list
- New `candidates` output attribute to get candidates with score and tags
- New `selectedcandidate` output attribute to get the best recognition candidate
- Add a candidate `select` feature to explicitly change the selected candidate
- Replace undo/redo/clear/recognize buttons by the `myscript-common-element` ones
- Replace the error panel by the `myscript-common-element` ones
- Upgrade from Polymer 1.2 to 1.4
- Add docs/demo buttons on component page
- Add getStats method to get various stats relative to ink in order to help evaluate the myscript cdk usage


### Bugs
- Fixes issue on resize due to CSS
- Explicit default values on documentation 
