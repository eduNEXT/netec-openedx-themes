Overview
========
New custom Open edX theme for Netec Digital based on a fork of
the default Stanford theme.

Created by Lawrence McDaniel
- lpm0073@gmail.com  
- http://lawrencemcdaniel.com
- https://www.linkedin.com/in/lawrencemcdaniel/
- +52 1 (55) 4388-3070
- +1 (415) 766-9012

The tree is organized to mimic the directory structure of the edX
codebase so that it's easy to tell where the files will end up upon
deploy. We'll use a special settings file to set the template and
static file paths properly to point to these files.

![Alt text](/netec-homescreen.jpg?raw=true "Netec Digital Open edX Default Theme Screenshot")

Theme Authoring
===============
To customize this theme:
- Fork this repository.
- Clone it into the theme directory next to your edx-platform directory and rename the theme directory to your new theme's name.
- Upload your own image assets.
- Edit the .scss file in static/sass/ and rename the file with your theme's name.
- Edit the lms.envs.json file in edx-platform and set 'USE_CUSTOM_THEME' to true, and 'THEME_NAME' to your theme's name.


License
=======

The code in this repo is licensed under the Apache 2.0 License.
See [LICENSE.txt](LICENSE.txt) for more info.
