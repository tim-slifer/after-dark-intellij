# After-Dark-IntelliJ

This is my editor color theme for IntelliJ IDEA.

I wanted to make a color theme that was not only easy to look at, but where the colors and text styles actually carry meaning and convey context. I started with a dark background (Darcula is the parent theme) and used a variety of bright, neon-ish colors. The theme font is Source Code Pro, but no font size is given in the theme as this should be set according to preference and screen resolution.

Generally, for language syntax:

Cool colors are used for object and functions/methods. Class declarations and references are in green. Function/Method declarations and calls are in blue.

Warm colors are used for class fields, parameters, and variables. Fields on classes are in yellow. Parameters and function/method local variables are in orange. 

Various grayscale colors are used for text-based content. Comments are a darker gray, String values are a lighter gray, punctuation/operators are a very light gray (near-white).

Keywords are in magenta. Numbers are purple. Annotation/Metadata are cyan.

Text styling is also utilized to signify context. Constants and static members are italicized. Method/Function parameters and global variables are bold. Reassigned values are underlined. Line and block comments are regular text, while doc comments are italicized.

For various other syntax, subsets of the same colors were used in order to maintain a level of consistency and limit the pallette to a group of colors. An effort was also made to theme similar formats with consistency. For example, HTML and XML are themed using the same set of colors, while others such as YAML, Properties, and JSON also share a similar color group.

Extensive use of the Lanugage Defaults was used in order to both maintain consistency and to more easily facilitate customization.

## Supported Formats

Syntax theming has been defined for:

ANTLR, CSS/Less/Sass/SCSS, Groovy, HTML, Java, JavaScript, JSON, Kotlin, Properties, TOML, TypeScript, XML, YAML

## Installation

Copy the `colors` folders in this project into the IntelliJ config folder and restart Idea.

For Linux users: `~/.config/JetBrains/IntelliJIdea<version>`

For Mac users: `~/Library/Application Support/JetBrains/IntelliJIdea<version>`

For Windows users: `%APPDATA%\JetBrains\IntelliJIdea<version>`

## Colors

Color Themes are selectable in Settings at Editor >> Colors Scheme.

## Info

I tend to update this file on an as-needed basis, and have avoided any sort of formal versioning. That being the case, keeping up to date is as simple as running a quick `git pull`.

The latest changes are known to work in IntelliJ Idea 2022.2.
