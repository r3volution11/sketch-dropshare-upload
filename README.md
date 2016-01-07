# Introduction

*Note: This is a fork of [Jacob Elias' Cloudapp Upload plugin](https://github.com/jelias/sketch-upload). I decided to fork it for those out there that may be concerned about modifying a plugin file. Thanks Jacob!*

This [Sketch](http://bohemiancoding.com/sketch) plugin allows you to upload a selected artboard or slice to 
[Dropshare](https://getdropsha.re/) with a simple shortcut `⇧⌘⌥U`.

The plugin works by exporting the selected artboard or layer to Sketch's cache
directory and uploading that file via Dropshare.

This works fine with the Cloudapp version installed too. 

# Installation

1. Download Zip.

2. Double-click the file `Dropshare Upload.sketchplugin` Sketch should open automatically and tell you that a new plugin was installed.

# Usage

1. Select the artboard you would like to upload.

2. Then run the plugin via `Plugins > Dropshare Upload` or the simple shortcut `⇧⌘⌥U`.

3. Sketch will prompt you to name your file.

4. That's it! Enjoy, and please share this plugin with everyone you know!


> ###Note: 

>	If you want to upload your designs via another service (i.e. Cloudapp) just change

> `var PREVIEW_APPLICATION = "Dropshare";`
	
>	to what ever app you use.

>	BUT BE SURE TO PUT THE APP NAME, NOT THE SERVICE NAME!


# Compatibility

This plugin was developed with the Non-App Store version of Sketch 3.3 and Cloud App 3.3.0

> ###Note:
> I have not tested v0.5 of Sketch Upload on Sketch 2. If there are problems revert to v.2 and let me know! 

# Troubleshooting

If there are any problems with this plugin try debuging the problem first. Simply edit the .sketchplugin file and set `DEBUG` to `true`  and check the console for errors.

If you are still having problems, create an issue and explain the problem in full detail. Please provide steps to reproduce the problem and if you are willing, the .sketch file. Logs would aslo be helpful :) 

## Known Problems

1. Cloudup does not work with this plugin. ([Issue #4](https://github.com/jelias/sketch-upload/issues/4))

2. Sketch Upload does not work without an artboard or slice named ```upload```. ([Issue #7](https://github.com/jelias/sketch-upload/issues/7))

# Original Author

[Jacob Elias](http://jelias.me)

Feel free to contribute, your help would be greatly appreciated.

#Thanks

Huge thanks to 
[Marc Schwieterman](https://github.com/marcisme) ([@mschwieterman](https://twitter.com/mschwieterman) / [@mbs](https://app.net/mbs)) for making all this possible!

This plugin is largely based on his [sketch-preview plugin](https://github.com/marcisme/sketch-preview), with a few tweeks from [David Klawitter](https://github.com/davidklaw) and his fork of [sketch-preview](https://github.com/davidklaw/sketch-preview). Seriously, Marc's plugin is a huge part of Sketch-Upload.

# License

MIT License
