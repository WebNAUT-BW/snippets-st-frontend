#フロントエンド開発でよく使うSublime Text用スニペット集

##汎用コメントアウト
commentout.large
```
/* ===============================================
#
=============================================== */
```

commentout.medium
```
/* -----------------------------
#
-------------------------------- */
```

commentout.small
```
/* #
----------------------- */
```


##汎用ダミーテキスト
dummytext.heading
```
この部分はコンテンツ見出しとなります。文字数は約○○文字前後となります。
```

dummytext.p-long
```
この部分は、○○文字以内のテキストが入ります。この部分は、○○文字以内のテキストが入ります。この部分は、○○文字以内のテキストが入ります。この部分は、○○文字以内のテキストが入ります。この部分は、○○文字以内のテキストが入ります。この部分は、○○文字以内のテキストが入ります。この部分は、○○文字以内のテキストが入ります。この部分は、○○文字以内のテキストが入ります。
```

dummytext.p
```
この部分は、○○文字以内のテキストが入ります。
```


##HTML
html.apple-touch-icon-precomposed
```
<link rel="apple-touch-icon-precomposed" href="apple-touch-icon.png" />
```

html.apple-touch-icon
```
<link rel="apple-touch-icon" href="apple-touch-icon.png" />
```

html.favicon
```
<link rel="shortcut icon" href="favicon.ico" />
```

html.if-IE
```
<!--[if IE]>

<![endif]-->
```

html.if-IE8under
```
<!--[if lt IE 9]>
<script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<script src="http://css3-mediaqueries-js.googlecode.com/svn/trunk/css3-mediaqueries.js"></script>
<![endif]-->
```

html.include-file
```
<!--#include file="/file/oooo.html" -->
```

html.include-virtual
```
<!--#include virtual="/file/oooo.html" -->
```

html.load-jquery-latest-min
```
<script src="http://code.jquery.com/jquery-latest.min.js"></script>
```

html.load-jquery-latest
```
<script src="http://code.jquery.com/jquery.js"></script>
```

html.load-jquery-1-9-1-min
```
<script src="http://code.jquery.com/jquery-1.9.1.min.js"></script>
```

html.load-jquery-1-9-1
```
<script src="http://code.jquery.com/jquery-1.9.1.js"></script>
```

html.load-jquery-1-10-1-min
```
<script src="http://code.jquery.com/jquery-1.10.1.min.js"></script>
```

html.load-jquery-1-10-1
```
<script src="http://code.jquery.com/jquery-1.10.1.js"></script>
```

html.load-jquery-1-11-1-min
```
<script src="http://code.jquery.com/jquery-1.11.1.js"></script>
```

html.load-jquery-1-11-1
```
<script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>
```

html.OGP
```
<meta property="og:title" content="ページタイトル" />
<meta property="og:type" content="websiteまたはarticle" />
<meta property="og:url" content="ページのURL（http://から指定）" />
<meta property="og:site_name" content="サイト名" />
<meta property="og:description" content="ページの説明" />
<meta property="og:image" content="画像のURL（http://から指定）" />

<meta property="fb:app_id" content="XXXXXXXXXXXXXXXX" />
<meta property="fb:page_id" content="XXXXXXXXXXXXXXXX" />
<meta property="fb:admins" content="XXXXXXXXXXXXXXXX" />
```

html.viewport-device-width
```
<meta name="viewport" content="width=device-width">
```

html.viewport-device-width-noZoom
```
<meta name="viewport" content="width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0,user-scalable=no">
```

html.viewport-device-width-zoom
```
<meta name="viewport" content="width=device-width,initial-scale=1.0">
```

html.viewport-320
```
<meta name="viewport" content="width=320">
```

##HTMLダミー画像
html.placeholder
```
<img src="http://placehold.it/${1:width}x${2:height}">
```

html.placeholder-color
```
<img src="http://placehold.it/${1:width}x${2:height}/${3:color}">
```

html.placeholder-all
```
<img src="http://placehold.it/${1:width}x${2:height}/${3:bgcolor}/${4:textcolor}&text=${5:text}">
```

html.placeholder-jp
```
<img src="http://placehold.jp/${1:width}x${2:height}.png">
```

html.placeholder-jp-all
```
<img src="http://placehold.jp/${1:bgcolor}/${2:textcolor}/${3:width}x${4:height}.png?text=${5:text}">
```

html.img-lpx
```
<img src="http://lorempixel.com/${1:320}/${2:240}/${3:category}" width="$1" height="$2" alt="${3:category}" title="${4:placeholder}">]]></content>
```

html.img-lpxg
```
<img src="http://lorempixel.com/g/${1:320}/${2:240}/${3:category}" width="$1" height="$2" alt="${3:category}" title="${4:placeholder}">]]></content>
```

html.img-lpx-all
```
<img src="http://lorempixel.com/${1:320}/${2:240}/abstract" width="$1" height="$2" alt="abstract" title="${3:placeholder}">
<img src="http://lorempixel.com/${1:320}/${2:240}/animals" width="$1" height="$2" alt="animals" title="${3:placeholder}">
<img src="http://lorempixel.com/${1:320}/${2:240}/business" width="$1" height="$2" alt="business" title="${3:placeholder}">
<img src="http://lorempixel.com/${1:320}/${2:240}/cats" width="$1" height="$2" alt="cats" title="${3:placeholder}">
<img src="http://lorempixel.com/${1:320}/${2:240}/city" width="$1" height="$2" alt="city" title="${3:placeholder}">
<img src="http://lorempixel.com/${1:320}/${2:240}/food" width="$1" height="$2" alt="food" title="${3:placeholder}">
<img src="http://lorempixel.com/${1:320}/${2:240}/nightlife" width="$1" height="$2" alt="nightlife" title="${3:placeholder}">
<img src="http://lorempixel.com/${1:320}/${2:240}/fashion" width="$1" height="$2" alt="fashion" title="${3:placeholder}">
<img src="http://lorempixel.com/${1:320}/${2:240}/people" width="$1" height="$2" alt="people" title="${3:placeholder}">
<img src="http://lorempixel.com/${1:320}/${2:240}/nature" width="$1" height="$2" alt="nature" title="${3:placeholder}">
<img src="http://lorempixel.com/${1:320}/${2:240}/sports" width="$1" height="$2" alt="sports" title="${3:placeholder}">
<img src="http://lorempixel.com/${1:320}/${2:240}/technics" width="$1" height="$2" alt="technics" title="${3:placeholder}">
<img src="http://lorempixel.com/${1:320}/${2:240}/transport" width="$1" height="$2" alt="transport" title="${3:placeholder}">]]></content>
```

html.img-lpx-sample
```
to get a random picture of 400 x 200 pixels
<img src="http://lorempixel.com/400/200">

to get a random gray picture of 400 x 200 pixels
<img src="http://lorempixel.com/g/400/200">

to get a random picture of the sports category
<img src="http://lorempixel.com/400/200/sports">

to get picture no. 1/10 from the sports category
<img src="http://lorempixel.com/400/200/sports/1">

...with a custom text on the random Picture
<img src="http://lorempixel.com/400/200/sports/Dummy-Text">

...with a custom text on the selected Picture
<img src="http://lorempixel.com/400/200/sports/1/Dummy-Text">]]></content>
```


##CSS,Compass
css.yui-reset
```
/* YUI 3.5.0 reset.css (http://developer.yahoo.com/yui/3/cssreset/) - http://cssreset.com */
html{color:#000;background:#FFF}body,div,dl,dt,dd,ul,ol,li,h1,h2,h3,h4,h5,h6,pre,code,form,fieldset,legend,input,textarea,p,blockquote,th,td{margin:0;padding:0}table{border-collapse:collapse;border-spacing:0}fieldset,img{border:0}address,caption,cite,code,dfn,em,strong,th,var{font-style:normal;font-weight:normal}ol,ul{list-style:none}caption,th{text-align:left}h1,h2,h3,h4,h5,h6{font-size:100%;font-weight:normal}q:before,q:after{content:''}abbr,acronym{border:0;font-variant:normal}sup{vertical-align:text-top}sub{vertical-align:text-bottom}input,textarea,select{font-family:inherit;font-size:inherit;font-weight:inherit}input,textarea,select{*font-size:100%}legend{color:#000}#yui3-css-stamp.cssreset{display:none}
```

compass.background-size
```
@include background-size(${1:value});
```

compass.border-image
```
@include border-image(url(${1:value}) 00 round fill);
```

compass.border-radius
```
@include border-radius(${1:value});
```

compass.box-shadow
```
@include box-shadow(${1:value} rgba(0,0,0,${0:0}));
```

compass.box-sizing
```
@include box-sizing(${1:border}-box);
```

compass.clearfix
```
@include clearfix;
```

compass.linear-gradient-rgba
```
@include background(linear-gradient(rgba(${1:0,0,0,0}) 0%, rgba(${0:0,0,0,0}) 100%));
```

compass.linear-gradient
```
@include background(linear-gradient(top, #fff, #eee));
```

compass.opacity
```
@include opacity(${1:.6});
```

compass.rotate
```
@include rotate(${1:value});
```

compass.text-shadow
```
@include text-shadow(rgba(#000, 0.5) 1px 1px 0);
```

compass.transition-duration
```
@include transition-duration(0.3s);
```

##JavaScript,jQuery
jquery.animate
```
\$('.selector').animate({
	'height' : '100px',
	'width' : '0px'},
1000);
```

jquery.click
```
\$('${1:value}').click(function(e) {

	e.preventDefault();
});
```

jquery.css
```
\$('${1:value}').css('${2:value}','${3:value}');
```

jquery.each
```
\$('${1:value}').each(function(){
	var _this = \$(this);

});
```

jquery.function
```
\$(function(){

});
```

jquery.mediaquery
```
//ウィンドウリサイズ毎にmediaQueryControlを実行する
\$(window).resize(function() {
    mediaQueryControl(\$(window).width());
});

function mediaQueryControl(width) {
    if (width > 1200) {
        // ウィンドウ幅1200px以上の場合
    } else if (width > 960) {
        // ウィンドウ幅960px以上の場合
    } else {
        // ウィンドウ幅それ以下の場合
    }
}
```

jquery.mouseover-toggle
```
\$('${1:value}').mouseover(function() {

}).mouseout(function() {

});
```

jquery.mouseover
```
\$('${1:value}').mouseover(function() {

});
```

jquery.ready
```
\$(document).ready(function (\$) {
});
```

jquery.ua
```
\$(function() {
	if(navigator.userAgent.indexOf('iPhone') > 0){
		\$('body').addClass('ua-iphone');
	}
	if(navigator.userAgent.indexOf('Android') > 0){
		\$('body').addClass('ua-android');
	}
	if(navigator.userAgent.indexOf('Android 2') > 0){
		\$('body').addClass('ua-android-2');
	}
	if(navigator.userAgent.indexOf('Android 3') > 0){
		\$('body').addClass('ua-android-3');
	}
	if(navigator.userAgent.indexOf('Android 4') > 0){
		\$('body').addClass('ua-android-4');
	}
	if(navigator.userAgent.indexOf('Mobile') > 0){
		\$('body').addClass('ua-mobile');
	}
	if(navigator.userAgent.indexOf('SC-01C') > 0){
		\$('body').addClass('ua-sc01c');
	}
	if(navigator.userAgent.indexOf('iPad') > 0){
		\$('body').addClass('ua-ipad');
	}
	if(navigator.userAgent.indexOf('iPod') > 0){
		\$('body').addClass('ua-ipod');
	}
	if(navigator.userAgent.indexOf('MSIE') > 0){
		\$('body').addClass('ua-ie');
	}
});
```

js.console
```
console.log('${1:value}=' + ${1:value});
```