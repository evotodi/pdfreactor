# RealObjects PDFreactor® PHP wrapper

PHP wrapper API for PDFreactor (PHP include, PHP sample), put into a composer-compatible library package which
autoloads the PDFreactor wrapper.

Please note that by installing and using PDFreactor itself (not the wrapper) you agree to the license, terms and
conditions of PDFreactor.com.

This package is not affiliated with RealObjects or PDFreactor.

When installing or updating evotodi/pdfreactor then the most recent version of the PDFreactor php client is downloaded and added to the composer autoload.

## Usage

Use composer to install the library via `composer require evotodi/pdfreactor`.

In an ideal world, you then have your composer-based application and just use it like this:

    $pdfReactor = new PDFreactor('http://yourServer:9423/service/rest');

or via .env logic

    $pdfReactor = new PDFreactor(getenv('PDFREACTOR_API_ENDPOINT'));

as the class is already available via the composer autoloader.

The default example taken from PDFreactor can be found under example/sample.php.

## License

The PDFreactor wrapper library is licensed under MIT, see LICENSE file for more details.
