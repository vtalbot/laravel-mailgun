# Laravel Mailgun

A Laravel Mailgun bundle, installable via the Artisan

  php artisan bundle:install mailgun

Add it to `application/bundles.php`

  return array(
    ...
    'mailgun' => array(
      'auto' => true
    ),
    ...
  );

To get a Mailgun instance:

  $mg = IoC::resolve('mailgun');