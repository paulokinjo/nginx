# Nginx

## Recommendation
Configure options for a web accelerator/proxy:

```
$ ./configure --with-http_ssl_module --with-http_realip_module --with-http_geoip_module --with-http_stub_status_module --with-openssl=${BUILD_DIR}/openssl-1.0.1c
```


And the following for a web server:

```
$ ./configure --with-http_stub_status_module
```


## Options/Params

<img src="img/nginx1.png" />
<img src="img/nginx2.png" />
<img src="img/nginx3.png" />
<img src="img/nginx4.png" />
<img src="img/tablehttp1.png" />
<img src="img/tablehttp2.png" />
<img src="img/httpmodule1.png" />
<img src="img/httpmodule2.png" />
<img src="img/disable1.png" />
<img src="img/disable2.png" />
<img src="img/disable3.png" />

# Global Directives
<img src="img/GlobalDirective1.png" />
<img src="img/GlobalDirective2.png" />

# HTTP Client Directive
<img src="img/httpClientDirective1.png" />
<img src="img/httpClientDirective2.png" />

# HTTP file I/O directives
<img src="img/FileioDirectives1.png" />
<img src="img/FileioDirectives2.png" />

# HTTP hash directives
<img src="img/hashDirectives1.png" />
<img src="img/hashDirectives2.png" />

# Socket directives
<img src="img/socketDirective1.png" />
<img src="img/socketDirective2.png" />

# Listen Parameters
<img src="img/listen1.png" />
<img src="img/listen2.png" />

# Location Modifiers
<img src="img/location.png" />

# Location-only Directives
<img src="img/locationDirectives.png" />

# Mail module directives
<img src="img/mailDirective.png" />
<img src="img/mailDirectiveSsl.png" />
<img src="img/mailDirectiveSsl2.png" />

