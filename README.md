# URL Scanner
Scan an array of URLs and report inaccessible ones. This is an exercise from the book Modern PHP.

## Install
Via Composer
``` bash
$ composer require keekeefulldive/scanner
```

## Usage
``` php
$urls = [
    'http://offworld.net',
    'selloutsoftware.com',
    'adoiauemaojid.io'
];
$scanner = new \Oreilly\ModernPHP\Url\Scanner($urls);
print_r($scanner->getInvalidUrls());
```

## Testing
No tests yet.

## Contributing
See [CONTRIBUTING][CONTRIBUTING.md] for details.

## Credits
- [Josh Lockhart](https://github.com/codeguy)
- [All Contributors](https://github.com/modernphp/scanner/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.