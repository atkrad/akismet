# Akismet

Akismet checks your comments against the Akismet web service to see if they look like spam or not and lets you review the spam it catches under your blog's "Comments" admin screen.

## Requirements

The master branch has the following requirements:

* Hurad 0.1.0 or greater.
* PHP 5.4 or greater.

## Installation

* Clone/Copy the files in this directory into `app/Plugin/Akismet`
* Activate the plugin from your admin panel.

### Using Composer

Ensure `require` is present in `composer.json`. This will install the plugin into `Plugin/Akismet`:

```
{
    "require": {
        "atkrad/akismet": "0.1.*"
    }
}
```

## Issues with Akismet

If you have issues with Akismet, you can report them at https://github.com/atkrad/akismet/issues