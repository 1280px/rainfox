<h1 align=center>/ //　/　/　☔ RainFox 5.3<!--<sup>β</sup>-->　//　/ /　/</h1>
<p align=center><img src="https://github.com/1280px/rainfox/blob/master/.readme-img/header.png"></img>
<br><i>Photon UI, reimagined</i></p>

Started as a remix of <a href="https://github.com/muckSponge/MaterialFox">MaterialFox</a> and <a href="https://github.com/coekuss/quietfox">QuietFox</a>, the main task of this userChrome style is to make Firefox interface more consistant, smooth and theme-adaptive. After Proton redesign came in, this style also tends to be a mix of old and new UIs with additional features and tweaks<br>
The idea behind this style is to keep Proton interface clarity and simplicity while re-implementing nice and unique Photon's icons and general look & feel.

<br><br>

<h1 align=center>/ //　/   /　/　Features　/　//　/ / //</h1>
<i>keep in mind that this style is modular, you can easily enable/disable almost everything you want!</i>
<pre><p align=center>Good ol' Photon UI icons<br>
<img src="https://github.com/1280px/rainfox/blob/master/.readme-img/sample.png" align=center></img></p></pre>
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
<pre><p align=center><b>[ disabled by default ]</b><br>Paranoia mode (unselected tabs are hidden until you hover it)<br>
<img src="https://github.com/1280px/rainfox/blob/master/.readme-img/feat6.webp" align=center></img></p></pre>
<p align=right><i>..and more!　　　　</i></p>

<br><br>

<h1 align=center>/ / /　// /　Installation　//　 / // /</h1><ol>
  <li>Make sure you're using <b>Mozilla Firefox 96</b> or newer <i>(looking for pre-Proton version? Check <a href="https://github.com/1280px/rainfox/releases/tag/v0.3">release v0.3!</a>)</i>
  <li>Download the latest build from <b>Code > Download ZIP</b> and extract folder <code>rainfox-master</code>
  <li>Go to <code>about:profiles</code>, find your profile, open <b>root</b> folder and create a folder <code>chrome</code> inside of it. If the folder already exists, wipe all its content
  <li>Move everything from <code>rainfox-master</code> to <code>chrome</code>
  <li>Now open <code>about:config</code> and change these values to <code><b>true</b></code>:<ul>
    <li><code>toolkit.legacyUserProfileCustomizations.stylesheets</code> <i>(<b>necessary</b>; enables custom CSS)</i>
    <li><code>layout.css.color-mix.enabled</code> <i>(<b>necessary</b>; allows context menus use hover and active color states)</i>
    <li><code>svg.context-properties.content.enabled</code> <i>(<b>necessary</b>; allows Photon icons use theme colors)</i>
    <li><code>security.secure_connection_icon_color_gray</code> <i>(<b>recommended</b>; uses green color for secure connection icons)</i></ul>
  <li>Restart Firefox. PROFIT!</ol>

<table >
	<tbody>
		<tr>
      <td colspan=3 align=center><b>style compatibility sheet</b></td>
		</tr><tr>
			<td>Windows 11</td><td align=center>✔️</td>
			<td><i>no issues found.</i></td>
		</tr><tr>
			<td>Windows 10</td><td align=center>✔️</td>
			<td><i>no issues found.</i></td>
		</tr><tr>
			<td>Windows 8.1</td><td align=center>🔘</td>
			<td>rare transparency glitches if you're using <a href="https://www.glass8.eu/">Aero Glass</a> and system theme</td>
		</tr><tr>
			<td>Windows 7</td><td align=center>🔘</td>
			<td>rare transparency glitches if you're using system theme</td>
		</tr><tr>
			<td>GNOME 4X</td><td align=center>⚠️</td>
			<td>context menu margins and icons aren't shown properly</td>
		</tr><tr>
			<td>Pantheon</td><td align=center>⚠️</td>
			<td>context menu margins and icons aren't shown properly</td>
		</tr><tr>
			<td>KDE</td><td align=center>❔</td>
			<td><i>NEEDS TESTING</i></td>
		</tr><tr>
	</tbody>
</table>

<br><br>

<h1 align=center>/ //　/　//　Known Issues　// / /　 / /</h1><ol>
<h3 align=center>Please check if you're using the last build of RainFox before reporting as issue!</h3>
<li>Icons may not scale properly if you're using non-100% scaling
<li>Some icon animations are partially broken (workin' on it)
<li>Bookmarks bar may work incorrectly sometimes when drag'n'dropping stuff</ol>

<br><br>

<h2 align=center>Custom themes used for screenshots:</h3><p align=center>
<a href="https://addons.mozilla.org/ru/firefox/addon/blues-yellows/" target=_blank>—　blues&yellows (by kaylakh10)　—</a><br>
<a href="https://addons.mozilla.org/ru/firefox/addon/rain-storm/" target=_blank>—　Rain Storm (by dietotaku)　—</a><br>
<a href="https://addons.mozilla.org/ru/firefox/addon/rainbow-blur-1/" target=_blank>—　Rainbow Blur (by Alix P)　—</a><br>
<a href="https://addons.mozilla.org/ru/firefox/addon/modern-purple-polygon/" target=_blank>—　Modern Purple Polygon (by Kujou)　—</a><br>
<a href="https://addons.mozilla.org/ru/firefox/addon/windows95aesthetic/" target=_blank>—　Ｗｉｎｄｏｗｓ　９５ (by Vovan29)　—</a><br>
<a href="https://addons.mozilla.org/ru/firefox/addon/purp-grid/" target=_blank>—　Purp Grid (by Benedict)　—</a></p>
