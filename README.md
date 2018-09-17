# Custom Drupal 8 module for pre-configured media

This module installs Drupal core media and adds some useful configurion:

- An enhanced media library using the [entity_browser](https://www.drupal.org/project/entity_browser) module)

More configuration (like the [entity_embed](https://www.drupal.org/project/entity_embed) module and configuration) will be added later.

## Usage

Just install as any other drupal module using `composer require`.

```
composer require mediadukes/mdm_media:^1.0
```

If it's not already present in your repositories array you'll need to define inside your root `composer.json` where mediadukes packages can be found.

```
"repositories": [
  {
    "type": "composer",
    "url": "https://packages.mediadukes.be"
  }
]
```

Or you can use the [mediadukes drupal-project template](https://github.com/mediadukes/drupal-project) where the repository is already in combination with the custom [Amatus profile](https://github.com/mediadukes/mdp_amatus).
