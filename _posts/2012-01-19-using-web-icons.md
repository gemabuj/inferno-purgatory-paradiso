---
layout: post
title: Using the Web Icons
category: Design

excerpt: Quick overview on how to use the Typicon web font icons included with this template. 

---

This template uses [Typicons][ty] web font, provided by [Fontello][fo] font bundling service. It allows you to quickly
add nice icons into your pages by using css tags. 

To add an icon somewhere in the template simply do:

{% highlight html %}
<i class="icon-home"></i>
{% endhighlight %}

This will insert a home icon, just as the one seen in the sidebar. The available class names you can use are as follows:

![Available Icons][icons]

These should work in all the browsers, all the way down to and including IE7, but not IE6.

[ty]: http://typicons.com/
[fo]: http://fontello.com/

[icons]: /resources/img/icons.png "Available Icons"

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


