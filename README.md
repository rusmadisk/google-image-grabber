# Google Image Grabber

Scrape google images using PHP

## Getting Started

Get this up and running

### Prerequisites

composer

### Installing

```bash
composer require rusmadisk/google-image-grabber
```

### Usage

```php
use Rusmadisk\GoogleImageGrabber\GoogleImageGrabber;

$keyword = 'makan nasi';

$images = GoogleImageGrabber::grab($keyword);

```

## Test

```bash
./vendor/bin/kahlan --reporter=verbose
```

## Authors

* **Mochammad Masbuchin**

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

MIT
