# FHEM WebIF Blue Dark Themes
 For <strong>FHEM</strong> Smarthome software a custom Theme Dark Blue for Webinterface ;-)
 <br>

<h2>Usage / Installation</h2>
Copy all 3 CSS files to:
<br><br>
<pre>
<code>/opt/fhem/www/pgm2</code>
</pre>

FHEM logo and all other icons from /images to:
<br><br>
<pre>
<code>/opt/fhem/www/images/default</code>
</pre>


<h2>Owner must user: fhem and Group dialout</h2>
For the newly copied files the rights and the owner must be adjusted on <code>fhem</code> and group <code>dialout</code>.
<br><br>
<pre>
<code>chown -R fhem:dialout /opt/fhem/www/images/default</code>
<code>chown -R fhem:dialout /opt/fhem/www/pgm2</code>
</pre>


<h2>Webinterface FHEM ip-adresse:8083</h2>
Set editor attribute for JavaEditor to:
<pre>
<code>attr WEB JavaScripts codemirror/fhem_codemirror.js</code>
</pre>

<strong>Saving for FHEM-Updates</strong>
<pre>
<code>attr global exclude_from_update fhemicon_dark_topaLE.png fhemicon_darksmall.png icoEverything.png 10px-kreis-gelb.png 10px-kreis-rot.png 10px-kreis-gruen.png Zoom-in.png Zoom-out.png topa_LECommon.css topa_LEstyle.css dashboard_topa_LEstyle.css</code>
</pre>

FHEM Reboot per Konsole with:

<code>shutdown restart</code>
<br><br>
Have Fun ;-)
<br>
<h2>Screenshots</h2>
<img src="https://github.com/topa-LE/fhem_blue_dark_themes/blob/master/screenshots/screen-0.png?raw=true" alt="Folder" style="max-width:100%;" width="500">
