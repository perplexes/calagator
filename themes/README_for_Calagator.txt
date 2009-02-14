= Additional theming information for Calagator

These instructions extend and replace those in themes/README.txt

== Generic vs. default theme

You should derive your custom theme from the "generic" theme, which is a
minimalistic theme that contains just enough to demonstrate how to include
logic and styling into your site.

In contrast, the "default" theme is used by "calagator.org", and is a fully
styled site that gives a comphresensive demonstration of theme use.

== Custom files

You should add or replace the following files in your theme:

* views/site/_description.html.erb
    Displayed at "/", provides a short description of your site.

* views/site/about.html.erb
    Displayed at "/about", provides a longer description of your site.
