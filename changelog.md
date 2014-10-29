<a name="1.3.0-pre9"></a>
### 1.3.0-pre9 (2014-10-24)


#### Bug Fixes

* **compile:** Keep copyright notices in minified files ([9fe51ab6](http://github.com/fraywing/textAngular/commit/9fe51ab68a1b2d31528abc0fbee186c9e70b0698))
* **styling:** Support other CSS frameworks. ([280522a3](http://github.com/fraywing/textAngular/commit/280522a3daa4ec4a62710a98ce6ef5e2a662878a))
* **taBind:** Fixes paste lists, more lenient stripping of spans. ([5ff572f6](http://github.com/fraywing/textAngular/commit/5ff572f6c50d2bf68df0c2b729a0f224b2be78a1))
* **taExecCommand:** Attempt to wrap unwrapped content in list breaks. ([7b873df8](http://github.com/fraywing/textAngular/commit/7b873df8e4c58d4b62962b136eb598984d17d1e9))


<a name="1.3.0-pre8"></a>
### 1.3.0-pre8 (2014-10-23)


#### Bug Fixes

* **taBind:** Fix some paste from word issues. ([ca8af8b1](http://github.com/fraywing/textAngular/commit/ca8af8b17a363a9b70d63b1ebf5115ecb53b55c1))


<a name="1.3.0-pre7"></a>
### 1.3.0-pre7 (2014-10-22)


#### Bug Fixes

* **Setup:** Make the rangy loaded check more forgiving. ([ec778431](http://github.com/fraywing/textAngular/commit/ec7784311bc7256b0d216cd2b8a0321c897dd43b))


<a name="1.3.0-pre6"></a>
### 1.3.0-pre6 (2014-10-21)


#### Bug Fixes

* **taBind:** Fix the drop handler not re-applying on select handler ([af233b9f](http://github.com/fraywing/textAngular/commit/af233b9f2443c386afe9f83c5b1b2cd69d62e39d))
* **taExecCommand:** Fix lists for FF specifically. ([0924a8ca](http://github.com/fraywing/textAngular/commit/0924a8ca22493f018b679cc6a0805f8f1152f832), closes [#290](http://github.com/fraywing/textAngular/issues/290))
* **taSanitize:** Allow id attribute. ([7afc96c0](http://github.com/fraywing/textAngular/commit/7afc96c0896a60cec4d95099d172f7bfa37ed7a1), closes [#355](http://github.com/fraywing/textAngular/issues/355))
* **taTranslations:** Change Constant to Value ([58781ee9](http://github.com/fraywing/textAngular/commit/58781ee907a690c3f1e980c76ac71d67fb2187a6))


#### Features

* **taBind.undoManager:** Add undoManager to taBind. ([bd2bb0ae](http://github.com/fraywing/textAngular/commit/bd2bb0aee69953f5caa043571b854219a28145d0))


<a name="1.3.0-pre5"></a>
### 1.3.0-pre5 (2014-10-20)


#### Bug Fixes

* **bower:** Fixes angular bower dependancy to support 1.3.0 ([491c8daf](http://github.com/fraywing/textAngular/commit/491c8daf31078ccb38e02f2058bf2e5acbe7c4c9), closes [#358](http://github.com/fraywing/textAngular/issues/358))


#### Features

* **taBind:** Add paste from word converting. ([e9edbdfe](http://github.com/fraywing/textAngular/commit/e9edbdfe7376f28bc27a376ce15a61a6e14b2b81))


<a name="1.3.0-pre4"></a>
### 1.3.0-pre4 (2014-10-06)


#### Bug Fixes

* **taTools:** Fixes the wordcount to count correctly. ([fb208874](http://github.com/fraywing/textAngular/commit/fb208874a53abd2bea7c4f7fedd260dcee489141))


<a name="1.3.0-pre3"></a>
### 1.3.0-pre3 (2014-10-06)


<a name="1.3.0-pre2"></a>
### 1.3.0-pre2 (2014-10-06)


<a name="1.3.0-pre1"></a>
### 1.3.0-pre1 (2014-10-06)


###OLD Changelog - PRE v1.3.0-pre1

2014-07-26 v1.2.2

- FIX #190, #201, #206, #223, #224, 
- Merge #209, #204
- Add option to disable sanitizer #233

2014-05-19 v1.2.1

- Release

2014-05-12 v1.2.1-pre6

- FIX some FormatBlock issues.
- Add .ta-bind class to the ta-bind directive.

2014-05-01 v1.2.1-pre5

- ADD Included some css built into the editor - no need for extra stylesheets unless you want to override.
- CHANGE The registerTools function to be the entire signature so directives can be included as wanted.
- ADD resizeOverlay functionality, includes a new scroll window that the ta-text editor nests inside to make positioning better (TODO: tests).
- FIX ta-default-wrap in chrome bug.
- ADD Class .ta-bind to all ta-bind directive elements.
- FIX ta-default-wrap and other funkyness with ul/ol tags, #155.
- FIX some execCommand bugs by adding taExecCommand.

2014-04-08 v1.2.1-pre4

- Fixing IE bugs with ta-default-wrap.

2014-04-08 v1.2.1-pre3

- Fixing a change focus bug introduced in v1.2.1-pre2
- Changing the code so ta-bind no longer requires rangy-core.js, making it an optional requirement again.

2014-04-08 v1.2.1-pre2

- Fixed up ta-default-wrap. This now requires rangy-core.js
- Fixed an IE Paste issue.
- Fixed a webkit bug causing contenteditables not to loose focus.

2014-03-24 v1.2.1-pre1

- Moved setup functions into a seperate file, textAngularSetup.js. This file must be included before textAngular.js file. Using the defaults and textAngular.min.js causes no changes.
- Adding the Image and Link click popup functions.
- Adding ability to drag and drop files into the editor.
- Manager now can add and remove tools dynamically.
- Added Custom Renderers adding the ability to use placeholders, eg an image, in the editor and display something else in display mode. Uses factory function `taApplyCustomRenderers` to do this.

2014-02-28 v1.2.0

- Lots and Lots of changes, too many to list. Structural changes and added functionality. Supports down to IE8 and all other browsers.

2013-12-11 v1.1.2

- Updated to work correctly with IE (console.log bug)

2013-12-11 v1.1.2-pre3

- Added support for .focussed class and ng-focus to allow dynamic styling on focus events. #47
- Updates to fix Angular.JS breaking with parameter renaming minification. #49
- Minor bug fix to disable links from being 'clickable' in the editor.
- Updated the default toolbar to include ALL default tools.
- Update the tools to use activeState better.
- Small update to allow use of ta-bind outside of textAngular.
- Changed the raw html view to use a text-area for better compatability.

2013-12-09 v1.1.2-pre2

- Added input for form submission. #43
- Slight restructure and update into of /demo.
- Moved a lot of the README.md to the online Wiki. #34
- Changed pre-release tag names to -preX as we aren't really doing alpha - beta - RC format.

2013-12-05 v1.1.2-alpha (v1.1.2-pre1)

- Added bundled demo pages.
- Fixed Escaping of < and > #30
- Fixed stripping of style and class attributes and other parsing issues whilst maintaining the chrome fixes. #35 #30 #5
- Fixed two-way-binding not working #38
- Updated Readme.md and consolidated the readme out of the textAngular.js file.

2013-12-2 v1.1.1

- Fixed buttons still submitting form. #29
- Fix for Null ngModel value. Thanks to @slobo #22
- Added Ability to override just "display" for default button set. Thanks to @slobo #27

2013-11-9 v1.1.0

- Re-written to only depend on Angular and Angular-Sanitize. No More jQuery.
- Re-worked to be more angular-esq in it's initiation and use. Less reliance on global variables except for defaults and more use of bindings on attributes.
- Default styles are Bootstrap 3 classes, options to change these classes.
- Restructured the Toolbar to make it more plugin friendly, all tool buttons are encapsulated in their own scope that is a child of the individual textAngular bound scope.

2013-11-6 v1.0.3

- $sce isn't required anymore* Thanks to @nadeeshacabral
- bower support added* Thanks to @edouard-lopez

2013-10-11 v1.0.2

- Fixed issue with images not calling the compileHTML method*
- Fixed issue in chrome where styling was getting added for unordered lists*
- You can now change the model from the outside and have it affect the textAngular instance contents*
- Cleaned up code*

2013-10-10 v1.0.1 

- Added Tooltip Option, title has been renamed icon, and title is now the tooltip*
- The minified version actually works now*
