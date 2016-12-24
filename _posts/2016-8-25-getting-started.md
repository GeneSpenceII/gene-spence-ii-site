---
layout: post
title: Getting Started
description: Ipsum dolor sit amet
image: assets/images/pic01.jpg
published: true
---
<div id="placeholder-div"></div>
<script>
    window.___gcfg = {
      lang: 'zh-CN',
      parsetags: 'onload'
    };

    function renderButton(){
      gapi.hangout.render('placeholder-div', {
          'render': 'createhangout',
          'initial_apps': [
            { app_id : '184219133185', start_data : 'dQw4w9WgXcQ', 'app_type' : 'ROOM_APP' }
          ]
        });
    }
</script>
<script src="https://apis.google.com/js/platform.js" async defer></script>
Send me a hangout request and we can get your site set up!
