<h2 align=center>/ //　/　/　RainFox doesn't work? Try this:　//　/ /　/</h2>

<ol>
<li> Make sure you <b>restarted Firefox</b> after copying files.

<li>Check if you copied files right!<br>
<i>your <b>root</b> profile folder should look like this:</i><pre>
abcdefgh.profileName
└─── ...some folders and files...
└─── <b>chrome</b>
　　　└─── .icon
　　　└─── .readme-img
　　　└─── userChrome.css
　　　└─── userChromeAnimations.css
　　　└─── (etc.)
└─── ...more folders and files...
</pre><i>and <b>NOT</b> like this:</i><pre>
abcdefgh.profileName
└─── ...some folders and files...
└─── <b>chrome</b>
　　　└─── rainfox-master
　　　　　　└─── .icon
　　　　　　└─── .readme-img
　　　　　　└─── userChrome.css
　　　　　　└─── userChromeAnimations.css
　　　　　　└─── (etc.)
└─── ...more folders and files...
</pre><i>or this:</i><pre>
abcdefgh.profileName
└─── ...some folders and files...
└─── <b>chrome</b>
└─── rainfox-master
　　　└─── .icon
　　　└─── .readme-img
　　　└─── userChrome.css
　　　└─── userChromeAnimations.css
　　　└─── (etc.)
└─── ...more folders and files...
</pre>

<li>Open <code>about:config</code> and check if you enabled all the required variables<br>
listed in the <a href="https://github.com/1280px/rainfox/blob/master/README.md#Installation">installation guide</a>

<li>Make sure you using the last versions of both Firefox and RainFox.<br>
If you're on Firefox Beta/Nightly, try downgrading to stable version

<li>Is your operating system compatible with RainFox?<ul>
	<li>If you're using Windows 7 or higher, everything should be fine
	<li>You may experience some problems on Linux depending on what DE you're using
	<li>macOS and other systems are not supported.</ul>

<li>If everything above didn't work... well... try cleaning or reinstalling your Firefox or ask help at <a href="https://reddit.com/r/firefox/">/r/firefox</a></ol>