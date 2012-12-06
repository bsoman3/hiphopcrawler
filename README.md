<h1>Hiphop Crawler</h1>
This is a plug-in for Burp Proxy.
It reads the output from a static analyser built using Hiphop PHP.
The output of the analyser should be placed inside the "input" folder here.
<h2>Usage</h2>
Run the .jar file using the following command:
	<pre><code>java -jar hiphopcrawler.jar burp.startBurp</code></pre>
<p>This shoudl fire-up an instance of Burp with the Hiphop Crawler Plug-in. Configure your browser to route requests through the Burp Proxy.</p>
<p>Navigate to the site to be crawled. In the "site map" tab under the "target" tab in Burp, right click on your website and select "HiphopCrawler"</p>
<p>The plugin will now read data from the "input" folder to send additional requests, resulting in a more comprehensive crawl of the website.</p>

