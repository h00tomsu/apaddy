# apaddy
Caddy browse template that replicate the output from apache mod_autoindex for compability with kodi.
## Installation
Just copy the apaddy folder to the path you want to serve with caddy.
## Example Caddyfile
```
sub.domain.tld {
        root * /path/to/served/directory
        file_server {
                browse /path/to/served/directory/apaddy/apaddy_browse_template.html
        }
}

```
## Screenshot
![screenshot](.github/screenshot.png)
## Prefer Caddys default look and feel?
Have a look at [CaddyBrowseForKodi](https://github.com/h00tomsu/CaddyBrowseForKodi). A modified version of caddys default browse template that works with Kodi.