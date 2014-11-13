#!!!The new package system doesn't make the files from packages easily available any more. This package will not work with Meteor 0.9.0 and higher version

# LESS Hat for Meteor
## LESS Hat. Get MORE of LESS with smart mixins on Meteor.

Use LESS hat mixins for easy cross-browser compatability. See http://lesshat.com/

## How to install

1. `npm install -g meteorite` (if not already installed)
2. `mrt add less`
3. `mrt add lesshat`
4. Create a .less file anywhere in your project to be served to the client and add `@import "/packages/lesshat/lesshat.less";`

## Meteorite version < pre-0.6.0

Previous version of Meteorite stored the packages in .meteor/meteorite/, in which case you need to change the `@import` path to `@import "/.meteor/meteorite/packages/lesshat/lesshat.less";`

## License

This package is licensed with the MIT license.

## Contributors
- [Michael Klaus](https://github.com/QaDeS/)
