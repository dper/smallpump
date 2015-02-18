smallpump
=========

A bit of JavaScript to show a user's pump.io recent activity.

The JavaScript should be adapted to your own use.  There is some documentation within the files themselves.

There are several files of interest here.
* <code>smallpump.user.html</code>.  A script that shows a user's most recent activity.
* <code>smallpump.firehose.html</code>.  A script that shows the most recent activity from a pump.io Firehose.

These files depend on JSON feed files.  To make these files at all useful, the JSON feeds need to be generated on the fly.  There are several ways to do this.
* Use a CGI script to access a remote feed.  This avoids cross site scripting problems.
* Use a server side cron job to periodically update the local feed file.  This introduces a time delay.
* Install pump.io run a Firehose locally and read it from within JavaScript.  This is probably the most elegant solution.

Accessing a user's feed requires OAuth, it seems, so whatever solution is chosen will need to take that into account.  The main OFirehose server does not require OAuth.

The JSON is parsed using jQuery, which is available under the MIT License.  See the [jQuery](http://jquery.org/license) website.  


Source
======

* Browse: <https://dperkins.org/git/gitlist/smallpump.git/>.
* Clone: <https://dperkins.org/git/public/smallpump.git/>.
* GitHub: <https://github.com/dper/smallpump/>.


Contact
=======

If you want to contact the author, here are some ways.  Bug reports and improvements are always welcome.

* <https://microca.st/dper>
* <https://twitter.com/dpp0>
* <https://dperkins.org/tag/contact.html>