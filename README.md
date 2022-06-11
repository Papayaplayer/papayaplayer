<h1>General</h1>
Make your own internet-cinema with papayaplayer.com

Add a few lines of code to your website and get:
<ul>
	<li><a>A player that plays torrent-videos like a regular video, without downloading to the device;</a></li>
	<li><a>Search for the right videos on hundreds of integrated torrent-aggregators;</a></li>
	<li><a>Add videos to favorites;</a></li>
	<li><a>Browsing history.</a></li>
![For instruction](https://user-images.githubusercontent.com/97943999/173193949-de83753b-8d50-4fe3-8f49-eb5e14a78d03.png)
</ul>

In addition, you can add a video launch function next to the torrent download function:
![First variants2 eng](https://user-images.githubusercontent.com/97943999/161525432-c344662d-79de-448e-aeae-e5bf2ba05f92.png)

<h1>Anti-ban system</h1>
Don't worry, the player is designed so that if a separate server is blocked, the new ones will “catch up” automatically, you won't have to do anything on the site for this. We have made the operation of the service uninterrupted and resistant to the banhammer.

<h1>Features</h1>
<ul>
	<li><a>Supports magnet-url and external torrent-files</a></li>
	<li><a>Supports video (avi, mkv, mp4, m4v)</a></li>
	<li><a>No additional plugins/extensions required</a></li>
</ul>

<h1>How to use</h1>
The code that allows you to run torrent files in the player through our service:

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240); color: rgb(68, 68, 68);"><span class="xml"><span class="hljs-tag">&lt;<span class="hljs-name" style="font-weight: 700;">head</span>&gt;</span>
<span class="hljs-tag">&lt;<span class="hljs-name" style="font-weight: 700;">link</span> <span class="hljs-attr">href</span>=<span class="hljs-string" style="color: rgb(136, 0, 0);">"https://github.com/Papayaplayer/papayaplayer/releases/download/v0.0.1/papaya.js"</span> <span class="hljs-attr">rel</span>=<span class="hljs-string" style="color: rgb(136, 0, 0);">"preload"</span> <span class="hljs-attr">as</span>=<span class="hljs-string" style="color: rgb(136, 0, 0);">"script"</span>&gt;</span>
<span class="hljs-tag">&lt;/<span class="hljs-name" style="font-weight: 700;">head</span>&gt;</span>
<span class="hljs-tag">&lt;<span class="hljs-name" style="font-weight: 700;">body</span>&gt;</span>
<span class="hljs-tag">&lt;<span class="hljs-name" style="font-weight: 700;">div</span> <span class="hljs-attr">id</span>=<span class="hljs-string" style="color: rgb(136, 0, 0);">"papaya"</span> <span class="hljs-attr">data-status</span>=<span class="hljs-string" style="color: rgb(136, 0, 0);">"true"</span> <span class="hljs-attr">data-locale</span>=<span class="hljs-string" style="color: rgb(136, 0, 0);">"ru|en"</span>  <span class="hljs-attr">data-search</span>=<span class="hljs-string" style="color: rgb(136, 0, 0);">"true|false"</span> <span class="hljs-attr">data-height</span>=<span class="hljs-string" style="color: rgb(136, 0, 0);">"height"</span> <span class="hljs-attr">data-width</span>=<span class="hljs-string" style="color: rgb(136, 0, 0);">"width"</span> <span class="hljs-attr">data-link</span>=<span class="hljs-string" style="color: rgb(136, 0, 0);">"link"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name" style="font-weight: 700;">div</span>&gt;</span>
<span class="hljs-tag">&lt;<span class="hljs-name" style="font-weight: 700;">script</span> <span class="hljs-attr">src</span>=<span class="hljs-string" style="color: rgb(136, 0, 0);">"https://github.com/Papayaplayer/papayaplayer/releases/download/v0.0.1/papaya.js"</span>&gt;</span><span class="undefined"></span><span class="hljs-tag">&lt;/<span class="hljs-name" style="font-weight: 700;">script</span>&gt;</span>
<span class="hljs-tag">&lt;/<span class="hljs-name" style="font-weight: 700;">body</span>&gt;</span></span></pre>

<h1>Important</h1>
<ul>
	<li>All parameters (height, width, link) are required!</li>
	<li>Please, use all files from release catalog. Then, when you change the server, the service will continue to work.</li>
</ul>

<h1>How it works</h1>
	<li>the code in the <b>header</b> block - refers to github for a file that gives the current non-banned server addresses.</li>
	<li><b>data-locate</b> - allows you to configure the language. Now there are 2 of them, but there will be more in the future.</li>
	<li><b>data-search</b> - allows you to turn on and off the torrent aggregator search service.</li>
	<li><b>data-height</b> and <b>data-width</b> - allow you to set the height and width of the player window.</li>
	<li><b>data-link</b> - allows you to set the torrent “by default".</li>
