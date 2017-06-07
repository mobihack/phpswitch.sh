# phpversionswitcher
Switch PHP version using bash!

## Requirements
sudo (restart apache2 & create symlinks)

Install php and mod_php(apache2) for all needed php versions.

Apache a2dismod & a2enmod is needed!

## Install
```
curl -L -O https://github.com/mobihack/phpversionswitcher/raw//master/phpswitch.sh
chmod +x phpswitch.sh

```

## Usage
Run from terminal:

`bash 'phpswitch.sh'`

This will list all installed php version.
Enter the php version to switch to.
Apache is restarted automatically!
Done!

## License
Licensed under MIT License. Please create better versions if possible :)
