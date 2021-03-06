[![CircleCI](https://circleci.com/gh/Victoire/WidgetRenderBundle.svg?style=shield)](https://circleci.com/gh/Victoire/WidgetRenderBundle)

Victoire Render Bundle
============

## What is the purpose of this bundle

This bundle gives you access to the *Render Widget*.

## Set Up Victoire

If you haven't already, you can follow the steps to set up Victoire *[here](https://github.com/Victoire/victoire/blob/master/doc/setup.md)*

## Install the Bundle

Run the following composer command :

    php composer.phar require victoire/render-widget

The render bundle handles Bootstrap and Foundation view.

### Reminder

Do not forget to add the bundle in your AppKernel !

    class AppKernel extends Kernel
    {
        public function registerBundles()
        {
            $bundles = array(
                ...
                new Victoire\Widget\RenderBundle\VictoireWidgetRenderBundle(),
            );

            return $bundles;
        }
    }
