# ember-cli-neat

Include neat in an ember-cli app.

When the addon is installed, it will add neat 1.7.2 as
a bower dependency.

## Dependencies

Your project should already be set up to handle sass/scss builds. If you're not, do so by running:

    ember install ember-cli-sass

## Usage

In your ember-cli (>= 0.1.1) project, run:

    ember install ember-cli-neat

The generator will create an `app.scss` with the sole contents being:

    @import "bourbon";
    @import "neat";

If you already have content in your `app.scss`, you can just choose "n" and add that
line to the top of `app.scss` yourself.

- `git clone <repository-url>` this repository
- `cd ember-cli-neat`
- `npm install`
- `bower install`

- Ember.js v2.18 or above
- Ember CLI v2.13 or above

## Installation

```
ember install my-addon
```

## Usage

For more information on using ember-cli, visit [https://ember-cli.com/](https://ember-cli.com/).

## Credit

Inspired by the [ember-cli-bourbon](https://github.com/yapplabs/ember-cli-bourbon) addon made by the good folks at Yapp.
