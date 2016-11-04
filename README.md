WordPress XHProf
=========


A WordPress plugin which makes it easy to view XHProf report for the current page request.

To active, add the following to `wp-config.php`, before `wp-settings.php` is included.

  require_once(ABSPATH . 'wp-content/plugins/wp-xhprof/xhprof-loader.php');

Please note that `xhprof-loader.php` currently starts XH Prof and sets `DONOTCACHEPAGE` even if the plugin is disabled.

If available, the plugin will use the 'tideways' extension instead of xhprof
(xhprof is no longer maintained and does not support php 5.6 or php 7)
