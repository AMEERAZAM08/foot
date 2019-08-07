# foot



<!DOCTYPE html>
<html lang="en-US">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="profile" href="https://ameerazam08.github.io/" />
<link rel="pingback" href="https://ameerazam08.github.io/" />
<title>Blog - Programming Liftoff</title>

<!-- This site is optimized with the Yoast SEO plugin v11.4 - https://yoast.com/wordpress/plugins/seo/ -->
<link rel="canonical" href="https://ameerazam08.github.io/" />
<link rel="next" href="https://ameerazam08.github.io/"  />
<meta property="og:locale" content="en_US" />
<meta property="og:type" content="website" />
<meta property="og:title" content="Blog - Programming Liftoff" />
<meta property="og:description" content="Learn how to send a text message from Python! This video teaches you how to send a text message using Python3 and Twilio. Everything in this video can be done using ..." />
<meta property="og:url" content="https://ameerazam08.github.io/" />
<meta property="og:site_name" content="Programming Liftoff" />
<meta name="twitter:card" content="summary" />
<meta name="twitter:description" content="Learn how to send a text message from Python! This video teaches you how to send a text message using Python3 and Twilio. Everything in this video can be done using ..." />
<meta name="twitter:title" content="Blog - Programming Liftoff" />
<script type='application/ld+json' class='yoast-schema-graph yoast-schema-graph--main'>{"@context":"https://schema.org","@graph":[{"@type":"Organization","@id":"https://programmingliftoff.com/#organization","name":"","url":"https://programmingliftoff.com/","sameAs":[]},{"@type":"WebSite","@id":"https://programmingliftoff.com/#website","url":"https://programmingliftoff.com/","name":"Programming Liftoff","publisher":{"@id":"https://programmingliftoff.com/#organization"},"potentialAction":{"@type":"SearchAction","target":"https://programmingliftoff.com/?s={search_term_string}","query-input":"required name=search_term_string"}},{"@type":"WebPage","@id":"https://programmingliftoff.com/blog/#webpage","url":"https://programmingliftoff.com/blog/","inLanguage":"en-US","name":"Blog - Programming Liftoff","isPartOf":{"@id":"https://programmingliftoff.com/#website"}}]}</script>
<!-- / Yoast SEO plugin. -->

<link rel='dns-prefetch' href='//s0.wp.com' />
<link rel='dns-prefetch' href='//fonts.googleapis.com' />
<link rel='dns-prefetch' href='//s.w.org' />
<link rel="alternate" type="application/rss+xml" title="Programming Liftoff &raquo; Feed" href="https://programmingliftoff.com/feed/" />
<link rel="alternate" type="application/rss+xml" title="Programming Liftoff &raquo; Comments Feed" href="https://ameerazam08.github.io/" />
<!-- This site uses the Google Analytics by MonsterInsights plugin v7.7.1 - Using Analytics tracking - https://www.monsterinsights.com/ -->
<script type="text/javascript" data-cfasync="false">
	var mi_version         = '7.7.1';
	var mi_track_user      = true;
	var mi_no_track_reason = '';
	
	var disableStr = 'ga-disable-UA-82637401-2';

	/* Function to detect opted out users */
	function __gaTrackerIsOptedOut() {
		return document.cookie.indexOf(disableStr + '=true') > -1;
	}

	/* Disable tracking if the opt-out cookie exists. */
	if ( __gaTrackerIsOptedOut() ) {
		window[disableStr] = true;
	}

	/* Opt-out function */
	function __gaTrackerOptout() {
	  document.cookie = disableStr + '=true; expires=Thu, 31 Dec 2099 23:59:59 UTC; path=/';
	  window[disableStr] = true;
	}
	
	if ( mi_track_user ) {
		(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
			(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
			m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
		})(window,document,'script','//www.google-analytics.com/analytics.js','__gaTracker');

		__gaTracker('create', 'UA-82637401-2', 'auto');
		__gaTracker('set', 'forceSSL', true);
		__gaTracker('require', 'displayfeatures');
		__gaTracker('send','pageview');
	} else {
		console.log( "" );
		(function() {
			/* https://developers.google.com/analytics/devguides/collection/analyticsjs/ */
			var noopfn = function() {
				return null;
			};
			var noopnullfn = function() {
				return null;
			};
			var Tracker = function() {
				return null;
			};
			var p = Tracker.prototype;
			p.get = noopfn;
			p.set = noopfn;
			p.send = noopfn;
			var __gaTracker = function() {
				var len = arguments.length;
				if ( len === 0 ) {
					return;
				}
				var f = arguments[len-1];
				if ( typeof f !== 'object' || f === null || typeof f.hitCallback !== 'function' ) {
					console.log( 'Not running function __gaTracker(' + arguments[0] + " ....) because you are not being tracked. " + mi_no_track_reason );
					return;
				}
				try {
					f.hitCallback();
				} catch (ex) {

				}
			};
			__gaTracker.create = function() {
				return new Tracker();
			};
			__gaTracker.getByName = noopnullfn;
			__gaTracker.getAll = function() {
				return [];
			};
			__gaTracker.remove = noopfn;
			window['__gaTracker'] = __gaTracker;
					})();
		}
</script>
<!-- / Google Analytics by MonsterInsights -->
		<script type="text/javascript">
			window._wpemojiSettings = {"baseUrl":"https:\/\/s.w.org\/images\/core\/emoji\/12.0.0-1\/72x72\/","ext":".png","svgUrl":"https:\/\/s.w.org\/images\/core\/emoji\/12.0.0-1\/svg\/","svgExt":".svg","source":{"concatemoji":"https:\/\/programmingliftoff.com\/wp-includes\/js\/wp-emoji-release.min.js?ver=5.2.2"}};
			!function(a,b,c){function d(a,b){var c=String.fromCharCode;l.clearRect(0,0,k.width,k.height),l.fillText(c.apply(this,a),0,0);var d=k.toDataURL();l.clearRect(0,0,k.width,k.height),l.fillText(c.apply(this,b),0,0);var e=k.toDataURL();return d===e}function e(a){var b;if(!l||!l.fillText)return!1;switch(l.textBaseline="top",l.font="600 32px Arial",a){case"flag":return!(b=d([55356,56826,55356,56819],[55356,56826,8203,55356,56819]))&&(b=d([55356,57332,56128,56423,56128,56418,56128,56421,56128,56430,56128,56423,56128,56447],[55356,57332,8203,56128,56423,8203,56128,56418,8203,56128,56421,8203,56128,56430,8203,56128,56423,8203,56128,56447]),!b);case"emoji":return b=d([55357,56424,55356,57342,8205,55358,56605,8205,55357,56424,55356,57340],[55357,56424,55356,57342,8203,55358,56605,8203,55357,56424,55356,57340]),!b}return!1}function f(a){var c=b.createElement("script");c.src=a,c.defer=c.type="text/javascript",b.getElementsByTagName("head")[0].appendChild(c)}var g,h,i,j,k=b.createElement("canvas"),l=k.getContext&&k.getContext("2d");for(j=Array("flag","emoji"),c.supports={everything:!0,everythingExceptFlag:!0},i=0;i<j.length;i++)c.supports[j[i]]=e(j[i]),c.supports.everything=c.supports.everything&&c.supports[j[i]],"flag"!==j[i]&&(c.supports.everythingExceptFlag=c.supports.everythingExceptFlag&&c.supports[j[i]]);c.supports.everythingExceptFlag=c.supports.everythingExceptFlag&&!c.supports.flag,c.DOMReady=!1,c.readyCallback=function(){c.DOMReady=!0},c.supports.everything||(h=function(){c.readyCallback()},b.addEventListener?(b.addEventListener("DOMContentLoaded",h,!1),a.addEventListener("load",h,!1)):(a.attachEvent("onload",h),b.attachEvent("onreadystatechange",function(){"complete"===b.readyState&&c.readyCallback()})),g=c.source||{},g.concatemoji?f(g.concatemoji):g.wpemoji&&g.twemoji&&(f(g.twemoji),f(g.wpemoji)))}(window,document,window._wpemojiSettings);
		</script>
		<style type="text/css">
img.wp-smiley,
img.emoji {
	display: inline !important;
	border: none !important;
	box-shadow: none !important;
	height: 1em !important;
	width: 1em !important;
	margin: 0 .07em !important;
	vertical-align: -0.1em !important;
	background: none !important;
	padding: 0 !important;
}
</style>
	<link rel='stylesheet' id='wp-block-library-css'  href='https://programmingliftoff.com/wp-includes/css/dist/block-library/style.min.css?ver=5.2.2' type='text/css' media='all' />
<link rel='stylesheet' id='ap-front-styles-css'  href='https://programmingliftoff.com/wp-content/plugins/accesspress-anonymous-post/css/frontend-style.css?ver=2.7.6' type='text/css' media='all' />
<link rel='stylesheet' id='wordpress-popular-posts-css-css'  href='https://programmingliftoff.com/wp-content/plugins/wordpress-popular-posts/public/css/wpp.css?ver=4.2.2' type='text/css' media='all' />
<link rel='stylesheet' id='onepress-fonts-css'  href='https://fonts.googleapis.com/css?family=Raleway%3A400%2C500%2C600%2C700%2C300%2C100%2C800%2C900%7COpen+Sans%3A400%2C300%2C300italic%2C400italic%2C600%2C600italic%2C700%2C700italic&#038;subset=latin%2Clatin-ext' type='text/css' media='all' />
<link rel='stylesheet' id='onepress-animate-css'  href='https://programmingliftoff.com/wp-content/themes/onepress/assets/css/animate.min.css' type='text/css' media='all' />
<link rel='stylesheet' id='onepress-fa-css'  href='https://programmingliftoff.com/wp-content/themes/onepress/assets/css/font-awesome.min.css?ver=4.7.0' type='text/css' media='all' />
<link rel='stylesheet' id='onepress-bootstrap-css'  href='https://programmingliftoff.com/wp-content/themes/onepress/assets/css/bootstrap.min.css' type='text/css' media='all' />
<link rel='stylesheet' id='onepress-style-css'  href='https://programmingliftoff.com/wp-content/themes/onepress/style.css?ver=5.2.2' type='text/css' media='all' />
<style id='onepress-style-inline-css' type='text/css'>
#main .video-section section.hero-slideshow-wrapper{background:transparent}.hero-slideshow-wrapper:after{position:absolute;top:0px;left:0px;width:100%;height:100%;background-color:rgba(30,115,190,1);display:block;content:""}.body-desktop .parallax-hero .hero-slideshow-wrapper:after{display:none!important}#parallax-hero>.parallax-bg::before{background-color:rgba(30,115,190,1);opacity:1}.body-desktop .parallax-hero .hero-slideshow-wrapper:after{display:none!important}#footer-widgets{}.gallery-carousel .g-item{padding:0px 10px}.gallery-carousel{margin-left:-10px;margin-right:-10px}.gallery-grid .g-item,.gallery-masonry .g-item .inner{padding:10px}.gallery-grid,.gallery-masonry{margin:-10px}
</style>
<link rel='stylesheet' id='child-style-css'  href='https://programmingliftoff.com/wp-content/themes/onepress-child/style.css?ver=2.0.2' type='text/css' media='all' />
<link rel='stylesheet' id='onepress-gallery-lightgallery-css'  href='https://programmingliftoff.com/wp-content/themes/onepress/assets/css/lightgallery.css?ver=5.2.2' type='text/css' media='all' />
<link rel='stylesheet' id='prismCSS-css'  href='https://programmingliftoff.com/wp-content/themes/onepress-child/prism.css?ver=5.2.2' type='text/css' media='all' />
<link rel='stylesheet' id='gca-column-styles-css'  href='https://programmingliftoff.com/wp-content/plugins/genesis-columns-advanced/css/gca-column-styles.css?ver=5.2.2' type='text/css' media='all' />
<link rel='stylesheet' id='jetpack_css-css'  href='https://programmingliftoff.com/wp-content/plugins/jetpack/css/jetpack.css?ver=7.4.1' type='text/css' media='all' />
<script type='text/javascript'>
/* <![CDATA[ */
var monsterinsights_frontend = {"js_events_tracking":"true","download_extensions":"doc,exe,js,pdf,ppt,tgz,zip,xls","inbound_paths":"[]","home_url":"https:\/\/programmingliftoff.com","hash_tracking":"false"};
/* ]]> */
</script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-content/plugins/google-analytics-for-wordpress/assets/js/frontend.min.js?ver=7.7.1'></script>
<script type='text/javascript'>
/* <![CDATA[ */
var onepress_js_settings = {"onepress_disable_animation":"","onepress_disable_sticky_header":"","onepress_vertical_align_menu":"","hero_animation":"flipInX","hero_speed":"5000","hero_fade":"750","hero_duration":"5000","hero_disable_preload":"","is_home":"","gallery_enable":"1","is_rtl":""};
/* ]]> */
</script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-includes/js/jquery/jquery.js?ver=1.12.4-wp'></script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-includes/js/jquery/jquery-migrate.min.js?ver=1.4.1'></script>
<script type='text/javascript'>
/* <![CDATA[ */
var wpp_params = {"sampling_active":"0","sampling_rate":"100","ajax_url":"https:\/\/programmingliftoff.com\/wp-json\/wordpress-popular-posts\/v1\/popular-posts\/","ID":"","token":"dda958cbdd","debug":""};
/* ]]> */
</script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-content/plugins/wordpress-popular-posts/public/js/wpp-4.2.0.min.js?ver=4.2.2'></script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-content/themes/onepress-child/prism.js?ver=5.2.2'></script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-content/themes/onepress-child/mailchimp_submit.js?ver=5.2.2'></script>
<link rel='https://api.w.org/' href='https://programmingliftoff.com/wp-json/' />
<link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://programmingliftoff.com/xmlrpc.php?rsd" />
<link rel="wlwmanifest" type="application/wlwmanifest+xml" href="https://programmingliftoff.com/wp-includes/wlwmanifest.xml" /> 
<meta name="generator" content="WordPress 5.2.2" />

<link rel='dns-prefetch' href='//v0.wordpress.com'/>
<link rel='dns-prefetch' href='//i0.wp.com'/>
<link rel='dns-prefetch' href='//i1.wp.com'/>
<link rel='dns-prefetch' href='//i2.wp.com'/>
<style type='text/css'>img#wpstats{display:none}</style>		<style type="text/css">.recentcomments a{display:inline !important;padding:0 !important;margin:0 !important;}</style>
		<link rel="icon" href="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/08/cropped-rocket_v1.png?fit=32%2C32&#038;ssl=1" sizes="32x32" />
<link rel="icon" href="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/08/cropped-rocket_v1.png?fit=192%2C192&#038;ssl=1" sizes="192x192" />
<link rel="apple-touch-icon-precomposed" href="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/08/cropped-rocket_v1.png?fit=180%2C180&#038;ssl=1" />
<meta name="msapplication-TileImage" content="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/08/cropped-rocket_v1.png?fit=270%2C270&#038;ssl=1" />


</head>

<body data-rsssl=1 class="blog">
<div id="page" class="hfeed site">
        <a class="skip-link screen-reader-text" href="#content">Skip to content</a>
    <div id="header-section" class="h-on-top no-transparent">        <header id="masthead" class="site-header header-contained is-sticky no-scroll no-t h-on-top" role="banner">
            <div class="container">
                <div class="site-branding">
                <div class="site-brand-inner no-logo-img has-title has-desc"><p class="site-title"><a class="site-text-logo" href="https://programmingliftoff.com/" rel="home">Programming Liftoff</a></p><p class="site-description">Learn to program!</p></div>                </div>
                <div class="header-right-wrapper">
                    <a href="#0" id="nav-toggle">Menu<span></span></a>
                    <nav id="site-navigation" class="main-navigation" role="navigation">
                        <ul class="onepress-menu">
                            <li id="menu-item-68" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-home menu-item-68"><a href="https://programmingliftoff.com">Home</a></li>
<li id="menu-item-62" class="menu-item menu-item-type-post_type menu-item-object-page current-menu-item page_item page-item-37 current_page_item current_page_parent menu-item-62"><a href="https://programmingliftoff.com/blog/" aria-current="page">Blog</a></li>
<li id="menu-item-64" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-64"><a href="https://programmingliftoff.com/about/">About</a></li>
<li id="menu-item-65" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-65"><a href="https://programmingliftoff.com/contact-us/">Contact Us</a></li>
                        </ul>
                    </nav>
                    <!-- #site-navigation -->
                </div>
            </div>
        </header><!-- #masthead -->
        </div>
                    <div class="page-header">
                <div class="container">
                    <h1 class="entry-title">Blog</h1>                </div>
            </div>
                	<div id="content" class="site-content">
                <div id="content-inside" class="container right-sidebar">
			<div id="primary" class="content-area">
				<main id="main" class="site-main" role="main">

				
											<header>
							<h1 class="page-title screen-reader-text">Blog</h1>
						</header>
					
										
						
<article id="post-86" class="list-article clearfix post-86 post type-post status-publish format-standard has-post-thumbnail sticky hentry category-python-programming-languages category-twilio tag-application tag-beginner tag-code tag-free tag-introduction tag-learn tag-programming tag-py tag-python tag-python-tips tag-python3 tag-sms tag-text tag-text-message tag-tips tag-tutorial tag-twilio">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/send-text-messages-from-python-100-free/">
			<img width="300" height="150" src="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/thumbnail.png?resize=300%2C150&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="" srcset="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/thumbnail.png?resize=300%2C150&amp;ssl=1 300w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/thumbnail.png?zoom=2&amp;resize=300%2C150&amp;ssl=1 600w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/thumbnail.png?zoom=3&amp;resize=300%2C150&amp;ssl=1 900w" sizes="(max-width: 300px) 100vw, 300px" data-attachment-id="87" data-permalink="https://programmingliftoff.com/send-text-messages-from-python-100-free/thumbnail/" data-orig-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/thumbnail.png?fit=1280%2C702&amp;ssl=1" data-orig-size="1280,702" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="sms python twilio" data-image-description="" data-medium-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/thumbnail.png?fit=300%2C165&amp;ssl=1" data-large-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/thumbnail.png?fit=800%2C439&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/programming-languages/python-programming-languages/" rel="category tag">Python</a> / <a href="https://programmingliftoff.com/category/twilio/" rel="category tag">Twilio</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/send-text-messages-from-python-100-free/" rel="bookmark">Send text messages from Python using Twilio!</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p>Learn how to send a text message from Python! This video teaches you how to send a text message using Python3 and Twilio. Everything in this video can be done using the free credits that Twilio gives you when you &hellip;</p>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-83" class="list-article clearfix post-83 post type-post status-publish format-standard has-post-thumbnail sticky hentry category-python-programming-languages category-qt tag-application tag-beginner tag-calculator tag-code tag-gui tag-introduction tag-learn tag-programming tag-py tag-pyqt tag-pyqt5 tag-python tag-python3 tag-qt tag-qt5 tag-tips tag-tutorial">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/qt-python-tutorial/">
			<img width="300" height="150" src="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/CalculatorPic.png?resize=300%2C150&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="" srcset="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/CalculatorPic.png?resize=300%2C150&amp;ssl=1 300w, https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/CalculatorPic.png?zoom=2&amp;resize=300%2C150&amp;ssl=1 600w, https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/CalculatorPic.png?zoom=3&amp;resize=300%2C150&amp;ssl=1 900w" sizes="(max-width: 300px) 100vw, 300px" data-attachment-id="84" data-permalink="https://programmingliftoff.com/qt-python-tutorial/calculatorpic/" data-orig-file="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/CalculatorPic.png?fit=1280%2C657&amp;ssl=1" data-orig-size="1280,657" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="Qt Python Calculator" data-image-description="" data-medium-file="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/CalculatorPic.png?fit=300%2C154&amp;ssl=1" data-large-file="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/CalculatorPic.png?fit=800%2C411&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/programming-languages/python-programming-languages/" rel="category tag">Python</a> / <a href="https://programmingliftoff.com/category/qt/" rel="category tag">Qt</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/qt-python-tutorial/" rel="bookmark">QT Python Tutorial</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p>Learn how to design and code a GUI user interface for a calculator using Qt.  First we quickly create our GUI using Qt&#8217;s drag-and-drop GUI designer.  In the following videos we use one of the most popular and fastest growing &hellip;</p>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-79" class="list-article clearfix post-79 post type-post status-publish format-standard has-post-thumbnail sticky hentry category-c-programming-languages category-qt tag-application tag-c tag-calculator tag-code tag-cpp tag-gui tag-introduction tag-learn tag-programming tag-qt tag-qt5 tag-tutorial">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/qt-cpp-tutorial/">
			<img width="300" height="150" src="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/Qt-CPP-Part-2-Thumbnail.png?resize=300%2C150&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="" srcset="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/Qt-CPP-Part-2-Thumbnail.png?resize=300%2C150&amp;ssl=1 300w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/Qt-CPP-Part-2-Thumbnail.png?zoom=2&amp;resize=300%2C150&amp;ssl=1 600w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/Qt-CPP-Part-2-Thumbnail.png?zoom=3&amp;resize=300%2C150&amp;ssl=1 900w" sizes="(max-width: 300px) 100vw, 300px" data-attachment-id="82" data-permalink="https://programmingliftoff.com/qt-cpp-tutorial/qt-cpp-part-2-thumbnail/" data-orig-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/Qt-CPP-Part-2-Thumbnail.png?fit=1280%2C704&amp;ssl=1" data-orig-size="1280,704" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="Qt CPP Calculator" data-image-description="" data-medium-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/Qt-CPP-Part-2-Thumbnail.png?fit=300%2C165&amp;ssl=1" data-large-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/09/Qt-CPP-Part-2-Thumbnail.png?fit=800%2C440&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/programming-languages/c-programming-languages/" rel="category tag">C++</a> / <a href="https://programmingliftoff.com/category/qt/" rel="category tag">Qt</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/qt-cpp-tutorial/" rel="bookmark">QT C++ Tutorial</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p>Learn how to design and code a GUI user interface for a calculator using Qt. First we quickly create our GUI using Qt&#8217;s drag-and-drop GUI designer. In the following videos we use one of the most widely used programming languages &hellip;</p>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-1" class="list-article clearfix post-1 post type-post status-publish format-standard has-post-thumbnail sticky hentry category-getting-started">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/welcome/">
			<img width="300" height="150" src="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2017/08/rocket_v1.png?resize=300%2C150&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="Image of rocket with programming languages" data-attachment-id="11" data-permalink="https://programmingliftoff.com/rocket_v1/" data-orig-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2017/08/rocket_v1.png?fit=501%2C483&amp;ssl=1" data-orig-size="501,483" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="rocket" data-image-description="" data-medium-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2017/08/rocket_v1.png?fit=300%2C289&amp;ssl=1" data-large-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2017/08/rocket_v1.png?fit=501%2C483&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/getting-started/" rel="category tag">Getting Started</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/welcome/" rel="bookmark">Welcome!</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p>Welcome to Programming Liftoff! We&#8217;re excited to grow a community of learners. Programming is such an amazing thing, giving ordinary people the ability to have an extraordinary impact on the world. We want to help <em>you</em> improve every day so &hellip;</p>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-417" class="list-article clearfix post-417 post type-post status-publish format-standard hentry category-react-frontend-frameworks category-sublime-text-3 tag-quick-tip">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/enable-jsx-commenting-sublime-text-3/">
			<img alt="" src="https://programmingliftoff.com/wp-content/themes/onepress/assets/images/placholder2.png">		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/frontend-frameworks/react-frontend-frameworks/" rel="category tag">React</a> / <a href="https://programmingliftoff.com/category/code-editors/sublime-text-3/" rel="category tag">Sublime Text 3</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/enable-jsx-commenting-sublime-text-3/" rel="bookmark">How to Enable JSX Commenting in Sublime Text 3</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p>This is a short post to show you how to enable JSX commenting in Sublime Text 3.  At the end of this post you will be able to comment and uncomment JSX by pressing <code>CMD</code> + <code>/</code> or <code>Ctl</code> + &hellip;</p>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-273" class="list-article clearfix post-273 post type-post status-publish format-standard has-post-thumbnail hentry category-beginner category-css category-github-pages category-gitlab-pages category-html category-javascript category-web-development">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/create-basic-webpage-css-javascript/">
			<img width="300" height="150" src="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?resize=300%2C150&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="Image of basic webpage with four pictures from unsplash" srcset="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?resize=300%2C150&amp;ssl=1 300w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?zoom=2&amp;resize=300%2C150&amp;ssl=1 600w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?zoom=3&amp;resize=300%2C150&amp;ssl=1 900w" sizes="(max-width: 300px) 100vw, 300px" data-attachment-id="391" data-permalink="https://programmingliftoff.com/create-basic-webpage-css-javascript/create-website-css-and-js/" data-orig-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?fit=1280%2C741&amp;ssl=1" data-orig-size="1280,741" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="create-website-css-and-js" data-image-description="" data-medium-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?fit=300%2C174&amp;ssl=1" data-large-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?fit=800%2C463&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/difficulty/beginner/" rel="category tag">Beginner</a> / <a href="https://programmingliftoff.com/category/programming-languages/css/" rel="category tag">CSS</a> / <a href="https://programmingliftoff.com/category/hosting/github-pages/" rel="category tag">GitHub Pages</a> / <a href="https://programmingliftoff.com/category/hosting/gitlab-pages/" rel="category tag">GitLab Pages</a> / <a href="https://programmingliftoff.com/category/programming-languages/html/" rel="category tag">HTML</a> / <a href="https://programmingliftoff.com/category/programming-languages/javascript/" rel="category tag">JavaScript</a> / <a href="https://programmingliftoff.com/category/web-development/" rel="category tag">Web Development</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/create-basic-webpage-css-javascript/" rel="bookmark">Create a Basic Webpage with CSS and JavaScript</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p><em>Note: If you already have your website and just need to upload it to GitHub and enable GitHub Pages, read <a href="https://programmingliftoff.com/upload-website-github-pages/">Upload a Website to GitHub Pages</a></em></p>
<p>Prefer to watch this tutorial instead of reading it?  Scroll to the bottom of &hellip;</p>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-363" class="list-article clearfix post-363 post type-post status-publish format-standard has-post-thumbnail hentry category-visual-studio-code">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/visual-studio-code-user-settings/">
			<img width="300" height="150" src="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?resize=300%2C150&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="Image of the settings file in Visual Studio Code Application" srcset="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?resize=300%2C150&amp;ssl=1 300w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?zoom=2&amp;resize=300%2C150&amp;ssl=1 600w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?zoom=3&amp;resize=300%2C150&amp;ssl=1 900w" sizes="(max-width: 300px) 100vw, 300px" data-attachment-id="366" data-permalink="https://programmingliftoff.com/visual-studio-code-user-settings/vscodeusersettings/" data-orig-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?fit=1280%2C778&amp;ssl=1" data-orig-size="1280,778" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="VSCodeUserSettings" data-image-description="" data-medium-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?fit=300%2C182&amp;ssl=1" data-large-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?fit=800%2C486&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/code-editors/visual-studio-code/" rel="category tag">Visual Studio Code</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/visual-studio-code-user-settings/" rel="bookmark">My Visual Studio Code User Settings</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p><img data-attachment-id="366" data-permalink="https://programmingliftoff.com/visual-studio-code-user-settings/vscodeusersettings/" data-orig-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?fit=1280%2C778&amp;ssl=1" data-orig-size="1280,778" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="VSCodeUserSettings" data-image-description="" data-medium-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?fit=300%2C182&amp;ssl=1" data-large-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?fit=800%2C486&amp;ssl=1" src="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?resize=800%2C486" alt="Image of the settings file in Visual Studio Code Application" width="800" height="486" class="aligncenter size-full wp-image-366" srcset="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?w=1280&amp;ssl=1 1280w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?resize=300%2C182&amp;ssl=1 300w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?resize=768%2C467&amp;ssl=1 768w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeUserSettings.png?resize=1024%2C622&amp;ssl=1 1024w" sizes="(max-width: 800px) 100vw, 800px" data-recalc-dims="1" /></p>
<p>Here is my &#8216;User Settings&#8217; file for VS Code.  After this code section, each line is explained so you can decide if you would benefit from including it in your own settings.</p>
<pre class="line-numbers"><code class="language-JSON">
{
    "python.pythonPath": "/usr/local/bin/python3"
}
</code></pre>
<h2>Line By Line</h2>
<h3>Line </h3>&hellip;					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-370" class="list-article clearfix post-370 post type-post status-publish format-standard has-post-thumbnail hentry category-visual-studio-code">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/tools-packages-use-visual-studio-code/">
			<img width="300" height="150" src="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?resize=300%2C150&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="Welcome screen for Visual Studio Code" srcset="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?resize=300%2C150&amp;ssl=1 300w, https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?zoom=2&amp;resize=300%2C150&amp;ssl=1 600w, https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?zoom=3&amp;resize=300%2C150&amp;ssl=1 900w" sizes="(max-width: 300px) 100vw, 300px" data-attachment-id="372" data-permalink="https://programmingliftoff.com/tools-packages-use-visual-studio-code/vscodewelcomescreen/" data-orig-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?fit=1280%2C778&amp;ssl=1" data-orig-size="1280,778" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="VSCodeWelcomeScreen" data-image-description="" data-medium-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?fit=300%2C182&amp;ssl=1" data-large-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?fit=800%2C486&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/code-editors/visual-studio-code/" rel="category tag">Visual Studio Code</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/tools-packages-use-visual-studio-code/" rel="bookmark">Tools and Packages I use for Visual Studio Code</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p><img data-attachment-id="372" data-permalink="https://programmingliftoff.com/tools-packages-use-visual-studio-code/vscodewelcomescreen/" data-orig-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?fit=1280%2C778&amp;ssl=1" data-orig-size="1280,778" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="VSCodeWelcomeScreen" data-image-description="" data-medium-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?fit=300%2C182&amp;ssl=1" data-large-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?fit=800%2C486&amp;ssl=1" src="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?resize=800%2C486" alt="Welcome screen for Visual Studio Code" width="800" height="486" class="aligncenter size-full wp-image-372" srcset="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?w=1280&amp;ssl=1 1280w, https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?resize=300%2C182&amp;ssl=1 300w, https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?resize=768%2C467&amp;ssl=1 768w, https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/VSCodeWelcomeScreen.png?resize=1024%2C622&amp;ssl=1 1024w" sizes="(max-width: 800px) 100vw, 800px" data-recalc-dims="1" /></p>
<p>Here is a list of settings I tweaked and packages I installed to improve my VS Code experience.</p>
<h3>Python Language Extension</h3>
<p>To install the Python language extension, open the extensions sidebar (CMD+Shift+X -or- View-Extensions)<br />
Then search for Python in &hellip;</p>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-355" class="list-article clearfix post-355 post type-post status-publish format-standard has-post-thumbnail hentry category-mac category-quick-tip tag-finder tag-keyboard-shortcut tag-open-terminal">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/mac-open-terminal-finder/">
			<img width="300" height="150" src="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?resize=300%2C150&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="Image of open Terminal window and Mac system preferences" srcset="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?resize=300%2C150&amp;ssl=1 300w, https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?zoom=2&amp;resize=300%2C150&amp;ssl=1 600w, https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?zoom=3&amp;resize=300%2C150&amp;ssl=1 900w" sizes="(max-width: 300px) 100vw, 300px" data-attachment-id="359" data-permalink="https://programmingliftoff.com/mac-open-terminal-finder/openterminalatfolder/" data-orig-file="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?fit=1052%2C578&amp;ssl=1" data-orig-size="1052,578" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="openTerminalAtFolder" data-image-description="" data-medium-file="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?fit=300%2C165&amp;ssl=1" data-large-file="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?fit=800%2C440&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/os/mac/" rel="category tag">Mac</a> / <a href="https://programmingliftoff.com/category/quick-tip/" rel="category tag">Quick Tip</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/mac-open-terminal-finder/" rel="bookmark">Mac Open Terminal From Finder</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p><img data-attachment-id="359" data-permalink="https://programmingliftoff.com/mac-open-terminal-finder/openterminalatfolder/" data-orig-file="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?fit=1052%2C578&amp;ssl=1" data-orig-size="1052,578" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="openTerminalAtFolder" data-image-description="" data-medium-file="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?fit=300%2C165&amp;ssl=1" data-large-file="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?fit=800%2C440&amp;ssl=1" src="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?resize=800%2C440" alt="Image of open Terminal window and Mac system preferences" width="800" height="440" class="aligncenter size-full wp-image-359" srcset="https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?w=1052&amp;ssl=1 1052w, https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?resize=300%2C165&amp;ssl=1 300w, https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?resize=768%2C422&amp;ssl=1 768w, https://i2.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/openTerminalAtFolder.png?resize=1024%2C563&amp;ssl=1 1024w" sizes="(max-width: 800px) 100vw, 800px" data-recalc-dims="1" /></p>
<h4>Instructions</h4>
<p>First go to: System Preferences -Keyboard -Shortcuts Tab -Services (in side menu)</p>
<p>Scroll down to &#8220;New Terminal at Folder&#8221; and check the box next to it.</p>
<p>You can also click the &#8220;None&#8221; to the right to &hellip;</p>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-340" class="list-article clearfix post-340 post type-post status-publish format-standard has-post-thumbnail hentry category-beginner category-github category-github-pages">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/upload-website-github-pages/">
			<img width="300" height="150" src="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?resize=300%2C150&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="Image of basic webpage with four pictures from unsplash" srcset="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?resize=300%2C150&amp;ssl=1 300w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?zoom=2&amp;resize=300%2C150&amp;ssl=1 600w, https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?zoom=3&amp;resize=300%2C150&amp;ssl=1 900w" sizes="(max-width: 300px) 100vw, 300px" data-attachment-id="391" data-permalink="https://programmingliftoff.com/create-basic-webpage-css-javascript/create-website-css-and-js/" data-orig-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?fit=1280%2C741&amp;ssl=1" data-orig-size="1280,741" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="create-website-css-and-js" data-image-description="" data-medium-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?fit=300%2C174&amp;ssl=1" data-large-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/create-website-css-and-js.png?fit=800%2C463&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/difficulty/beginner/" rel="category tag">Beginner</a> / <a href="https://programmingliftoff.com/category/version-control/github/" rel="category tag">GitHub</a> / <a href="https://programmingliftoff.com/category/hosting/github-pages/" rel="category tag">GitHub Pages</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/upload-website-github-pages/" rel="bookmark">Upload a Website to GitHub Pages</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p><em>Note: Before following these steps you should have created a website on your local machine.  If you do not have a website yet, complete the tutorial <a href="https://programmingliftoff.com/create-basic-webpage-css-javascript/">Create a Basic Webpage with CSS and JavaScript</a> to create a website, then come </em>&hellip;</p>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-270" class="list-article clearfix post-270 post type-post status-publish format-standard has-post-thumbnail hentry category-web-development tag-ajax tag-json">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/json-simplified/">
			<img width="300" height="150" src="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/json-simplified-webpage.png?resize=300%2C150&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="Image of simple webpage displaying JSON data" srcset="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/json-simplified-webpage.png?resize=300%2C150&amp;ssl=1 300w, https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/json-simplified-webpage.png?resize=480%2C239&amp;ssl=1 480w" sizes="(max-width: 300px) 100vw, 300px" data-attachment-id="293" data-permalink="https://programmingliftoff.com/json-simplified/json-simplified-webpage/" data-orig-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/json-simplified-webpage.png?fit=483%2C239&amp;ssl=1" data-orig-size="483,239" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="json-simplified-webpage" data-image-description="" data-medium-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/json-simplified-webpage.png?fit=300%2C148&amp;ssl=1" data-large-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/json-simplified-webpage.png?fit=483%2C239&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/web-development/" rel="category tag">Web Development</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/json-simplified/" rel="bookmark">JSON Simplified</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p>JSON is an essential part of the web today.  It&#8217;s unavoidable for anyone programming in JavaScript.  JSON stands for JavaScript Object Notation.  An AJAX request is used in JavaScript to request JSON data from a server.  AJAX stands for Asynchronous &hellip;</p>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-275" class="list-article clearfix post-275 post type-post status-publish format-standard has-post-thumbnail hentry category-github category-github-pages category-html">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/create-your-first-website-on-gitlab-pages/">
			<img width="300" height="150" src="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/gitlab_homepage.png?resize=300%2C150&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="Screenshot of GitLab Homepage" srcset="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/gitlab_homepage.png?resize=300%2C150&amp;ssl=1 300w, https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/gitlab_homepage.png?zoom=2&amp;resize=300%2C150&amp;ssl=1 600w, https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/gitlab_homepage.png?zoom=3&amp;resize=300%2C150&amp;ssl=1 900w" sizes="(max-width: 300px) 100vw, 300px" data-attachment-id="279" data-permalink="https://programmingliftoff.com/create-your-first-website-on-gitlab-pages/gitlab_homepage/" data-orig-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/gitlab_homepage.png?fit=1280%2C777&amp;ssl=1" data-orig-size="1280,777" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="gitlab_homepage" data-image-description="&lt;p&gt;GitLab Homepage&lt;/p&gt;
" data-medium-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/gitlab_homepage.png?fit=300%2C182&amp;ssl=1" data-large-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2018/02/gitlab_homepage.png?fit=800%2C486&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/version-control/github/" rel="category tag">GitHub</a> / <a href="https://programmingliftoff.com/category/hosting/github-pages/" rel="category tag">GitHub Pages</a> / <a href="https://programmingliftoff.com/category/programming-languages/html/" rel="category tag">HTML</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/create-your-first-website-on-gitlab-pages/" rel="bookmark">Create your first website on GitLab Pages</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p>This video will walk you step by step through creating a live website using GitLab Pages.  This video is intended for people who may have experience building websites, but have not used GitLab Pages to host their website.  Want to &hellip;</p>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-251" class="list-article clearfix post-251 post type-post status-publish format-standard has-post-thumbnail hentry category-regular-expressions-regex">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/learn-regular-expressions-using-atom/">
			<img width="262" height="87" src="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/11/Atom-Regex.png?resize=262%2C87&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="Image of Atom Regex in &#039;find and replace&#039; utility" data-attachment-id="257" data-permalink="https://programmingliftoff.com/learn-regular-expressions-using-atom/atom-regex/" data-orig-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/11/Atom-Regex.png?fit=262%2C87&amp;ssl=1" data-orig-size="262,87" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="Atom Regex" data-image-description="&lt;p&gt;Image of Atom Regex in &#8216;find and replace&#8217; utility&lt;/p&gt;
" data-medium-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/11/Atom-Regex.png?fit=262%2C87&amp;ssl=1" data-large-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/11/Atom-Regex.png?fit=262%2C87&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/regular-expressions-regex/" rel="category tag">Regular Expressions (Regex)</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/learn-regular-expressions-using-atom/" rel="bookmark">Learn Regular Expressions using Atom</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p>This is a short little post with the goal of helping you to learn the elusive regular expressions!</p>
<p>This takes advantage of a built in regex feature in the Atom text editor. It may work in other text editors as &hellip;</p>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
						
<article id="post-188" class="list-article clearfix post-188 post type-post status-publish format-standard has-post-thumbnail hentry category-c category-c-programming-languages category-docker category-getting-started category-go category-python-programming-languages category-ruby">

	<div class="list-article-thumb">
		<a href="https://programmingliftoff.com/using-docker-for-experimenting-with-code/">
			<img width="145" height="108" src="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/10/moby_small.png?resize=145%2C108&amp;ssl=1" class="attachment-onepress-blog-small size-onepress-blog-small wp-post-image" alt="" data-attachment-id="204" data-permalink="https://programmingliftoff.com/using-docker-for-experimenting-with-code/moby_small/" data-orig-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/10/moby_small.png?fit=145%2C108&amp;ssl=1" data-orig-size="145,108" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="moby_small" data-image-description="" data-medium-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/10/moby_small.png?fit=145%2C108&amp;ssl=1" data-large-file="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/10/moby_small.png?fit=145%2C108&amp;ssl=1" />		</a>
	</div>

	<div class="list-article-content">
		<div class="list-article-meta">
			<a href="https://programmingliftoff.com/category/programming-languages/c/" rel="category tag">C</a> / <a href="https://programmingliftoff.com/category/programming-languages/c-programming-languages/" rel="category tag">C++</a> / <a href="https://programmingliftoff.com/category/docker/" rel="category tag">Docker</a> / <a href="https://programmingliftoff.com/category/getting-started/" rel="category tag">Getting Started</a> / <a href="https://programmingliftoff.com/category/programming-languages/go/" rel="category tag">Go</a> / <a href="https://programmingliftoff.com/category/programming-languages/python-programming-languages/" rel="category tag">Python</a> / <a href="https://programmingliftoff.com/category/programming-languages/ruby/" rel="category tag">Ruby</a>		</div>
		<header class="entry-header">
			<h2 class="entry-title"><a href="https://programmingliftoff.com/using-docker-for-experimenting-with-code/" rel="bookmark">Using Docker for Experimenting with Code</a></h2>		</header><!-- .entry-header -->
		<div class="entry-excerpt">
			<p><img data-attachment-id="202" data-permalink="https://programmingliftoff.com/using-docker-for-experimenting-with-code/horizontal_large/" data-orig-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2017/10/horizontal_large.png?fit=594%2C160&amp;ssl=1" data-orig-size="594,160" data-comments-opened="1" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="docker_horizontal_large" data-image-description="&lt;p&gt;Docker Logo&lt;/p&gt;
" data-medium-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2017/10/horizontal_large.png?fit=300%2C81&amp;ssl=1" data-large-file="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2017/10/horizontal_large.png?fit=594%2C160&amp;ssl=1" class="aligncenter size-medium wp-image-202" src="https://i0.wp.com/programmingliftoff.com/wp-content/uploads/2017/10/horizontal_large-300x81.png?resize=300%2C81" alt="Docker Logo" width="300" height="81" srcset="https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2017/10/horizontal_large.png?resize=300%2C81&amp;ssl=1 300w, https://i1.wp.com/programmingliftoff.com/wp-content/uploads/2017/10/horizontal_large.png?w=594&amp;ssl=1 594w" sizes="(max-width: 300px) 100vw, 300px" data-recalc-dims="1" /></p>
<section class="language-markup">One of the best ways to learn to code is by writing or modifying programs to see what they do. For me, this usually involves creating a file named something like <code>delete.py</code>, and writing some code in it to &hellip;</section>					</div><!-- .entry-content -->
	</div>

</article><!-- #post-## -->

					
					
	<nav class="navigation posts-navigation" role="navigation">
		<h2 class="screen-reader-text">Posts navigation</h2>
		<div class="nav-links"><div class="nav-previous"><a href="https://programmingliftoff.com/blog/page/2/" >Older posts</a></div></div>
	</nav>
				
				</main><!-- #main -->
			</div><!-- #primary -->

                            
<div id="secondary" class="widget-area sidebar" role="complementary">
	<aside id="search-2" class="widget widget_search"><form role="search" method="get" class="search-form" action="https://programmingliftoff.com/">
				<label>
					<span class="screen-reader-text">Search for:</span>
					<input type="search" class="search-field" placeholder="Search &hellip;" value="" name="s" />
				</label>
				<input type="submit" class="search-submit" value="Search" />
			</form></aside>
<aside id="wpp-2" class="widget popular-posts">
<h2 class="widget-title">Most Popular</h2>
<!-- WordPress Popular Posts -->

<ul class="wpp-list">
<li>
<a href="https://programmingliftoff.com/upload-website-github-pages/" title="Upload a Website to GitHub Pages" class="wpp-post-title" target="_self">Upload a Website to GitHub Pages</a>
</li>
<li>
<a href="https://programmingliftoff.com/create-basic-webpage-css-javascript/" title="Create a Basic Webpage with CSS and JavaScript" class="wpp-post-title" target="_self">Create a Basic Webpage with CSS and JavaScript</a>
</li>
<li>
<a href="https://programmingliftoff.com/create-your-first-website-on-github-pages/" title="Create your first website on GitHub Pages" class="wpp-post-title" target="_self">Create your first website on GitHub Pages</a>
</li>
</ul>

</aside>
<aside id="categories-2" class="widget widget_categories"><h2 class="widget-title">Categories</h2>		<ul>
				<li class="cat-item cat-item-79"><a href="https://programmingliftoff.com/category/difficulty/beginner/">Beginner</a>
</li>
	<li class="cat-item cat-item-66"><a href="https://programmingliftoff.com/category/programming-languages/c/">C</a>
</li>
	<li class="cat-item cat-item-52"><a href="https://programmingliftoff.com/category/programming-languages/c-programming-languages/">C++</a>
</li>
	<li class="cat-item cat-item-76"><a href="https://programmingliftoff.com/category/programming-languages/css/">CSS</a>
</li>
	<li class="cat-item cat-item-65"><a href="https://programmingliftoff.com/category/docker/">Docker</a>
</li>
	<li class="cat-item cat-item-2"><a href="https://programmingliftoff.com/category/getting-started/">Getting Started</a>
</li>
	<li class="cat-item cat-item-70"><a href="https://programmingliftoff.com/category/version-control/github/">GitHub</a>
</li>
	<li class="cat-item cat-item-73"><a href="https://programmingliftoff.com/category/hosting/github-pages/">GitHub Pages</a>
</li>
	<li class="cat-item cat-item-74"><a href="https://programmingliftoff.com/category/hosting/gitlab-pages/">GitLab Pages</a>
</li>
	<li class="cat-item cat-item-67"><a href="https://programmingliftoff.com/category/programming-languages/go/">Go</a>
</li>
	<li class="cat-item cat-item-75"><a href="https://programmingliftoff.com/category/programming-languages/html/">HTML</a>
</li>
	<li class="cat-item cat-item-77"><a href="https://programmingliftoff.com/category/programming-languages/javascript/">JavaScript</a>
</li>
	<li class="cat-item cat-item-85"><a href="https://programmingliftoff.com/category/os/mac/">Mac</a>
</li>
	<li class="cat-item cat-item-53"><a href="https://programmingliftoff.com/category/programming-languages/python-programming-languages/">Python</a>
</li>
	<li class="cat-item cat-item-13"><a href="https://programmingliftoff.com/category/qt/">Qt</a>
</li>
	<li class="cat-item cat-item-91"><a href="https://programmingliftoff.com/category/quick-tip/">Quick Tip</a>
</li>
	<li class="cat-item cat-item-56"><a href="https://programmingliftoff.com/category/frontend-frameworks/react-frontend-frameworks/">React</a>
</li>
	<li class="cat-item cat-item-68"><a href="https://programmingliftoff.com/category/regular-expressions-regex/">Regular Expressions (Regex)</a>
</li>
	<li class="cat-item cat-item-54"><a href="https://programmingliftoff.com/category/programming-languages/ruby/">Ruby</a>
</li>
	<li class="cat-item cat-item-50"><a href="https://programmingliftoff.com/category/testing/selenium/">Selenium</a>
</li>
	<li class="cat-item cat-item-95"><a href="https://programmingliftoff.com/category/code-editors/sublime-text-3/">Sublime Text 3</a>
</li>
	<li class="cat-item cat-item-49"><a href="https://programmingliftoff.com/category/testing/">Testing</a>
</li>
	<li class="cat-item cat-item-35"><a href="https://programmingliftoff.com/category/twilio/">Twilio</a>
</li>
	<li class="cat-item cat-item-93"><a href="https://programmingliftoff.com/category/code-editors/visual-studio-code/">Visual Studio Code</a>
</li>
	<li class="cat-item cat-item-5"><a href="https://programmingliftoff.com/category/web-development/">Web Development</a>
</li>
		</ul>
			</aside><aside id="recent-comments-2" class="widget widget_recent_comments"><h2 class="widget-title">Recent Comments</h2><ul id="recentcomments"><li class="recentcomments"><span class="comment-author-link">Programming Liftoff</span> on <a href="https://programmingliftoff.com/using-docker-for-experimenting-with-code/#comment-6">Using Docker for Experimenting with Code</a></li><li class="recentcomments"><span class="comment-author-link">Paul Truzzi</span> on <a href="https://programmingliftoff.com/using-docker-for-experimenting-with-code/#comment-5">Using Docker for Experimenting with Code</a></li><li class="recentcomments"><span class="comment-author-link">Programming Liftoff</span> on <a href="https://programmingliftoff.com/using-docker-for-experimenting-with-code/#comment-4">Using Docker for Experimenting with Code</a></li><li class="recentcomments"><span class="comment-author-link">Paul Truzzi</span> on <a href="https://programmingliftoff.com/using-docker-for-experimenting-with-code/#comment-3">Using Docker for Experimenting with Code</a></li><li class="recentcomments"><span class="comment-author-link">Programming Liftoff</span> on <a href="https://programmingliftoff.com/using-docker-for-experimenting-with-code/#comment-2">Using Docker for Experimenting with Code</a></li></ul></aside></div><!-- #secondary -->
            
		</div><!--#content-inside -->
	</div><!-- #content -->

    <footer id="colophon" class="site-footer" role="contentinfo">
                        <div class="footer-connect">
            <div class="container">
                <div class="row">
                     <div class="col-md-8 offset-md-2 col-sm-12 offset-md-0">        <div class="footer-social">
            <h5 class="follow-heading">Keep Updated</h5><div class="footer-social-icons"><a target="_blank" href="https://twitter.com/programliftoff" title="Twitter"><i class="fa fa fa-twitter"></i></a><a target="_blank" href="https://www.youtube.com/programmingliftoff" title="YouTube"><i class="fa fa fa-youtube-play"></i></a><a target="_blank" href="https://www.facebook.com/programmingliftoff/" title="Facebook"><i class="fa fa fa-facebook"></i></a><a target="_blank" href="https://github.com/programming-liftoff" title="GitHub"><i class="fa fa fa-github"></i></a></div>        </div>
        </div>                </div>
            </div>
        </div>
    
        <div class="site-info">
            <div class="container">
                                    <div class="btt">
                        <a class="back-top-top" href="#page" title="Back To Top"><i class="fa fa-angle-double-up wow flash" data-wow-duration="2s"></i></a>
                    </div>
                                        Copyright &copy; 2019 Programming Liftoff        <span class="sep"> &ndash; </span>
        <a href="https://www.famethemes.com/themes/onepress">OnePress</a> theme by FameThemes                    </div>
        </div>
        <!-- .site-info -->

    </footer><!-- #colophon -->
    </div><!-- #page -->

<script type='text/javascript' src='https://programmingliftoff.com/wp-content/plugins/jetpack/_inc/build/photon/photon.min.js?ver=20190201'></script>
<script type='text/javascript'>
/* <![CDATA[ */
var ap_form_required_message = "This field is required";
var ap_captcha_error_message = "Sum is not correct.";
/* ]]> */
</script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-content/plugins/accesspress-anonymous-post/js/frontend.js?ver=2.7.6'></script>
<script type='text/javascript'>
/* <![CDATA[ */
var countVars = {"disqusShortname":"programming-liftoff"};
/* ]]> */
</script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-content/plugins/disqus-comment-system/public/js/comment_count.js?ver=3.0.17'></script>
<script type='text/javascript' src='https://s0.wp.com/wp-content/js/devicepx-jetpack.js?ver=201932'></script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-content/themes/onepress/assets/js/plugins.js?ver=2.0.2'></script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-content/themes/onepress/assets/js/bootstrap.min.js?ver=2.0.2'></script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-content/themes/onepress/assets/js/theme.js?ver=2.0.2'></script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-includes/js/wp-embed.min.js?ver=5.2.2'></script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-content/plugins/jetpack/_inc/build/spin.min.js?ver=1.3'></script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-content/plugins/jetpack/_inc/build/jquery.spin.min.js?ver=1.3'></script>
<script type='text/javascript'>
/* <![CDATA[ */
var jetpackCarouselStrings = {"widths":[370,700,1000,1200,1400,2000],"is_logged_in":"","lang":"en","ajaxurl":"https:\/\/programmingliftoff.com\/wp-admin\/admin-ajax.php","nonce":"7ebcc19c21","display_exif":"1","display_geo":"1","single_image_gallery":"1","single_image_gallery_media_file":"","background_color":"black","comment":"Comment","post_comment":"Post Comment","write_comment":"Write a Comment...","loading_comments":"Loading Comments...","download_original":"View full size <span class=\"photo-size\">{0}<span class=\"photo-size-times\">\u00d7<\/span>{1}<\/span>","no_comment_text":"Please be sure to submit some text with your comment.","no_comment_email":"Please provide an email address to comment.","no_comment_author":"Please provide your name to comment.","comment_post_error":"Sorry, but there was an error posting your comment. Please try again later.","comment_approved":"Your comment was approved.","comment_unapproved":"Your comment is in moderation.","camera":"Camera","aperture":"Aperture","shutter_speed":"Shutter Speed","focal_length":"Focal Length","copyright":"Copyright","comment_registration":"0","require_name_email":"0","login_url":"https:\/\/programmingliftoff.com\/wp-login.php?redirect_to=https%3A%2F%2Fprogrammingliftoff.com%2Fcreate-basic-webpage-css-javascript%2F","blog_id":"1","meta_data":["camera","aperture","shutter_speed","focal_length","copyright"],"local_comments_commenting_as":"<fieldset><label for=\"email\">Email<\/label> <input type=\"text\" name=\"email\" class=\"jp-carousel-comment-form-field jp-carousel-comment-form-text-field\" id=\"jp-carousel-comment-form-email-field\" \/><\/fieldset><fieldset><label for=\"author\">Name<\/label> <input type=\"text\" name=\"author\" class=\"jp-carousel-comment-form-field jp-carousel-comment-form-text-field\" id=\"jp-carousel-comment-form-author-field\" \/><\/fieldset><fieldset><label for=\"url\">Website<\/label> <input type=\"text\" name=\"url\" class=\"jp-carousel-comment-form-field jp-carousel-comment-form-text-field\" id=\"jp-carousel-comment-form-url-field\" \/><\/fieldset>"};
/* ]]> */
</script>
<script type='text/javascript' src='https://programmingliftoff.com/wp-content/plugins/jetpack/_inc/build/carousel/jetpack-carousel.min.js?ver=20190102'></script>
<script type='text/javascript' src='https://stats.wp.com/e-201932.js' async='async' defer='defer'></script>
<script type='text/javascript'>
	_stq = window._stq || [];
	_stq.push([ 'view', {v:'ext',j:'1:7.4.1',blog:'147213226',post:'37',tz:'0',srv:'programmingliftoff.com'} ]);
	_stq.push([ 'clickTrackerInit', '147213226', '37' ]);
</script>

</body>
</html>
