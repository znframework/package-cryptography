<h2>ZN Framework Cryptography Package</h2>
<p>
Follow the steps below for installation and use.
</p>

<h3>Installation</h3>
<p>
You only need to run the following code for the installation.
</p>

```
composer require znframework/package-cryptography
```

<h3>Documentation</h3>
<p>
Click for <a href="https://docs.znframework.com/kriptografi-guvenlik/kripto-kutuphanesi">documentation</a> of your library.
</p>

<h3>Example Usage</h3>
<p>
Basic level usage is shown below.
</p>

```php
<?php require 'vendor/autoload.php';

ZN\ZN::run();

$encrypt = Crypto::encrypt('Example Data',
[
    'key'  => 'xxcv2151',
    'mode' => 'cbc'
]);

echo $encrypt;
```
