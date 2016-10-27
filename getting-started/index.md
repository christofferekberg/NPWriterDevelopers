---
layout: default
title: Getting started 
---

# Getting started

Newspilot Writer consists of two different projects, the NPWriter core 
and the NPWriterPluginBundle. One containing the writer itself and the other
one Infomakers plugins.
 By using this approach we, as core developers gets
the exact same development environment as third party developers. This way we have to
eat our own dog food.

### Clone and start Newspilot Writer

Download and clone from Github

~~~text

git clone git@github.com:Infomaker/NPWriter.git
npm install
npm run dev

~~~

You can now open thw writer with a demo document [localhost:5000/#demo](http://localhost:5000/#demo)


### Clone and start the plugin bundle
~~~ 

git clone git@github.com:Infomaker/NPWriterPluginBundle.git
npm install 
npm run dev

~~~ 
Plugin server started at [localhost:5001](http://localhost:5001)

## Create and add your own plugin

<!--
//~~~ javascript

// Get all nodes in the document
const nodes = api.document.getBlockNodes()
let myvar = "this"
let myvar = "this"
let myvar = "this"

~~~ 
-->



***

###  Discuss this

<div id="disqus_thread"></div>
<script>

var disqus_config = function () {
this.page.url = "{{ site.url }}{{ page.url }}";  
this.page.identifier = "PAGE_{{ page.url }}";
};

(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = '//developer-portal.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
                                