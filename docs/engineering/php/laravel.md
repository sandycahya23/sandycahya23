## Optimization

### Config Caching

```
# Run this command to cache Laravel config
php artisan config:cache
# Run this command to clear cache (if there is route changes)
php artisan config:clear
```
### Routes Caching

```
# Run this command to cache Laravel route
php artisan route:cache
# Run this command to clear route (if there is route changes)
php artisan route:clear
```

### Remove Unused Service

### Classmap Optimization

```
php artisan optimize --force
```

### Optimize Composer

```
# Run this command to allow Composer to make a separate directory for autoloader optimization.
composer install --prefer-dist --no-dev -o
```

### Limit Include Libraries


### JIT Compiler

### Choose a Fast Cache & Session Driver

#### Cache Queries Results

### Use Horizontal Scaling


### References

- https://www.cloudways.com/blog/laravel-performance-optimization/
