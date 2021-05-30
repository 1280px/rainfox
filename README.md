<!-- <p align=center><img src="https://github.com/1280px/rainfox/blob/master/.readme-img/logo.png"></img> -->
<h1 align=center>/　 // /　/　RainFox 0.5<sup><b>β</b></sup>　//　/ /　/</h1>
<p align=center><img src="https://github.com/1280px/rainfox/blob/master/.readme-img/header.png"></img>
<br><i>it's like Photon, but better</i></p>


Started as a remix of MaterialFox and QuietFox, the main task of this userChrome style is to make Firefox more theme-adaptive, smooth and homogeneous. After Proton UI redesign came in, this style also tends to be some kind of "Photon-theme-Restorer" but with improvements on the previous design. <br>
The current philosophy of this uC is to save Proton's clarity and simplicity while re-implementing nice Photon's icons, elements and general look & feel


<h1 align=center>/ //　/   /　/　Features　/　//　/ / //</h1>
<h3>Any of the features can be easily enabled/disabled in <code>userChrome.css</code> if you want to. <br> <b>[X]</b> means "disabled by default"</h3>

<pre><p align=center>Pre-Proton rounded tabs without lines<br>
<img src="https://github.com/1280px/rainfox/blob/master/.readme-img/feat1.webp" align=center></img></p></pre>
<pre><p align=center>Photon-ish context menus and panels!<br>
<img src="https://github.com/1280px/rainfox/blob/master/.readme-img/feat2.webp" align=center></img></p></pre>
<pre><p align=center>Animated auto-hide bookmarks panel<br>
<img src="https://github.com/1280px/rainfox/blob/master/.readme-img/feat3.webp" align=center></img></p></pre>
<pre><p align=center>Animated auto-hide "Forward" button<br>
<img src="https://github.com/1280px/rainfox/blob/master/.readme-img/feat4.webp" align=center></img></p></pre>
<pre><p align=center>Hourglass tab loading animation<br>
<img src="https://github.com/1280px/rainfox/blob/master/.readme-img/feat5.webp" align=center></img></p></pre>
<pre><p align=center><b>[X]</b> Paranoia mode (unselected tabs are hidden until you hover it)<br>
<img src="https://github.com/1280px/rainfox/blob/master/.readme-img/feat6.webp" align=center></img></p></pre>
<p align=right><i>..and more!　　　　</i></p>


<h1 align=center>/ / /　// /　Requirements　//　 / // /</h1><ul>
<li>Mozilla Firefox 90.0 or newer <i>(looking for pre-Proton version? Check <a href="https://github.com/1280px/rainfox/releases/tag/v0.3">release v3.0!</a>)</i>
<li><code>toolkit.legacyUserProfileCustomizations.stylesheets == TRUE</code> <i>(enables custom CSS)</i>
<li><code>svg.context-properties.content.enabled == TRUE</code> <i>(allows custom SVGs use context colors)</i>
<li><code>security.secure_connection_icon_color_gray == FALSE</code> <i>(recommended; uses green color for secure connection icons)</i>
</ul>
<b>Style was tested on Firefox 90 @ Windows 10 (100% and 125% scaling).<br>I'll appreciate your feedback from other systems! (especially from macOS and Linux)</b>
<br><br>
<small><i>Style doesn't work? Check <a href="https://github.com/1280px/rainfox/blob/master/!help%20help%20style%20doesnt%20work.txt">this step-by-step guide</a> to find a solution!</i></smakk>


<h1 align=center>/ //　/　//　Known Issues　// / /　 / /</h1><ol>
<li><b>[!]</b> System shadows still appear on some of the context menus (currently seems to be impossible to fix) 
<li>Icon scaling issues with any system scaling except 100%
<li>Refresh icon animation is broken (and I don't know how to fix it)
<li>Bookmarks bar may go trippy sometimes when working with folders
