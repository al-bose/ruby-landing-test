<template>
  <div id="app">
    <title>Rubyfornia</title>

    <meta name="description" content="Super cute emoji for YOUR dog">

    <link rel="canonical" href="https://slack.com/features">
    <meta charset="utf-8">
    <meta name="superfish" content="nofish">
    <meta name="author" content="Slack">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">


    <!-- output_css "marketing_css_core" -->
    <link href="https://a.slack-edge.com/68582/style/rollup-marketing.css" rel="stylesheet" type="text/css" crossorigin="anonymous"
          onload="window._cdn &amp;&amp; _cdn.ok(this, arguments)" onerror="window._cdn &amp;&amp; _cdn.failed(this, arguments)">


    <!-- output_css "regular" -->
    <link href="https://a.slack-edge.com/cbc02/style/libs/lato-2-compressed.css" rel="stylesheet" type="text/css" crossorigin="anonymous"
          onload="window._cdn &amp;&amp; _cdn.ok(this, arguments)" onerror="window._cdn &amp;&amp; _cdn.failed(this, arguments)">
    <link href="https://a.slack-edge.com/ce9b3e/marketing/style/page_why_slack.css" rel="stylesheet" type="text/css" crossorigin="anonymous"
          onload="window._cdn &amp;&amp; _cdn.ok(this, arguments)" onerror="window._cdn &amp;&amp; _cdn.failed(this, arguments)">



    <body class="" data-gr-c-s-loaded="true">
    <iframe src='javascript:""' id="__cvo_iframe" style="width: 0px; height: 0px; border: 0px; position: absolute; left: -2000px;"></iframe>


    <header role="banner">
      <nav class="c-nav c-nav--primary" role="navigation" aria-label="Primary Navigation">
        <div class="c-nav__row o-content-container">
          <div class="c-slacklogo">
            <img src="./dogs/Rubyfornia-logo-BW.png" class="rf-nav-logo"/>Rubyfornia
          </div>
        </div>
      </nav>

    </header>
    <main id="main" role="main">
      <section class="o-section--feature v--borderless">
        <div class="o-content-container u-padding--flush">
          <div class="c-marquee is-animated">
            <div class="c-marquee__container grid" v-html="theHtml">
            </div>
          </div>
        </div>
      </section>

      <section class="o-section-- v--borderless">
        <div class="o-wrap-medium u-text--center-on-desktop">
          <h2>Welcome to Rubyfornia!</h2>
          <p class="display-as-hero u-margin-bottom--large">
            Follow us on Instagram!
          </p>
            <button v-on:click="composer_method">Test</button>
            <a href="https://slack.com/customer-stories/lever" class="c-marquee__item" data-clog-click="" data-clog-ui-step="page_features"
               data-clog-ui-element="link_customer_story" data-clog-params="trigger=lever">
                <img src="./dogs/Rubyfornia-dog-1.png"	class="c-marquee__attribution c-marquee__dog"/>
                <span class="c-marquee__text">Blu 1</span>
            </a>
            <a href="https://slack.com/customer-stories/lever" class="c-marquee__item" data-clog-click="" data-clog-ui-step="page_features"
               data-clog-ui-element="link_customer_story" data-clog-params="trigger=lever">
                <img src="./dogs/Rubyfornia-dog-2.png"	class="c-marquee__attribution c-marquee__dog"/>
                <span class="c-marquee__text">Blu 2</span>
            </a>
            <p>{{theHtml}}</p>
        </div>
      </section>
    </main>

    <footer class="c-nav c-nav--footer ">
      <div class="c-nav--footer__menu">
        <div class="o-content-container c-nav--footer__row">
          <nav class="c-footer--wrap t-contains-subtle-links" role="navigation" aria-label="Footer Navigation">
            <div class="c-nav--footer__block">
              <p class="c-nav--footer__listheader">Rubyfornia</p>
              <ul class="c-nav--footer__list">
                <li class="c-nav--footer__listitem">
                  <a data-clog-click="" data-clog-ui-step="page_features" data-clog-ui-component="inc_footer_nav" data-clog-ui-element="link_about_us"
                     href="https://slack.com/about" data-qa="about_us_footer">About Us</a>
                </li>
              </ul>
            </div>

            <div class="c-nav--footer__block">
              <p class="c-nav--footer__listheader">&nbsp;</p>
              <ul class="c-nav--footer__list">
                <li class="c-nav--footer__listitem">
                  <a data-clog-click="" data-clog-ui-step="page_features" data-clog-ui-component="inc_footer_nav" data-clog-ui-element="link_careers"
                     href="https://slack.com/careers" data-qa="careers">Careers</a>
                </li>
              </ul>
            </div>
            <div class="c-nav--footer__block">
              <p class="c-nav--footer__listheader">&nbsp;</p>
              <ul class="c-nav--footer__list">
                <li class="c-nav--footer__listitem">
                  <a data-clog-click="" data-clog-ui-step="page_features" data-clog-ui-component="inc_footer_nav" data-clog-ui-element="link_careers"
                     href="https://slack.com/careers" data-qa="careers">Privacy Policy</a>
                </li>
              </ul>
            </div>
            <div class="c-nav--footer__block">
              <p class="c-nav--footer__listheader">&nbsp;</p>
              <ul class="c-nav--footer__list">
                <li class="c-nav--footer__listitem">
                  <a data-clog-click="" data-clog-ui-step="page_features" data-clog-ui-component="inc_footer_nav" data-clog-ui-element="link_careers"
                     href="https://slack.com/careers" data-qa="careers">Terms of Use</a>
                </li>
              </ul>
            </div>

          </nav>
        </div>
      </div>
      <div style="height:40px;"></div>

    </footer>


    </body>

  </div>
</template>

<script>


export default {
  name: 'app',

    data() {
        return {
            dnum : 1,
            theHtml : '',
            composers : [
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-1.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-2.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-3.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-4.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-5.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-6.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-7.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-8.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-9.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-10.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-11.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-12.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-13.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-14.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-15.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-16.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-17.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-18.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-19.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-20.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-21.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-22.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-23.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-24.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-25.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-26.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-27.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-28.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-29.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-30.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-31.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-32.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-33.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-34.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-35.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-36.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-37.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-38.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-39.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-40.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-41.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-42.png',
                    description: '',
                    name: 'Blu'
                },
                {
                    title: 'Great Dane',
                    photo: 'Rubyfornia-dog-43.png',
                    description: '',
                    name: 'Blu'
                },
            ],

        }
    },


    methods: {
      composer_method() {
          var index;
          for(index = 0; index <  this.composers.length; index ++) {
              this.theHtml += '\t<a href="https://slack.com/customer-stories/lever" class="c-marquee__item" data-clog-click="" data-clog-ui-step="page_features"\r';
              this.theHtml += '\tdata-clog-ui-element="link_customer_story" data-clog-params="trigger=lever">\r';
              this.theHtml += '\t<img src="./dogs/' + this.composers[index].photo + '"';
              this.theHtml += '\t class="c-marquee__attribution c-marquee__dog"/> \r';
              this.theHtml += '\t\t<span class="c-marquee__text">' + this.composers[index].name + ' ' + this.dnum + '</span>\r';
              this.theHtml += '\t </a> \r';
              this.dnum++;
          }
      }


    }
}






</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.rf-nav-logo {
  width:24px;
  height: auto;
  margin-right: 16px;
}
.c-marquee__item {
  background-image: none;
  box-shadow:none;
  padding:0;
  margin-left:2px;
  margin-right:16px;
  width:auto;
  bottom: 0px;
  position: relative;
}
.c-marquee.is-hover .c-marquee__item, .c-marquee:hover .c-marquee__item {
  box-shadow: none;
}
.c-marquee__item:nth-child(odd) {
  margin-bottom: 0px;
}
.c-marquee__item:nth-child(even) {
  margin-top: 0px;
}
.c-marquee__text {
  position:absolute;
  bottom: 0px;
  left:50%;
  text-align:center;
}
.c-marquee__dog {
  #position: absolute;
  bottom:0px;
  min-width:100%;
  height: auto;
}
.c-marquee__item:nth-child(5n+1):before,
.c-marquee__item:before,
.c-marquee__item:nth-child(5n+2):before,
.c-marquee__item:nth-child(5n+3):before,
.c-marquee__item:nth-child(5n+4):before  {
  background-image: none;
  padding:0;
  margin-left:2px;
  margin-right:16px;
  width:auto;
  bottom: 0px;
}
.o-section--feature {
  padding: 0rem;
  padding-top: 5rem;
}
@media screen and (min-width: 48rem) {
  .o-section--feature {
    padding: 0rem;
    padding-top: 5rem;
  }
}

@media (-webkit-min-device-pixel-ratio: 2), (min-resolution: 192dpi) {
  .c-marquee__item:nth-child(5n+1):before,
  .c-marquee__item:before,
  .c-marquee__item:nth-child(5n+2):before,
  .c-marquee__item:nth-child(5n+3):before,
  .c-marquee__item:nth-child(5n+4):before  {
    background-image: none;
    padding:0;
    margin-left:2px;
    margin-right:16px;
    width:auto;
    bottom: 0px;
  }
}
</style>
