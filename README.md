Requirements
============

-   [Sublime Package Control](http://wbond.net/sublime_packages/package_control)

-   Menlo Font (Which isn't installed on Windows, so I'll maybe switch to the
    equally great (though much more free) [Meslo Font](https://github.com/andreberg/Meslo-Font).

Installation
============

1.  Install Sublime Package Control, then close Sublime.

1.  Go to the `Packages/User` directory.

2.  Clone the repo - it'll create a folder `super-sublime`.

3.  If you just want to use this as your base configuration, just move
    everything from `super-sublime/` into `User/` and remove `super-sublime`.
    If you're using bash, you can use this command:

    `mv super-sublime/* . && rm !#^:h`

4.  Open Sublime (there may be errors). Open the Console (ctrl+\`) to view the
    output. Trigger the Command Palette, and select
    `Package Control: Upgrade/Overwrite All Packages`.

5.  If there are any errors or if Sublime crashes, just quit Sublime and redo
    Step 4.

6.  Restart Sublime again to activate all the plugins.

Issues
======

-   Some packages have external dependencies. The package should open its own
    readme or notify you in the Console on installation. I primarily use OSX, so
    many package requirements are already installed on my system. Let me know if
    there are any dependencies I should add to this README.

-   The color scheme "Base 16 Color Schemes" may give you a bunch of errors on
    first startup. If you'd like, you can install this package manually to
    prevent error dialogs from getting in your way.
