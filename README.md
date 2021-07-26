# subsplash-webview-control
Logic to help control content or functionality of a webpage when it's loaded inside of a Subsplash app's webview

```php
<?php
    // Checks for existence of a specific Subsplash header value in SERVER global array
    if (array_key_exists('HTTP_SAP_USER_INSTALL_ID', $_SERVER)) {
    // Expected behavior inside Subsplash webview
    } else {
    // Expected behavior outside Subsplash webview
    }
?>
```
