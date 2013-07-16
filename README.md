smallpump
=========

A bit of JavaScript to show a user's pump.io recent activity.

The JavaScript should be adapted to your own use.  Certainly you will want to change what pump.io feed you're pulling from.  Activity feeds are found at: <code>/api/user/&lt;nickname&gt;/feed/major</code>.  Some OAuth is required to get access to them, so for now we'll work with a static file.

The JSON is parsed using jQuery, which is available under the MIT License.  See the jQuery website.

http://jquery.org/license
