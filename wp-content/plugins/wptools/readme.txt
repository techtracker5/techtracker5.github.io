=== WP Tools Increase Maximum Limits, Repair, Server PHP Info, Javascript errors, File Permissions, Transients, Error Log ==
Contributors: sminozzi
Tags: increase file size limit, increase upload limit, php info, error_log, server load
Requires at least: 5.2
Tested up to: 6.6
Stable tag: 4.59
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

47 Tools, Increase Max upload file size limit, Maximum Execution Time, Folder Permissions, show PHP Version, Server Stats, Server Benchmark, PHP Info 

== Description ==
> The WP Tools plugin (wp-tools) features a comprehensive dashboard showcasing server statistics, including a chart of errors, page load time also by page and boasts over 47 tools designed to simplify your WordPress management tasks. It serves as a versatile Swiss army knife for your WordPress needs.
Catch and alert about Javascript Errors (and also PHP/MYSQL errors). Block notification email of updates, Hide Admin Bar, Disable Lazy Load, Displays the folders that are taking up more disk space and a lot more... Multilanguage ready. Included also Italian, Portuguese, Spanish language files.

A must have plugin also by cloud hosting as AWS Amazon Lightsail, EC2 instance, Bitnami, Contabo, Azure, Google Cloud, Digital Ocean and others. 

* Increase the PHP memory limit, Increase Maximum Execution Time limit, and Increase maximum upload file size limit without editing any WordPress or PHP files.
* Show the WordPress errors (PHP errors error_log, error log or error reporting), limited to 200 last WordPress errors to Help you fix issues.
* Show the PHPINFO with a lot of info about your PHP server configuration, also server IP.
* Disable WordPress Native Sitemap Automatic Creation or only user's sitemap.
* Disables the default notification email sent by a site after an automatic core, theme or plugin update.
* Add Google Search Central HTML TAG.
* Add Google Analytics GA4 Tracking ID.
* Alert on Top Admin Bar if WordPress Debug is active.
* Hide Admin Bar from non Administrators.
* Deactivate Lazy Load functionality.
* Deactivate Emojis functionality.
* Page Load Info: Number of SQL queries per page and page load time.
* Record and send email notifications when PHP notices, warnings and errors happen.
* Show and edit the file robots.txt.
* Show and check MySQL tables and database usage and MySQL details.
* Bypass WordPress debug and show errors and warnings on screen.
* Show Cron Jobs table and delete Cron Jobs without functionality.
* Show file .htaccess.
* Show file wp-config.php.
* Show Cookies.
* Restores the previous classic widgets settings UI screens and disables the gutenberg block editor from managing widgets.
* Disable the WP Admin Bar / Toolbar on the frontend of sites.
* Show Button with WordPress Errors on Admin Toolbar.
* Show Files and Folders Permissions.
* Show Table only with Javascript errors and jQuery Version.
* Replace WordPress logo at login screen.
* Remove WordPress icon from the admin bar.
* Erase readme.html and license.txt files at root folder.
* Show disk total space, disk used and disk free.
* Show Server Benchmark Server Check-Up or Server Checkup.
* Show MySQL Info and database information.
* Disable javascript console log for non administrators.
* Show and check file permissions.
* Enables the WordPress database tools to optimize and repair InnoDB and MyISAM database tables.
* Show and delete Transients.
* Disable Self PingBack.
* Show Search Engine Visibility WordPress Setup.
* Show Server Root Path.
* Site Health Alert.
* Show PHP Extensions Loaded.
* Show PHP Disabled Functions.
* Show MYSQL Table Prefix.
* Show Database charset.
* Show Robots.txt.
* Erase file .maintenance.
* Resolve 'Incompatible Archive' issue when installing plugins from zip files by using PclZip instead of ZipArchive. Consider using this option only for new plugin installations.
* Show Server Load Average percentage for the last minute at top admin bar. **

With the last tool, now you can monitor your server load (CPU Usage), in real time, from your wordpress admin panel.

**Requirements for use Show Server Load Tool and Dashboard**

* Linux Server (not Windows server)
* shell_exec enabled on your PHP (ask for your hosting to enable it if necessary)
* Server Files Readable: /proc/cpuinfo and /proc/stat
* php functions enabled: sys_getloadavg(), disk_total_space(), disk_free_space()

== Lifetime license with premium enhancements: One-time payment of just $17.99! ==

<a href="https://wptoolsplugin.com/help/index.php">Online Documentation</a>
    
<a href="https://billminozzi.com/dove/">Support Site</a>

<a href="https://wptoolsplugin.com/blog/">Blog With Free Tips</a>

<a href="https://siterightaway.net/troubleshooting/">Plugin Troubleshooting</a>

<a href="https://github.com/sminozzi/wptools/blob/master/readme.md">Github Page</a>

== Screenshots ==
1. Dashboard Charts
2. Dashboard Info
3. Server Errors 
4. More a Lot of Info and Tools

== PHP INFO DETAILS ==

On PHP INFO page, you can get, for example:

* Display PHP Version
* Operating System details
* PHP.INI path (Configuration File (php.ini) Path )
* Log Errors on or off
* FTP (FTP Support)   
* GD 
* MySql and MySqli version
* Session 
* Soap 
* XML 
* ZIP 
* ZLIB 
* Timezone
* Cookies
* Modules
* PHP Variables 
* Post Max Size (Post Max Size, Post Maximum Size)
* max_execution_time (set_time_limit, max execution time, (maximum execution time exceeded))
* max_file_uploads, upload_max_filesize	(max file uploads, maximum file uploads)
* max_input_nesting_level (max input nesting level) 	
* max_input_time (max input time, maximum input time)	
* max_input_vars (max input vars, maximum input vars)	
* memory_limit (Memory Limit)
* smtp_port (smtp port)
* A lot more ...

== mySQL info ==
On database details page, you can get, for example:

* MySQL (or Maria Database) version
* Database size (Database Usage)
* Index size (Index Disk Usage)
* max_allowed_packet (max allowed packet, maximum allowed packet)
* default_storage_engine (default storage engine)
* max_connections (max_connections, maximum connections)
* max_user_connections (max user connections, maximum user connections)
* thread_cache_size (thread cache size)
* query_cache_type (query cache type)
* query_cache_size (query cache size)
* sort_buffer_size (sort buffer size)
* read_buffer_size (read buffer size)
* port (mysql Port)
* tmp_table_size  (tmp table size)
* read_rnd_buffer_size (read rnd buffer size)
* join_buffer_size (join buffer size)
* table_definition_cache (table definition cache)
* table_open_cache (table open cache)
* character_set_system (character set system)
* default_storage_engine (default storage engine)
* A lot more ...


== Multisite ==
Not tested on Multisite.

== Installation ==

1) Install via wordpress.org

2) Activate through 'Plugins' menu or extract zip to wp-content/plugins/ and activate from Plugins page.

== FAQ ==
**How to Install?**

1) Install via wordpress.org

2) Activate through 'Plugins' menu or extract zip to wp-content/plugins/ and activate from Plugins page.


**How can I check my WordPress web server performance using your plugin?**

Our plugin includes comprehensive benchmarking tools to help you evaluate your WordPress web server performance. By using these tools, you can perform a detailed WordPress benchmark to understand how your server stacks up against others. The plugin's web server benchmark feature provides insights into various aspects of server performance, including CPU usage and memory limits.

To check your WordPress website performance, our plugin conducts a server performance test, comparing your results against industry standards and providing a vs benchmark analysis. This allows you to see how well your server performs versus benchmark scores from other similar setups.

By utilizing these benchmarking tools, you can ensure your WordPress site is optimized and running efficiently, giving you a clear view of your web server's capabilities and performance metrics.


**How can I optimize my website's speed and perform a comprehensive speed test using your plugin?**

Our plugin offers powerful tools for pagespeed optimization, allowing you to test website speed and gain insights into various performance metrics. By performing a page speed test, you can analyze the loading time of your website and make necessary adjustments to improve it.

Our plugin also performs a comprehensive benchmark of your server, providing detailed insights into its performance and identifying potential areas for improvement.

By running a page test speed, you can check the average page load time and identify areas for improvement. Our plugin also includes a page load timer to measure the loading time for your website, providing a detailed website speed check.

With these comprehensive testing tools, you can optimize your site to achieve better performance and faster load times, ensuring a smoother user experience and better SEO results.

**What limits can be adjusted or monitored in a WordPress environment using the WPTools plugin?**
Time Limit controls how long a PHP script can run.
Maximum Execution Time determines the maximum time PHP scripts are allowed to run.
Maximum Limits refer to various server-side limits that can affect operations like database queries or file uploads.
File Size Limit limits the size of files that can be uploaded to your WordPress site.
Disk Usage monitors the amount of storage space allocated to your site.
Max Upload File Size specifies the largest file that can be uploaded through WordPress.
Max Upload Limit controls the total size of uploads allowed.
Max Post Size specifies the maximum size of POST data that PHP will accept.

**How can the WPTools plugin assist in monitoring Errors and Debugging on my site?**
The WPTools plugin enhances your ability to monitor Errors and Debugging on your site with advanced features such as JavaScript, PHP and database error monitoring, which includes trapping, reporting, logging, and notifying about JavaScript errors. It also helps in handling PHP errors and maintaining an error log. With WPTools, you can streamline your debugging process and ensure smooth site operation. The notification feature ensures that you are promptly informed of any critical errors, allowing for quick resolution and maintenance of site performance.
Additionally, WPTools provides comprehensive website health check capabilities. It functions as a complete site health check, offering detailed insights and guidance. The plugin includes a health check plugin and offers a checkup guide, as well as the option to connect with a checkup freelancer or a checkup doctor. Whether you need an immediate review with checkup now, detailed analysis through checkup PHP, or a cost-effective option like checkup free, WPTools supports all aspects of health check & troubleshooting to ensure your site runs optimally.

**How does the WPTools plugin provide additional information about the server that is not typically supplied by hosting companies?**
The WPTools plugin is very useful for providing additional information about the server that is typically not supplied by hosting companies like Azure, Digital Ocean, Contabo, and Amazon WS. This information will help you better understand your server’s performance and optimize your WordPress site accordingly. With WPTools, you can monitor server metrics, track disk usage, and view error logs (also javascript errors), which are crucial for maintaining a healthy and efficient website. Additionally, WPTools offers insights into maximum execution times, file size limits, and various other server-side configurations, enabling you to make informed decisions and quickly address potential issues. This comprehensive approach ensures your website runs smoothly and efficiently, providing an enhanced user experience.

**What is the purpose of the additional tools and utilities provided by the WP Tools plugin**
The WP Tools plugin provides a wide range of additional tools and features to enhance the management and performance of your WordPress site. Some of the most relevant tools include:
Remove WordPress Icon: Allows you to remove the WordPress icon from the admin bar.
Directory and File Permissions: Provides information about the directory and file permissions on your site, helping to identify and resolve access issues.
Cron Jobs: Allows you to view and delete scheduled tasks (Cron Jobs) on your site.
View and Delete Transients: Enables you to view and delete temporary data (Transients) on your site.
Analytics Tag: Allows you to add an analytics tag to improve monitoring of your site.
View Cookies: Provides the ability to view information about the cookies stored on your site.
and more...

**How can I start fixing JavaScript errors in WordPress?**

To start fixing JavaScript errors in WordPress, we recommend installing our free plugin, WPTools. WPTools will help you catch, log, and notify you of any WordPress console errors. It effectively handles WordPress frontend JavaScript errors and WordPress backend JavaScript errors, making WordPress JavaScript troubleshooting easier by identifying and providing detailed reports on where and why errors are occurring.

**What are the best practices for JavaScript error monitoring in WordPress?**

JavaScript error monitoring in WordPress involves setting up tools to constantly watch for errors and log them for review. We recommend using our free plugin, WPTools, for comprehensive JavaScript error reporting WordPress. WPTools enables effective WordPress JavaScript error logging and consistent JavaScript error monitoring to help you proactively identify and address potential problems.

**How do I detect and handle JavaScript errors in my WordPress site?**

To effectively detect and handle JavaScript errors on your WordPress site, install our free plugin, WPTools. WPTools can help you catch and handle JavaScript errors gracefully within your scripts. Proper WordPress JavaScript errors detection with WPTools ensures you can trap JavaScript errors early, preventing them from affecting user experience.

**What options are available for JavaScript error notification in WordPress?**

For JavaScript error notification in WordPress, install our free plugin, WPTools. WPTools provides automated systems that alert you whenever an error occurs, ensuring effective JavaScript error reporting. Integrating JavaScript error notification through WPTools helps maintain the health of your site by promptly informing you about issues, allowing for quick resolution.

** What are some common JavaScript errors in WordPress and how can I avoid them?**

 Common JavaScript errors in WordPress include conflicts between plugins, outdated scripts, and errors in custom code. To avoid these, regularly update your themes and plugins, and ensure they are compatible with each other. Watch for JavaScript console warnings WordPress as they can indicate potential issues. Addressing WordPress admin JavaScript issues promptly and thoroughly testing any custom scripts before deployment can also prevent many common errors. For comprehensive error handling, we recommend installing our free plugin, WPTools, which can help you catch, log, and notify you of JavaScript errors.




== 3rd party as a service == 

The WP Tools plugin offers an a optional free Community Server Performance service. 
To participate, you must enable the feature within the plugin by checking 
the box labeled "Participate in Community Server Performance." on plugin Settings page.

Enabling this feature allows your site to share only server performance data with the WP Tools Plugin. 
In return, your WordPress site receives updated aggregated industry average data.

The data collect are:

Time	
PHP and MYSQL Version	
Platform is Linux?
Server ip address	
Benchmark (only time): Math, String, Loops, Conditionals
MYSQL (only time):  Connect, Select DB, Query Version, Benchmark		

We will create an aggregated industry average data and let you see in your dashboard.

	

These are the terms of use for <a href="https://siterightaway.net/terms-of-use-of-our-plugins-and-themes/">our plugins</a>.

To learn more details about the wptools plugin, visit the <a href="https://wptoolsplugin.com/">plugin site</a>.



=== changelog ===
This file contains changelog entries.
