# Default WordPress

This is a default wordpress depository with some basic plugins for start new project quicky.

## Getting Started

To install this repository just run the command,

```sh
$ git clone https://github.com/Faisalawanisee/default-wordpress.git
```

### Plugins

List of plugins

| Plugin | URL |
| ------ | ------ |
| Disable Comments | https://wordpress.org/plugins/disable-comments |
| Duplicator | https://wordpress.org/plugins/duplicator |
| Elementor Page Builder | https://wordpress.org/plugins/elementor |
| Email Log | https://wordpress.org/plugins/email-log |
| Google XML Sitemaps | https://wordpress.org/plugins/google-sitemap-generator |
| Lazy Load by WP Rocket | https://wordpress.org/plugins/rocket-lazy-load |
| Login LockDown | https://wordpress.org/plugins/login-lockdown |


### WP-Cli Development

Open your favorite Terminal and run these commands.

```sh
$ wp config create --dbname=testing --dbuser=wp --dbpass=securepswd --extra-php <<PHP
define( 'WP_DEBUG', true );
define( 'WP_DEBUG_LOG', true );
PHP
```

```sh
$ wp core install --url=example.com --title=Example --admin_user=supervisor --admin_password=strongpassword --admin_email=info@example.com
```

```sh
$ wp core update
```

```sh
$ wp plugin update --all
```

```sh
$ wp theme update --all
```

## Authors

* **Faisal Awan** - *PHP Developer* - [Facebook](https://www.facebook.com/faisalawan.iw)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
