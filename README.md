Utility CSS
===========

This module adds autocomplete to class fields in block configuration by searching the active theme's info file for utility_class configuration.

This is currently a proof of concept.

![Screenshot of utility class module suggesting classes in block configuration](https://github.com/backdrop-contrib/utlility_css/raw/master/utility-class.png)

This functionality works with Basis out of the box, or add config like the following to your theme's .info file:

```
utility_css[font][] = 'color-inverse'
utility_css[font][] = 'font-size-xxxxlarge'
utility_css[font][] = 'font-size-xxxlarge'
utility_css[font][] = 'font-size-xxlarge'
utility_css[font][] = 'font-size-xlarge'
utility_css[font][] = 'font-size-large'
utility_css[font][] = 'font-size-medium'
utility_css[font][] = 'font-size-normal'
utility_css[font][] = 'font-size-small'
utility_css[font][] = 'font-size-xsmall'
utility_css[font][] = 'font-weight-bold'
utility_css[font][] = 'font-weight-normal'
utility_css[font][] = 'font-weight-normal'
utility_css[font][] = 'font-style-italic'
utility_css[font][] = 'font-style-normal'
```

These are example utility classes from Basis.


Roadmap
-------

Want to add the following features:

* Have different predefined groups for classes, e.g. font, layout, spacing, background, etc.
* Add text field widget so custom fields can use this functionality
* Show good groups in different contexts
* Maybe have some classes that are exclusive (e.g. you shouldn't be able to add font-weight-bold font-weight-normal on the same thing)
* Provide a stylesheet with a lot of utilities that can be loaded in over any theme
* Provide bootstrap layout classes if layout is using bootstrap?
* Add ability for layout to provide utility classes?
* Allow base theme to provide utility classes


License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Maintainers
-----------

- Wes Ruvalcaba (https://github.com/wesruv)
