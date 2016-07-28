## Intro

Forked from [FrozenNode/Laravel-Administrator](https://github.com/FrozenNode/Laravel-Administrator) with the following changes:

* UI Improved
* UX Improved (Editor view stick, hover effect etc.)
* Model deletion with Sweet alert confirmation
* Batch model deletion
* Refresh btn
* Reduce page css and js file request number
* Edit view hint

## Install

### 1. composer require

```
composer require "3sure/administrator"
```

### 2. add provider

Edit `config/app.php` in `providers` array add provider:

```php
'providers' => [
	Frozennode\Administrator\AdministratorServiceProvider::class,
]
```

### 3. publish assets/config

```
php artisan vendor:publish
```

Read the docs: http://administrator.frozennode.com

-- end
