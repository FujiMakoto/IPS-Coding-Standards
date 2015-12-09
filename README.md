# IPS Coding Standards Files
This repository contains an unofficial collection of IDE configurations and other files for use with IPS' own coding standards.

## phpStorm
To import the PHP Storm code style configuration, go to File > Import Settings. Select the phpStorm.jar file included in this repository. Afterwards, open up the Setting page (File > Settings) and navigate to Editor > Code Style > PHP.

![phpStorm demonstration](https://i.imgur.com/ZgsiynN.png)

From the right-hand side of the scheme selection box, click on Manage. You should now see the IPS code style available for use!

This repository also includes a [projectCodeStyle.xml](https://github.com/FujiMakoto/IPS-Coding-Standards/blob/master/projectCodeStyle.xml) document, which you can use to automatically import the IPS coding styles in your own repositories for anyone else that uses phpStorm. To do this, you'll need to copy this file to the .idea/ directory in your projects root and commit it.

If you decide to do this, it's recommended you set up your .gitignore configuration to *only* commit this file in your .idea directory and ignore everything else.

## Scrutinizer
Scrutinizer is a great service for performing automated code checks and *scrutinizing* your code for quality, and best of all, it's completely free to use for open-source projects! To learn more about it, head over to the [official website](https://scrutinizer-ci.com).
