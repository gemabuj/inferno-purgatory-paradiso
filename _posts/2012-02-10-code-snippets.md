---
layout: post
title: Code Snippets
category: Design

excerpt: Quick overview on how to post code snippets using Liquid tags and how to escape or not escape markdown and HTML in your blog entries. 
comments: true
---

Whenever you need to post a code snippet, use the liquid tags `hilight` and `endhilight` like this:

{% highlight ruby %}
# some code goes here
puts "Hello World!"
{% endhighlight %}

Note that this only provides color-coding. For that you might need to use a front end colorization engine like Highlight.JS or something similar.

{% if page.comments %}

<div id="disqus_thread"></div>
<script type="text/javascript">
    /* * * CONFIGURATION VARIABLES * * */
    var disqus_shortname = 'myinfernopurgatoryparadiso';
    
    /* * * DON'T EDIT BELOW THIS LINE * * */
    (function() {
        var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
        dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
        (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>


<script type="text/javascript">
    /* * * CONFIGURATION VARIABLES * * */
    var disqus_shortname = 'myinfernopurgatoryparadiso';
    
    /* * * DON'T EDIT BELOW THIS LINE * * */
    (function () {
        var s = document.createElement('script'); s.async = true;
        s.type = 'text/javascript';
        s.src = '//' + disqus_shortname + '.disqus.com/count.js';
        (document.getElementsByTagName('HEAD')[0] || document.getElementsByTagName('BODY')[0]).appendChild(s);
    }());
</script>
    
{% endif %}
