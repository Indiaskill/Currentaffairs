<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>

<link href='http://fonts.googleapis.com/css?family=Oswald' rel='stylesheet' type='text/css'/>

<b:include data='blog' name='all-head-content'/>

<b:if cond='data:blog.url == data:blog.homepageUrl'>


</b:if>

<!-- Start www.bloggertipandtrick.net: Changing the Blogger Title Tag  -->
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<title><data:blog.pageTitle/></title> 
<b:else/>
<title><data:blog.pageName/> ~ <data:blog.title/></title>
</b:if>
<!-- End www.bloggertipandtrick.net: Changing the Blogger Title Tag  -->

<link href='YOUR-FAVICON-URL' rel='shortcut icon' type='image/vnd.microsoft.icon'/>

    <b:skin><![CDATA[/*
-----------------------------------------------
Blogger Template Style
Name:   Learner
Author: Lasantha Bandara
URL 1:  http://www.btemplates.com/author/pbtemplates/
URL 2:  http://www.bloggertipandtrick.net/
Date:   April 2012
License:  This free Blogger template is licensed under the Creative Commons Attribution 3.0 License, which permits both personal and commercial use.
However, to satisfy the 'attribution' clause of the license, you are required to keep the footer links intact which provides due credit to its authors. For more specific details about the license, you may visit the URL below:
http://creativecommons.org/licenses/by/3.0/
----------------------------------------------- */

body#layout ul{list-style-type:none;list-style:none}
body#layout ul li{list-style-type:none;list-style:none}
body#layout #myGallery{display:none}
body#layout .featuredposts{display:none}
body#layout .fp-slider{display:none}
body#layout #navcontainer{display:none}
body#layout .menu-secondary-wrap{display:none}
body#layout .menu-secondary-container{display:none}
body#layout #skiplinks{display:none}
body#layout .feedtwitter{display:none}
body#layout #header-wrapper {margin-bottom:10px;min-height:50px;}
body#layout .social-profiles-widget h3 {display:none;}

/* Variable definitions
   ====================
   <Variable name="bgcolor" description="Page Background Color"
             type="color" default="#fff" value="#ffffff">
   <Variable name="textcolor" description="Text Color"
             type="color" default="#333" value="#333333">
   <Variable name="linkcolor" description="Link Color"
             type="color" default="#58a" value="#5588aa">
   <Variable name="pagetitlecolor" description="Blog Title Color"
             type="color" default="#666" value="#666666">
   <Variable name="descriptioncolor" description="Blog Description Color"
             type="color" default="#999" value="#999999">
   <Variable name="titlecolor" description="Post Title Color"
             type="color" default="#c60" value="#cc6600">
   <Variable name="bordercolor" description="Border Color"
             type="color" default="#ccc" value="#cccccc">
   <Variable name="sidebarcolor" description="Sidebar Title Color"
             type="color" default="#999" value="#999999">
   <Variable name="sidebartextcolor" description="Sidebar Text Color"
             type="color" default="#666" value="#666666">
   <Variable name="visitedlinkcolor" description="Visited Link Color"
             type="color" default="#999" value="#999999">
   <Variable name="bodyfont" description="Text Font"
             type="font" default="normal normal 100% Georgia, Serif" value="normal normal 100% Georgia, Serif">
   <Variable name="headerfont" description="Sidebar Title Font"
             type="font"
             default="normal normal 78% 'Trebuchet MS',Trebuchet,Arial,Verdana,Sans-serif" value="normal normal 78% 'Trebuchet MS',Trebuchet,Arial,Verdana,Sans-serif">
   <Variable name="pagetitlefont" description="Blog Title Font"
             type="font"
             default="normal normal 200% Georgia, Serif" value="normal normal 200% Georgia, Serif">
   <Variable name="descriptionfont" description="Blog Description Font"
             type="font"
             default="normal normal 78% 'Trebuchet MS', Trebuchet, Arial, Verdana, Sans-serif" value="normal normal 78% 'Trebuchet MS', Trebuchet, Arial, Verdana, Sans-serif">
   <Variable name="postfooterfont" description="Post Footer Font"
             type="font"
             default="normal normal 78% 'Trebuchet MS', Trebuchet, Arial, Verdana, Sans-serif" value="normal normal 78% 'Trebuchet MS', Trebuchet, Arial, Verdana, Sans-serif">
   <Variable name="startSide" description="Side where text starts in blog language"
             type="automatic" default="left" value="left">
   <Variable name="endSide" description="Side where text ends in blog language"
             type="automatic" default="right" value="right">
*/

/* Use this with templates/template-twocol.html */

body{background:#2D5594 url(http://1.bp.blogspot.com/-8zM4IJ9cm2U/T9lmxDhI2_I/AAAAAAAAEUc/cXF_7fvoJdk/s000/background.jpg) center top no-repeat;color:#555555;font-family: Arial, Helvetica, Sans-serif;font-size: 13px;margin:0px;padding:0px;}
a:link,a:visited{color:#2D5594;text-decoration:underline;outline:none;}
a:hover{color:#EB3839;text-decoration:none;outline:none;}
a img{border-width:0}
#body-wrapper{margin:0px;padding:0px;}
/* Header-----------------------------------------------*/
#header-wrapper{width:960px;margin:0px auto 0px;height:60px;padding:31px 0px 31px 0px;overflow:hidden;background:url(http://4.bp.blogspot.com/-a3wGXEreHW0/T9lmxqVAltI/AAAAAAAAEUk/3mx6b5tdAi8/s000/header-bg.png) center top no-repeat;}
#header-inner{background-position:center;margin-left:auto;margin-right:auto}
#header{margin:0;border:0 solid $bordercolor;color:$pagetitlecolor;float:left;width:48%;overflow:hidden;}
#header h1{color:#2D5594;text-shadow:0px 1px 0px #fff;margin:0 5px 0;padding:0px 0px 0px 15px;font-family:&#39;Oswald&#39;,Arial,Helvetica,Sans-serif;font-weight:bold;font-size:32px;line-height:32px;}
#header .description{padding-left:22px;color:#2D5594;text-shadow:0px 1px 0px #fff;line-height:14px;font-size:14px;padding-top:0px;margin-top:10px;font-family:Arial,Helvetica,Sans-serif;}
#header h1 a,#header h1 a:visited{color:#2D5594;text-decoration:none}
#header h2{padding-left:5px;color:#2D5594;font:14px Arial,Helvetica,Sans-serif}
#header2{float:right;width:51%;margin-right:0px;padding-right:0px;overflow:hidden;}
#header2 .widget{padding:0px 15px 0px 0px;float:right}
.social-profiles-widget img{margin:0 4px 0 0}
.social-profiles-widget img:hover{opacity:0.8}
#top-social-profiles{padding-top:10px;height:32px;text-align:right;float:right}
#top-social-profiles img{margin:0 6px 0 0 !important}
#top-social-profiles img:hover{opacity:0.8}
#top-social-profiles .widget-container{background:none;padding:0;border:0}
/* Outer-Wrapper----------------------------------------------- */
#outer-wrapper{width:960px;margin:0px auto 0px;padding:0px;text-align:left;}
#content-wrapper{background:#fff;padding:15px;}
#main-wrapper{width:615px;float:left;margin:0px;padding:0px 0px 0px 0px;word-wrap:break-word;overflow:hidden;text-shadow:0 1px 0 #fff;}
#rsidebar-wrapper{width:290px;float:right;margin:0px;padding:0px 0px 0px 0px;word-wrap:break-word;overflow:hidden;text-shadow:0 1px 0 #fff;}
/* Headings----------------------------------------------- */
h2{}
/* Posts-----------------------------------------------*/
h2.date-header{margin:1.5em 0 .5em;display:none;}
.wrapfullpost{}
.post{margin-bottom:15px;}
.post-title{color:#2E589B;margin:0 0 10px 0;padding:0;font-family:Arial,Helvetica,Sans-serif;font-size:24px;line-height:24px;font-weight:bold;}
.post-title a,.post-title a:visited,.post-title strong{display:block;text-decoration:none;color:#2E589B;text-decoration:none;}
.post-title strong,.post-title a:hover{color:#DA2D2F;text-decoration:none;}
.post-body{margin:0px;padding:0px 10px 0px 0px;font-family:Arial, Helvetica, Sans-serif;font-size:12px;line-height: 20px;}
.post-footer{margin:5px 0;}
.comment-link{margin-$startSide:.6em}
.post-body img{padding:6px;border:1px solid #eee;background:#ffffff;}
.postmeta-primary{color:#999;font-size:12px;line-height:18px;padding:0 0 5px 0}
.postmeta-secondary{color:#999;font-size:12px;line-height:18px;padding:0 0 10px 0}
.postmeta-primary span,.postmeta-secondary span{padding:3px 0 3px 20px;background-position:left center;background-repeat:no-repeat}
.meta_date{background-image:url(http://4.bp.blogspot.com/-V7T21hTgMbs/T9lmyGbfHvI/AAAAAAAAEUs/vFRywAoPQ1Q/s000/date.png)}
.meta_author{background-image:url(http://4.bp.blogspot.com/-haq6YlDlXL8/T9lmyQEAdZI/AAAAAAAAEUw/488q9-OqxAI/s000/author.png)}
.meta_comments{background-image:url(http://2.bp.blogspot.com/-BNjw6ysYCdE/T9lmyghVkZI/AAAAAAAAEU8/xsWB-Khv4EA/s000/comments.png)}
.meta_edit{background-image:url(images/edit.png)}
.meta_categories{background-image:url(http://4.bp.blogspot.com/-FnzfAT3H_0U/T9lmy3l5-nI/AAAAAAAAEVE/6XrU5zn4Q20/s000/category.png)}
.meta_tags{background-image:url(http://2.bp.blogspot.com/-aMnJjhZG9Lc/T9lmzFpxZoI/AAAAAAAAEVM/I43J6iF6ick/s000/tags.png)}
.readmore{margin-bottom:5px;float:right}
.readmore a{color:#fff;text-shadow:0px 1px 0px #000;background:#2D5594 url(http://3.bp.blogspot.com/-3voImxW37yE/T9lmzVoCO3I/AAAAAAAAEVU/CITdeNqv0Gk/s000/readmore-bg.png) left top repeat-x;padding:8px 14px;display:inline-block;font-size:12px;line-height:12px;text-decoration:none;text-transform:uppercase}
.readmore a:hover{color:#fff;text-shadow:0px 1px 0px #000;background:#BE1D1F url(http://3.bp.blogspot.com/-3voImxW37yE/T9lmzVoCO3I/AAAAAAAAEVU/CITdeNqv0Gk/s000/readmore-bg.png) left -126px repeat-x;text-decoration:none}
/* Sidebar Content----------------------------------------------- */
.sidebar{margin:0 0 10px 0;font-size:13px;color:#193E79;}
.sidebar a{text-decoration:none;color:#193E79;}
.sidebar a:hover{text-decoration:none;color:#CC2527;}
.sidebar h2{border-bottom:3px solid #EF4F51;margin:0 0 10px 0;padding:10px 0 4px 0;color:#2D5594;font-size:16px;line-height:16px;font-family:Arial,Helvetica,Sans-serif;font-weight:bold;text-decoration:none;text-transform:uppercase;}
.sidebar ul{list-style-type:none;list-style:none;margin:0px;padding:0px;}
.sidebar ul li{padding:0 0 9px 12px;margin:0 0 8px 0;background:url(http://4.bp.blogspot.com/-H0IMm_hr1-w/T9lmzUF5caI/AAAAAAAAEVc/yNLaywXG2zA/s000/widget-list.png) left 3px no-repeat;border-bottom:0;}
.sidebar .widget{margin:0 0 15px 0;padding:0;color:#193E79;font-size:13px;}
.main .widget{margin:0 0 5px;padding:0 0 2px}
.main .Blog{border-bottom-width:0}
/* FOOTER ----------------------------------------------- */
#footer{margin-bottom:15px;margin-top:10px}
#copyrights{color:#FFF;background:#3760A0;text-align:center;padding:20px 0;text-shadow:0 1px 0 #000;}
#copyrights a{color:#FFF}
#copyrights a:hover{color:#FFF;text-decoration:none}
#credits{color:#DAE7FB;text-align:center;font-size:11px;padding:10px 0 0 0;text-shadow:0 1px 0 #000;}
#credits a{color:#DAE7FB;text-decoration:none}
#credits a:hover{text-decoration:none;color:#DAE7FB}
.crelink {float:right;text-align:right;}
#footer-widgets{background:#FFF;padding:20px 0 0 0;border-top:4px solid #F0F9FE;text-shadow:0px 1px 0px #fff;}
.footer-widget-box{width:300px;float:left;margin-left:15px}
.footer-widget-box-last{}
#footer-widgets .widget-container{color:#193E79;}
#footer-widgets .widget-container a{text-decoration:none;color:#193E79;}
#footer-widgets .widget-container a:hover{text-decoration:none;color:#CC2527;}
#footer-widgets h2{border-bottom:3px solid #EF4F51;margin:0 0 10px 0;padding:10px 0 4px 0;color:#2D5594;font-size:16px;line-height:16px;font-family:Arial,Helvetica,Sans-serif;font-weight:bold;text-decoration:none;text-transform:uppercase;}
#footer-widgets .widget ul{list-style-type:none;list-style:none;margin:0px;padding:0px;}
#footer-widgets .widget ul li{padding:0 0 9px 12px;margin:0 0 8px 0;background:url(http://4.bp.blogspot.com/-H0IMm_hr1-w/T9lmzUF5caI/AAAAAAAAEVc/yNLaywXG2zA/s000/widget-list.png) left 3px no-repeat;border-bottom:0;}
.footersec {}
.footersec .widget{margin-bottom:20px;}
.footersec ul{}
.footersec ul li{}
/* Search ----------------------------------------------- */
#search{border:1px solid #C1D4E6;background:#FFF url(http://4.bp.blogspot.com/-P4WIo247Q3c/T9lmz31OkdI/AAAAAAAAEVk/iJuTDSvJe3w/s000/search.png) 99% 50% no-repeat;text-align:left;padding:6px 24px 6px 6px}
#search #s{background:none;color:#3669A6;border:0;width:100%;padding:0;margin:0;outline:none}
#content-search{width:300px;padding:15px 0}
/* Comments----------------------------------------------- */
#comments{padding:10px;background-color:#fff;border:0px dashed #ddd;}
#comments h4{font-size:16px;font-weight:bold;margin:1em 0;color:$sidebarcolor}
#comments-block3{padding:0;margin:0;float:left;overflow:hidden;position:relative;}
#comment-name-url{width:465px;float:left}
#comment-date{width:465px;float:left;margin-top:5px;font-size:10px;}
#comment-header{float:left;padding:5px 0 40px 10px;margin:5px 0px 15px 0px;position:relative;background-color:#fff;border:1px dashed #ddd;}
.avatar-image-container{background:url(http://4.bp.blogspot.com/-FSDRuoDW_jI/T9lm0FpuFBI/AAAAAAAAEVs/SdnvJYsgF9g/s000/comment-avatar.jpg);width:32px;height:32px;float:right;margin:5px 10px 5px 5px;border:1px solid #ddd;}
.avatar-image-container img{width:32px;height:32px;}
a.comments-autor-name{color:#000;font:normal bold 14px Arial,Tahoma,Verdana}
a.says{color:#000;font:normal 14px Arial,Tahoma,Verdana}
.says a:hover{text-decoration:none}
.deleted-comment{font-style:italic;color:gray}
#blog-pager-newer-link{float:$startSide}
#blog-pager-older-link{float:$endSide}
#blog-pager{text-align:center}
.feed-links{clear:both;line-height:2.5em}
/* Profile ----------------------------------------------- */
.profile-img{float:$startSide;margin-top:0;margin-$endSide:5px;margin-bottom:5px;margin-$startSide:0;padding:4px;border:1px solid $bordercolor}
.profile-data{margin:0;text-transform:uppercase;letter-spacing:.1em;font:$postfooterfont;color:$sidebarcolor;font-weight:bold;line-height:1.6em}
.profile-datablock{margin:.5em 0 .5em}
.profile-textblock{margin:0.5em 0;line-height:1.6em}
.avatar-image-container{background:url(http://4.bp.blogspot.com/-FSDRuoDW_jI/T9lm0FpuFBI/AAAAAAAAEVs/SdnvJYsgF9g/s000/comment-avatar.jpg);width:32px;height:32px;float:right;margin:5px 10px 5px 5px;border:1px solid #ddd;}
.avatar-image-container img{width:32px;height:32px;}
.profile-link{font:$postfooterfont;text-transform:uppercase;letter-spacing:.1em}
#navbar-iframe{height:0;visibility:hidden;display:none;}

]]></b:skin>

<script src='https://ajax.googleapis.com/ajax/libs/jquery/1.5.1/jquery.min.js' type='text/javascript'/>

<script type='text/javascript'>
//<![CDATA[

(function($){
	/* hoverIntent by Brian Cherne */
	$.fn.hoverIntent = function(f,g) {
		// default configuration options
		var cfg = {
			sensitivity: 7,
			interval: 100,
			timeout: 0
		};
		// override configuration options with user supplied object
		cfg = $.extend(cfg, g ? { over: f, out: g } : f );

		// instantiate variables
		// cX, cY = current X and Y position of mouse, updated by mousemove event
		// pX, pY = previous X and Y position of mouse, set by mouseover and polling interval
		var cX, cY, pX, pY;

		// A private function for getting mouse position
		var track = function(ev) {
			cX = ev.pageX;
			cY = ev.pageY;
		};

		// A private function for comparing current and previous mouse position
		var compare = function(ev,ob) {
			ob.hoverIntent_t = clearTimeout(ob.hoverIntent_t);
			// compare mouse positions to see if they've crossed the threshold
			if ( ( Math.abs(pX-cX) + Math.abs(pY-cY) ) < cfg.sensitivity ) {
				$(ob).unbind("mousemove",track);
				// set hoverIntent state to true (so mouseOut can be called)
				ob.hoverIntent_s = 1;
				return cfg.over.apply(ob,[ev]);
			} else {
				// set previous coordinates for next time
				pX = cX; pY = cY;
				// use self-calling timeout, guarantees intervals are spaced out properly (avoids JavaScript timer bugs)
				ob.hoverIntent_t = setTimeout( function(){compare(ev, ob);} , cfg.interval );
			}
		};

		// A private function for delaying the mouseOut function
		var delay = function(ev,ob) {
			ob.hoverIntent_t = clearTimeout(ob.hoverIntent_t);
			ob.hoverIntent_s = 0;
			return cfg.out.apply(ob,[ev]);
		};

		// A private function for handling mouse 'hovering'
		var handleHover = function(e) {
			// next three lines copied from jQuery.hover, ignore children onMouseOver/onMouseOut
			var p = (e.type == "mouseover" ? e.fromElement : e.toElement) || e.relatedTarget;
			while ( p && p != this ) { try { p = p.parentNode; } catch(e) { p = this; } }
			if ( p == this ) { return false; }

			// copy objects to be passed into t (required for event object to be passed in IE)
			var ev = jQuery.extend({},e);
			var ob = this;

			// cancel hoverIntent timer if it exists
			if (ob.hoverIntent_t) { ob.hoverIntent_t = clearTimeout(ob.hoverIntent_t); }

			// else e.type == "onmouseover"
			if (e.type == "mouseover") {
				// set "previous" X and Y position based on initial entry point
				pX = ev.pageX; pY = ev.pageY;
				// update "current" X and Y position based on mousemove
				$(ob).bind("mousemove",track);
				// start polling interval (self-calling timeout) to compare mouse coordinates over time
				if (ob.hoverIntent_s != 1) { ob.hoverIntent_t = setTimeout( function(){compare(ev,ob);} , cfg.interval );}

			// else e.type == "onmouseout"
			} else {
				// unbind expensive mousemove event
				$(ob).unbind("mousemove",track);
				// if hoverIntent state is true, then call the mouseOut function after the specified delay
				if (ob.hoverIntent_s == 1) { ob.hoverIntent_t = setTimeout( function(){delay(ev,ob);} , cfg.timeout );}
			}
		};

		// bind the function to the two event listeners
		return this.mouseover(handleHover).mouseout(handleHover);
	};
	
})(jQuery);

//]]>
</script>

<script type='text/javascript'>
//<![CDATA[

/*
 * Superfish v1.4.8 - jQuery menu widget
 * Copyright (c) 2008 Joel Birch
 *
 * Dual licensed under the MIT and GPL licenses:
 * 	http://www.opensource.org/licenses/mit-license.php
 * 	http://www.gnu.org/licenses/gpl.html
 *
 * CHANGELOG: http://users.tpg.com.au/j_birch/plugins/superfish/changelog.txt
 */

;(function($){
	$.fn.superfish = function(op){

		var sf = $.fn.superfish,
			c = sf.c,
			$arrow = $(['<span class="',c.arrowClass,'"> &#187;</span>'].join('')),
			over = function(){
				var $$ = $(this), menu = getMenu($$);
				clearTimeout(menu.sfTimer);
				$$.showSuperfishUl().siblings().hideSuperfishUl();
			},
			out = function(){
				var $$ = $(this), menu = getMenu($$), o = sf.op;
				clearTimeout(menu.sfTimer);
				menu.sfTimer=setTimeout(function(){
					o.retainPath=($.inArray($$[0],o.$path)>-1);
					$$.hideSuperfishUl();
					if (o.$path.length && $$.parents(['li.',o.hoverClass].join('')).length<1){over.call(o.$path);}
				},o.delay);	
			},
			getMenu = function($menu){
				var menu = $menu.parents(['ul.',c.menuClass,':first'].join(''))[0];
				sf.op = sf.o[menu.serial];
				return menu;
			},
			addArrow = function($a){ $a.addClass(c.anchorClass).append($arrow.clone()); };
			
		return this.each(function() {
			var s = this.serial = sf.o.length;
			var o = $.extend({},sf.defaults,op);
			o.$path = $('li.'+o.pathClass,this).slice(0,o.pathLevels).each(function(){
				$(this).addClass([o.hoverClass,c.bcClass].join(' '))
					.filter('li:has(ul)').removeClass(o.pathClass);
			});
			sf.o[s] = sf.op = o;
			
			$('li:has(ul)',this)[($.fn.hoverIntent && !o.disableHI) ? 'hoverIntent' : 'hover'](over,out).each(function() {
				if (o.autoArrows) addArrow( $('>a:first-child',this) );
			})
			.not('.'+c.bcClass)
				.hideSuperfishUl();
			
			var $a = $('a',this);
			$a.each(function(i){
				var $li = $a.eq(i).parents('li');
				$a.eq(i).focus(function(){over.call($li);}).blur(function(){out.call($li);});
			});
			o.onInit.call(this);
			
		}).each(function() {
			var menuClasses = [c.menuClass];
			if (sf.op.dropShadows  && !($.browser.msie && $.browser.version < 7)) menuClasses.push(c.shadowClass);
			$(this).addClass(menuClasses.join(' '));
		});
	};

	var sf = $.fn.superfish;
	sf.o = [];
	sf.op = {};
	sf.IE7fix = function(){
		var o = sf.op;
		if ($.browser.msie && $.browser.version > 6 && o.dropShadows && o.animation.opacity!=undefined)
			this.toggleClass(sf.c.shadowClass+'-off');
		};
	sf.c = {
		bcClass     : 'sf-breadcrumb',
		menuClass   : 'sf-js-enabled',
		anchorClass : 'sf-with-ul',
		arrowClass  : 'sf-sub-indicator',
		shadowClass : 'sf-shadow'
	};
	sf.defaults = {
		hoverClass	: 'sfHover',
		pathClass	: 'overideThisToUse',
		pathLevels	: 1,
		delay		: 800,
		animation	: {opacity:'show'},
		speed		: 'normal',
		autoArrows	: true,
		dropShadows : true,
		disableHI	: false,		// true disables hoverIntent detection
		onInit		: function(){}, // callback functions
		onBeforeShow: function(){},
		onShow		: function(){},
		onHide		: function(){}
	};
	$.fn.extend({
		hideSuperfishUl : function(){
			var o = sf.op,
				not = (o.retainPath===true) ? o.$path : '';
			o.retainPath = false;
			var $ul = $(['li.',o.hoverClass].join(''),this).add(this).not(not).removeClass(o.hoverClass)
					.find('>ul').hide().css('visibility','hidden');
			o.onHide.call($ul);
			return this;
		},
		showSuperfishUl : function(){
			var o = sf.op,
				sh = sf.c.shadowClass+'-off',
				$ul = this.addClass(o.hoverClass)
					.find('>ul:hidden').css('visibility','visible');
			sf.IE7fix.call($ul);
			o.onBeforeShow.call($ul);
			$ul.animate(o.animation,o.speed,function(){ sf.IE7fix.call($ul); o.onShow.call($ul); });
			return this;
		}
	});

})(jQuery);



//]]>
</script>

<script type='text/javascript'>
//<![CDATA[

/*
 * jQuery Cycle Plugin (with Transition Definitions)
 * Examples and documentation at: http://jquery.malsup.com/cycle/
 * Copyright (c) 2007-2010 M. Alsup
 * Version: 2.88 (08-JUN-2010)
 * Dual licensed under the MIT and GPL licenses.
 * http://jquery.malsup.com/license.html
 * Requires: jQuery v1.2.6 or later
 */
(function($){var ver="2.88";if($.support==undefined){$.support={opacity:!($.browser.msie)};}function debug(s){if($.fn.cycle.debug){log(s);}}function log(){if(window.console&&window.console.log){window.console.log("[cycle] "+Array.prototype.join.call(arguments," "));}}$.fn.cycle=function(options,arg2){var o={s:this.selector,c:this.context};if(this.length===0&&options!="stop"){if(!$.isReady&&o.s){log("DOM not ready, queuing slideshow");$(function(){$(o.s,o.c).cycle(options,arg2);});return this;}log("terminating; zero elements found by selector"+($.isReady?"":" (DOM not ready)"));return this;}return this.each(function(){var opts=handleArguments(this,options,arg2);if(opts===false){return;}opts.updateActivePagerLink=opts.updateActivePagerLink||$.fn.cycle.updateActivePagerLink;if(this.cycleTimeout){clearTimeout(this.cycleTimeout);}this.cycleTimeout=this.cyclePause=0;var $cont=$(this);var $slides=opts.slideExpr?$(opts.slideExpr,this):$cont.children();var els=$slides.get();if(els.length<2){log("terminating; too few slides: "+els.length);return;}var opts2=buildOptions($cont,$slides,els,opts,o);if(opts2===false){return;}var startTime=opts2.continuous?10:getTimeout(els[opts2.currSlide],els[opts2.nextSlide],opts2,!opts2.rev);if(startTime){startTime+=(opts2.delay||0);if(startTime<10){startTime=10;}debug("first timeout: "+startTime);this.cycleTimeout=setTimeout(function(){go(els,opts2,0,(!opts2.rev&&!opts.backwards));},startTime);}});};function handleArguments(cont,options,arg2){if(cont.cycleStop==undefined){cont.cycleStop=0;}if(options===undefined||options===null){options={};}if(options.constructor==String){switch(options){case"destroy":case"stop":var opts=$(cont).data("cycle.opts");if(!opts){return false;}cont.cycleStop++;if(cont.cycleTimeout){clearTimeout(cont.cycleTimeout);}cont.cycleTimeout=0;$(cont).removeData("cycle.opts");if(options=="destroy"){destroy(opts);}return false;case"toggle":cont.cyclePause=(cont.cyclePause===1)?0:1;checkInstantResume(cont.cyclePause,arg2,cont);return false;case"pause":cont.cyclePause=1;return false;case"resume":cont.cyclePause=0;checkInstantResume(false,arg2,cont);return false;case"prev":case"next":var opts=$(cont).data("cycle.opts");if(!opts){log('options not found, "prev/next" ignored');return false;}$.fn.cycle[options](opts);return false;default:options={fx:options};}return options;}else{if(options.constructor==Number){var num=options;options=$(cont).data("cycle.opts");if(!options){log("options not found, can not advance slide");return false;}if(num<0||num>=options.elements.length){log("invalid slide index: "+num);return false;}options.nextSlide=num;if(cont.cycleTimeout){clearTimeout(cont.cycleTimeout);cont.cycleTimeout=0;}if(typeof arg2=="string"){options.oneTimeFx=arg2;}go(options.elements,options,1,num>=options.currSlide);return false;}}return options;function checkInstantResume(isPaused,arg2,cont){if(!isPaused&&arg2===true){var options=$(cont).data("cycle.opts");if(!options){log("options not found, can not resume");return false;}if(cont.cycleTimeout){clearTimeout(cont.cycleTimeout);cont.cycleTimeout=0;}go(options.elements,options,1,(!opts.rev&&!opts.backwards));}}}function removeFilter(el,opts){if(!$.support.opacity&&opts.cleartype&&el.style.filter){try{el.style.removeAttribute("filter");}catch(smother){}}}function destroy(opts){if(opts.next){$(opts.next).unbind(opts.prevNextEvent);}if(opts.prev){$(opts.prev).unbind(opts.prevNextEvent);}if(opts.pager||opts.pagerAnchorBuilder){$.each(opts.pagerAnchors||[],function(){this.unbind().remove();});}opts.pagerAnchors=null;if(opts.destroy){opts.destroy(opts);}}function buildOptions($cont,$slides,els,options,o){var opts=$.extend({},$.fn.cycle.defaults,options||{},$.metadata?$cont.metadata():$.meta?$cont.data():{});if(opts.autostop){opts.countdown=opts.autostopCount||els.length;}var cont=$cont[0];$cont.data("cycle.opts",opts);opts.$cont=$cont;opts.stopCount=cont.cycleStop;opts.elements=els;opts.before=opts.before?[opts.before]:[];opts.after=opts.after?[opts.after]:[];opts.after.unshift(function(){opts.busy=0;});if(!$.support.opacity&&opts.cleartype){opts.after.push(function(){removeFilter(this,opts);});}if(opts.continuous){opts.after.push(function(){go(els,opts,0,(!opts.rev&&!opts.backwards));});}saveOriginalOpts(opts);if(!$.support.opacity&&opts.cleartype&&!opts.cleartypeNoBg){clearTypeFix($slides);}if($cont.css("position")=="static"){$cont.css("position","relative");}if(opts.width){$cont.width(opts.width);}if(opts.height&&opts.height!="auto"){$cont.height(opts.height);}if(opts.startingSlide){opts.startingSlide=parseInt(opts.startingSlide);}else{if(opts.backwards){opts.startingSlide=els.length-1;}}if(opts.random){opts.randomMap=[];for(var i=0;i<els.length;i++){opts.randomMap.push(i);}opts.randomMap.sort(function(a,b){return Math.random()-0.5;});opts.randomIndex=1;opts.startingSlide=opts.randomMap[1];}else{if(opts.startingSlide>=els.length){opts.startingSlide=0;}}opts.currSlide=opts.startingSlide||0;var first=opts.startingSlide;$slides.css({position:"absolute",top:0,left:0}).hide().each(function(i){var z;if(opts.backwards){z=first?i<=first?els.length+(i-first):first-i:els.length-i;}else{z=first?i>=first?els.length-(i-first):first-i:els.length-i;}$(this).css("z-index",z);});$(els[first]).css("opacity",1).show();removeFilter(els[first],opts);if(opts.fit&&opts.width){$slides.width(opts.width);}if(opts.fit&&opts.height&&opts.height!="auto"){$slides.height(opts.height);}var reshape=opts.containerResize&&!$cont.innerHeight();if(reshape){var maxw=0,maxh=0;for(var j=0;j<els.length;j++){var $e=$(els[j]),e=$e[0],w=$e.outerWidth(),h=$e.outerHeight();if(!w){w=e.offsetWidth||e.width||$e.attr("width");}if(!h){h=e.offsetHeight||e.height||$e.attr("height");}maxw=w>maxw?w:maxw;maxh=h>maxh?h:maxh;}if(maxw>0&&maxh>0){$cont.css({width:maxw+"px",height:maxh+"px"});}}if(opts.pause){$cont.hover(function(){this.cyclePause++;},function(){this.cyclePause--;});}if(supportMultiTransitions(opts)===false){return false;}var requeue=false;options.requeueAttempts=options.requeueAttempts||0;$slides.each(function(){var $el=$(this);this.cycleH=(opts.fit&&opts.height)?opts.height:($el.height()||this.offsetHeight||this.height||$el.attr("height")||0);this.cycleW=(opts.fit&&opts.width)?opts.width:($el.width()||this.offsetWidth||this.width||$el.attr("width")||0);if($el.is("img")){var loadingIE=($.browser.msie&&this.cycleW==28&&this.cycleH==30&&!this.complete);var loadingFF=($.browser.mozilla&&this.cycleW==34&&this.cycleH==19&&!this.complete);var loadingOp=($.browser.opera&&((this.cycleW==42&&this.cycleH==19)||(this.cycleW==37&&this.cycleH==17))&&!this.complete);var loadingOther=(this.cycleH==0&&this.cycleW==0&&!this.complete);if(loadingIE||loadingFF||loadingOp||loadingOther){if(o.s&&opts.requeueOnImageNotLoaded&&++options.requeueAttempts<100){log(options.requeueAttempts," - img slide not loaded, requeuing slideshow: ",this.src,this.cycleW,this.cycleH);setTimeout(function(){$(o.s,o.c).cycle(options);},opts.requeueTimeout);requeue=true;return false;}else{log("could not determine size of image: "+this.src,this.cycleW,this.cycleH);}}}return true;});if(requeue){return false;}opts.cssBefore=opts.cssBefore||{};opts.animIn=opts.animIn||{};opts.animOut=opts.animOut||{};$slides.not(":eq("+first+")").css(opts.cssBefore);if(opts.cssFirst){$($slides[first]).css(opts.cssFirst);}if(opts.timeout){opts.timeout=parseInt(opts.timeout);if(opts.speed.constructor==String){opts.speed=$.fx.speeds[opts.speed]||parseInt(opts.speed);}if(!opts.sync){opts.speed=opts.speed/2;}var buffer=opts.fx=="shuffle"?500:250;while((opts.timeout-opts.speed)<buffer){opts.timeout+=opts.speed;}}if(opts.easing){opts.easeIn=opts.easeOut=opts.easing;}if(!opts.speedIn){opts.speedIn=opts.speed;}if(!opts.speedOut){opts.speedOut=opts.speed;}opts.slideCount=els.length;opts.currSlide=opts.lastSlide=first;if(opts.random){if(++opts.randomIndex==els.length){opts.randomIndex=0;}opts.nextSlide=opts.randomMap[opts.randomIndex];}else{if(opts.backwards){opts.nextSlide=opts.startingSlide==0?(els.length-1):opts.startingSlide-1;}else{opts.nextSlide=opts.startingSlide>=(els.length-1)?0:opts.startingSlide+1;}}if(!opts.multiFx){var init=$.fn.cycle.transitions[opts.fx];if($.isFunction(init)){init($cont,$slides,opts);}else{if(opts.fx!="custom"&&!opts.multiFx){log("unknown transition: "+opts.fx,"; slideshow terminating");return false;}}}var e0=$slides[first];if(opts.before.length){opts.before[0].apply(e0,[e0,e0,opts,true]);}if(opts.after.length>1){opts.after[1].apply(e0,[e0,e0,opts,true]);}if(opts.next){$(opts.next).bind(opts.prevNextEvent,function(){return advance(opts,opts.rev?-1:1);});}if(opts.prev){$(opts.prev).bind(opts.prevNextEvent,function(){return advance(opts,opts.rev?1:-1);});}if(opts.pager||opts.pagerAnchorBuilder){buildPager(els,opts);}exposeAddSlide(opts,els);return opts;}function saveOriginalOpts(opts){opts.original={before:[],after:[]};opts.original.cssBefore=$.extend({},opts.cssBefore);opts.original.cssAfter=$.extend({},opts.cssAfter);opts.original.animIn=$.extend({},opts.animIn);opts.original.animOut=$.extend({},opts.animOut);$.each(opts.before,function(){opts.original.before.push(this);});$.each(opts.after,function(){opts.original.after.push(this);});}function supportMultiTransitions(opts){var i,tx,txs=$.fn.cycle.transitions;if(opts.fx.indexOf(",")>0){opts.multiFx=true;opts.fxs=opts.fx.replace(/\s*/g,"").split(",");for(i=0;i<opts.fxs.length;i++){var fx=opts.fxs[i];tx=txs[fx];if(!tx||!txs.hasOwnProperty(fx)||!$.isFunction(tx)){log("discarding unknown transition: ",fx);opts.fxs.splice(i,1);i--;}}if(!opts.fxs.length){log("No valid transitions named; slideshow terminating.");return false;}}else{if(opts.fx=="all"){opts.multiFx=true;opts.fxs=[];for(p in txs){tx=txs[p];if(txs.hasOwnProperty(p)&&$.isFunction(tx)){opts.fxs.push(p);}}}}if(opts.multiFx&&opts.randomizeEffects){var r1=Math.floor(Math.random()*20)+30;for(i=0;i<r1;i++){var r2=Math.floor(Math.random()*opts.fxs.length);opts.fxs.push(opts.fxs.splice(r2,1)[0]);}debug("randomized fx sequence: ",opts.fxs);}return true;}function exposeAddSlide(opts,els){opts.addSlide=function(newSlide,prepend){var $s=$(newSlide),s=$s[0];if(!opts.autostopCount){opts.countdown++;}els[prepend?"unshift":"push"](s);if(opts.els){opts.els[prepend?"unshift":"push"](s);}opts.slideCount=els.length;$s.css("position","absolute");$s[prepend?"prependTo":"appendTo"](opts.$cont);if(prepend){opts.currSlide++;opts.nextSlide++;}if(!$.support.opacity&&opts.cleartype&&!opts.cleartypeNoBg){clearTypeFix($s);}if(opts.fit&&opts.width){$s.width(opts.width);}if(opts.fit&&opts.height&&opts.height!="auto"){$slides.height(opts.height);}s.cycleH=(opts.fit&&opts.height)?opts.height:$s.height();s.cycleW=(opts.fit&&opts.width)?opts.width:$s.width();$s.css(opts.cssBefore);if(opts.pager||opts.pagerAnchorBuilder){$.fn.cycle.createPagerAnchor(els.length-1,s,$(opts.pager),els,opts);}if($.isFunction(opts.onAddSlide)){opts.onAddSlide($s);}else{$s.hide();}};}$.fn.cycle.resetState=function(opts,fx){fx=fx||opts.fx;opts.before=[];opts.after=[];opts.cssBefore=$.extend({},opts.original.cssBefore);opts.cssAfter=$.extend({},opts.original.cssAfter);opts.animIn=$.extend({},opts.original.animIn);opts.animOut=$.extend({},opts.original.animOut);opts.fxFn=null;$.each(opts.original.before,function(){opts.before.push(this);});$.each(opts.original.after,function(){opts.after.push(this);});var init=$.fn.cycle.transitions[fx];if($.isFunction(init)){init(opts.$cont,$(opts.elements),opts);}};function go(els,opts,manual,fwd){if(manual&&opts.busy&&opts.manualTrump){debug("manualTrump in go(), stopping active transition");$(els).stop(true,true);opts.busy=false;}if(opts.busy){debug("transition active, ignoring new tx request");return;}var p=opts.$cont[0],curr=els[opts.currSlide],next=els[opts.nextSlide];if(p.cycleStop!=opts.stopCount||p.cycleTimeout===0&&!manual){return;}if(!manual&&!p.cyclePause&&!opts.bounce&&((opts.autostop&&(--opts.countdown<=0))||(opts.nowrap&&!opts.random&&opts.nextSlide<opts.currSlide))){if(opts.end){opts.end(opts);}return;}var changed=false;if((manual||!p.cyclePause)&&(opts.nextSlide!=opts.currSlide)){changed=true;var fx=opts.fx;curr.cycleH=curr.cycleH||$(curr).height();curr.cycleW=curr.cycleW||$(curr).width();next.cycleH=next.cycleH||$(next).height();next.cycleW=next.cycleW||$(next).width();if(opts.multiFx){if(opts.lastFx==undefined||++opts.lastFx>=opts.fxs.length){opts.lastFx=0;}fx=opts.fxs[opts.lastFx];opts.currFx=fx;}if(opts.oneTimeFx){fx=opts.oneTimeFx;opts.oneTimeFx=null;}$.fn.cycle.resetState(opts,fx);if(opts.before.length){$.each(opts.before,function(i,o){if(p.cycleStop!=opts.stopCount){return;}o.apply(next,[curr,next,opts,fwd]);});}var after=function(){$.each(opts.after,function(i,o){if(p.cycleStop!=opts.stopCount){return;}o.apply(next,[curr,next,opts,fwd]);});};debug("tx firing; currSlide: "+opts.currSlide+"; nextSlide: "+opts.nextSlide);opts.busy=1;if(opts.fxFn){opts.fxFn(curr,next,opts,after,fwd,manual&&opts.fastOnEvent);}else{if($.isFunction($.fn.cycle[opts.fx])){$.fn.cycle[opts.fx](curr,next,opts,after,fwd,manual&&opts.fastOnEvent);}else{$.fn.cycle.custom(curr,next,opts,after,fwd,manual&&opts.fastOnEvent);}}}if(changed||opts.nextSlide==opts.currSlide){opts.lastSlide=opts.currSlide;if(opts.random){opts.currSlide=opts.nextSlide;if(++opts.randomIndex==els.length){opts.randomIndex=0;}opts.nextSlide=opts.randomMap[opts.randomIndex];if(opts.nextSlide==opts.currSlide){opts.nextSlide=(opts.currSlide==opts.slideCount-1)?0:opts.currSlide+1;}}else{if(opts.backwards){var roll=(opts.nextSlide-1)<0;if(roll&&opts.bounce){opts.backwards=!opts.backwards;opts.nextSlide=1;opts.currSlide=0;}else{opts.nextSlide=roll?(els.length-1):opts.nextSlide-1;opts.currSlide=roll?0:opts.nextSlide+1;}}else{var roll=(opts.nextSlide+1)==els.length;if(roll&&opts.bounce){opts.backwards=!opts.backwards;opts.nextSlide=els.length-2;opts.currSlide=els.length-1;}else{opts.nextSlide=roll?0:opts.nextSlide+1;opts.currSlide=roll?els.length-1:opts.nextSlide-1;}}}}if(changed&&opts.pager){opts.updateActivePagerLink(opts.pager,opts.currSlide,opts.activePagerClass);}var ms=0;if(opts.timeout&&!opts.continuous){ms=getTimeout(els[opts.currSlide],els[opts.nextSlide],opts,fwd);}else{if(opts.continuous&&p.cyclePause){ms=10;}}if(ms>0){p.cycleTimeout=setTimeout(function(){go(els,opts,0,(!opts.rev&&!opts.backwards));},ms);}}$.fn.cycle.updateActivePagerLink=function(pager,currSlide,clsName){$(pager).each(function(){$(this).children().removeClass(clsName).eq(currSlide).addClass(clsName);});};function getTimeout(curr,next,opts,fwd){if(opts.timeoutFn){var t=opts.timeoutFn.call(curr,curr,next,opts,fwd);while((t-opts.speed)<250){t+=opts.speed;}debug("calculated timeout: "+t+"; speed: "+opts.speed);if(t!==false){return t;}}return opts.timeout;}$.fn.cycle.next=function(opts){advance(opts,opts.rev?-1:1);};$.fn.cycle.prev=function(opts){advance(opts,opts.rev?1:-1);};function advance(opts,val){var els=opts.elements;var p=opts.$cont[0],timeout=p.cycleTimeout;if(timeout){clearTimeout(timeout);p.cycleTimeout=0;}if(opts.random&&val<0){opts.randomIndex--;if(--opts.randomIndex==-2){opts.randomIndex=els.length-2;}else{if(opts.randomIndex==-1){opts.randomIndex=els.length-1;}}opts.nextSlide=opts.randomMap[opts.randomIndex];}else{if(opts.random){opts.nextSlide=opts.randomMap[opts.randomIndex];}else{opts.nextSlide=opts.currSlide+val;if(opts.nextSlide<0){if(opts.nowrap){return false;}opts.nextSlide=els.length-1;}else{if(opts.nextSlide>=els.length){if(opts.nowrap){return false;}opts.nextSlide=0;}}}}var cb=opts.onPrevNextEvent||opts.prevNextClick;if($.isFunction(cb)){cb(val>0,opts.nextSlide,els[opts.nextSlide]);}go(els,opts,1,val>=0);return false;}function buildPager(els,opts){var $p=$(opts.pager);$.each(els,function(i,o){$.fn.cycle.createPagerAnchor(i,o,$p,els,opts);});opts.updateActivePagerLink(opts.pager,opts.startingSlide,opts.activePagerClass);}$.fn.cycle.createPagerAnchor=function(i,el,$p,els,opts){var a;if($.isFunction(opts.pagerAnchorBuilder)){a=opts.pagerAnchorBuilder(i,el);debug("pagerAnchorBuilder("+i+", el) returned: "+a);}else{a='<a href="#">'+(i+1)+"</a>";}if(!a){return;}var $a=$(a);if($a.parents("body").length===0){var arr=[];if($p.length>1){$p.each(function(){var $clone=$a.clone(true);$(this).append($clone);arr.push($clone[0]);});$a=$(arr);}else{$a.appendTo($p);}}opts.pagerAnchors=opts.pagerAnchors||[];opts.pagerAnchors.push($a);$a.bind(opts.pagerEvent,function(e){e.preventDefault();opts.nextSlide=i;var p=opts.$cont[0],timeout=p.cycleTimeout;if(timeout){clearTimeout(timeout);p.cycleTimeout=0;}var cb=opts.onPagerEvent||opts.pagerClick;if($.isFunction(cb)){cb(opts.nextSlide,els[opts.nextSlide]);}go(els,opts,1,opts.currSlide<i);});if(!/^click/.test(opts.pagerEvent)&&!opts.allowPagerClickBubble){$a.bind("click.cycle",function(){return false;});}if(opts.pauseOnPagerHover){$a.hover(function(){opts.$cont[0].cyclePause++;},function(){opts.$cont[0].cyclePause--;});}};$.fn.cycle.hopsFromLast=function(opts,fwd){var hops,l=opts.lastSlide,c=opts.currSlide;if(fwd){hops=c>l?c-l:opts.slideCount-l;}else{hops=c<l?l-c:l+opts.slideCount-c;}return hops;};function clearTypeFix($slides){debug("applying clearType background-color hack");function hex(s){s=parseInt(s).toString(16);return s.length<2?"0"+s:s;}function getBg(e){for(;e&&e.nodeName.toLowerCase()!="html";e=e.parentNode){var v=$.css(e,"background-color");if(v.indexOf("rgb")>=0){var rgb=v.match(/\d+/g);return"#"+hex(rgb[0])+hex(rgb[1])+hex(rgb[2]);}if(v&&v!="transparent"){return v;}}return"#ffffff";}$slides.each(function(){$(this).css("background-color",getBg(this));});}$.fn.cycle.commonReset=function(curr,next,opts,w,h,rev){$(opts.elements).not(curr).hide();opts.cssBefore.opacity=1;opts.cssBefore.display="block";if(w!==false&&next.cycleW>0){opts.cssBefore.width=next.cycleW;}if(h!==false&&next.cycleH>0){opts.cssBefore.height=next.cycleH;}opts.cssAfter=opts.cssAfter||{};opts.cssAfter.display="none";$(curr).css("zIndex",opts.slideCount+(rev===true?1:0));$(next).css("zIndex",opts.slideCount+(rev===true?0:1));};$.fn.cycle.custom=function(curr,next,opts,cb,fwd,speedOverride){var $l=$(curr),$n=$(next);var speedIn=opts.speedIn,speedOut=opts.speedOut,easeIn=opts.easeIn,easeOut=opts.easeOut;$n.css(opts.cssBefore);if(speedOverride){if(typeof speedOverride=="number"){speedIn=speedOut=speedOverride;}else{speedIn=speedOut=1;}easeIn=easeOut=null;}var fn=function(){$n.animate(opts.animIn,speedIn,easeIn,cb);};$l.animate(opts.animOut,speedOut,easeOut,function(){if(opts.cssAfter){$l.css(opts.cssAfter);}if(!opts.sync){fn();}});if(opts.sync){fn();}};$.fn.cycle.transitions={fade:function($cont,$slides,opts){$slides.not(":eq("+opts.currSlide+")").css("opacity",0);opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts);opts.cssBefore.opacity=0;});opts.animIn={opacity:1};opts.animOut={opacity:0};opts.cssBefore={top:0,left:0};}};$.fn.cycle.ver=function(){return ver;};$.fn.cycle.defaults={fx:"fade",timeout:4000,timeoutFn:null,continuous:0,speed:1000,speedIn:null,speedOut:null,next:null,prev:null,onPrevNextEvent:null,prevNextEvent:"click.cycle",pager:null,onPagerEvent:null,pagerEvent:"click.cycle",allowPagerClickBubble:false,pagerAnchorBuilder:null,before:null,after:null,end:null,easing:null,easeIn:null,easeOut:null,shuffle:null,animIn:null,animOut:null,cssBefore:null,cssAfter:null,fxFn:null,height:"auto",startingSlide:0,sync:1,random:0,fit:0,containerResize:1,pause:0,pauseOnPagerHover:0,autostop:0,autostopCount:0,delay:0,slideExpr:null,cleartype:!$.support.opacity,cleartypeNoBg:false,nowrap:0,fastOnEvent:0,randomizeEffects:1,rev:0,manualTrump:true,requeueOnImageNotLoaded:true,requeueTimeout:250,activePagerClass:"activeSlide",updateActivePagerLink:null,backwards:false};})(jQuery);
/*
 * jQuery Cycle Plugin Transition Definitions
 * This script is a plugin for the jQuery Cycle Plugin
 * Examples and documentation at: http://malsup.com/jquery/cycle/
 * Copyright (c) 2007-2010 M. Alsup
 * Version:	 2.72
 * Dual licensed under the MIT and GPL licenses:
 * http://www.opensource.org/licenses/mit-license.php
 * http://www.gnu.org/licenses/gpl.html
 */
(function($){$.fn.cycle.transitions.none=function($cont,$slides,opts){opts.fxFn=function(curr,next,opts,after){$(next).show();$(curr).hide();after();};};$.fn.cycle.transitions.scrollUp=function($cont,$slides,opts){$cont.css("overflow","hidden");opts.before.push($.fn.cycle.commonReset);var h=$cont.height();opts.cssBefore={top:h,left:0};opts.cssFirst={top:0};opts.animIn={top:0};opts.animOut={top:-h};};$.fn.cycle.transitions.scrollDown=function($cont,$slides,opts){$cont.css("overflow","hidden");opts.before.push($.fn.cycle.commonReset);var h=$cont.height();opts.cssFirst={top:0};opts.cssBefore={top:-h,left:0};opts.animIn={top:0};opts.animOut={top:h};};$.fn.cycle.transitions.scrollLeft=function($cont,$slides,opts){$cont.css("overflow","hidden");opts.before.push($.fn.cycle.commonReset);var w=$cont.width();opts.cssFirst={left:0};opts.cssBefore={left:w,top:0};opts.animIn={left:0};opts.animOut={left:0-w};};$.fn.cycle.transitions.scrollRight=function($cont,$slides,opts){$cont.css("overflow","hidden");opts.before.push($.fn.cycle.commonReset);var w=$cont.width();opts.cssFirst={left:0};opts.cssBefore={left:-w,top:0};opts.animIn={left:0};opts.animOut={left:w};};$.fn.cycle.transitions.scrollHorz=function($cont,$slides,opts){$cont.css("overflow","hidden").width();opts.before.push(function(curr,next,opts,fwd){$.fn.cycle.commonReset(curr,next,opts);opts.cssBefore.left=fwd?(next.cycleW-1):(1-next.cycleW);opts.animOut.left=fwd?-curr.cycleW:curr.cycleW;});opts.cssFirst={left:0};opts.cssBefore={top:0};opts.animIn={left:0};opts.animOut={top:0};};$.fn.cycle.transitions.scrollVert=function($cont,$slides,opts){$cont.css("overflow","hidden");opts.before.push(function(curr,next,opts,fwd){$.fn.cycle.commonReset(curr,next,opts);opts.cssBefore.top=fwd?(1-next.cycleH):(next.cycleH-1);opts.animOut.top=fwd?curr.cycleH:-curr.cycleH;});opts.cssFirst={top:0};opts.cssBefore={left:0};opts.animIn={top:0};opts.animOut={left:0};};$.fn.cycle.transitions.slideX=function($cont,$slides,opts){opts.before.push(function(curr,next,opts){$(opts.elements).not(curr).hide();$.fn.cycle.commonReset(curr,next,opts,false,true);opts.animIn.width=next.cycleW;});opts.cssBefore={left:0,top:0,width:0};opts.animIn={width:"show"};opts.animOut={width:0};};$.fn.cycle.transitions.slideY=function($cont,$slides,opts){opts.before.push(function(curr,next,opts){$(opts.elements).not(curr).hide();$.fn.cycle.commonReset(curr,next,opts,true,false);opts.animIn.height=next.cycleH;});opts.cssBefore={left:0,top:0,height:0};opts.animIn={height:"show"};opts.animOut={height:0};};$.fn.cycle.transitions.shuffle=function($cont,$slides,opts){var i,w=$cont.css("overflow","visible").width();$slides.css({left:0,top:0});opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,true,true,true);});if(!opts.speedAdjusted){opts.speed=opts.speed/2;opts.speedAdjusted=true;}opts.random=0;opts.shuffle=opts.shuffle||{left:-w,top:15};opts.els=[];for(i=0;i<$slides.length;i++){opts.els.push($slides[i]);}for(i=0;i<opts.currSlide;i++){opts.els.push(opts.els.shift());}opts.fxFn=function(curr,next,opts,cb,fwd){var $el=fwd?$(curr):$(next);$(next).css(opts.cssBefore);var count=opts.slideCount;$el.animate(opts.shuffle,opts.speedIn,opts.easeIn,function(){var hops=$.fn.cycle.hopsFromLast(opts,fwd);for(var k=0;k<hops;k++){fwd?opts.els.push(opts.els.shift()):opts.els.unshift(opts.els.pop());}if(fwd){for(var i=0,len=opts.els.length;i<len;i++){$(opts.els[i]).css("z-index",len-i+count);}}else{var z=$(curr).css("z-index");$el.css("z-index",parseInt(z)+1+count);}$el.animate({left:0,top:0},opts.speedOut,opts.easeOut,function(){$(fwd?this:curr).hide();if(cb){cb();}});});};opts.cssBefore={display:"block",opacity:1,top:0,left:0};};$.fn.cycle.transitions.turnUp=function($cont,$slides,opts){opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,true,false);opts.cssBefore.top=next.cycleH;opts.animIn.height=next.cycleH;});opts.cssFirst={top:0};opts.cssBefore={left:0,height:0};opts.animIn={top:0};opts.animOut={height:0};};$.fn.cycle.transitions.turnDown=function($cont,$slides,opts){opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,true,false);opts.animIn.height=next.cycleH;opts.animOut.top=curr.cycleH;});opts.cssFirst={top:0};opts.cssBefore={left:0,top:0,height:0};opts.animOut={height:0};};$.fn.cycle.transitions.turnLeft=function($cont,$slides,opts){opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,false,true);opts.cssBefore.left=next.cycleW;opts.animIn.width=next.cycleW;});opts.cssBefore={top:0,width:0};opts.animIn={left:0};opts.animOut={width:0};};$.fn.cycle.transitions.turnRight=function($cont,$slides,opts){opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,false,true);opts.animIn.width=next.cycleW;opts.animOut.left=curr.cycleW;});opts.cssBefore={top:0,left:0,width:0};opts.animIn={left:0};opts.animOut={width:0};};$.fn.cycle.transitions.zoom=function($cont,$slides,opts){opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,false,false,true);opts.cssBefore.top=next.cycleH/2;opts.cssBefore.left=next.cycleW/2;opts.animIn={top:0,left:0,width:next.cycleW,height:next.cycleH};opts.animOut={width:0,height:0,top:curr.cycleH/2,left:curr.cycleW/2};});opts.cssFirst={top:0,left:0};opts.cssBefore={width:0,height:0};};$.fn.cycle.transitions.fadeZoom=function($cont,$slides,opts){opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,false,false);opts.cssBefore.left=next.cycleW/2;opts.cssBefore.top=next.cycleH/2;opts.animIn={top:0,left:0,width:next.cycleW,height:next.cycleH};});opts.cssBefore={width:0,height:0};opts.animOut={opacity:0};};$.fn.cycle.transitions.blindX=function($cont,$slides,opts){var w=$cont.css("overflow","hidden").width();opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts);opts.animIn.width=next.cycleW;opts.animOut.left=curr.cycleW;});opts.cssBefore={left:w,top:0};opts.animIn={left:0};opts.animOut={left:w};};$.fn.cycle.transitions.blindY=function($cont,$slides,opts){var h=$cont.css("overflow","hidden").height();opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts);opts.animIn.height=next.cycleH;opts.animOut.top=curr.cycleH;});opts.cssBefore={top:h,left:0};opts.animIn={top:0};opts.animOut={top:h};};$.fn.cycle.transitions.blindZ=function($cont,$slides,opts){var h=$cont.css("overflow","hidden").height();var w=$cont.width();opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts);opts.animIn.height=next.cycleH;opts.animOut.top=curr.cycleH;});opts.cssBefore={top:h,left:w};opts.animIn={top:0,left:0};opts.animOut={top:h,left:w};};$.fn.cycle.transitions.growX=function($cont,$slides,opts){opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,false,true);opts.cssBefore.left=this.cycleW/2;opts.animIn={left:0,width:this.cycleW};opts.animOut={left:0};});opts.cssBefore={width:0,top:0};};$.fn.cycle.transitions.growY=function($cont,$slides,opts){opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,true,false);opts.cssBefore.top=this.cycleH/2;opts.animIn={top:0,height:this.cycleH};opts.animOut={top:0};});opts.cssBefore={height:0,left:0};};$.fn.cycle.transitions.curtainX=function($cont,$slides,opts){opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,false,true,true);opts.cssBefore.left=next.cycleW/2;opts.animIn={left:0,width:this.cycleW};opts.animOut={left:curr.cycleW/2,width:0};});opts.cssBefore={top:0,width:0};};$.fn.cycle.transitions.curtainY=function($cont,$slides,opts){opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,true,false,true);opts.cssBefore.top=next.cycleH/2;opts.animIn={top:0,height:next.cycleH};opts.animOut={top:curr.cycleH/2,height:0};});opts.cssBefore={left:0,height:0};};$.fn.cycle.transitions.cover=function($cont,$slides,opts){var d=opts.direction||"left";var w=$cont.css("overflow","hidden").width();var h=$cont.height();opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts);if(d=="right"){opts.cssBefore.left=-w;}else{if(d=="up"){opts.cssBefore.top=h;}else{if(d=="down"){opts.cssBefore.top=-h;}else{opts.cssBefore.left=w;}}}});opts.animIn={left:0,top:0};opts.animOut={opacity:1};opts.cssBefore={top:0,left:0};};$.fn.cycle.transitions.uncover=function($cont,$slides,opts){var d=opts.direction||"left";var w=$cont.css("overflow","hidden").width();var h=$cont.height();opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,true,true,true);if(d=="right"){opts.animOut.left=w;}else{if(d=="up"){opts.animOut.top=-h;}else{if(d=="down"){opts.animOut.top=h;}else{opts.animOut.left=-w;}}}});opts.animIn={left:0,top:0};opts.animOut={opacity:1};opts.cssBefore={top:0,left:0};};$.fn.cycle.transitions.toss=function($cont,$slides,opts){var w=$cont.css("overflow","visible").width();var h=$cont.height();opts.before.push(function(curr,next,opts){$.fn.cycle.commonReset(curr,next,opts,true,true,true);if(!opts.animOut.left&&!opts.animOut.top){opts.animOut={left:w*2,top:-h/2,opacity:0};}else{opts.animOut.opacity=0;}});opts.cssBefore={left:0,top:0};opts.animIn={left:0};};$.fn.cycle.transitions.wipe=function($cont,$slides,opts){var w=$cont.css("overflow","hidden").width();var h=$cont.height();opts.cssBefore=opts.cssBefore||{};var clip;if(opts.clip){if(/l2r/.test(opts.clip)){clip="rect(0px 0px "+h+"px 0px)";}else{if(/r2l/.test(opts.clip)){clip="rect(0px "+w+"px "+h+"px "+w+"px)";}else{if(/t2b/.test(opts.clip)){clip="rect(0px "+w+"px 0px 0px)";}else{if(/b2t/.test(opts.clip)){clip="rect("+h+"px "+w+"px "+h+"px 0px)";}else{if(/zoom/.test(opts.clip)){var top=parseInt(h/2);var left=parseInt(w/2);clip="rect("+top+"px "+left+"px "+top+"px "+left+"px)";}}}}}}opts.cssBefore.clip=opts.cssBefore.clip||clip||"rect(0px 0px 0px 0px)";var d=opts.cssBefore.clip.match(/(\d+)/g);var t=parseInt(d[0]),r=parseInt(d[1]),b=parseInt(d[2]),l=parseInt(d[3]);opts.before.push(function(curr,next,opts){if(curr==next){return;}var $curr=$(curr),$next=$(next);$.fn.cycle.commonReset(curr,next,opts,true,true,false);opts.cssAfter.display="block";var step=1,count=parseInt((opts.speedIn/13))-1;(function f(){var tt=t?t-parseInt(step*(t/count)):0;var ll=l?l-parseInt(step*(l/count)):0;var bb=b<h?b+parseInt(step*((h-b)/count||1)):h;var rr=r<w?r+parseInt(step*((w-r)/count||1)):w;$next.css({clip:"rect("+tt+"px "+rr+"px "+bb+"px "+ll+"px)"});(step++<=count)?setTimeout(f,13):$curr.css("display","none");})();});opts.cssBefore={display:"block",opacity:1,top:0,left:0};opts.animIn={left:0};opts.animOut={left:0};};})(jQuery);

//]]>
</script>

<script type='text/javascript'>
/* <![CDATA[ */
jQuery.noConflict();
jQuery(function(){ 
	jQuery('ul.menu-primary').superfish({ 
	animation: {opacity:'show'},
autoArrows:  true,
                dropShadows: false, 
                speed: 200,
                delay: 800
                });
            });

jQuery(function(){ 
	jQuery('ul.menu-secondary').superfish({ 
	animation: {opacity:'show'},
autoArrows:  true,
                dropShadows: false, 
                speed: 200,
                delay: 800
                });
            });

jQuery(document).ready(function() {
	jQuery('.fp-slides').cycle({
		fx: 'scrollHorz',
		timeout: 4000,
		delay: 0,
		speed: 400,
		next: '.fp-next',
		prev: '.fp-prev',
		pager: '.fp-pager',
		continuous: 0,
		sync: 1,
		pause: 1,
		pauseOnPagerHover: 1,
		cleartype: true,
		cleartypeNoBg: true
	});
 });

/* ]]> */

</script>

<script type='text/javascript'>
//<![CDATA[

function showrecentcomments(json){for(var i=0;i<a_rc;i++){var b_rc=json.feed.entry[i];var c_rc;if(i==json.feed.entry.length)break;for(var k=0;k<b_rc.link.length;k++){if(b_rc.link[k].rel=='alternate'){c_rc=b_rc.link[k].href;break;}}c_rc=c_rc.replace("#","#comment-");var d_rc=c_rc.split("#");d_rc=d_rc[0];var e_rc=d_rc.split("/");e_rc=e_rc[5];e_rc=e_rc.split(".html");e_rc=e_rc[0];var f_rc=e_rc.replace(/-/g," ");f_rc=f_rc.link(d_rc);var g_rc=b_rc.published.$t;var h_rc=g_rc.substring(0,4);var i_rc=g_rc.substring(5,7);var j_rc=g_rc.substring(8,10);var k_rc=new Array();k_rc[1]="Jan";k_rc[2]="Feb";k_rc[3]="Mar";k_rc[4]="Apr";k_rc[5]="May";k_rc[6]="Jun";k_rc[7]="Jul";k_rc[8]="Aug";k_rc[9]="Sep";k_rc[10]="Oct";k_rc[11]="Nov";k_rc[12]="Dec";if("content" in b_rc){var l_rc=b_rc.content.$t;}else if("summary" in b_rc){var l_rc=b_rc.summary.$t;}else var l_rc="";var re=/<\S[^>]*>/g;l_rc=l_rc.replace(re,"");if(m_rc==true)document.write('On '+k_rc[parseInt(i_rc,10)]+' '+j_rc+' ');document.write('<a href="'+c_rc+'">'+b_rc.author[0].name.$t+'</a> commented');if(n_rc==true)document.write(' on '+f_rc);document.write(': ');if(l_rc.length<o_rc){document.write('<i>&#8220;');document.write(l_rc);document.write('&#8221;</i><br/><br/>');}else{document.write('<i>&#8220;');l_rc=l_rc.substring(0,o_rc);var p_rc=l_rc.lastIndexOf(" ");l_rc=l_rc.substring(0,p_rc);document.write(l_rc+'&hellip;&#8221;</i>');document.write('<br/><br/>');}}}

function rp(json){document.write('<ul>');for(var i=0;i<numposts;i++){document.write('<li>');var entry=json.feed.entry[i];var posttitle=entry.title.$t;var posturl;if(i==json.feed.entry.length)break;for(var k=0;k<entry.link.length;k++){if(entry.link[k].rel=='alternate'){posturl=entry.link[k].href;break}}posttitle=posttitle.link(posturl);var readmorelink="(more)";readmorelink=readmorelink.link(posturl);var postdate=entry.published.$t;var cdyear=postdate.substring(0,4);var cdmonth=postdate.substring(5,7);var cdday=postdate.substring(8,10);var monthnames=new Array();monthnames[1]="Jan";monthnames[2]="Feb";monthnames[3]="Mar";monthnames[4]="Apr";monthnames[5]="May";monthnames[6]="Jun";monthnames[7]="Jul";monthnames[8]="Aug";monthnames[9]="Sep";monthnames[10]="Oct";monthnames[11]="Nov";monthnames[12]="Dec";if("content"in entry){var postcontent=entry.content.$t}else if("summary"in entry){var postcontent=entry.summary.$t}else var postcontent="";var re=/<\S[^>]*>/g;postcontent=postcontent.replace(re,"");document.write(posttitle);if(showpostdate==true)document.write(' - '+monthnames[parseInt(cdmonth,10)]+' '+cdday);if(showpostsummary==true){if(postcontent.length<numchars){document.write(postcontent)}else{postcontent=postcontent.substring(0,numchars);var quoteEnd=postcontent.lastIndexOf(" ");postcontent=postcontent.substring(0,quoteEnd);document.write(postcontent+'...'+readmorelink)}}document.write('</li>')}document.write('</ul>')}

//]]>
</script>

<script type='text/javascript'>
summary_noimg = 550;
summary_img = 450;
img_thumb_height = 150;
img_thumb_width = 200; 
</script>
<script type='text/javascript'>
//<![CDATA[

function removeHtmlTag(strx,chop){ 
	if(strx.indexOf("<")!=-1)
	{
		var s = strx.split("<"); 
		for(var i=0;i<s.length;i++){ 
			if(s[i].indexOf(">")!=-1){ 
				s[i] = s[i].substring(s[i].indexOf(">")+1,s[i].length); 
			} 
		} 
		strx =  s.join(""); 
	}
	chop = (chop < strx.length-1) ? chop : strx.length-2; 
	while(strx.charAt(chop-1)!=' ' && strx.indexOf(' ',chop)!=-1) chop++; 
	strx = strx.substring(0,chop-1); 
	return strx+'...'; 
}

function createSummaryAndThumb(pID){
	var div = document.getElementById(pID);
	var imgtag = "";
	var img = div.getElementsByTagName("img");
	var summ = summary_noimg;
	if(img.length>=1) {	
		imgtag = '<span style="float:left; padding:0px 10px 5px 0px;"><img src="'+img[0].src+'" width="'+img_thumb_width+'px" height="'+img_thumb_height+'px"/></span>';
		summ = summary_img;
	}
	
	var summary = imgtag + '<div>' + removeHtmlTag(div.innerHTML,summ) + '</div>';
	div.innerHTML = summary;
}

//]]>
</script>

<style type='text/css'>
.clearfix:after{content:&quot;\0020&quot;;display:block;height:0;clear:both;visibility:hidden;overflow:hidden}
#container,#header,#main,#main-fullwidth,#footer,.clearfix{display:block}
.clear{clear:both}
h1,h2,h3,h4,h5,h6{margin-bottom:16px;font-weight:normal;line-height:1}
h1{font-size:40px}
h2{font-size:30px}
h3{font-size:20px}
h4{font-size:16px}
h5{font-size:14px}
h6{font-size:12px}
h1 img,h2 img,h3 img,h4 img,h5 img,h6 img{margin:0}
table{margin-bottom:20px;width:100%}
th{font-weight:bold}
thead th{background:#c3d9ff}
th,td,caption{padding:4px 10px 4px 5px}
tr.even td{background:#e5ecf9}
tfoot{font-style:italic}
caption{background:#eee}
li ul,li ol{margin:0}
ul,ol{margin:0 20px 20px 0;padding-left:40px}
ul{list-style-type:disc}
ol{list-style-type:decimal}
dl{margin:0 0 20px 0}
dl dt{font-weight:bold}
dd{margin-left:20px}
blockquote{margin:20px;color:#666;}
pre{margin:20px 0;white-space:pre}
pre,code,tt{font:13px &#39;andale mono&#39;,&#39;lucida console&#39;,monospace;line-height:18px}
#search {overflow:hidden;}
#header h1{font-family:&#39;Oswald&#39;,Arial,Helvetica,Sans-serif;}
#header .description{font-family:Arial,Helvetica,Sans-serif;}
.post-title {font-family:Arial,Helvetica,Sans-serif;}
.sidebar h2{font-family:Arial,Helvetica,Sans-serif;}
#footer-widgets .widgettitle{font-family:Arial,Helvetica,Sans-serif;}
.menus,.menus *{margin:0;padding:0;list-style:none;list-style-type:none;line-height:1.0}
.menus ul{position:absolute;top:-999em;width:100%}
.menus ul li{width:100%}
.menus li:hover{visibility:inherit}
.menus li{float:left;position:relative}
.menus a{display:block;position:relative}
.menus li:hover ul,.menus li.sfHover ul{left:0;top:100%;z-index:99}
.menus li:hover li ul,.menus li.sfHover li ul{top:-999em}
.menus li li:hover ul,.menus li li.sfHover ul{left:100%;top:0}
.menus li li:hover li ul,.menus li li.sfHover li ul{top:-999em}
.menus li li li:hover ul,.menus li li li.sfHover ul{left:100%;top:0}
.sf-shadow ul{padding:0 8px 9px 0;-moz-border-radius-bottomleft:17px;-moz-border-radius-topright:17px;-webkit-border-top-right-radius:17px;-webkit-border-bottom-left-radius:17px}
.menus .sf-shadow ul.sf-shadow-off{background:transparent}
.menu-primary-container{padding:0;position:relative;height:34px;background:none;z-index:400;float:right;margin-top:10px}
.menu-primary{}
.menu-primary ul{min-width:160px}
.menu-primary li a{color:#244D8E;text-shadow:0px 1px 0px #fff;padding:12px 15px 11px 15px;text-decoration:none;text-transform:uppercase;font:normal 11px/11px Arial,Helvetica,Sans-serif;background:url(http://1.bp.blogspot.com/--aoBwDYRiN4/T9lm0XUNflI/AAAAAAAAEV0/17_GcuzY2Xw/s000/menu-primary-bg.png) left top repeat-x;margin:0 0 0 4px}
.menu-primary li a:hover,.menu-primary li a:active,.menu-primary li a:focus,.menu-primary li:hover &gt; a,.menu-primary li.current-cat &gt; a,.menu-primary li.current_page_item &gt; a,.menu-primary li.current-menu-item &gt; a{color:#DC2F30;text-shadow:0px 1px 0px #fff;outline:0;background:url(http://1.bp.blogspot.com/--aoBwDYRiN4/T9lm0XUNflI/AAAAAAAAEV0/17_GcuzY2Xw/s000/menu-primary-bg.png) left -134px repeat-x}
.menu-primary li li{margin:0 0 0 4px}
.menu-primary li li li{margin:0}
.menu-primary li li a{color:#234D8E;text-shadow:0px 1px 0px #fff;text-transform:none;background:#FFF;padding:10px 15px;margin:0;border:0;font-weight:normal}
.menu-primary li li a:hover,.menu-primary li li a:active,.menu-primary li li a:focus,.menu-primary li li:hover &gt; a,.menu-primary li li.current-cat &gt; a,.menu-primary li li.current_page_item &gt; a,.menu-primary li li.current-menu-item &gt; a{color:#fff;text-shadow:0px 1px 0px #000;background:#D72425;outline:0;border-bottom:0;text-decoration:none}
.menu-primary a.sf-with-ul{padding-right:20px;min-width:1px}
.menu-primary .sf-sub-indicator{position:absolute;display:block;overflow:hidden;right:0;top:0;padding:10px 10px 0 0}
.menu-primary li li .sf-sub-indicator{padding:9px 10px 0 0}
.wrap-menu-primary .sf-shadow ul{background:url(&#39;http://4.bp.blogspot.com/-WxFcGujetx0/T9lm0qqPGcI/AAAAAAAAEV8/sCT_k03gXQU/s000/menu-primary-shadow.png&#39;) no-repeat bottom right}
.menu-secondary-container{position:relative;height:44px;z-index:300;background:url(http://2.bp.blogspot.com/-bogXpJWiiiM/T9lm1M0VCEI/AAAAAAAAEWE/7VFEIvlEmt4/s000/menu-secondary-bg.png) left top repeat-x;margin:0 -12px -16px -12px;padding:0 12px 10px 12px}
.menu-secondary{}
.menu-secondary ul{min-width:160px}
.menu-secondary li a{color:#FFF;text-shadow:0px 1px 0px #000;padding:13px 15px;text-decoration:none;text-transform:uppercase;font:bold 12px/12px Arial,Helvetica,Sans-serif}
.menu-secondary li a:hover,.menu-secondary li a:active,.menu-secondary li a:focus,.menu-secondary li:hover &gt; a,.menu-secondary li.current-cat &gt; a,.menu-secondary li.current_page_item &gt; a,.menu-secondary li.current-menu-item &gt; a{color:#fff;background:url(http://2.bp.blogspot.com/-bogXpJWiiiM/T9lm1M0VCEI/AAAAAAAAEWE/7VFEIvlEmt4/s000/menu-secondary-bg.png) left top repeat-x;outline:0}
.menu-secondary li li a{color:#fff;background:#D52B2C;padding:10px 15px;text-transform:none;margin:0;font-weight:normal}
.menu-secondary li li a:hover,.menu-secondary li li a:active,.menu-secondary li li a:focus,.menu-secondary li li:hover &gt; a,.menu-secondary li li.current-cat &gt; a,.menu-secondary li li.current_page_item &gt; a,.menu-secondary li li.current-menu-item &gt; a{color:#fff;background:#BF1D1F;outline:0}
.menu-secondary a.sf-with-ul{padding-right:26px;min-width:1px}
.menu-secondary .sf-sub-indicator{position:absolute;display:block;overflow:hidden;right:0;top:0;padding:12px 13px 0 0}
.menu-secondary li li .sf-sub-indicator{padding:9px 13px 0 0}
.wrap-menu-secondary .sf-shadow ul{background:url(&#39;http://3.bp.blogspot.com/-F548TsSa9_4/T9lm1W93quI/AAAAAAAAEWM/rxvRJHK4XoY/s000/menu-secondary-shadow.png&#39;) no-repeat bottom right}
.fp-slider{margin:0 0 15px 0;padding:0px;width:930px;height:332px;overflow:hidden;position:relative;}
.fp-slides-container{}
.fp-slides,.fp-thumbnail,.fp-prev-next,.fp-nav{width:930px}
.fp-slides,.fp-thumbnail{height:300px;overflow:hidden;position:relative}
.fp-title{color:#fff;text-shadow:0px 1px 0px #000;font:bold 18px Arial,Helvetica,Sans-serif;padding:0 0 2px 0;margin:0}
.fp-title a,.fp-title a:hover{color:#fff;text-shadow:0px 1px 0px #000;text-decoration:none}
.fp-content{position:absolute;bottom:0;left:0;right:0;background:#111;opacity:0.7;filter:alpha(opacity = 70);padding:10px 15px;overflow:hidden}
.fp-content p{color:#fff;text-shadow:0px 1px 0px #000;padding:0;margin:0;line-height:18px}
.fp-more,.fp-more:hover{color:#fff;font-weight:bold}
.fp-nav{height:12px;text-align:center;padding:10px 0;background:#2D5594;}
.fp-pager a{background-image:url(http://3.bp.blogspot.com/-qVWe26DbbGo/T9lm1p3iSqI/AAAAAAAAEWU/4-chs6YfNkM/s000/featured-pager.png);cursor:pointer;margin:0 8px 0 0;padding:0;display:inline-block;width:12px;height:12px;overflow:hidden;text-indent:-999px;background-position:0 0;float:none;line-height:1;opacity:0.7;filter:alpha(opacity = 70)}
.fp-pager a:hover,.fp-pager a.activeSlide{text-decoration:none;background-position:0 -112px;opacity:1.0;filter:alpha(opacity = 100)}
.fp-prev-next-wrap{position:relative;z-index:200}
.fp-prev-next{position:absolute;bottom:130px;left:0;right:0;height:37px}
.fp-prev{margin-top:-180px;float:left;margin-left:14px;width:37px;height:37px;background:url(http://4.bp.blogspot.com/-MgCQ62BMJI8/T9lm15mJxcI/AAAAAAAAEWc/ZXMZrS9vg08/s000/featured-prev.png) left top no-repeat;opacity:0.6;filter:alpha(opacity = 60)}
.fp-prev:hover{opacity:0.8;filter:alpha(opacity = 80)}
.fp-next{margin-top:-180px;float:right;width:36px;height:37px;margin-right:14px;background:url(http://4.bp.blogspot.com/-LcqyU3RpgfY/T9lm2LcuqhI/AAAAAAAAEWk/zvLvK-alSiw/s000/featured-next.png) right top no-repeat;opacity:0.6;filter:alpha(opacity = 60)}
.fp-next:hover{opacity:0.8;filter:alpha(opacity = 80)}
/* -- number page navigation -- */
#blog-pager {padding:6px;font-size:11px;}
#comment-form iframe{padding:5px;width:580px;height:275px;}
.tabs-widget{list-style:none;list-style-type:none;margin:0 0 10px 0;padding:0;height:26px}
.tabs-widget li{list-style:none;list-style-type:none;margin:0 0 0 4px;padding:0;float:left}
.tabs-widget li:first-child{margin:0}
.tabs-widget li a{color:#fff;text-shadow:0px 1px 0px #000;background:url(http://2.bp.blogspot.com/-bUY95LjISyU/T9lm2PF-kDI/AAAAAAAAEWs/dF4lPOLU_RY/s000/tabs-bg.png) left top repeat-x;padding:6px 16px;display:block;text-decoration:none;font:bold 12px/12px Arial,Helvetica,Sans-serif}
.tabs-widget li a:hover,.tabs-widget li a.tabs-widget-current{background:url(http://2.bp.blogspot.com/-bUY95LjISyU/T9lm2PF-kDI/AAAAAAAAEWs/dF4lPOLU_RY/s000/tabs-bg.png) left top repeat-x;color:#fff;text-shadow:0px 1px 0px #000;text-decoration:none}
.tabs-widget-content{}
.tabviewsection{margin-top:10px;margin-bottom:10px;}
#crosscol-wrapper{display:none;}
.PopularPosts .item-title{font-weight:bold;padding-bottom:0.2em;text-shadow:0px 1px 0px #fff;}
.PopularPosts .widget-content ul li{padding:0.7em 0;background:none}
.widget-container{list-style-type:none;list-style:none;margin:0 0 15px 0;padding:0;color:#193E79;font-size:13px}
.widget-container2{list-style-type:none;list-style:none;margin:5px 15px 10px 0px;padding:0;color:#193E79;font-size:13px}
h3.widgettitle{border-bottom:3px solid #EF4F51;margin:0 0 10px 0;padding:10px 0 4px 0;color:#2D5594;font-size:16px;line-height:16px;font-family:Arial,Helvetica,Sans-serif;font-weight:bold;text-decoration:none;text-transform:uppercase;}
div.span-1,div.span-2,div.span-3,div.span-4,div.span-5,div.span-6,div.span-7,div.span-8,div.span-9,div.span-10,div.span-11,div.span-12,div.span-13,div.span-14,div.span-15,div.span-16,div.span-17,div.span-18,div.span-19,div.span-20,div.span-21,div.span-22,div.span-23,div.span-24{float:left;margin-right:10px}
.span-1{width:30px}.span-2{width:70px}.span-3{width:110px}.span-4{width:150px}.span-5{width:190px}.span-6{width:230px}.span-7{width:270px}.span-8{width:310px}.span-9{width:350px}.span-10{width:390px}.span-11{width:430px}.span-12{width:470px}.span-13{width:510px}.span-14{width:550px}.span-15{width:590px}.span-16{width:630px}.span-17{width:670px}.span-18{width:710px}.span-19{width:750px}.span-20{width:790px}.span-21{width:830px}.span-22{width:870px}.span-23{width:910px}.span-24,div.span-24{width:960px;margin:0}input.span-1,textarea.span-1,input.span-2,textarea.span-2,input.span-3,textarea.span-3,input.span-4,textarea.span-4,input.span-5,textarea.span-5,input.span-6,textarea.span-6,input.span-7,textarea.span-7,input.span-8,textarea.span-8,input.span-9,textarea.span-9,input.span-10,textarea.span-10,input.span-11,textarea.span-11,input.span-12,textarea.span-12,input.span-13,textarea.span-13,input.span-14,textarea.span-14,input.span-15,textarea.span-15,input.span-16,textarea.span-16,input.span-17,textarea.span-17,input.span-18,textarea.span-18,input.span-19,textarea.span-19,input.span-20,textarea.span-20,input.span-21,textarea.span-21,input.span-22,textarea.span-22,input.span-23,textarea.span-23,input.span-24,textarea.span-24{border-left-width:1px!important;border-right-width:1px!important;padding-left:5px!important;padding-right:5px!important}input.span-1,textarea.span-1{width:18px!important}input.span-2,textarea.span-2{width:58px!important}input.span-3,textarea.span-3{width:98px!important}input.span-4,textarea.span-4{width:138px!important}input.span-5,textarea.span-5{width:178px!important}input.span-6,textarea.span-6{width:218px!important}input.span-7,textarea.span-7{width:258px!important}input.span-8,textarea.span-8{width:298px!important}input.span-9,textarea.span-9{width:338px!important}input.span-10,textarea.span-10{width:378px!important}input.span-11,textarea.span-11{width:418px!important}input.span-12,textarea.span-12{width:458px!important}input.span-13,textarea.span-13{width:498px!important}input.span-14,textarea.span-14{width:538px!important}input.span-15,textarea.span-15{width:578px!important}input.span-16,textarea.span-16{width:618px!important}input.span-17,textarea.span-17{width:658px!important}input.span-18,textarea.span-18{width:698px!important}input.span-19,textarea.span-19{width:738px!important}input.span-20,textarea.span-20{width:778px!important}input.span-21,textarea.span-21{width:818px!important}input.span-22,textarea.span-22{width:858px!important}input.span-23,textarea.span-23{width:898px!important}input.span-24,textarea.span-24{width:938px!important}.last{margin-right:0;padding-right:0}
.last,div.last{margin-right:0}
</style>

<b:if cond='data:blog.pageType == &quot;static_page&quot;'>
<style type='text/css'>
.post-body img {padding:0px;background:transparent;border:none;}
</style>
</b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<style type='text/css'>
.post-body img {padding:0px;background:transparent;border:none;}
</style>
</b:if>

<!--[if lte IE 8]>
<style type='text/css'>
#search{border:1px solid #C1D4E6;background:#FFF url(http://4.bp.blogspot.com/-P4WIo247Q3c/T9lmz31OkdI/AAAAAAAAEVk/iJuTDSvJe3w/s000/search.png) 99% 20% no-repeat;text-align:left;padding:6px 24px 6px 6px;height:16px;}
.fp-slider {height:300px;}
.fp-nav {display:none;}
</style>
<![endif]-->

<script src='http://apis.google.com/js/plusone.js' type='text/javascript'>
{lang: &#39;en-US&#39;}
</script>

  </head>

  <body>

  <div id='body-wrapper'><div id='outer-wrapper'><div id='wrap2'>
  
<div class='span-24'>
<div class='menu-primary-container'>
<b:section class='pagelistmenusblog' id='pagelistmenusblog' showaddelement='no'>
<b:widget id='PageList8' locked='false' title='Pages - Menu' type='PageList'>
<b:includable id='main'>
              <b:if cond='data:title'><!--<h2><data:title/></h2>--></b:if>
              <div class='widget-content'>
                <ul class='menus menu-primary'>
                  <b:loop values='data:links' var='link'>
                    <b:if cond='data:link.isCurrentPage'>
                      <li id='currentpage'><a expr:href='data:link.href'><data:link.title/></a></li>
                    <b:else/>
                      <li><a expr:href='data:link.href'><data:link.title/></a></li>
                    </b:if>
                  </b:loop>
                </ul>
                <b:include name='quickedit'/>
              </div>
            </b:includable>
</b:widget>
</b:section>
</div>
</div>

<div style='clear:both;'/>

    <div id='header-wrapper'>
      <b:section class='header' id='header' maxwidgets='1' showaddelement='no'>
<b:widget id='Header1' locked='true' title='Learner (Header)' type='Header'>
<b:includable id='title'>
<a expr:href='data:blog.homepageUrl'><data:title/></a>
</b:includable>
<b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
<b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;REPLACE&quot;'>
      <!--Show just the image, no text-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block;padding-left:15px;padding-top:0px;'/>
        </a>
      </div>
    <b:else/>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height + &quot;px;&quot;                      + &quot;_height: &quot; + data:height + &quot;px;&quot;                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
        <div class='titlewrapper' style='background: transparent'>
          <h1 class='title' style='background: transparent; border-width: 0px'>
            <b:include name='title'/>
          </h1>
        </div>
        <b:include name='description'/>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <b:include name='title'/>
        </h1>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
</b:widget>
</b:section>

<b:section class='header' id='header2' maxwidgets='1' showaddelement='yes'>
<b:widget id='HTML1' locked='false' title='' type='HTML'>
<b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
</b:section>
<div style='clear:both;'/>

    </div>
<div style='clear:both;'/>

<div class='span-24'>
<div class='menu-secondary-container'>

<ul class='menus menu-secondary'>

<li><a expr:href='data:blog.homepageUrl'>Home</a></li>

<li><a href='#'>Business</a>
<ul class='children'>
<li><a href='#'>Internet</a></li>
<li><a href='#'>Market</a></li>
<li><a href='#'>Stock</a></li>
</ul>
</li>

<li><a href='#'>Downloads</a>
<ul class='children'>
<li><a href='#'>Dvd</a></li>
<li><a href='#'>Games</a></li>
<li><a href='#'>Software</a>
<ul class='children'>
<li><a href='#'>Office</a>
</li>
</ul>
</li>
</ul>
</li>

<li><a href='#'>Parent Category</a>
<ul class='children'>
<li><a href='#'>Child Category 1</a>
<ul class='children'>
<li><a href='#'>Sub Child Category 1</a></li>
<li><a href='#'>Sub Child Category 2</a></li>
<li><a href='#'>Sub Child Category 3</a></li>
</ul>
</li>
<li><a href='#'>Child Category 2</a></li>
<li><a href='#'>Child Category 3</a></li>
<li><a href='#'>Child Category 4</a></li>
</ul>
</li>

<li><a href='#'>Featured</a></li>

<li><a href='#'>Health</a>
<ul class='children'>
<li><a href='#'>Childcare</a></li>
<li><a href='#'>Doctors</a></li>
</ul>
</li>

<li><a href='#'>Uncategorized</a></li>
		
</ul>
</div>
</div>
<div style='clear:both;'/>
 
    <div id='content-wrapper'>
	
<!-- Featured Content Slider Started -->

<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>

<div class='fp-slider clearfix'>
<div class='fp-slides-container clearfix'>

<div class='fp-slides'>

<!-- Slide 1 Code Start -->
<div class='fp-slides-items'>
<div class='fp-thumbnail'>
<a href='#'><img src='http://3.bp.blogspot.com/-P3TluGJbY-E/T9lm2ckGUnI/AAAAAAAAEW0/6TKZQ_-sbYY/s000/1.jpg'/></a>
</div>
<div class='fp-content-wrap'>
<div class='fp-content'>
<h3 class='fp-title'>
<a href='#'>This is default featured slide 1 title</a>
</h3>
<p>
Go to Blogger edit html and find these sentences.Now replace these sentences with your own descriptions. 
</p>
</div>
<div class='fp-prev-next-wrap clearfix'>
    <a class='fp-next' href='#fp-next'/>
    <a class='fp-prev' href='#fp-prev'/>
</div>
</div>
</div>
<!-- Slide 1 Code End -->

<!-- Slide 2 Code Start -->
<div class='fp-slides-items'>
<div class='fp-thumbnail'>
<a href='#'><img src='http://3.bp.blogspot.com/-YIm41oKBs48/T9lm20Tr8-I/AAAAAAAAEW8/oURZn4bIsuE/s000/2.jpg'/></a>
</div>
<div class='fp-content-wrap'>
<div class='fp-content'>
<h3 class='fp-title'>
<a href='#'>This is default featured slide 2 title</a>
</h3>
<p>
Go to Blogger edit html and find these sentences.Now replace these sentences with your own descriptions. 
</p>
</div>
<div class='fp-prev-next-wrap clearfix'>
    <a class='fp-next' href='#fp-next'/>
    <a class='fp-prev' href='#fp-prev'/>
</div>
</div>
</div>
<!-- Slide 2 Code End -->

<!-- Slide 3 Code Start -->
<div class='fp-slides-items'>
<div class='fp-thumbnail'>
<a href='#'><img src='http://1.bp.blogspot.com/-9-X0yhG3Mk8/T9lm3PXGeYI/AAAAAAAAEXE/F5pCkXCdFi4/s000/3.jpg'/></a>
</div>
<div class='fp-content-wrap'>
<div class='fp-content'>
<h3 class='fp-title'>
<a href='#'>This is default featured slide 3 title</a>
</h3>
<p>
Go to Blogger edit html and find these sentences.Now replace these sentences with your own descriptions. 
</p>
</div>
<div class='fp-prev-next-wrap clearfix'>
    <a class='fp-next' href='#fp-next'/>
    <a class='fp-prev' href='#fp-prev'/>
</div>
</div>
</div>
<!-- Slide 3 Code End -->

<!-- Slide 4 Code Start -->
<div class='fp-slides-items'>
<div class='fp-thumbnail'>
<a href='#'><img src='http://1.bp.blogspot.com/-qrwJxT3WzU8/T9lm3tMUjFI/AAAAAAAAEXM/zZ1KgyCD6Rw/s000/4.jpg'/></a>
</div>
<div class='fp-content-wrap'>
<div class='fp-content'>
<h3 class='fp-title'>
<a href='#'>This is default featured slide 4 title</a>
</h3>
<p>
Go to Blogger edit html and find these sentences.Now replace these sentences with your own descriptions. 
</p>
</div>
<div class='fp-prev-next-wrap clearfix'>
    <a class='fp-next' href='#fp-next'/>
    <a class='fp-prev' href='#fp-prev'/>
</div>
</div>
</div>
<!-- Slide 4 Code End -->

<!-- Slide 5 Code Start -->
<div class='fp-slides-items'>
<div class='fp-thumbnail'>
<a href='#'><img src='http://1.bp.blogspot.com/-lNfKstOoiKc/T9lm3wGdO5I/AAAAAAAAEXU/XHjmp5pVkcU/s000/5.jpg'/></a>
</div>
<div class='fp-content-wrap'>
<div class='fp-content'>
<h3 class='fp-title'>
<a href='#'>This is default featured slide 5 title</a>
</h3>
<p>
Go to Blogger edit html and find these sentences.Now replace these sentences with your own descriptions. 
</p>
</div>
<div class='fp-prev-next-wrap clearfix'>
    <a class='fp-next' href='#fp-next'/>
    <a class='fp-prev' href='#fp-prev'/>
</div>
</div>
</div>
<!-- Slide 5 Code End -->

</div>

<div class='fp-nav'>
    <span class='fp-pager'/>
</div>  
            
</div>
</div>
<div style='clear:both;'/>

</b:if></b:if>

<!-- Featured Content Slider End -->

      <div id='crosscol-wrapper' style='text-align:center'>
        <b:section class='crosscol' id='crosscol' showaddelement='yes'/>
      </div>

<div id='main-wrapper'>

        <b:section class='main' id='main' showaddelement='no'>
<b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog'>
<b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
<b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showOrkutButton'><a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToOrkutMsg/></span></a></b:if><b:if cond='data:top.showDummy'><div class='goog-inline-block dummy-container'><data:post.dummyTag/></div></b:if>
</b:includable>
<b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        if (entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
            }
          }
        }
        return entry.content.$t;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
<b:includable id='backlinks' var='post'>
  <a name='links'/><h4><data:post.backlinksLabel/></h4>
  <b:if cond='data:post.numBacklinks != 0'>
    <dl class='comments-block' id='comments-block'>
      <b:loop values='data:post.backlinks' var='backlink'>
        <div class='collapsed-backlink backlink-control'>
          <dt class='comment-title'>
            <span class='backlink-toggle-zippy'>&#160;</span>
            <a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a>
            <b:include data='backlink' name='backlinkDeleteIcon'/>
          </dt>
          <dd class='comment-body collapseable'>
            <data:backlink.snippet/>
          </dd>
          <dd class='comment-footer collapseable'>
            <span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
            <span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
          </dd>
        </div>
      </b:loop>
    </dl>
  </b:if>
  <p class='comment-footer'>
    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'><data:post.createLinkLabel/></a>
  </p>
</b:includable>
<b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
<b:includable id='post' var='post'>
<div class='wrapfullpost'>
  <div class='post hentry'>
    <a expr:name='data:post.id'/>

    <b:if cond='data:post.title'>
      <h3 class='post-title entry-title'>
     <b:if cond='data:post.link'>
       <a expr:href='data:post.link'><data:post.title/></a>
     <b:else/>
        <b:if cond='data:post.url'>
          <a expr:href='data:post.url'><data:post.title/></a>
        <b:else/>
          <data:post.title/>
        </b:if>
     </b:if>
      </h3>
    </b:if>

    <div class='post-header-line-1'/>
	
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<div class='postmeta-primary'>
<span class='meta_date'><data:post.timestamp/></span>
 &amp;nbsp;<span class='meta_categories'><b:if cond='data:post.labels'><b:loop values='data:post.labels' var='label'><a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>, </b:if></b:loop></b:if></span>
 &amp;nbsp;<span class='meta_comments'><b:if cond='data:post.allowComments'><a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 0'>No comments</b:if><b:if cond='data:post.numComments == 1'>1 comment</b:if><b:if cond='data:post.numComments &gt;= 2'><data:post.numComments/> comments</b:if></a></b:if></span> 
</div>
</b:if>

    <div class='post-body entry-content'>

<p>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<div expr:id='&quot;summary&quot; + data:post.id'><data:post.body/></div>
<script type='text/javascript'>createSummaryAndThumb(&quot;summary<data:post.id/>&quot;);</script>
</b:if>
</b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'><data:post.body/></b:if>

<b:if cond='data:blog.pageType == &quot;static_page&quot;'><data:post.body/></b:if></p>

<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<div class='readmore'>
<a expr:href='data:post.url'>Read More</a>
</div>
</b:if>
</b:if>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
<div style='clear:both;'/>
<div class='post-share-buttons'>
<b:include data='post' name='shareButtons'/>
</div>
<span class='reaction-buttons'>
<b:if cond='data:top.showReactions'>
<table border='0' cellpadding='0' width='100%'><tr>
<td style='font-size:12px;padding-top:2px;' valign='top'><span class='reactions-label'><data:top.reactionsLabel/></span></td>
<td><iframe allowtransparency='true' class='reactions-iframe' expr:src='data:post.reactionsUrl' frameborder='0' name='reactions' scrolling='no'/></td>
</tr></table>
</b:if>
</span>
</b:if>

      <div style='clear: both;'/> <!-- clear for photos floats -->
    </div>
  
    <b:if cond='data:post.hasJumpLink'>
      <div class='jump-link'>
        <a expr:href='data:post.url + &quot;#more&quot;'><data:post.jumpText/></a>  
      </div>
    </b:if>
    
    <div class='post-footer'>

<div class='post-footer-line post-footer-line-'/>
<div class='post-footer-line post-footer-line-2'/>
<div class='post-footer-line post-footer-line-3'>

<!-- Feature added by BTemplates.com -->
	<b:include data='post' name='postQuickEdit'/>
</div></div>
</div>
</div>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
<!-- navigation -->
<b:include name='nextprev'/>
</b:if>

</b:includable>
<b:includable id='status-message'>
  <b:if cond='data:navMessage'>
  <div class='status-msg-wrap'>
    <div class='status-msg-body'>
      <data:navMessage/>
    </div>
    <div class='status-msg-border'>
      <div class='status-msg-bg'>
        <div class='status-msg-hidden'><data:navMessage/></div>
      </div>
    </div>
  </div>
  <div style='clear: both;'/>
  </b:if>
</b:includable>
<b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
    </script>
  </div>
</b:includable>
<b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4>
      <b:if cond='data:post.numComments == 1'>
        1 <data:commentLabel/>:
      <b:else/>
        <data:post.numComments/> <data:commentLabelPlural/>:
      </b:if>
    </h4>

    <div class='comments-content'>
      <b:if cond='data:post.embedCommentForm'>
        <b:include data='post' name='threaded_comment_js'/>
      </b:if>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
<b:includable id='backlinkDeleteIcon' var='backlink'>
  <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
    <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
      <img src='//www.blogger.com/img/icon_delete13.gif'/>
    </a>
  </span>
</b:includable>
<b:includable id='mobile-nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <div class='mobile-link-button' id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
      </div>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>

    <div class='mobile-link-button' id='blog-pager-home-link'>
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
    </div>

    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
    </div>

  </div>
  <div class='clear'/>
</b:includable>
<b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template'>
          <a expr:name='data:post.id'/>
          <b:if cond='data:post.title'>
            <h3 class='post-title entry-title'>
              <b:if cond='data:post.link'>
                <a expr:href='data:post.link'><data:post.title/></a>
              <b:else/>
                <b:if cond='data:post.url'>
                  <b:if cond='data:blog.url != data:post.url'>
                    <a expr:href='data:post.url'><data:post.title/></a>
                  <b:else/>
                    <data:post.title/>
                  </b:if>
                <b:else/>
                  <data:post.title/>
                </b:if>
              </b:if>
            </h3>
          </b:if>

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn'>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <data:post.author/>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn'><data:post.author/></span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              <span class='post-comment-link'>
                <b:if cond='data:blog.pageType != &quot;item&quot;'>
                  <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                    <b:if cond='data:post.allowComments'>
                      <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
                    </b:if>
                  </b:if>
                </b:if>
              </span>
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
              <b:if cond='data:top.showDummy'>
                <div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
              </b:if>
            </div>

          </div>
        </div>

        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
      </div>
    </div>
  </div>
</b:includable>
<b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='' class='icon-action' height='18' src='http://img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
<b:includable id='main' var='top'>
  <b:if cond='data:mobile == &quot;false&quot;'>

    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <data:defaultAdStart/>
      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.isDateStart'>
          <b:if cond='data:post.isFirstPost == &quot;false&quot;'>
            &lt;/div&gt;&lt;/div&gt;
          </b:if>
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-outer&quot;&gt;
        </b:if>
        <b:if cond='data:post.dateHeader'>
          <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-posts&quot;&gt;
        </b:if>
        <div class='post-outer'>
        <b:include data='post' name='post'/>
        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
        </div>
        <b:if cond='data:post.includeAd'>
          <b:if cond='data:post.isFirstPost'>
            <data:defaultAdEnd/>
          <b:else/>
            <data:adEnd/>
          </b:if>
          <div class='inline-ad'>
            <data:adCode/>
          </div>
          <data:adStart/>
        </b:if>
      </b:loop>
      <b:if cond='data:numPosts != 0'>
        &lt;/div&gt;&lt;/div&gt;
      </b:if>
      <data:adEnd/>
    </div>

<b:if cond='data:blog.pageType != &quot;item&quot;'>
<!-- navigation -->
<b:include name='nextprev'/>
</b:if>

    <!-- feed links -->
    <b:include name='feedLinks'/>

    <b:if cond='data:top.showStars'>
      <script src='//www.google.com/jsapi' type='text/javascript'/>
      <script type='text/javascript'>
        google.load(&quot;annotations&quot;, &quot;1&quot;, {&quot;locale&quot;: &quot;<data:top.languageCode/>&quot;});
        function initialize() {
          google.annotations.setApplicationId(<data:top.blogspotReviews/>);
          google.annotations.createAll();
          google.annotations.fetch();
        }
        google.setOnLoadCallback(initialize);
      </script>
    </b:if>

  <b:else/>
    <b:include name='mobile-main'/>
  </b:if>

  <b:if cond='data:top.showDummy'>
    <data:top.dummyBootstrap/>
  </b:if>

</b:includable>
<b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
        <img src='//www.blogger.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
<b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>

    <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.allowComments'>
          <b:if cond='data:post.feedLinks'>
            <b:include data='post.feedLinks' name='feedLinksBody'/>
          </b:if>
        </b:if>
      </b:loop>
    </div>
  </b:if>
</b:includable>
<b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
    </script>
  </div>
</b:includable>
<b:includable id='mobile-index-post' var='post'>
  <div class='mobile-date-outer date-outer'>
    <b:if cond='data:post.dateHeader'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </b:if>

    <div class='mobile-post-outer'>
      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title'>
          <data:post.title/>
        </h3>

        <div class='mobile-index-arrow'>&amp;rsaquo;</div>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
          </b:if>

          <div class='post-body'>
            <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
          </div>
        </div>

        <div style='clear: both;'/>
      </a>

      <div class='mobile-index-comment'>
        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
          <b:if cond='data:post.allowComments'>
            <b:if cond='data:post.numComments != 0'>
              <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
            </b:if>
          </b:if>
        </b:if>
      </div>
    </div>
  </div>
</b:includable>
<b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:feedLinksMsg/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
<b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
      <h4>
        <b:if cond='data:post.numComments == 1'>
          1 <data:commentLabel/>:
        <b:else/>
          <data:post.numComments/> <data:commentLabelPlural/>:
        </b:if>
      </h4>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
          &#160;
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
        </span>
      </b:if>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
          <b:loop values='data:post.comments' var='comment'>
            <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
              <b:if cond='data:comment.favicon'>
                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
              </b:if>
              <a expr:name='data:comment.anchorName'/>
              <b:if cond='data:blog.enabledCommentProfileImages'>
                <data:comment.authorAvatarImage/>
              </b:if>
              <b:if cond='data:comment.authorUrl'>
                <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
              <b:else/>
                <data:comment.author/>
              </b:if>
              <data:commentPostedByMsg/>
            </dt>
            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
              <b:else/>
                <p>
                  <data:comment.body/>
                </p>
              </b:if>
            </dd>
            <dd class='comment-footer'>
              <span class='comment-timestamp'>
                <a expr:href='data:comment.url' title='comment permalink'>
                  <data:comment.timestamp/>
                </a>
                <b:include data='comment' name='commentDeleteIcon'/>
              </span>
            </dd>
          </b:loop>
        </dl>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
            <data:post.oldestLinkText/>
          </a>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
            <data:post.olderLinkText/>
          </a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
            <data:post.newerLinkText/>
          </a>
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
            <data:post.newestLinkText/>
          </a>
        </span>
      </b:if>

      <p class='comment-footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='comment-form'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:else/>
          <b:if cond='data:post.allowComments'>
            <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
          </b:if>
        </b:if>

      </p>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
</b:widget>
</b:section>
      </div>

      <div id='rsidebar-wrapper'>
	  
<div class='widget-container'>
<div class='social-profiles-widget'>
<h3 class='widgettitle'>Social Profiles</h3>
<a href='http://twitter.com/YOUR_USERNAME' target='_blank'><img alt='Twitter' src='http://4.bp.blogspot.com/-nF2uTaQLCTc/T9lm4KWWpaI/AAAAAAAAEXY/1N_DAVqwRho/s000/twitter.png' title='Twitter'/></a><a href='http://facebook.com/YOUR_USERNAME' target='_blank'><img alt='Facebook' src='http://3.bp.blogspot.com/-MRN_kfiik8I/T9lm4T6L1JI/AAAAAAAAEXg/mCxXeLTo1Lk/s000/facebook.png' title='Facebook'/></a><a href='https://plus.google.com/' target='_blank'><img alt='Google Plus' src='http://4.bp.blogspot.com/-MoXujys3FY4/T9lm4jKn_sI/AAAAAAAAEXs/IHGr6lRB4As/s000/gplus.png' title='Google Plus'/></a><a href='http://www.linkedin.com/' target='_blank'><img alt='LinkedIn' src='http://1.bp.blogspot.com/-uwguR02EZLE/T9lm49NW1VI/AAAAAAAAEX0/XLoruq35euY/s000/linkedin.png' title='LinkedIn'/></a><a expr:href='data:blog.homepageUrl + &quot;feeds/posts/default&quot;' target='_blank'><img alt='RSS Feed' src='http://2.bp.blogspot.com/-HZGlgnM-DKg/T9lm4wWfX8I/AAAAAAAAEX8/LM6_t6WjYcc/s000/rss.png' title='RSS Feed'/></a><a href='mailto:your@email.com' target='_blank'><img alt='Email' src='http://4.bp.blogspot.com/-SCtfrzhJxjI/T9lm5aYTG3I/AAAAAAAAEYE/VTXB0fsLFJQ/s000/email.png' title='Email'/></a>
</div>
</div>
<div style='clear:both;'/>

<div class='widget-container'>
<div id='search' title='Type and hit enter'>
    <form expr:action='data:blog.homepageUrl + &quot;search/&quot;' id='searchform' method='get'> 
        <input id='s' name='q' onblur='if (this.value == &quot;&quot;) {this.value = &quot;Search&quot;;}' onfocus='if (this.value == &quot;Search&quot;) {this.value = &quot;&quot;;}' type='text' value='Search'/>
    </form>
</div>
</div>
<div style='clear:both;'/>

<div class='widget-container'>
<div class='tabviewsection'>

<script type='text/javascript'>
            jQuery(document).ready(function($){
                $(&quot;.tabs-widget-content-widget-themater_tabs-1432447472-id&quot;).hide();
            	$(&quot;ul.tabs-widget-widget-themater_tabs-1432447472-id li:first a&quot;).addClass(&quot;tabs-widget-current&quot;).show();
            	$(&quot;.tabs-widget-content-widget-themater_tabs-1432447472-id:first&quot;).show();
       
            	$(&quot;ul.tabs-widget-widget-themater_tabs-1432447472-id li a&quot;).click(function() {
            		$(&quot;ul.tabs-widget-widget-themater_tabs-1432447472-id li a&quot;).removeClass(&quot;tabs-widget-current a&quot;); 
            		$(this).addClass(&quot;tabs-widget-current&quot;); 
            		$(&quot;.tabs-widget-content-widget-themater_tabs-1432447472-id&quot;).hide(); 
            	    var activeTab = $(this).attr(&quot;href&quot;); 
            	    $(activeTab).fadeIn();
            		return false;
            	});
            });
        </script>

<ul class='tabs-widget tabs-widget-widget-themater_tabs-1432447472-id'>
<li><a href='#widget-themater_tabs-1432447472-id1'>Popular</a></li>
<li><a href='#widget-themater_tabs-1432447472-id2'>Tags</a></li>
<li><a href='#widget-themater_tabs-1432447472-id3'>Blog Archives</a></li>
</ul>

<div class='tabs-widget-content tabs-widget-content-widget-themater_tabs-1432447472-id' id='widget-themater_tabs-1432447472-id1'>
<b:section class='sidebar' id='sidebartab1' preferred='yes'>
<b:widget id='PopularPosts1' locked='false' title='Popular Posts' type='PopularPosts'>
<b:includable id='main'>
  <b:if cond='data:title'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='data:showThumbnails == &quot;false&quot;'>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (3) Show only thumbnails -->
            <div class='item-thumbnail-only'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            </div>
            <div style='clear: both;'/>
          <b:else/>
            <!-- (4) Show snippets and thumbnails -->
            <div class='item-content'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
              <div class='item-snippet'><data:post.snippet/></div>
            </div>
            <div style='clear: both;'/>
          </b:if>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
</b:widget>
<b:widget id='Attribution1' locked='true' title='' type='Attribution'>
<b:includable id='main'>
    <b:if cond='data:feedbackSurveyLink'>
      <div class='mobile-survey-link' style='text-align: center;'>
        <data:feedbackSurveyLink/>
      </div>
    </b:if>

    <div class='widget-content' style='text-align: center;'>
      <b:if cond='data:attribution != &quot;&quot;'>
       <data:attribution/>
      </b:if>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
</b:widget>
</b:section>                                       
</div>							
								
<div class='tabs-widget-content tabs-widget-content-widget-themater_tabs-1432447472-id' id='widget-themater_tabs-1432447472-id2'>
<b:section class='sidebar' id='sidebartab2' preferred='yes'>
<b:widget id='Label3' locked='false' title='Labels' type='Label'>
<b:includable id='main'>
  <b:if cond='data:title'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
      <b:loop values='data:labels' var='label'>
        <li>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </li>
      </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
</b:widget>
</b:section>                                         
</div>							
								
<div class='tabs-widget-content tabs-widget-content-widget-themater_tabs-1432447472-id' id='widget-themater_tabs-1432447472-id3'>
<b:section class='sidebar' id='sidebartab3' preferred='yes'>
<b:widget id='BlogArchive2' locked='false' title='Blog Archive' type='BlogArchive'>
<b:includable id='main'>
  <b:if cond='data:title'>
    <h2><data:title/></h2>
  </b:if>
  <div class='widget-content'>
  <div id='ArchiveList'>
  <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
    <b:if cond='data:style == &quot;HIERARCHY&quot;'>
     <b:include data='data' name='interval'/>
    </b:if>
    <b:if cond='data:style == &quot;FLAT&quot;'>
      <b:include data='data' name='flat'/>
    </b:if>
    <b:if cond='data:style == &quot;MENU&quot;'>
      <b:include data='data' name='menu'/>
    </b:if>
  </div>
  </div>
  <b:include name='quickedit'/>
  </div>
</b:includable>
<b:includable id='flat' var='data'>
  <ul class='flat'>
    <b:loop values='data:data' var='i'>
      <li class='archivedate'>
        <a expr:href='data:i.url'><data:i.name/></a> (<data:i.post-count/>)
      </li>
    </b:loop>
  </ul>
</b:includable>
<b:includable id='menu' var='data'>
  <select expr:id='data:widget.instanceId + &quot;_ArchiveMenu&quot;'>
    <option value=''><data:title/></option>
    <b:loop values='data:data' var='i'>
      <option expr:value='data:i.url'><data:i.name/> (<data:i.post-count/>)</option>
    </b:loop>
  </select>
</b:includable>
<b:includable id='interval' var='intervalData'>
  <b:loop values='data:intervalData' var='i'>
      <ul class='hierarchy'>
        <li expr:class='&quot;archivedate &quot; + data:i.expclass'>
          <b:include data='i' name='toggle'/>
          <a class='post-count-link' expr:href='data:i.url'><data:i.name/></a>
            <span class='post-count' dir='ltr'>(<data:i.post-count/>)</span>
          <b:if cond='data:i.data'>
            <b:include data='i.data' name='interval'/>
          </b:if>
          <b:if cond='data:i.posts'>
            <b:include data='i.posts' name='posts'/>
          </b:if>
        </li>
      </ul>
  </b:loop>
</b:includable>
<b:includable id='toggle' var='interval'>
  <b:if cond='data:interval.toggleId'>
  <b:if cond='data:interval.expclass == &quot;expanded&quot;'>
    <a class='toggle' href='javascript:void(0)'>
      <span class='zippy toggle-open'>&#9660;&#160;</span>
    </a>
  <b:else/>
    <a class='toggle' href='javascript:void(0)'>
      <span class='zippy'>
        <b:if cond='data:blog.languageDirection == &quot;rtl&quot;'>
          &#9668;&#160;
        <b:else/>
          &#9658;&#160;
        </b:if>
      </span>
    </a>
  </b:if>
 </b:if>
</b:includable>
<b:includable id='posts' var='posts'>
  <ul class='posts'>
    <b:loop values='data:posts' var='i'>
      <li><a expr:href='data:i.url'><data:i.title/></a></li>
    </b:loop>
  </ul>
</b:includable>
</b:widget>
</b:section>                                        
</div>

</div>
</div>

<div style='height:5px;clear:both;'/>


        <b:section class='sidebar' id='sidebarright' preferred='yes'>
<b:widget id='HTML5' locked='false' title='Blogger templates' type='HTML'>
<b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
</b:section>

<p/></div>

      <!-- spacer for skins that want sidebar and main to be the same height-->
      <div class='clear'>&#160;</div>

    </div> <!-- end content-wrapper -->
	
<div style='clear:both;'/>
<div id='footer-widgets-container'>
<div class='clearfix' id='footer-widgets'>

<div class='footer-widget-box'>
<ul class='widget-container'>
<li>
<b:section class='footersec' id='footersec1' showaddelement='yes'>
<b:widget id='HTML4' locked='false' title='Blogger news' type='HTML'>
<b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
</b:section>
</li>
</ul>
</div>

<div class='footer-widget-box'>
<ul class='widget-container'>
<li>
<b:section class='footersec' id='footersec2' showaddelement='yes'>
<b:widget id='HTML3' locked='false' title='Blogroll' type='HTML'>
<b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
</b:section>
</li>
</ul>
</div>

<div class='footer-widget-box footer-widget-box-last'>
<ul class='widget-container'>
<li>
<b:section class='footersec' id='footersec3' showaddelement='yes'>
<b:widget id='HTML2' locked='false' title='About' type='HTML'>
<b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
</b:widget>
</b:section>
</li>
</ul>
</div>

</div>
</div>
<div style='clear:both;'/>
<div id='footer-container'>
<div id='footer'>   
<div id='copyrights'>
Copyright &amp;copy; <script type='text/javascript'>var creditsyear = new Date();document.write(creditsyear.getFullYear());</script> <a expr:href='data:blog.homepageUrl'><data:blog.title/></a> | Powered by <a href='http://www.blogger.com/'>Blogger</a> 
</div>       
<div id='credits'>
<!-- you don't have permission to remove or change these  -->
Design by <a href='http://newwpthemes.com/' target='_blank'>NewWpThemes</a> | Blogger Theme by <a href='http://www.bloggertipandtrick.net/' target='_blank' title='Best Blogging Tutorials'>Lasantha</a> - <a href='http://www.btemplates.com/author/pbtemplates/' target='_blank' title='Free Blogger Templates' rel="nofollow">Premium Blogger Themes</a> | <a href='http://www.virtualservergeeks.com/virtual-private-server/' target='_blank'>Virtual Private Server</a>
</div>          
</div><!-- #footer -->
</div>
<div style='clear:both;'/>

  </div></div></div> <!-- end outer-wrapper -->

</body>
</html>
