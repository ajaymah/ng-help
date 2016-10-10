<article class="markdown-body entry-content">
<h1>Angular js ng-class with condison</h1>
</article>
<pre><code>ng-class="{'orange': '{{progressvalue+0}}' >= 100}"
</code></pre>

<h2>Angular js limit set in paragraph with Read More &gt;&gt; </h2>
<p></p>
<pre><code>{{ index.description | limitTo : 140 }}{{index.description.length > 140 ? 'Read More' : ''}}</code></pre>

