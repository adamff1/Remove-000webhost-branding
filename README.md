# Remove 000webhost branding
A little trick for removing <a href="https://www.000webhost.com/">000webhost</a> branding without being a premium user.

000webhost branding:

<img src="https://raw.githubusercontent.com/BlueArduino20/Remove-000webhost-branding/master/img/1.PNG">

As you can see, you need to be a premium user in order to disable the branding, but with this little trick you can do it being a free user.

<img src="https://raw.githubusercontent.com/BlueArduino20/Remove-000webhost-branding/master/img/2.PNG">

## Instructions

In your HTML file:

Replace this:
<pre><code>&lt;/body&gt;
&lt;/html&gt;
</pre></code>
For this:
<pre><code>&lt;!--
&lt;/body&gt;
&lt;/html&gt;
--&gt;
</pre></code>

And that's all!
