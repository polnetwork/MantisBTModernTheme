# Mantis Bugtracker Modern Theme

![MantisBTModernTheme Screenshot](files/MantisBTModernTheme_Screenshot_2.png)

## About

I wanted a modern & clean theme for MantisBT. 
Based on https://github.com/Tagirijus/MantisBTDarkTheme

## Installation

Upload the whole folder into your `plugins/` folder in the mantis installation so that you e.g. have `MANTIS_INSTALLATION/plugins/MantisBTModernTheme/MantisBTModernTheme.php`. After that the plugin should show up on the `manage_plugin_page.php` page in the mantis settings. There you can simply install it to activate it.

I recommend you to set this colors inside your config/config_inc.php file

```php
$g_status_colors = array( 'new' => '#ffa0a0', # red,
    'feedback' => '#ff50a8', # purple
    'acknowledged' => '#ffd850', # orange
    'confirmed' => '#ffffb0', # yellow
    'assigned' => '#c8c8ff', # blue
    'resolved' => '#cceedd', # buish-green
    'closed' => '#e8e8e8'); # light gray
```