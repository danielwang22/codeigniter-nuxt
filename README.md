# codeigniter-nuxt

> codeigniter3 + nuxtjs
>
> server: codeigniter
> client: nuxtjs

## Git Clone

```bash
# xampp active directory
$ cd c:\xampp\htdocs\

$ git clone https://github.com/camelg/codeigniter-nuxt.git
```

## Composer Install

```bash
$ cd codeigniter-nuxt/application

$ composer install
```

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).

## Apache Config

```bash
# c:\xampp\apache\conf\extra\httpd-vhosts.conf
<VirtualHost *:80>
    DocumentRoot "C:\xampp\htdocs\codeigniter-nuxt\public_html"
    ServerName codeigniter-nuxt
</VirtualHost>
```
