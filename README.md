# DNS Tracer

[![Latest Stable Version](https://poser.pugx.org/wilkques/dns-dig/v/stable)](https://packagist.org/packages/wilkques/dns-dig)
[![License](https://poser.pugx.org/wilkques/dns-dig/license)](https://packagist.org/packages/wilkques/dns-dig)

## Description
Use PHP to simulate the functionality of DNS tools like DIG or Nslookup

## Installation
`composer require wilkques/dns-tracer`

## How to use
```php
$dig = new \Wilkques\DNS\DNSTracer;

$resolve = $dig->trace('<host name>', '<dns type>');

var_dump(
    $resolve
);
```