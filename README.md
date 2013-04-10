wpdb-profiler
=============

A WordPress plugin that uses built-in profiling tools in wpdb to troubleshoot DB performance issues


Plugin structure
----------------

* Will use `SAVEQUERIES` hook in wpdb to save queries with elapsed time and stack trace.
* Will be based on Dewdrop and use `package` CLI command for no conflict distribution. <https://github.com/DeltaSystems/dewdrop>
* Will use PHPMyAdmin components to pretty-print SQL statements. <http://stackoverflow.com/questions/2078661/use-php-to-format-an-input-sql-query-as-html>
* Will be GPL licensed and available from WordPress.org.
* Will allow activation of profiling manually, based upon logged-in user, and based upon environment.
* Will integrate with WP admin bar.

