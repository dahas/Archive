
# Cookie Management

## Requirements

- jQuery

## Usage

- Include the file after the jQuery library:
<pre>&lt;script src="[your_path]/cookie_mgmt.js" type="text/javascript">&lt;/script></pre>
- Make an instance:
<pre>var Cookie = new Cookie("the_cookie_name");</pre>
- Adding a value to the cookie (creates cookie, if it doesn´t exist.):
<pre>Cookie.set(parameter, value [, expires, path]);</pre>
- Reading a paramter from the cookie:
<pre>Cookie.get(parameter);</pre>
- Deleting a parameter and its value (removes the cookie, if no other parameter exists.):
<pre>Cookie.clear(parameter);</pre>
- Remove the cookie:
<pre>Cookie.delete();</pre>