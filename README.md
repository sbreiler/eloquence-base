# Sofa/Eloquence

**Custom Fork, which works with Laravel v5.6**

[See original idea](https://github.com/jarektkaczyk/eloquence-base/pull/1)

Easy and flexible extensions for the [Eloquent ORM](https://laravel.com/docs/eloquent).

**If I'm saving you some time with my work, you can back me up on [Patreon page](https://patreon.com/jarektkaczyk).**

Currently available extensions:

1. [Base - Searchable](https://github.com/jarektkaczyk/eloquence-base) query - crazy-simple fulltext search through any related model 
1. [Validable](https://github.com/jarektkaczyk/eloquence-validable) - self-validating models
2. [Mappable](https://github.com/jarektkaczyk/eloquence-mappable) -map attributes to table fields and/or related models
3. [Metable](https://github.com/jarektkaczyk/eloquence-metable) - meta attributes made easy
4. [Mutable](https://github.com/jarektkaczyk/eloquence-mutable) - flexible attribute get/set mutators with quick setup 
5. [Mutator](https://github.com/jarektkaczyk/eloquence-mutable) - pipe-based mutating

## Installation

Add custom repositories to your composer.json:
```json
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/sbreiler/eloquence-base"
    },
    {
        "type": "vcs",
        "url": "https://github.com/sbreiler/hookable"
    },
    {
        "type": "vcs",
        "url": "https://github.com/sbreiler/eloquence-mutable"
    },
    {
        "type": "vcs",
        "url": "https://github.com/sbreiler/eloquence-metable"
    },
    {
        "type": "vcs",
        "url": "https://github.com/sbreiler/eloquence-validable"
    },
    {
        "type": "vcs",
        "url": "https://github.com/sbreiler/eloquence-mappable"
    }
]
```
and require packages with version 5.6, e.g.:
```json
"require": {
  "sofa/eloquence-base": "5.6.*",
  "sofa/eloquence-mappable": "5.6.*",
  "sofa/eloquence-metable": "5.6.*",
  "sofa/eloquence-mutable": "5.6.*",
  "sofa/eloquence-validable": "5.6.*"
}
```

**Check the [documentation](https://github.com/jarektkaczyk/eloquence/wiki) for installation and usage info, [website](http://softonsofa.com/tag/eloquence/) for examples and [API reference](http://jarektkaczyk.github.io/eloquence-api)**
