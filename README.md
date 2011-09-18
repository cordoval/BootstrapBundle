# Symfony2 Bootstrap Bundle v1.2.0

A [Symfony2](http://symfony.com) Bundle for using the [bootstrap CSS](http://twitter.github.com/bootstrap) from twitter.

## Installation ##

Add to your dependencies:

    [NavitronicBootstrapBundle]
        git=http://github.com/navitronic/BootstrapBundle.git
        target=/bundles/Navitronic/Bundle/BootstrapBundle
        
and run in the root of your project:

    php bin/vendors install

Add the autoload paths to your bundles in AppKernel.php

    new Navitronic\Bundle\BootstrapBundle\NavitronicBootstrapBundle()
    
## Usage ##

Coming soon.

## To Do List ##

- Improve HTML5 base template using HTML5 Boilerplate.
- Add Modernizr and jQuery fallbacks.
- -Work out if putting this in the `vendor/bundles` directory is the right way to go.- It's how FOS and some others do it.
- Work out using assettic to directly process the LESS files.
- Other git/symfony noob fixes I imagine.

Inspired by Flint's [HTML5 Boilerplate bundle](https://github.com/FlintLabs/H5BP-Symfony2-Bundle)