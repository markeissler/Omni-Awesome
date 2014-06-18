
## Omni Awesome v4.1.0 (Font Awesome for OmniGraffle)
Built on top of the [Font Awesome Iconic Font and CSS framework from Dave Gandy](https://github.com/FortAwesome/Font-Awesome), Omni Awesome provides a series of OmniGraffle stencils that include vectorized versions of the complete set of FA icons.

### Introduction
I've used Font Awesome in the past to speed IOS and Web Development wire framing. Maybe you have too. I like to use [OmniGraffle](http://www.omnigroup.com/omniGraffle) to do this wire framing work. Putting two and two together I thought it would be awesome to have an OmniGraffle stencil to speed access to this large and useful icon collection.

[Previous efforts](https://github.com/patcheung/Font-Awesome-OmniGraffle-Stencil) sought to accomplish this task by simply creating a single huge stencil with icons embedded as text. The approach had a couple of short comings:

* requires the end user to install the Font Awesome font on their device
* each icon is simply text and can only be manipulated as text

What I wanted was a vector graphic that could be resized just like any other stencil element. After many hours of work converting each icon to a vector outline, the goal has been reached!

### Compatibility
These stencils have been developed and tested on OmniGraffle 6.

### Installation - OmniGraffle 6
The easiest way to install the provided stencils is via the Resource Browser in OmniGraffle 6:

File->Resource Browser...

* Click on the `Gear` drop down menu (bottom of browser window)
* Select *Add Resources to Library*
* Locate the Omni Awesome .gstencil files, select, and click on the `Open` button

### Installation - OmniGraffle 5.4.4
Omni Awesome can also be installed in OmniGraffle 5.4 (I tested 5.4.4) but it's more of a manual install:

* Select the stencils and drag them into the following folder:
`~/Library/Application\ Support/The\ Omni\ Group/OmniGraffle/Stencils/`

**NOTE:** Make sure you escape the spaces in the path. You can select the path from the Finder directly by opening a new Finder window, then pressing `Shift-Command-G`.

##Versioning
**In general, the Omni Awesome major release number will be 3 behind the upstream release of Font Awesome upon which it is based.** Therefore, OA 1.1.0 is based on FA 4.1.0. The patch number will not be synchronized with the upstream FA project.

Omni Awesome will be maintained under the Semantic Versioning guidelines as much as possible. Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions, including new icons, without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

For more information on SemVer, please visit http://semver.org.

## Bugs and such
Submit bugs by opening an issue on this project's GitHub page.

## Appreciation
If you find Omni Awesome useful and would like to fund further development, you can send some kudos my way courtesy of Flattr:

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=markeissler&url=https://github.com/markeissler/Omni-Awesome&title=Omni%20Awesome&language=bash&tags=github&category=software)

## Acknowledgements
These stencils would not be possible without the continued work of the Font Awesome team:

GitHub: [https://github.com/FortAwesome/Font-Awesome](https://github.com/FortAwesome/Font-Awesome)

## License
This code has been made available under the MIT License.
