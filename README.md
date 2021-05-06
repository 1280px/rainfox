<h1 align=center>/ 　/ //　/　/　　RainFox v0.4　 //　/ /　　//</h1>
<p align=center><img src="https://github.com/1280px/rainfox/blob/master/readme-img0.png"></img>
<br><i>It's like Photon and Proton combined together</i></p>


Started as a remix of MaterialFox and QuietFox, the main task of this userChrome style is to make Firefox more theme-adaptive, smooth and homogeneous.
After Proton UI redesign came in, this style also tends to be some kind of "Photon-theme-Restorer" but with improvements on the previous design. <br>
The current philosophy of this uC is to save Proton's clarity and simplicity while re-implementing nice Photon's icons, elements and general look & feel

<h1 align=center>/ //　/ / 　/　/　　Features　　/　//　/ / /　/</h1>
<h3>Any of the features can be easily enabled/disabled in <code>userChrome.css</code> if you want to. <br> <b>[X]<b> means "disabled by default"</h3>
  
<pre>Pre-proton rounded tabs without lines</b>
<img src="https://github.com/1280px/rainfox/blob/master/readme-img4.png" align=center></img></pre>
<pre>Photon-ish context menus and panels!</b>
<img src="https://github.com/1280px/rainfox/blob/master/readme-img2.png" align=center></img></pre>
<pre><b>Animated auto-hide bookmarks panel</b>
<img src="https://github.com/1280px/rainfox/blob/master/readme-img1.png" align=center></img></pre>
<pre>Animated auto-hide "Forward" button</b>
<img src="https://github.com/1280px/rainfox/blob/master/readme-img5.png" align=center></img></pre>
<pre>[X] Hourglass tab loading animation</b>
<img src="https://github.com/1280px/rainfox/blob/master/readme-img3.png" align=center></img></pre>
<pre>[X] Paranoia mode (unselected tabs are hidden until you hover it)</b>
<img src="https://github.com/1280px/rainfox/blob/master/readme-img6.png" align=center></img></pre>
<p align=right><i>..and more!　　　　</i></p>



<h1 align=center>/　/　 / / // /　　Requirements　　//　 / //　　/　/</h1><ul>
<li>Mozilla Firefox 90.0 or newer <i>(looking for pre-Proton version? Check the first release, v3.0!)</i>
<li><code>toolkit.legacyUserProfileCustomizations.stylesheets == TRUE</code> <i>(enables custom CSS)</i>
<li><code>svg.context-properties.content.enabled == TRUE</code> <i>(allows custom SVGs use context colors)</i>
<li><code>security.secure_connection_icon_color_gray == FALSE</code> <i>(recommended; uses green color for secure connection icons)</i>
</ul>
<b>Style was tested on Firefox 90.0a1 @ Windows 10 (100% scaling).<br>I'll appreciate your feedback from other configs (especially from MacOS and Linux!)</b>


<h1 align=center>/ 　// /　/　/ /　　Known Issues　　/　 / /　 / ///</h1><ol>
<li>! Some of the featues are currently incompatible with compact mode (working on it...)
<li>Tabbar will break if you have overflow and pinned tabs at the same time
<li>Refresh icon animation is broken (IDK how to fix it)
<li>Bookmarks bar may go trippy sometimes when working with folders
<li>System shadows still appers on some of the context menus (currently seems to be impossible to fix)

</ol>
