# All In One WP Migration Fork

### (from Version 6.77)

This is the last version of the All In One WP Migration plugin to include import functionality functionality. Versions after this were also stripped of WP-CLI functionality.

The file upload size limit has been modified to be `32GB`. To change this you may define the limit in byes on line 284 in `constants.php` (if 32 Gigs doesn't float your boat).

```php
// =================
// = Max File Size =
// =================
define( 'AI1WM_MAX_FILE_SIZE', 34359738368 );
```
