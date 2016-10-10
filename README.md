<article class="markdown-body entry-content">
<h1>Angular js ng-class with condison</h1>
</article>
<pre><code>ng-class="{'orange': '{{progressvalue+0}}' >= 100}"
</code></pre>

<h2>Angular js limit set in paragraph with Read More &gt;&gt; </h2>
<p></p>
<pre><code>{{ index.description | limitTo : 140 }}{{index.description.length > 140 ? 'Read More' : ''}}</code></pre>

<h2>Angular js Accordian</h2>
<p>Angular js you can simply define the accordian content  using bellow code:- you can set the default value in ng-init directive</p>
<pre lang="no-highlight"><code>
&lt;div ng-init='Accordian=2'&gt;

&lt;h2 ng-click="Accordian=1" ng-class='{active:Accordian==1}'&gt;Heading-1 &lt;/h2&gt;
&lt;div ng-show="Accordian==1" &gt;
&lt;h3&gt;What is Lorem Ipsum? Heading-1 &lt;/h3&gt;
&lt;p&gt;Lorem Ipsum is simply dummy text of the printing and typesetting industry.&lt;/p&gt;&lt;/div&gt;

&lt;h2 ng-click="Accordian=2" ng-class='{active:Accordian==2}'&gt;Heading-2 &lt;/h2&gt;
&lt;div ng-show="Accordian==2"&gt;
&lt;h3&gt;What is Lorem Ipsum? Heading-2 &lt;/h3&gt;
&lt;p&gt;Lorem Ipsum is simply dummy text of the printing and typesetting industry.1500s,&lt;/p&gt;
&lt;/div&gt;
&lt;/div&gt;

&lt;/code></pre>

