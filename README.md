# Laravel WebSockets Demo 🛰

##Install on Digital Ocean

###SSH to your Dropbla

```
bash <(curl -L -Ss https://raw.githubusercontent.com/putheng/chat-demo/master/install.sh)
```

## Usage

1. Clone this repository
2. `composer install`
3. `cp .env.example .env`
4. `php artisan migrate`
5. `php artisan key:generate`
6. `php artisan websockets:serve`

7. `npm install`
8. `npm run dev`

## Credits

- [Marcel Pociot](https://github.com/mpociot)
- [Freek Van der Herten](https://github.com/freekmurze)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.