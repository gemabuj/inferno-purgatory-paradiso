---
layout: post
title:  "My Lyx Preamble"
date:   2015-09-02 17:28:03
categories: jekyll update
comments: true
---

For those who struggling with Lyx, I want to help you as comrade. Especially you! Yes, you, all my brethren Thesis Warriors. 

Here's the ultimate weapon. Here's the Holy Grail: My Lyx Preamble. Lo and behold! With this gift from the Old Warriors, you'll vanquish you enemies and avenge your brother-in-arms death. To Valhalla!

{% highlight latex %}

\renewcommand{\cfttoctitlefont}{\hfill\normalfont\MakeUppercase}
\renewcommand{\cftaftertoctitle}{\hfill}
\renewcommand{\cftloftitlefont}{\hfill\normalfont\MakeUppercase}
\renewcommand{\cftafterloftitle}{\hfill}
\renewcommand{\cftlottitlefont}{\hfill\normalfont\MakeUppercase}
\renewcommand{\cftafterlottitle}{\hfill}

\renewcommand{\cftfigpresnum}{Gambar\ }
\renewcommand{\cfttabpresnum}{Tabel\ }

\newlength{\mylenf}
\settowidth{\mylenf}{\cftfigpresnum}
\setlength{\cftfignumwidth}{\dimexpr\mylenf+2.6em}
\setlength{\cfttabnumwidth}{\dimexpr\mylenf+2.0em}

{% endhighlight %}

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