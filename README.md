# subsplash-webview-exclude
Logic to help control content or functionaly in a Subsplash app's webview

```php
<?php
    // Checks for existence of a specific Subsplash header value in SERVER global array
    if (array_key_exists('HTTP_SAP_USER_INSTALL_ID', $_SERVER)) {
    // Do Something
    } else {
    // Do Something Else
    }
?>
```
