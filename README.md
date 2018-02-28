# nginx_goss
 Call people to use Goss for nginx

### Make goss.yaml
```
$goss add service nginx
$goss add process nginx
$goss add port nginx
$goss add port 80
$goss add package nginx
$goss add user nginx
$goss add group nginx
```
### Use Goss
```
$goss validate
```

```
$goss validate
...............

Total Duration: 0.053s
Count: 15, Failed: 0, Skipped: 0
```
