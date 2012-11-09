sauce-connect-composer
======================

A Composer Package for Sauce Connect.

Sauce Connect is a special tunnel-creating binary application (see the [Sauce
Connect Docs](http://saucelabs.com/docs/connect)). It is bundled as a
composer package (`sauce/connect`), designed to accompany
[Sausage](http://github.com/jlipps/sausage) (`sauce/sausage`), which you can
add to your `composer.json` requirements:

```json
{
  "require": {
    "sauce/sausage": ">=0.6",
    "sauce/connect": ">=3.0"
  }
}
```

If you've already run `vendor/bin/sauce_config` or otherwise set your Sauce
credentials, starting sauce connect is as easy as:

    vendor/bin/sauce_connect

Or on Windows:

    vendor\bin\sauce_connect.bat

Run that and you'll be testing against your local test server in no time!
