Research@JCU Themes
===================

Usage
-----

Firstly, install Sass_. Then, to pre-process::


    sass research-theme.scss research-theme.css


This resulting CSS file can be included within Plone.  It is designed to be
included after the existing Sunburst basic theme and hence includes numerous
overrides to avoid having to reproduce Sunburst's CSS.

.. _Sass: http://sass-lang.com/

Customising for subsites
------------------------

Follow the existing examples for the Research@JCU site or CCRN sites: provide
a more-specific selector to target the site, customise the variables to modify
colours and designs, and then ``import 'base-theme'`` again.  This results in
anything present within ``base-theme`` being wrapped in the specific
selector.

For Plone, this is just a matter of specifying ``.site-[id]`` or
``.section-[id]``, depending on whether subsites or sections are being used to
target the content for styling.
