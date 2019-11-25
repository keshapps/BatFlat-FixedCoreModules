Sitemap is available at `example.com/sitemap.xml`. There are two ways to make your sitemap available to search engines:

+ Submit it to Google using the [Search Console Sitemaps tool](https://www.google.com/webmasters/tools/sitemap-list)
+ Insert special line anywhere in your `robots.txt` file, e.g. `Sitemap: http://example.com/sitemap.xml`

This module was updated by Piotr Płaczek https://pplaczek.pl.

You need to place below directives to `.htacces` file:
```
<IfModule mod_php7.c>
 php_flag short_open_tag off
</IfModule>
```
