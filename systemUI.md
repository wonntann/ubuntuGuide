Table of contents
=================

<!--ts-->
  * [Desktop](#desktop)
    * [Adding to Webpage to Launcher](#desktopLauncher)
  
<!--ts-->
 
 
 
 
 Desktop
============
Adding to Webpage to Launcher
-----
<p>Try the following to create a launcher to open a website with Firefox and add it to Ubuntu dock.</p>

<ol>
<li><p>Create a new file, say <code>MyWebsite.desktop</code> in your <code>~/.local/share/applications/</code> directory. You can do that by running the following in Terminal </p>

<pre><code>touch ~/.local/share/applications/MyWebsite.desktop
</code></pre></li>
<li><p>Open this file with a text-editor, for example by running </p>

<pre><code>gedit ~/.local/share/applications/MyWebsite.desktop
</code></pre></li>
<li><p>Add the following lines to this file and save the file </p>

<pre><code>[Desktop Entry]
Comment=Open XYZ website
Terminal=false
Name=XYZ website
Exec=firefox website-URL
Type=Application
Icon=applications-internet
NoDisplay=false
</code></pre>

<p>In place of <code>website-URL</code> put the address you want to visit, for example <code>https://askubuntu.com</code> for Ask Ubuntu. Also edit the the <code>Comment=</code> and <code>Name=</code> fields accordingly.</p></li>
<li><p>Click on "<em>Activities</em>" at the top bar or "<em>Show Applications</em>" in the dock and search for "XYZ website". It should appear.</p></li>
<li><p>Right click on it and select "Add to favourites". </p></li>
</ol>
    </div>
