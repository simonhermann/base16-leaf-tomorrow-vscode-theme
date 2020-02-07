# Change Log

## 1.1.1

* tweak activityBar icon colors

## 1.1.0

* Slightly adjusted main color value
* Better UI colors and add contrast border. To disable border, add this to your settings.json: 
  ```json
  "workbench.colorCustomizations": {
    "contrastBorder": "#ffffff00",
  },
  ```
* Add suggestions how to set colors for indent-rainbow and Bracket Pair Colorizer Plugins
* Fix: sometimes selection in UI input boxes was invisible

## 1.0.0

* adjustments to support the new `editorIndentGuide.activeBackground`
* darker `sideBarSectionHeader.background`, matching activitybar now
* decided to go for v1.0.0, after half a year of extensive testing

## 0.0.6 - 0.0.8

* minor fixes

## 0.0.5

* umproved markdown! Now less distracting:
  * using less colors, now matching _Leafy_ mood
  * less gaudy color for links, tags and other non-important parts

## 0.0.4

* make indent guides more visible
* make white space color less prominent
* fetch improvements from original theme _base16-tomorrow-dark_:
  * property names + object literal keys are now properly colored
  * make markdown and css prettier
  * add new gitdecoration colors
  * ...

## 0.0.3

* minor fixes

## 0.0.2

* Tweak some workbench colors to make the sideBar distinguishable from statusBar and activityBar
* Make color of bracketMatch highlight less prominent
* change activityBar badges to have green background color

## 0.0.1

* Initial release
