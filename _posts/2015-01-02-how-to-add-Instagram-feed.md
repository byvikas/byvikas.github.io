---
layout: post
title:  "Help - How to add Instagram Feed"
date:   2015-01-02 21:19:23
categories: help css
---

<pre> {% assign image = '{{image}}' %}
 {% assign link = '{{link}}' %}
 <script src="/assets/instafeed.js" type="text/javascript"></script>
 
 <script type="text/javascript">
      var feed = new Instafeed({
    	get:'user',
	userId: USER_ID,
	accessToken: 'USER_ID.TOKEN_FROM_INSTAGRAM_MANAGE_CLIENT',
        clientId: '{{site.instafeed.clientId}}',
        resolution: 'standard_resolution',
        limit: 30,
    });
    feed.run();
    </script></pre>
