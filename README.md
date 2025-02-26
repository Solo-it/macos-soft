# Instruction

## PHP more versions

https://stackoverflow.com/questions/34909101/how-can-i-easily-switch-between-php-versions-on-mac-osx

if php 7.4 not install then weed install from:
```
   brew install shivammathur/php/php@7.4
   brew list | grep php
```
## Change from 8.4 to 7.4
```
   brew unlink php
   brew link php@7.4
```
## Change from 7.4 to 8.4
```
  brew unlink php@7.4
  brew link php
```

## Composer update

```
   composer self-update
```
