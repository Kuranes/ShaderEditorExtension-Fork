## current

Features:
- fold (block, preprocessor)
- match hilighght
- debug value using "render value as Color" (click on gutter)
- edit Shader
- preprocessor and unused function cleaner
- add support for themes
- movie recorder
- Uniform Hover for Value
- glsl keyword hover for link to doc.

bugfixes
- fixed a race condition (udpate a shader while it's being used.)
- fix unused uniform still binding

Internals:
- upgrade to latest codemiror
- upgrade to latest code mirror addons
- seperate folder upong different submodules (so that we can migrate to
- submodules for codemirror, shadereditor, glsl-optimzer)
- make shader editor independant of chrome extensions so that it's
 reusable otw. (as a vorlonjs plugin for instance, for mobile shader
 remote debug)
- added glsl preprocessor to clean uber shader to just what is used
- enabled new codemirror addons (mathhilight on word select, fold block
 or define block)
- added search documentation on main page (seems noboby knows how it
 works)
 - add option for logging/debugger spawns fo better chrome ext debug


## V1.0.17 (2016-3-3)

Features:

- Moved settings load to be done first thing when loading the extension: should create less potential problems when loading

## v1.0.16 (2015-10-10)

Bugfixes:

 - Codemirror search working ([#14](https://github.com/spite/ShaderEditorExtension/issues/14))
 - Moved localStorage from panel to chrome.storage on background page (was broken with blocked third party cookies)
 
## v1.0.15 (2015-07-13)

Features:

 - Added toggling of shaders
 - Added texture monitor/editor: shows textures created and can be replaced by new images (no support for cubemaps yet)
 - Added settings panel: toggle shader highlighting and texture monitoring
 - Created CHANGELOG.md

## v1.0.14 

Features:

 - Support for shader/program names [Issue #10](https://github.com/spite/ShaderEditorExtension/issues/10)

## v1.0.13 

Features:

 - Support for live reload across browsing session (https://github.com/spite/ShaderEditorExtension/issues/1)

## v1.0.12 

Workarounds:

 - Fix for three.js

## v1.0.11 

Bugfixes:

 - Fixed bug with uniform retrieving: shadertoy and other cool sites supported!
 
## v1.0.10 

Features:
 - Improved error reporting

Bugfixes:
 - Several fixes

## v1.0.9 

Features:

 - Starting options panel
 - Added setting for highlighting

## v1.0.8 

Features:

 - New icon (thanks @ebraminio & @markusfisch)

Bugfixes:

 - Restored extension support

## v1.0.7 

Features:

 - Added error checks for attributes (possible bug?)
 
## v1.0.6 

Features:

 - Redone main code
 - highlight brought back

## v1.0.5 

Features:

 - Compiler status
  
Bugfixes:

 - Fixes
 
## v1.0.4 

Bugfixes:

 - fixed some shaders not compiling (issue #4)

## v1.0.3 

Workarounds:

 - rolled back, colouring introducing bugs

## v1.0.2 

Features

 - added colour highlighting for hover

## v1.0.1 

Bugfixes:

 - Fix extensions not being enabled 

## v1.0.0 

Features:

 - Initial release
