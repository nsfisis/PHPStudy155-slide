Personal Home Page Tools (PHP Tools)
1995/6/8

https://ja.wikipedia.org/wiki/PHP_(%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0%E8%A8%80%E8%AA%9E)
https://ja.wikipedia.org/wiki/%E3%83%A9%E3%82%B9%E3%83%9E%E3%82%B9%E3%83%BB%E3%83%A9%E3%83%BC%E3%83%89%E3%83%95

FI (Form Interpreter)
Personal Home Page Construction Kit
PHP/FI

PHP/FI Version 2.0 (PHP 2)  1996/6

PHP 3.0 (PHP: Hypertext Preprocessor) 1998/6

PHP 4.0 (Zend Engine) 2000/5
PHP 5
PHP 6 (欠番)
PHP 7
PHP 8

https://www.php.net/manual/ja/history.php.php

https://groups.google.com/g/comp.infosystems.www.authoring.cgi/c/PyJ25gZ6z7A/m/M9FkTUVDfcwJ?pli=1

> Announcing the Personal Home Page Tools (PHP Tools) version 1.0.
> These tools are a set of small tight cgi binaries written in C.
> They perform a number of functions including:
>
> . Logging accesses to your pages in your own private log files
> . Real-time viewing of log information
> . Providing a nice interface to this log information
> . Displaying last access information right on your pages
> . Full daily and total access counters
> . Banning access to users based on their domain
> . Password protecting pages based on users' domains
> . Tracking accesses ** based on users' e-mail addresses **
> . Tracking referring URL's - HTTP_REFERER support
> . Performing server-side includes without needing server support for it
> . Ability to not log accesses from certain domains (ie. your own)
> . Easily create and display forms
> . Ability to use form information in following documents
> 
> Here is what you don't need to use these tools:
> 
> . You do not need root access - install in your ~/public_html dir
> . You do not need server-side includes enabled in your server
> . You do not need access to Perl or Tcl or any other script interpreter
> . You do not need access to the httpd log files
> 
> The only requirement for these tools to work is that you have
> the ability to execute your own cgi programs. Ask your system
> administrator if you are not sure what this means.
> 
> The tools also allow you to implement a guestbook or any other
> form that needs to write information and display it to users
> later in about 2 minutes.
> 
> The tools are in the public domain distributed under the GNU
> Public License. Yes, that means they are free!
> 
> For a complete demonstration of these tools, point your browser
> at: http://www.io.org/~rasmus
> 
> --
> Rasmus Lerdorf
> ras...@io.org
> http://www.io.org/~rasmus


https://www.jetbrains.com/ja-jp/lp/php-25/

https://twitter.com/rasmus/status/226405807305138176

https://www.php.net/releases/

https://www.php.net/manual/php3.php

http://museum.php.net/php3/php-3.0.18.tar.gz





$ ./php -h
Usage: php [-q] [-h] [-s] [-v] [-i] [-f <file>] | {<file> [args...]}
  -q       Quiet-mode.  Suppress HTTP Header output.
  -s       Display colour syntax highlighted source.
  -f<file> Parse <file>.  Implies `-q'
  -v       Version number
  -p       Pretokenize a script (creates a .php3p file)
  -e       Execute a pretokenized (.php3p) script
  -c<path> Look for php3.ini file in this directory
  -i       PHP information
  -h       This help


$ ./php -i
X-Powered-By: PHP/3.0.18
Content-type: text/html

<center><h1>PHP Version 3.0.18</h1></center>
by <a href="mailto:rasmus@lerdorf.on.ca">Rasmus Lerdorf</a>,
<a href="mailto:andi@zend.com">Andi Gutmans</a>,
<a href="mailto:bourbon@netvision.net.il">Zeev Suraski</a>,
<a href="mailto:ssb@fast.no">Stig Bakken</a>,
<a href="mailto:shane@caraveo.com">Shane Caraveo</a>,
<a href="mailto:jimw@php.net">Jim Winstead</a>, and countless others.<P>
<hr><center>System: Linux my-notebook 6.2.0-26-generic #26~22.04.1-Ubuntu SMP PREEMPT_DYNAMIC Thu Jul 13 16:27:29 UTC 2 x86_64 x86_64 x86_64 GNU/Linux<br>Build Date: Aug 11 2023</center>
<center>
<hr><h2>Extensions</h2>
<table border=5 width="600">
<tr><th bgcolor="#00DDDD">Extensions</th><th bgcolor="#00DDDD">Additional Information</th></tr>
<tr><th align=left bgcolor="#999999">PHP core</th>
<td bgcolor="#DDDDDD"><tt>CFLAGS=<br>
HSREGEX=</td></tr>
<tr><th align=left bgcolor="#999999">Basic Functions</th><td bgcolor="#DDDDDD">No additional information.</td></tr>
<tr><th align=left bgcolor="#999999">PHP_DL</th><td bgcolor="#DDDDDD">Dynamic Library support enabled.
</td></tr>
<tr><th align=left bgcolor="#999999">PHP_dir</th><td bgcolor="#DDDDDD">No additional information.</td></tr>
<tr><th align=left bgcolor="#999999">PHP_filestat</th><td bgcolor="#DDDDDD">No additional information.</td></tr>
<tr><th align=left bgcolor="#999999">PHP_file</th><td bgcolor="#DDDDDD">No additional information.</td></tr>
<tr><th align=left bgcolor="#999999">PHP_head</th><td bgcolor="#DDDDDD">No additional information.</td></tr>
<tr><th align=left bgcolor="#999999">Sendmail</th><td bgcolor="#DDDDDD">Path to sendmail: <tt>/usr/lib/sendmail -t</tt></td></tr>
<tr><th align=left bgcolor="#999999">Syslog</th><td bgcolor="#DDDDDD">No additional information.</td></tr>
<tr><th align=left bgcolor="#999999">Socket functions</th><td bgcolor="#DDDDDD">No additional information.</td></tr>
<tr><th align=left bgcolor="#999999">Regular Expressions</th><td bgcolor="#DDDDDD">Bundled regex library enabled
</td></tr>
<tr><th align=left bgcolor="#999999">DBM</th><td bgcolor="#DDDDDD">flat file support enabled</td></tr>
<tr><th align=left bgcolor="#999999">bcmath</th><td bgcolor="#DDDDDD">No additional information.</td></tr>
<tr><th align=left bgcolor="#999999">browscap</th><td bgcolor="#DDDDDD">No additional information.</td></tr>
<tr><th align=left bgcolor="#999999">PHP_pack</th><td bgcolor="#DDDDDD">No additional information.</td></tr>
<tr><th align=left bgcolor="#999999">PCRE</th><td bgcolor="#DDDDDD">Perl Compatible Regular Expressions<table cellpadding=5><tr><td>PCRE library version:</td><td>2.05 21-Apr-1999</td></tr></table></td></tr>
<tr><th align=left bgcolor="#999999">Posix</th><td bgcolor="#DDDDDD">$Revision: 1.19 $
</td></tr>
<tr><th align=left bgcolor="#999999">LCG</th><td bgcolor="#DDDDDD">No additional information.</td></tr>
</table>
<hr><h2>Configuration</h2>
Configure command: ./configure '--prefix=/home/ken/src/nil/php-3.0/build'<br>
php3.ini file path is set to: /usr/local/lib<br>
<table border=5 width="600">
<tr><th bgcolor="#00DDDD">Directive</th><th bgcolor="#00DDDD">Master Value</th><th bgcolor="#00DDDD">Local Value</th></tr>
<tr><td bgcolor="#999999">arg_separator</td><td bgcolor="#DDDDDD">&nbsp;&</td><td bgcolor="#DDDDDD">&nbsp;&</td></tr>
<tr><td bgcolor="#999999">asp_tags</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">auto_prepend_file</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">auto_append_file</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">browscap</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">cgi_ext</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">debugger.host</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">debugger.port</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">define_syslog_variables</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">display_errors</td><td bgcolor="#DDDDDD">1</td><td bgcolor="#DDDDDD">1</td></tr>
<tr><td bgcolor="#999999">doc_root</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">enable_dl</td><td bgcolor="#DDDDDD">1</td><td bgcolor="#DDDDDD">1</td></tr>
<tr><td bgcolor="#999999">engine</td><td bgcolor="#DDDDDD">1</td><td bgcolor="#DDDDDD">1</td></tr>
<tr><td bgcolor="#999999">error_log</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">error_append_string</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">error_prepend_string</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">error_reporting</td><td bgcolor="#DDDDDD">55</td><td bgcolor="#DDDDDD">55</td></tr>
<tr><td bgcolor="#999999">extension_dir</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">gpc_order</td><td bgcolor="#DDDDDD">&nbsp;GPC</td><td bgcolor="#DDDDDD">&nbsp;GPC</td></tr>
<tr><td bgcolor="#999999">ignore_user_abort</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">include_path</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">isapi_ext</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">last_modified</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">log_errors</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">max execution time</td><td bgcolor="#DDDDDD">30</td><td bgcolor="#DDDDDD">30</td></tr>
<tr><td bgcolor="#999999">magic_quotes_gpc</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">magic_quotes_runtime</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">magic_quotes_sybase</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">memory limit</td><td bgcolor="#DDDDDD">8388608</td><td bgcolor="#DDDDDD">8388608</td></tr>
<tr><td bgcolor="#999999">nsapi_ext</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">open_basedir</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">precision</td><td bgcolor="#DDDDDD">14</td><td bgcolor="#DDDDDD">14</td></tr>
<tr><td bgcolor="#999999">safe_mode</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">safe_mode_exec_dir</td><td bgcolor="#DDDDDD">&nbsp;/usr/local/php/bin</td><td bgcolor="#DDDDDD">&nbsp;/usr/local/php/bin</td></tr>
<tr><td bgcolor="#999999">sendmail_from</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">sendmail_path</td><td bgcolor="#DDDDDD">&nbsp;/usr/lib/sendmail -t</td><td bgcolor="#DDDDDD">&nbsp;/usr/lib/sendmail -t</td></tr>
<tr><td bgcolor="#999999">short_open_tag</td><td bgcolor="#DDDDDD">1</td><td bgcolor="#DDDDDD">1</td></tr>
<tr><td bgcolor="#999999">smtp</td><td bgcolor="#DDDDDD">&nbsp;localhost</td><td bgcolor="#DDDDDD">&nbsp;localhost</td></tr>
<tr><td bgcolor="#999999">sql_safe_mode</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">track_errors</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">track_vars</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">upload_max_filesize</td><td bgcolor="#DDDDDD">2097152</td><td bgcolor="#DDDDDD">2097152</td></tr>
<tr><td bgcolor="#999999">upload_tmp_dir</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">user_dir</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">warn_plus_overloading</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">xbithack</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">browscap</td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td><td bgcolor="#DDDDDD">&nbsp;<i>none</i></td></tr>
<tr><td bgcolor="#999999">y2k_compliance</td><td bgcolor="#DDDDDD">0</td><td bgcolor="#DDDDDD">0</td></tr>
<tr><td bgcolor="#999999">highlight_comment</td><td bgcolor="#DDDDDD"><font color=#FF8000>&nbsp;#FF8000</font></td><td bgcolor="#DDDDDD"><font color=#FF8000>&nbsp;#FF8000</font></td></tr>
<tr><td bgcolor="#999999">highlight_default</td><td bgcolor="#DDDDDD"><font color=#0000BB>&nbsp;#0000BB</font></td><td bgcolor="#DDDDDD"><font color=#0000BB>&nbsp;#0000BB</font></td></tr>
<tr><td bgcolor="#999999">highlight_html</td><td bgcolor="#DDDDDD"><font color=#000000>&nbsp;#000000</font></td><td bgcolor="#DDDDDD"><font color=#000000>&nbsp;#000000</font></td></tr>
<tr><td bgcolor="#999999">highlight_string</td><td bgcolor="#DDDDDD"><font color=#DD0000>&nbsp;#DD0000</font></td><td bgcolor="#DDDDDD"><font color=#DD0000>&nbsp;#DD0000</font></td></tr>
<tr><td bgcolor="#999999">highlight_bg</td><td bgcolor="#DDDDDD"><font color=#FFFFFF>&nbsp;#FFFFFF</font></td><td bgcolor="#DDDDDD"><font color=#FFFFFF>&nbsp;#FFFFFF</font></td></tr>
<tr><td bgcolor="#999999">highlight_keyword</td><td bgcolor="#DDDDDD"><font color=#007700>&nbsp;#007700</font></td><td bgcolor="#DDDDDD"><font color=#007700>&nbsp;#007700</font></td></tr>
</table><hr><h2>Environment</h2>
<table border=5 width="600">
<tr><th bgcolor="#00DDDD">Variable</th><th bgcolor="#00DDDD">Value</th></tr>
<tr><td bgcolor="#999999">...</td><td bgcolor="#DDDDDD">...</td></tr>
</table>
<hr><h2>PHP Variables</h2>
<table border=5 width="600">
<tr><th bgcolor="#00DDDD">Variable</th><th bgcolor="#00DDDD">Value</th></tr>
</table>
</center><hr><h2>PHP License</h2>
<PRE>This program is free software; you can redistribute it and/or modify
it under the terms of:

A) the GNU General Public License as published by the Free Software
   Foundation; either version 2 of the License, or (at your option)
   any later version.

B) the PHP License as published by the PHP Development Team and
   included in the distribution in the file: LICENSE

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of both licenses referred to here.
If you did not, or have any questions about PHP licensing, please
contact core@php.net.</PRE>



../build/php funclist.php3
