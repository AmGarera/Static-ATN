<template>
  <div>
  <!--<div class="mdl-card mdl-shadow--0dp demo-card-wide">
    <div class="mdl-card__supporting-text">-->
  <h3>Social Media</h3>
  <a class='social fa fa-google-plus' href='http://plus.google.com/106282679051641143141' target='_blank'></a>
  <a class='social fa fa-facebook' href='http://facebook.com/Android-TV-News-1648983095385498' target='_blank'></a>
  <a class='social fa fa-twitter' href='http://twitter.com/AndroidTV_News' target='_blank'></a>
  <a class='social fa fa-youtube' href='https://www.youtube.com/channel/UC1R_fgIcP7DJoPgR0nAUQ1w' target='_blank'></a>
  <a class='social fa fa-twitch' href='https://www.twitch.tv/androidtvnews' target='_blank'></a>
  <a class='social fa fa-rss' href='//androidtv.news/feed/' target='_blank'></a>

  <br><br>

  <style>
    .pushbullet-subscribe-widget {
      padding-left: 0px;
      position: relative;
    }
  </style>
  <!-- <span class="fa-stack fa-lg">
    <i class="fa fa-circle fa-stack-2x"></i>
    <i class="fa fa-arrow-right fa-stack-1x fa-inverse fa-rotate-90"></i>
    </span> -->
  <div>

    <a class="pushbullet-subscribe-widget" data-channel="Androidtvnews" data-widget="button" data-size="large"></a>
    <script type="text/javascript">
      /* eslint-disable indent */
      (function () {
      var a = document.createElement('script')
  a.type = 'text/javascript'
  a.async = true
  a.src = 'https://widget.pushbullet.com/embed.js'
  var b = document.getElementsByTagName('script')[0]
  b.parentNode.insertBefore(a, b)
})()
</script>
  </div>
  <!--</div>
  </div>-->

  <a href='https://www.patreon.com/androidtvnews' target='_blank'><img
    src='https://c4.patreon.com/toolbox/patreon_logo.png' width='24px'>&emsp;Support us on Patreon</a>
  </div>
</template>
<script>export default {
  name: 'social'
} </script>
<style>
  .social {
    font-size: 20pt;
    display: inline-block;
    margin-right: 8px;
    text-decoration: none;
  }

  .social.fa-google-plus {
    color: #F44336;
  }

  .social.fa-facebook {
    color: #3F51B5;
  }

  .social.fa-twitter {
    color: #03A9F4;
  }

  .social.fa-youtube {
    color: #F44336;
  }

  .social.fa-rss {
    color: #FF9800;
  }

  .social.fa-twitch {
    color: purple;
  }
</style>
