# Sublime NestingSnippet plugin

Replaces default brackets "({[" and quotes "'"" snippets in order to improve
indentation inserting.


### Installation

This plugin is part of [sublime-enhanced](http://github.com/shagabutdinov/sublime-enhanced)
plugin set. You can install sublime-enhanced and this plugin will be installed
automatically.

If you would like to install this package separately check "Installing packages
separately" section of [sublime-enhanced](http://github.com/shagabutdinov/sublime-enhanced)
package.


### WARNING

Does not work with multicursors because [sublime-snippet-caller](http://github.com/shagabutdinov/sublime-snippet-caller)
does not work with multicursors. If run with multicursors than it'll fallback
to default sublime behavior.


### Features

Fix wrong indentation issue after wrapping selected contents to snippet.


### Usage

  ```
    # {} is selection
    # before
    a or {b and
      c}

    # after
    a or ({b and
      c})

    # after (default sublime behavior)
    a or ({b and
      [extra tabs here]c})

  ```

### Dependencies

* [SnippetCaller](https://github.com/shagabutdinov/sublime-snippet-caller)