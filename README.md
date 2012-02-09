# Jquery Password Strength
This is a fork of a project that isn't on GitHub, but is released under the MIT license, so nyaa :)
It basically checks your password as you type it in and returns a colored bar that informs users of their password's relative strength.
I make no claims to the original source, or its effectiveness, but I intend to modify the crap out of it, until it suits my purposes.
Having said that, the original author calls himself Digital Spaghetti, and [the code was posted here](http://bit.ly/xR5pIa).
Everything is released under the MIT license, as usual on GitHub.


## Original Instructions (copypasta):
To install the script on your Web page follow these instructions:

1) Download this ZIP file with jQuery 1.2.1 and jquery.pstrength-min.1.2.js. Unpack the files and upload both to your server.

2) Insert this anywhere before the password field on the page:

<script type="text/javascript" src="js/jquery.js"></script>  // adjust the path as is required
<script type="text/javascript" src="js/jquery.pstrength-min.1.2.js">
</script>
<script type="text/javascript">
$(function() {
$('.password').pstrength();
});
</script>

3) Insert class="password" into your input box tag to identify a password box:

<INPUT class="password" type=password name="Password">

4) Insert these tags into your CSS and modify as is needed:

.password {
font-size : 12px;
border : 1px solid #cc9933;
width : 200px;
font-family : arial, sans-serif;
}
.pstrength-minchar {
font-size : 10px;
}

You can adjust a few more settings inside the jquery.pstrength-min.1.2.js script, such as messages, length/height of the bar, and so forth.


Visit the jQuery Web site for more details if needed