# scopackager changelog

## 0.2.8

- removed all repeated metadata ADL SCORM

## 0.2.7

- fix config identifier not being used when generating the schema manifests

## 0.2.6

- included MIT LICENSE
- fix for non-latin languages

## 0.2.5

- changed behavior of adding timestamp to .zip file: by default, this is _not_ added. It can be added by setting `package.appendTimeToOutput: true` in the options object.

## 0.2.4

- package.vcard.org value is now correctly assigned
- language defaults changed to 'en' and any default string values (metadata descriptions) changed to english
- modify README.md options formatting to show all default values
- add timestamp to .zip file outputs so repeated packaging doesn't overwrite existing archives
- fixed typo in metadata.js (appearence -> appearance)

## 0.2.3

- fixed mastery score to 0

## 0.2.2

- fixed package.json

## 0.2.1

- renamed CHANGELOG.MD to CHANGELOG.md

## 0.2.0

- CLI implementation init
- replaced archiver.bulk (deprecated) in favor of archiver.directory

## 0.1.7

- Basic functionality present, mostly spec-compliant

## 0.1.3

- First release capable of doing anything useful
- Still lots of basic functionality missing

## 0.1.0

- Initial experiment
