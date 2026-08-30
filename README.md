# site-error-page

HTML files for error pages

## Usage

1. Upload the `/src/error` directory to the target website.
2. Add to `.htaccess`

```apache
# Error pages
ErrorDocument 403 /error/403.html
ErrorDocument 404 /error/404.html
ErrorDocument 500 /error/500.html
```

## License

CC0
