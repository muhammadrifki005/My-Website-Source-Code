<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:defaultwidgetversion='2' b:layoutsVersion='3' b:responsive='true' b:templateUrl='vegeclub.xml' b:templateVersion='1.3.3' expr:dir='data:blog.languageDirection' expr:lang='data:blog.locale' lang='id' xml:lang='id' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
    <meta content='width=device-width, initial-scale=1' name='viewport'/>
    <meta content='Situs blog terpercaya,             disertai sumber asalnya             dan tanpa Copyright.' name='description'/>
    <title><data:view.title.escaped/></title>
    <link expr:href='data:blog.url' rel='canonical'/>

    <b:skin version='1.3.3'><![CDATA[/*! normalize.css v3.0.1 | MIT License | git.io/normalize */html{font-family:sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}body{margin:0}article,aside,details,figcaption,figure,footer,header,hgroup,main,nav,section,summary{display:block}audio,canvas,progress,video{display:inline-block;vertical-align:baseline}audio:not([controls]){display:none;height:0}[hidden],template{display:none}a{background:transparent}a:active,a:hover{outline:0}abbr[title]{border-bottom:1px dotted}b,strong{font-weight:bold}dfn{font-style:italic}h1{font-size:2em;margin:.67em 0}mark{background:#ff0;color:#000}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sup{top:-0.5em}sub{bottom:-0.25em}img{border:0}svg:not(:root){overflow:hidden}figure{margin:1em 40px}hr{-moz-box-sizing:content-box;box-sizing:content-box;height:0}pre{overflow:auto}code,kbd,pre,samp{font-family:monospace,monospace;font-size:1em}button,input,optgroup,select,textarea{color:inherit;font:inherit;margin:0}button{overflow:visible}button,select{text-transform:none}button,html input[type="button"],input[type="reset"],input[type="submit"]{-webkit-appearance:button;cursor:pointer}button[disabled],html input[disabled]{cursor:default}button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}input{line-height:normal}input[type="checkbox"],input[type="radio"]{box-sizing:border-box;padding:0}input[type="number"]::-webkit-inner-spin-button,input[type="number"]::-webkit-outer-spin-button{height:auto}input[type="search"]{-webkit-appearance:textfield;-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box}input[type="search"]::-webkit-search-cancel-button,input[type="search"]::-webkit-search-decoration{-webkit-appearance:none}fieldset{border:1px solid #c0c0c0;margin:0 2px;padding:.35em .625em .75em}legend{border:0;padding:0}textarea{overflow:auto}optgroup{font-weight:bold}table{border-collapse:collapse;border-spacing:0}td,th{padding:0}
/*

<!-- Variable definitions -->

<Variable name="keycolor" description="Main Color" type="color" default="#8abc0d" value="#b51200"/>
<Variable name="startSide" description="Start side in blog language" type="automatic" default="left" hideEditor="true" />
<Variable name="endSide" description="End side in blog language" type="automatic" default="right" hideEditor="true" />

<Variable name="generalFont" description="General fallback font" type="font" default="400 16px Ubuntu, sans-serif" hideEditor="true" value="400 16px Ubuntu, sans-serif"/>
<Variable name="generalFontLato" description="General fallback font, Lato" type="font" default="400 16px Lato, sans-serif" hideEditor="true" value="400 16px Lato, sans-serif"/>
<Variable name="blogTitleFont" description="Main blog title font" type="font" default="500 62px Ubuntu, sans-serif" hideEditor="true" value="500 62px Ubuntu, sans-serif"/>
<Variable name="blogTitleFontLato" description="Main blog title font, Lato" type="font" default="700 62px Lato, sans-serif" hideEditor="true" value="700 62px Lato, sans-serif"/>
<Variable name="blogTitleFontMerriweather" description="Main blog title font, Merriweather" type="font" default="700 62px Merriweather, Georgia, serif" hideEditor="true" value="700 62px Merriweather, Georgia, serif"/>
<Variable name="blogCollapsedTitleFont" description="Collapsed blog title font" type="font" default="500 36px Ubuntu, sans-serif" hideEditor="true" value="500 36px Ubuntu, sans-serif"/>
<Variable name="blogCollapsedTitleFontLato" description="Collapsed blog title font, Lato" type="font" default="700 36px Lato, sans-serif" hideEditor="true" value="700 36px Lato, sans-serif"/>
<Variable name="blogCollapsedTitleFontMerriweather" description="Collapsed blog title font, Merriweather" type="font" default="700 36px Merriweather, Georgia, serif" hideEditor="true" value="700 36px Merriweather, Georgia, serif"/>
<Variable name="blogDescriptionFont" description="Main blog description font" type="font" default="italic 300 14px Merriweather, Georgia, serif" hideEditor="true" value="italic 300 14px Merriweather, Georgia, serif"/>
<Variable name="headerItemFont" description="Header item font" type="font" default="700 12px Ubuntu, sans-serif" hideEditor="true" value="700 12px Ubuntu, sans-serif"/>
<Variable name="headerItemFontLato" description="Header item font, Lato" type="font" default="700 12px Lato, sans-serif" hideEditor="true" value="700 12px Lato, sans-serif"/>
<Variable name="textButtonFont" description="Text button font" type="font" default="500 12px Ubuntu, sans-serif" hideEditor="true" value="500 12px Ubuntu, sans-serif"/>
<Variable name="textButtonFontLato" description="Text button font, Lato" type="font" default="500 12px Lato, sans-serif" hideEditor="true" value="500 12px Lato, sans-serif"/>
<Variable name="searchFont" description="Search font" type="font" default="400 16px Merriweather, Georgia, serif" hideEditor="true" value="400 16px Merriweather, Georgia, serif"/>
<Variable name="searchPlaceholderFont" description="Search placeholder" type="font" default="italic 400 15px Merriweather, Georgia, serif" hideEditor="true" value="italic 400 15px Merriweather, Georgia, serif"/>
<Variable name="sidebarTitleFont" description="Sidebar title font" type="font" default="500 16px Ubuntu, sans-serif" hideEditor="true" value="500 16px Ubuntu, sans-serif"/>
<Variable name="sidebarTitleFontLato" description="Sidebar title font, Lato" type="font" default="500 16px Lato, sans-serif" hideEditor="true" value="500 16px Lato, sans-serif"/>
<Variable name="sidebarTitleFontMerriweather" description="Sidebar title font, Merriweather" type="font" default="700 16px Merriweather, Georgia, sans-serif" hideEditor="true" value="700 16px Merriweather, Georgia, sans-serif"/>
<Variable name="sidebarLinkFont" description="Sidebar link font" type="font" default="400 14px Merriweather, Georgia, serif" hideEditor="true" value="400 14px Merriweather, Georgia, serif"/>
<Variable name="sidebarPostTitleFont" description="Sidebar post title font" type="font" default="500 14px Ubuntu, sans-serif" hideEditor="true" value="500 14px Ubuntu, sans-serif"/>
<Variable name="sidebarPostTitleFontLato" description="Sidebar post title font, Lato" type="font" default="500 14px Lato, sans-serif" hideEditor="true" value="500 14px Lato, sans-serif"/>
<Variable name="sidebarPostFont" description="Sidebar post font" type="font" default="italic 400 14px Merriweather, Georgia, serif" hideEditor="true" value="italic 400 14px Merriweather, Georgia, serif"/>
<Variable name="titleFont" description="Title font" type="font" default="500 24px Ubuntu, sans-serif" hideEditor="true" value="500 24px Ubuntu, sans-serif"/>
<Variable name="titleFontLato" description="Title font, Lato" type="font" default="900 24px Lato, sans-serif" hideEditor="true" value="900 24px Lato, sans-serif"/>
<Variable name="titleFontMerriweather" description="Title font, Merriweather" type="font" default="900 24px Merriweather, Georgia, serif" hideEditor="true" value="900 24px Merriweather, Georgia, serif"/>
<Variable name="bylineFont" description="Byline font" type="font" default="italic 400 12px Merriweather, Georgia, serif" hideEditor="true" value="italic 400 12px Merriweather, Georgia, serif"/>
<Variable name="postFilterFont" description="Filter font" type="font" default="italic 400 18px Merriweather, Georgia, serif" hideEditor="true" value="italic 400 18px Merriweather, Georgia, serif"/>
<Variable name="labelsFont" description="Labels font" type="font" default="500 10.5px Ubuntu, sans-serif" hideEditor="true" value="500 10.5px Ubuntu, sans-serif"/>
<Variable name="labelsFontLato" description="Labels font, Lato" type="font" default="500 10px Lato, sans-serif" hideEditor="true" value="500 10px Lato, sans-serif"/>
<Variable name="sharingFont" description="Sharing font" type="font" default="400 14px Ubuntu, sans-serif" hideEditor="true" value="400 14px Ubuntu, sans-serif"/>
<Variable name="sharingFontLato" description="Sharing font, Lato" type="font" default="400 14px Lato, sans-serif" hideEditor="true" value="400 14px Lato, sans-serif"/>
<Variable name="bodyFont" description="Post body font" type="font" default="400 16px Merriweather, Georgia, serif" hideEditor="true" value="400 16px Merriweather, Georgia, serif"/>
<Variable name="bodyLineHeight" description="Line height of body text" type="length" default="32px" hideEditor="true" value="32px"/>
<Variable name="bodyFontSmall" description="Post body font (small)" type="font" default="400 14px Merriweather, Georgia, serif" hideEditor="true" value="400 14px Merriweather, Georgia, serif"/>
<Variable name="bodyLineHeightSmall" description="Line height of body text (small)" type="length" default="24px" hideEditor="true" value="24px"/>

<Variable name="white" description="White" type="color" default="#fff" hideEditor="true" value="#ffffff"/>
<Variable name="black50" description="Black 50" type="color" default="#fafafa" hideEditor="true" value="#fafafa"/>
<Variable name="lightGray" description="Light gray" type="color" default="#f7f7f7" hideEditor="true" value="#f7f7f7"/>
<Variable name="lightishGray" description="Lightish gray" type="color" default="#efefef" hideEditor="true" value="#efefef"/>
<Variable name="black600" description="Black 600" type="color" default="#757575" hideEditor="true" value="#737373"/>
<Variable name="darkishGray" description="Darkish gray" type="color" default="#535353" hideEditor="true" value="#4f4f4f"/>
<Variable name="black800" description="Black 800 " type="color" default="#424242" hideEditor="true" value="#3b3b3b"/>
<Variable name="black900" description="Black 900" type="color" default="#212121" hideEditor="true" value="#000000"/>
<Variable name="offBlack" description="Off black" type="color" default="#1f1f1f" hideEditor="true" value="#000000"/>
<Variable name="black" description="Black" type="color" default="#000" hideEditor="true" value="#000000"/>

<Variable name="vegeGreen" description="Vege green keycolor" type="color" default="#729c0b" hideEditor="true" value="#94190a"/>
<Variable name="lime" description="Lime keycolor" type="color" default="#f4ff81" hideEditor="true" value="#ff808c"/>
<Variable name="blueGray" description="Blue-gray color" type="color" default="#607d8b" hideEditor="true" value="#5e8964"/>
<Variable name="blueGrayDark" description="Blue-gray color (darkened)" type="color" default="#263238" hideEditor="true" value="#172118"/>
<Variable name="beige" description="Beige-blue background color" type="color" default="#eed7c2" hideEditor="true" value="#eec1e1"/>
<Variable name="beigeDark" description="Beige-blue accent color" type="color" default="#da7d5e" hideEditor="true" value="#da5cd2"/>
<Variable name="beigeBlue" description="Beige-blue keycolor" type="color" default="#374561" hideEditor="true" value="#335b46"/>
<Variable name="aqua" description="Aqua keycolor" type="color" default="#18ffff" hideEditor="true" value="#41ff15"/>
<Variable name="peach" description="Peach background" type="color" default="#f59b82" hideEditor="true" value="#f581f1"/>
<Variable name="peachBright" description="Peach keycolor" type="color" default="#ee582e" hideEditor="true" value="#ee2be7"/>
<Variable name="peachDark" description="Peach background (darkened)" type="color" default="#e8937b" hideEditor="true" value="#e87ae4"/>

<Variable name="transpDark03" description="Transparent background (3%)" type="color" default="rgba(0, 0, 0, 0.03)" hideEditor="true" value="rgba(0,0,0,0.027)"/>
<Variable name="transpDark10" description="Transparent background (10%)" type="color" default="rgba(0, 0, 0, 0.1)" hideEditor="true" value="rgba(0,0,0,0.098)"/>
<Variable name="transpDark30" description="Transparent background (30%)" type="color" default="rgba(0, 0, 0, 0.3)" hideEditor="true" value="rgba(0,0,0,0.298)"/>
<Variable name="transpLight" description="Transparent background (light)" type="color" default="rgba(255, 255, 255, 0.3)" hideEditor="true" value="rgba(255,255,255,0.298)"/>
<Variable name="transpBlack" description="Transparent background (black)" type="color" default="rgba(0, 0, 0, 0.87)" hideEditor="true" value="rgba(0,0,0,0.867)"/>

<Group description="Body">
  <Variable name="body.background.color" description="Body background color" type="color" default="#f7f7f7"  value="#FFFFFF"/>
  <Variable name="body.background" description="Background" type="background" color="#f7f7f7" default="$(color) none repeat scroll top left"  value="$(color) none repeat scroll top left"/>
  <Variable name="body.text.font" description="Font" type="font" default="$(generalFont)"  value="400 16px Ubuntu, sans-serif"/>
  <Variable name="body.text.color" description="Color" type="color" default="#000000"  value="#000000"/>
  <Variable name="body.link.color" description="Link color" type="color" default="$(keycolor)"  value="#B51200"/>
  <Variable name="body.link.visited.color" description="Visited Link Color" type="color" default="$(body.link.color)"  value="#B51200"/>
  <Variable name="body.link.hover.color" description="Link Hover Color" type="color" default="$(body.link.color)"  value="#0F9D58"/>
  <Variable name="body.button.font" description="Button font" type="font" default="$(textButtonFont)"  value="500 12px Ubuntu, sans-serif"/>
  <Variable name="body.button.color" description="Button color" type="color" default="$(keycolor)"  value="#B51200"/>
</Group>

<Group description="Blog title" selector="div.widget.Header">
  <Variable name="blog.title.font" description="Title Font" type="font" default="$(blogTitleFont)"  value="500 62px Ubuntu, sans-serif"/>
  <Variable name="blog.collapsed.title.font" description="Collapsed title font" type="font" default="$(blogCollapsedTitleFont)"  value="500 36px Ubuntu, sans-serif"/>
  <Variable name="blog.collapsed.title.color" description="Collapsed title color" type="color" default="$(blog.title.color)"  value="#000000"/>
  <Variable name="blog.title.color" description="Title color" type="color" default="#1f1f1f"  value="#000000"/>
  <Variable name="header.background.color" description="Header bar color" type="color" default="#efefef"  value="#EEEEEE"/>
  <Variable name="header.icons.color" description="Header icons color" type="color" default="$(keycolor)"  value="#B51200"/>
  <Variable name="header.separator.color" description="Header separator color" type="color" default="rgba(0, 0, 0, 0.3)"  value="rgba(0,0,0,0.298)"/>
  <Variable name="blog.description.font" description="Description font" type="font" default="$(blogDescriptionFont)"  value="italic 300 14px Merriweather, Georgia, serif"/>
  <Variable name="blog.description.color" description="Description Color" type="color" default="#1f1f1f"  value="#000000"/>
</Group>

<Group description="Tabs" selector="div.widget.PageList">
  <Variable name="tabs.text.font" description="Font" type="font" default="$(headerItemFont)"  value="700 12px Ubuntu, sans-serif"/>
  <Variable name="tabs.text.color" description="Text color" type="color" default="$(keycolor)"  value="#B51200"/>
  <Variable name="tabs.selected.color" description="Selected color" type="color" default="$(tabs.text.color)"  value="#B51200"/>
  <Variable name="tabs.background.color" description="Tabs background color" type="color" default="#fff"  value="#FFFFFF"/>
</Group>

<Group description="Posts" selector="div.widget.Blog">
  <Variable name="posts.background.color" description="Post background color" type="color" default="#fff"  value="#FFFFFF"/>
  <Variable name="posts.title.color" description="Post title color" type="color" default="#212121"  value="#000000"/>
  <Variable name="posts.title.font" description="Post title font" type="font" default="$(titleFont)"  value="500 24px Ubuntu, sans-serif"/>
  <Variable name="posts.byline.color" description="Post byline color" type="color" default="#757575"  value="#000000"/>
  <Variable name="posts.byline.font" description="Post byline font" type="font" default="$(bylineFont)"  value="italic 400 12px Merriweather, Georgia, serif"/>
  <Variable name="posts.text.font" description="Post text font" type="font" default="$(bodyFont)"  value="400 16px Merriweather, Georgia, serif"/>
  <Variable name="posts.text.color" description="Post text color" type="color" default="$(body.text.color)"  value="#000000"/>
  <Variable name="posts.text.lineHeight" description="Post text line height" min="10px" max="60px" type="length" default="$(bodyLineHeight)"  value="32px"/>
  <Variable name="posts.snippet.text.font" description="Post snippet text font" type="font" default="$(bodyFontSmall)"  value="400 14px Merriweather, Georgia, serif"/>
  <Variable name="posts.snippet.text.lineHeight" description="Post snippet text line height" min="10px" max="60px" type="length" default="$(bodyLineHeightSmall)"  value="24px"/>
  <Variable name="posts.link.color" description="Post link color" type="color" default="$(body.link.color)"  value="#B51200"/>
  <Variable name="posts.icons.color" description="Post icons color" type="color" default="$(posts.link.color)"  value="#B51200"/>
  <Variable name="posts.border.radius" description="Post border radius" type="length" default="0px" min="0px" max="32px"  value="0px"/>
  <Variable name="postFilter.background.color" description="Filter background color" type="color" default="$(keycolor)"  value="#B51200"/>
  <Variable name="postFilter.message.font" description="Filter text font" type="font" default="$(postFilterFont)"  value="italic 400 18px Merriweather, Georgia, serif"/>
  <Variable name="postFilter.message.color" description="Filter text color" type="color" default="$(posts.background.color)"  value="#FFFFFF"/>
  <Variable name="postFilter.message.link.color" description="Filter keyword color" type="color" default="$(postFilter.message.color)"  value="#FFFFFF"/>
  <Variable name="labels.font" description="Label font size" type="font" default="$(labelsFont)"  value="500 10.5px Ubuntu, sans-serif"/>
</Group>

<Group description="Sharing" selector=".sharing">
  <Variable name="sharing.background.color" description="Sharing background color" type="color" default="$(posts.background.color)"  value="#FFFFFF"/>
  <Variable name="sharing.text.font" description="Sharing text font" type="font" default="$(sharingFont)"  value="400 14px Ubuntu, sans-serif"/>
  <Variable name="sharing.text.color" description="Sharing text color" type="color" default="$(posts.text.color)"  value="#000000"/>
  <Variable name="sharing.icons.color" description="Sharing icons color" type="color" default="$(posts.icons.color)"  value="#000000"/>
</Group>

<Group description="Blockquotes">
  <Variable name="blockquote.color" description="Blockquote color" type="color" default="#424242"  value="#000000"/>
  <Variable name="blockquote.font" description="Blockquote font" type="font" default="$(body.text.font)"  value="400 16px Ubuntu, sans-serif"/>
</Group>

<Group description="Pictures">
  <Variable name="picture.caption.text.color" description="Caption text color" type="color" default="#424242"  value="#000000"/>
  <Variable name="picture.caption.font" description="Caption font" type="font" default="$(body.text.font)"  value="400 16px Ubuntu, sans-serif"/>
</Group>

<Group description="Sidebar" selector="div.sidebar_feed">
  <Variable name="sidebar.background.color" description="Background color" type="color" default="$(body.background.color)"  value="#FFFFFF"/>
  <Variable name="sidebar.separator.color" description="Separator color" type="color" default="rgba(0, 0, 0, 0.12)"  value="#9E9E9E"/>
  <Variable name="widget.title.font" description="Gadget title font" type="font" default="$(sidebarTitleFont)"  value="500 16px Ubuntu, sans-serif"/>
  <Variable name="widget.title.color" description="Gadget title color" type="color" default="$(body.text.color)"  value="#000000"/>
  <Variable name="sidebar.icons.color" description="Sidebar icons color" type="color" default="$(keycolor)"  value="#000000"/>
  <Variable name="sidebar.link.font" description="Link font" type="font" default="$(sidebarLinkFont)"  value="400 14px Merriweather, Georgia, serif"/>
  <Variable name="sidebar.link.color" description="Link color" type="color" default="$(keycolor)"  value="#B51200"/>
  <Variable name="sidebar.posts.title.font" description="Post title font" type="font" default="$(sidebarPostTitleFont)"  value="500 14px Ubuntu, sans-serif"/>
  <Variable name="sidebar.posts.text.font" description="Post text font" type="font" default="$(sidebarPostFont)"  value="italic 400 14px Merriweather, Georgia, serif"/>
  <Variable name="sidebar.posts.text.color" description="Post text color" type="color" default="#535353"  value="#000000"/>
</Group>

<Group description="Search bar" selector="div.search">
  <Variable name="search.text.color" description="Text color" type="color" default="$(offBlack)"  value="#000000"/>
  <Variable name="search.icon.color" description="Icon color" type="color" default="rgba(0, 0, 0, 0.38)"  value="#000000"/>
  <Variable name="search.font" description="Text font" type="font" default="$(searchFont)"  value="400 16px Merriweather, Georgia, serif"/>
  <Variable name="search.placeholder.font" description="Placeholder text font" type="font" default="$(searchPlaceholderFont)"  value="italic 400 15px Merriweather, Georgia, serif"/>
  <Variable name="search.placeholder.color" description="Placeholder text color" type="color" default="rgba(0, 0, 0, 0.38)"  value="#000000"/>
  <Variable name="search.background.color" description="Background color" type="color" default="rgba(0, 0, 0, 0.03)"  value="#FFFFFF"/>
</Group>

<Group description="Attribution" selector=".widget.Attribution">
  <Variable name="attribution.text.color" description="Attribution text color" type="color" default="$(body.text.color)"  value="#000000"/>
  <Variable name="attribution.link.color" description="Attribution link color" type="color" default="$(body.link.color)"  value="#B51200"/>
  <Variable name="attribution.icon.color" description="Attribution icon color" type="color" default="#757575" hideEditor="true"  value="#000000"/>
</Group>

<Group description="Widths">
  <Variable name="sidebar.width" description="Sidebar width" type="length" min="100px" max="1000px" default="280px"  value="280px"/>
  <Variable name="posts.width.stream" description="Post width (stream)" type="length" min="100px" max="1000px" default="385px"  value="385px"/>
</Group>
 */

/*!************************************************
 * Blogger Template Style
 * Name: Emporio
 **************************************************/
body{
overflow-wrap:break-word;
word-break:break-word;
word-wrap:break-word
}
.hidden{
display:none
}
.invisible{
visibility:hidden
}
.container::after,.float-container::after{
clear:both;
content:"";
display:table
}
.clearboth{
clear:both
}
#comments .comment .comment-actions,.subscribe-popup .FollowByEmail .follow-by-email-submit{
background:0 0;
border:0;
box-shadow:none;
color:$(body.link.color);
cursor:pointer;
font-size:14px;
font-weight:700;
outline:0;
text-decoration:none;
text-transform:uppercase;
width:auto
}
.dim-overlay{
background-color:rgba(0,0,0,.54);
height:100vh;
left:0;
position:fixed;
top:0;
width:100%
}
#sharing-dim-overlay{
background-color:transparent
}
input::-ms-clear{
display:none
}
.blogger-logo,.svg-icon-24.blogger-logo{
fill:#ff9800;
opacity:1
}
.skip-navigation{
background-color:#fff;
box-sizing:border-box;
color:#000;
display:block;
height:0;
left:0;
line-height:50px;
overflow:hidden;
padding-top:0;
position:fixed;
text-align:center;
top:0;
-webkit-transition:box-shadow .3s,height .3s,padding-top .3s;
transition:box-shadow .3s,height .3s,padding-top .3s;
width:100%;
z-index:900
}
.skip-navigation:focus{
box-shadow:0 4px 5px 0 rgba(0,0,0,.14),0 1px 10px 0 rgba(0,0,0,.12),0 2px 4px -1px rgba(0,0,0,.2);
height:50px
}
#main{
outline:0
}
.main-heading{
position:absolute;
clip:rect(1px,1px,1px,1px);
padding:0;
border:0;
height:1px;
width:1px;
overflow:hidden
}
.Attribution{
margin-top:1em;
text-align:center
}
.Attribution .blogger img,.Attribution .blogger svg{
vertical-align:bottom
}
.Attribution .blogger img{
margin-$endSide:.5em
}
.Attribution div{
line-height:24px;
margin-top:.5em
}
.Attribution .copyright,.Attribution .image-attribution{
font-size:.7em;
margin-top:1.5em
}
.BLOG_mobile_video_class{
display:none
}
.bg-photo{
background-attachment:scroll!important
}
body .CSS_LIGHTBOX{
z-index:900
}
.extendable .show-less,.extendable .show-more{
border-color:$(body.link.color);
color:$(body.link.color);
margin-top:8px
}
.extendable .show-less.hidden,.extendable .show-more.hidden{
display:none
}
.inline-ad{
display:none;
max-width:100%;
overflow:hidden
}
.adsbygoogle{
display:block
}
#cookieChoiceInfo{
bottom:0;
top:auto
}
iframe.b-hbp-video{
border:0
}
.post-body img{
max-width:100%
}
.post-body iframe{
max-width:100%
}
.post-body a[imageanchor="1"]{
display:inline-block
}
.byline{
margin-$endSide:1em
}
.byline:last-child{
margin-$endSide:0
}
.link-copied-dialog{
max-width:520px;
outline:0
}
.link-copied-dialog .modal-dialog-buttons{
margin-top:8px
}
.link-copied-dialog .goog-buttonset-default{
background:0 0;
border:0
}
.link-copied-dialog .goog-buttonset-default:focus{
outline:0
}
.paging-control-container{
margin-bottom:16px
}
.paging-control-container .paging-control{
display:inline-block
}
.paging-control-container .comment-range-text::after,.paging-control-container .paging-control{
color:$(body.link.color)
}
.paging-control-container .comment-range-text,.paging-control-container .paging-control{
margin-$endSide:8px
}
.paging-control-container .comment-range-text::after,.paging-control-container .paging-control::after{
content:"\b7";
cursor:default;
padding-$startSide:8px;
pointer-events:none
}
.paging-control-container .comment-range-text:last-child::after,.paging-control-container .paging-control:last-child::after{
content:none
}
.byline.reactions iframe{
height:20px
}
.b-notification{
color:#000;
background-color:#fff;
border-bottom:solid 1px #000;
box-sizing:border-box;
padding:16px 32px;
text-align:center
}
.b-notification.visible{
-webkit-transition:margin-top .3s cubic-bezier(.4,0,.2,1);
transition:margin-top .3s cubic-bezier(.4,0,.2,1)
}
.b-notification.invisible{
position:absolute
}
.b-notification-close{
position:absolute;
right:8px;
top:8px
}
.no-posts-message{
line-height:40px;
text-align:center
}
@media screen and (max-width:745px){
body.item-view .post-body a[imageanchor="1"][style*="float: left;"],body.item-view .post-body a[imageanchor="1"][style*="float: right;"]{
float:none!important;
clear:none!important
}
body.item-view .post-body a[imageanchor="1"] img{
display:block;
height:auto;
margin:0 auto
}
body.item-view .post-body>.separator:first-child>a[imageanchor="1"]:first-child{
margin-top:20px
}
.post-body a[imageanchor]{
display:block
}
body.item-view .post-body a[imageanchor="1"]{
margin-left:0!important;
margin-right:0!important
}
body.item-view .post-body a[imageanchor="1"]+a[imageanchor="1"]{
margin-top:16px
}
}
.item-control{
display:none
}
#comments{
border-top:1px dashed rgba(0,0,0,.54);
margin-top:20px;
padding:20px
}
#comments .comment-thread ol{
margin:0;
padding-left:0;
padding-$startSide:0
}
#comments .comment .comment-replybox-single,#comments .comment-thread .comment-replies{
margin-left:60px
}
#comments .comment-thread .thread-count{
display:none
}
#comments .comment{
list-style-type:none;
padding:0 0 30px;
position:relative
}
#comments .comment .comment{
padding-bottom:8px
}
.comment .avatar-image-container{
position:absolute
}
.comment .avatar-image-container img{
border-radius:50%
}
.avatar-image-container svg,.comment .avatar-image-container .avatar-icon{
border-radius:50%;
border:solid 1px $(posts.icons.color);
box-sizing:border-box;
fill:$(posts.icons.color);
height:35px;
margin:0;
padding:7px;
width:35px
}
.comment .comment-block{
margin-top:10px;
margin-$startSide:60px;
padding-bottom:0
}
#comments .comment-author-header-wrapper{
margin-left:40px
}
#comments .comment .thread-expanded .comment-block{
padding-bottom:20px
}
#comments .comment .comment-header .user,#comments .comment .comment-header .user a{
color:$(posts.title.color);
font-style:normal;
font-weight:700
}
#comments .comment .comment-actions{
bottom:0;
margin-bottom:15px;
position:absolute
}
#comments .comment .comment-actions>*{
margin-right:8px
}
#comments .comment .comment-header .datetime{
bottom:0;
color:rgba($(posts.title.color.red),$(posts.title.color.green),$(posts.title.color.blue),.54);
display:inline-block;
font-size:13px;
font-style:italic;
margin-$startSide:8px
}
#comments .comment .comment-footer .comment-timestamp a,#comments .comment .comment-header .datetime a{
color:rgba($(posts.title.color.red),$(posts.title.color.green),$(posts.title.color.blue),.54)
}
#comments .comment .comment-content,.comment .comment-body{
margin-top:12px;
word-break:break-word
}
.comment-body{
margin-bottom:12px
}
#comments.embed[data-num-comments="0"]{
border:0;
margin-top:0;
padding-top:0
}
#comments.embed[data-num-comments="0"] #comment-post-message,#comments.embed[data-num-comments="0"] div.comment-form>p,#comments.embed[data-num-comments="0"] p.comment-footer{
display:none
}
#comment-editor-src{
display:none
}
.comments .comments-content .loadmore.loaded{
max-height:0;
opacity:0;
overflow:hidden
}
.extendable .remaining-items{
height:0;
overflow:hidden;
-webkit-transition:height .3s cubic-bezier(.4,0,.2,1);
transition:height .3s cubic-bezier(.4,0,.2,1)
}
.extendable .remaining-items.expanded{
height:auto
}
.svg-icon-24,.svg-icon-24-button{
cursor:pointer;
height:24px;
width:24px;
min-width:24px
}
.touch-icon{
margin:-12px;
padding:12px
}
.touch-icon:active,.touch-icon:focus{
background-color:rgba(153,153,153,.4);
border-radius:50%
}
svg:not(:root).touch-icon{
overflow:visible
}
html[dir=rtl] .rtl-reversible-icon{
-webkit-transform:scaleX(-1);
-ms-transform:scaleX(-1);
transform:scaleX(-1)
}
.svg-icon-24-button,.touch-icon-button{
background:0 0;
border:0;
margin:0;
outline:0;
padding:0
}
.touch-icon-button .touch-icon:active,.touch-icon-button .touch-icon:focus{
background-color:transparent
}
.touch-icon-button:active .touch-icon,.touch-icon-button:focus .touch-icon{
background-color:rgba(153,153,153,.4);
border-radius:50%
}
.Profile .default-avatar-wrapper .avatar-icon{
border-radius:50%;
border:solid 1px $(sidebar.icons.color);
box-sizing:border-box;
fill:$(sidebar.icons.color);
margin:0
}
.Profile .individual .default-avatar-wrapper .avatar-icon{
padding:25px
}
.Profile .individual .avatar-icon,.Profile .individual .profile-img{
height:90px;
width:90px
}
.Profile .team .default-avatar-wrapper .avatar-icon{
padding:8px
}
.Profile .team .avatar-icon,.Profile .team .default-avatar-wrapper,.Profile .team .profile-img{
height:40px;
width:40px
}
.snippet-container{
margin:0;
position:relative;
overflow:hidden
}
.snippet-fade{
bottom:0;
box-sizing:border-box;
position:absolute;
width:96px
}
.snippet-fade{
$endSide:0
}
.snippet-fade:after{
content:"\2026"
}
.snippet-fade:after{
float:$endSide
}
.centered-top-container.sticky{
left:0;
position:fixed;
right:0;
top:0;
width:auto;
z-index:8;
-webkit-transition-property:opacity,-webkit-transform;
transition-property:opacity,-webkit-transform;
transition-property:transform,opacity;
transition-property:transform,opacity,-webkit-transform;
-webkit-transition-duration:.2s;
transition-duration:.2s;
-webkit-transition-timing-function:cubic-bezier(.4,0,.2,1);
transition-timing-function:cubic-bezier(.4,0,.2,1)
}
.centered-top-placeholder{
display:none
}
.collapsed-header .centered-top-placeholder{
display:block
}
.centered-top-container .Header .replaced h1,.centered-top-placeholder .Header .replaced h1{
display:none
}
.centered-top-container.sticky .Header .replaced h1{
display:block
}
.centered-top-container.sticky .Header .header-widget{
background:0 0
}
.centered-top-container.sticky .Header .header-image-wrapper{
display:none
}
.centered-top-container img,.centered-top-placeholder img{
max-width:100%
}
.collapsible{
-webkit-transition:height .3s cubic-bezier(.4,0,.2,1);
transition:height .3s cubic-bezier(.4,0,.2,1)
}
.collapsible,.collapsible>summary{
display:block;
overflow:hidden
}
.collapsible>:not(summary){
display:none
}
.collapsible[open]>:not(summary){
display:block
}
.collapsible:focus,.collapsible>summary:focus{
outline:0
}
.collapsible>summary{
cursor:pointer;
display:block;
padding:0
}
.collapsible:focus>summary,.collapsible>summary:focus{
background-color:transparent
}
.collapsible>summary::-webkit-details-marker{
display:none
}
.collapsible-title{
-webkit-box-align:center;
-webkit-align-items:center;
-ms-flex-align:center;
align-items:center;
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex
}
.collapsible-title .title{
-webkit-box-flex:1;
-webkit-flex:1 1 auto;
-ms-flex:1 1 auto;
flex:1 1 auto;
-webkit-box-ordinal-group:1;
-webkit-order:0;
-ms-flex-order:0;
order:0;
overflow:hidden;
text-overflow:ellipsis;
white-space:nowrap
}
.collapsible-title .chevron-down,.collapsible[open] .collapsible-title .chevron-up{
display:block
}
.collapsible-title .chevron-up,.collapsible[open] .collapsible-title .chevron-down{
display:none
}
.flat-button{
cursor:pointer;
display:inline-block;
font-weight:700;
text-transform:uppercase;
border-radius:2px;
padding:8px;
margin:-8px
}
.flat-icon-button{
background:0 0;
border:0;
margin:0;
outline:0;
padding:0;
margin:-12px;
padding:12px;
cursor:pointer;
box-sizing:content-box;
display:inline-block;
line-height:0
}
.flat-icon-button,.flat-icon-button .splash-wrapper{
border-radius:50%
}
.flat-icon-button .splash.animate{
-webkit-animation-duration:.3s;
animation-duration:.3s
}
body#layout .bg-photo,body#layout .bg-photo-overlay{
display:none
}
body#layout .page_body{
padding:0;
position:relative;
top:0
}
body#layout .page{
display:inline-block;
left:inherit;
position:relative;
vertical-align:top;
width:540px
}
body#layout .centered{
max-width:954px
}
body#layout .navigation{
display:none
}
body#layout .sidebar-container{
display:inline-block;
width:40%
}
body#layout .hamburger-menu,body#layout .search{
display:none
}
.overflowable-container{
max-height:$(tabs.text.font.size + 2 * 16px);
overflow:hidden;
position:relative
}
.overflow-button{
cursor:pointer
}
#overflowable-dim-overlay{
background:0 0
}
.overflow-popup{
box-shadow:0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12);
background-color:$(tabs.background.color);
left:0;
max-width:calc(100% - 32px);
position:absolute;
top:0;
visibility:hidden;
z-index:101
}
.overflow-popup ul{
list-style:none
}
.overflow-popup .tabs li,.overflow-popup li{
display:block;
height:auto
}
.overflow-popup .tabs li{
padding-left:0;
padding-right:0
}
.overflow-button.hidden,.overflow-popup .tabs li.hidden,.overflow-popup li.hidden{
display:none
}
.widget.Sharing .sharing-button{
display:none
}
.widget.Sharing .sharing-buttons li{
padding:0
}
.widget.Sharing .sharing-buttons li span{
display:none
}
.post-share-buttons{
position:relative
}
.centered-bottom .share-buttons .svg-icon-24,.share-buttons .svg-icon-24{
fill:$(sharing.icons.color)
}
.sharing-open.touch-icon-button:active .touch-icon,.sharing-open.touch-icon-button:focus .touch-icon{
background-color:transparent
}
.share-buttons{
background-color:$(sharing.background.color);
border-radius:2px;
box-shadow:0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12);
color:$(sharing.text.color);
list-style:none;
margin:0;
padding:8px 0;
position:absolute;
top:-11px;
min-width:200px;
z-index:101
}
.share-buttons.hidden{
display:none
}
.sharing-button{
background:0 0;
border:0;
margin:0;
outline:0;
padding:0;
cursor:pointer
}
.share-buttons li{
margin:0;
height:48px
}
.share-buttons li:last-child{
margin-bottom:0
}
.share-buttons li .sharing-platform-button{
box-sizing:border-box;
cursor:pointer;
display:block;
height:100%;
margin-bottom:0;
padding:0 16px;
position:relative;
width:100%
}
.share-buttons li .sharing-platform-button:focus,.share-buttons li .sharing-platform-button:hover{
background-color:rgba(128,128,128,.1);
outline:0
}
.share-buttons li svg[class*=" sharing-"],.share-buttons li svg[class^=sharing-]{
position:absolute;
top:10px
}
.share-buttons li span.sharing-platform-button{
position:relative;
top:0
}
.share-buttons li .platform-sharing-text{
display:block;
font-size:16px;
line-height:48px;
white-space:nowrap
}
.share-buttons li .platform-sharing-text{
margin-$startSide:56px
}
.sidebar-container{
background-color:$(sidebar.background.color);
max-width:$(sidebar.width);
overflow-y:auto;
-webkit-transition-property:-webkit-transform;
transition-property:-webkit-transform;
transition-property:transform;
transition-property:transform,-webkit-transform;
-webkit-transition-duration:.3s;
transition-duration:.3s;
-webkit-transition-timing-function:cubic-bezier(0,0,.2,1);
transition-timing-function:cubic-bezier(0,0,.2,1);
width:$(sidebar.width);
z-index:101;
-webkit-overflow-scrolling:touch
}
.sidebar-container .navigation{
line-height:0;
padding:16px
}
.sidebar-container .sidebar-back{
cursor:pointer
}
.sidebar-container .widget{
background:0 0;
margin:0 16px;
padding:16px 0
}
.sidebar-container .widget .title{
color:$(widget.title.color);
margin:0
}
.sidebar-container .widget ul{
list-style:none;
margin:0;
padding:0
}
.sidebar-container .widget ul ul{
margin-$startSide:1em
}
.sidebar-container .widget li{
font-size:16px;
line-height:normal
}
.sidebar-container .widget+.widget{
border-top:1px solid $(sidebar.separator.color)
}
.BlogArchive li{
margin:16px 0
}
.BlogArchive li:last-child{
margin-bottom:0
}
.Label li a{
display:inline-block
}
.BlogArchive .post-count,.Label .label-count{
float:$endSide;
margin-$startSide:.25em
}
.BlogArchive .post-count::before,.Label .label-count::before{
content:"("
}
.BlogArchive .post-count::after,.Label .label-count::after{
content:")"
}
.widget.Translate .skiptranslate>div{
display:block!important
}
.widget.Profile .profile-link{
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex
}
.widget.Profile .team-member .default-avatar-wrapper,.widget.Profile .team-member .profile-img{
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto;
margin-$endSide:1em
}
.widget.Profile .individual .profile-link{
-webkit-box-orient:vertical;
-webkit-box-direction:normal;
-webkit-flex-direction:column;
-ms-flex-direction:column;
flex-direction:column
}
.widget.Profile .team .profile-link .profile-name{
-webkit-align-self:center;
-ms-flex-item-align:center;
align-self:center;
display:block;
-webkit-box-flex:1;
-webkit-flex:1 1 auto;
-ms-flex:1 1 auto;
flex:1 1 auto
}
.dim-overlay{
background-color:rgba(0,0,0,.54);
z-index:100
}
body.sidebar-visible{
overflow-y:hidden
}
@media screen and (max-width:$(posts.width.stream + 15px + sidebar.width)){
.sidebar-container{
bottom:0;
position:fixed;
top:0;
left:auto;
right:0
}
.sidebar-container.sidebar-invisible{
-webkit-transition-timing-function:cubic-bezier(.4,0,.6,1);
transition-timing-function:cubic-bezier(.4,0,.6,1);
-webkit-transform:translateX(100%);
-ms-transform:translateX(100%);
transform:translateX(100%)
}
}
.dialog{
box-shadow:0 2px 2px 0 rgba(0,0,0,.14),0 3px 1px -2px rgba(0,0,0,.2),0 1px 5px 0 rgba(0,0,0,.12);
background:$(posts.background.color);
box-sizing:border-box;
color:$(posts.text.color);
padding:30px;
position:fixed;
text-align:center;
width:calc(100% - 24px);
z-index:101
}
.dialog input[type=email],.dialog input[type=text]{
background-color:transparent;
border:0;
border-bottom:solid 1px rgba($(body.text.color.red),$(body.text.color.green),$(body.text.color.blue),.12);
color:$(posts.text.color);
display:block;
font-family:$(body.text.font.family);
font-size:16px;
line-height:24px;
margin:auto;
padding-bottom:7px;
outline:0;
text-align:center;
width:100%
}
.dialog input[type=email]::-webkit-input-placeholder,.dialog input[type=text]::-webkit-input-placeholder{
color:rgba($(posts.text.color.red),$(posts.text.color.green),$(posts.text.color.blue),.5)
}
.dialog input[type=email]::-moz-placeholder,.dialog input[type=text]::-moz-placeholder{
color:rgba($(posts.text.color.red),$(posts.text.color.green),$(posts.text.color.blue),.5)
}
.dialog input[type=email]:-ms-input-placeholder,.dialog input[type=text]:-ms-input-placeholder{
color:rgba($(posts.text.color.red),$(posts.text.color.green),$(posts.text.color.blue),.5)
}
.dialog input[type=email]::-ms-input-placeholder,.dialog input[type=text]::-ms-input-placeholder{
color:rgba($(posts.text.color.red),$(posts.text.color.green),$(posts.text.color.blue),.5)
}
.dialog input[type=email]::placeholder,.dialog input[type=text]::placeholder{
color:rgba($(posts.text.color.red),$(posts.text.color.green),$(posts.text.color.blue),.5)
}
.dialog input[type=email]:focus,.dialog input[type=text]:focus{
border-bottom:solid 2px $(posts.link.color);
padding-bottom:6px
}
.dialog input.no-cursor{
color:transparent;
text-shadow:0 0 0 $(posts.text.color)
}
.dialog input.no-cursor:focus{
outline:0
}
.dialog input.no-cursor:focus{
outline:0
}
.dialog input[type=submit]{
font-family:$(body.text.font.family)
}
.dialog .goog-buttonset-default{
color:$(posts.link.color)
}
.loading-spinner-large{
-webkit-animation:mspin-rotate 1.568s infinite linear;
animation:mspin-rotate 1.568s infinite linear;
height:48px;
overflow:hidden;
position:absolute;
width:48px;
z-index:200
}
.loading-spinner-large>div{
-webkit-animation:mspin-revrot 5332ms infinite steps(4);
animation:mspin-revrot 5332ms infinite steps(4)
}
.loading-spinner-large>div>div{
-webkit-animation:mspin-singlecolor-large-film 1333ms infinite steps(81);
animation:mspin-singlecolor-large-film 1333ms infinite steps(81);
background-size:100%;
height:48px;
width:3888px
}
.mspin-black-large>div>div,.mspin-grey_54-large>div>div{
background-image:url(https://www.blogblog.com/indie/mspin_black_large.svg)
}
.mspin-white-large>div>div{
background-image:url(https://www.blogblog.com/indie/mspin_white_large.svg)
}
.mspin-grey_54-large{
opacity:.54
}
@-webkit-keyframes mspin-singlecolor-large-film{
from{
-webkit-transform:translateX(0);
transform:translateX(0)
}
to{
-webkit-transform:translateX(-3888px);
transform:translateX(-3888px)
}
}
@keyframes mspin-singlecolor-large-film{
from{
-webkit-transform:translateX(0);
transform:translateX(0)
}
to{
-webkit-transform:translateX(-3888px);
transform:translateX(-3888px)
}
}
@-webkit-keyframes mspin-rotate{
from{
-webkit-transform:rotate(0);
transform:rotate(0)
}
to{
-webkit-transform:rotate(360deg);
transform:rotate(360deg)
}
}
@keyframes mspin-rotate{
from{
-webkit-transform:rotate(0);
transform:rotate(0)
}
to{
-webkit-transform:rotate(360deg);
transform:rotate(360deg)
}
}
@-webkit-keyframes mspin-revrot{
from{
-webkit-transform:rotate(0);
transform:rotate(0)
}
to{
-webkit-transform:rotate(-360deg);
transform:rotate(-360deg)
}
}
@keyframes mspin-revrot{
from{
-webkit-transform:rotate(0);
transform:rotate(0)
}
to{
-webkit-transform:rotate(-360deg);
transform:rotate(-360deg)
}
}
.subscribe-popup{
max-width:364px
}
.subscribe-popup h3{
color:$(posts.title.color);
font-size:1.8em;
margin-top:0
}
.subscribe-popup .FollowByEmail h3{
display:none
}
.subscribe-popup .FollowByEmail .follow-by-email-submit{
color:$(posts.link.color);
display:inline-block;
margin:0 auto;
margin-top:24px;
width:auto;
white-space:normal
}
.subscribe-popup .FollowByEmail .follow-by-email-submit:disabled{
cursor:default;
opacity:.3
}
@media (max-width:800px){
.blog-name div.widget.Subscribe{
margin-bottom:16px
}
body.item-view .blog-name div.widget.Subscribe{
margin:8px auto 16px auto;
width:100%
}
}
.sidebar-container .svg-icon-24{
fill:$(sidebar.icons.color)
}
.centered-top .svg-icon-24{
fill:$(header.icons.color)
}
.centered-bottom .svg-icon-24.touch-icon,.centered-bottom a .svg-icon-24,.centered-bottom button .svg-icon-24{
fill:$(body.link.color)
}
.post-wrapper .svg-icon-24.touch-icon,.post-wrapper a .svg-icon-24,.post-wrapper button .svg-icon-24{
fill:$(posts.icons.color)
}
.centered-bottom .share-buttons .svg-icon-24,.share-buttons .svg-icon-24{
fill:$(sharing.icons.color)
}
.svg-icon-24.hamburger-menu{
fill:$(body.link.color)
}
body#layout .page_body{
padding:0;
position:relative;
top:0
}
body#layout .page{
display:inline-block;
left:inherit;
position:relative;
vertical-align:top;
width:540px
}
body{
background:$(body.background);
background-color:$(body.background.color);
background-size:cover;
color:$(body.text.color);
font:$(body.text.font);
margin:0;
min-height:100vh
}
h3,h3.title{
color:$(body.text.color)
}
.post-wrapper .post-title,.post-wrapper .post-title a,.post-wrapper .post-title a:hover,.post-wrapper .post-title a:visited{
color:$(posts.title.color)
}
a{
color:$(body.link.color);
font-style:normal;
text-decoration:none
}
a:visited{
color:$(body.link.visited.color)
}
a:hover{
color:$(body.link.hover.color)
}
blockquote{
color:$(blockquote.color);
font:$(blockquote.font);
font-size:x-large;
font-style:italic;
font-weight:300;
text-align:center
}
.dim-overlay{
z-index:100
}
.page{
box-sizing:border-box;
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
-webkit-box-orient:vertical;
-webkit-box-direction:normal;
-webkit-flex-direction:column;
-ms-flex-direction:column;
flex-direction:column;
min-height:100vh;
padding-bottom:1em
}
.page>*{
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto
}
.page>#footer{
margin-top:auto
}
.bg-photo-container{
overflow:hidden
}
.bg-photo-container,.bg-photo-container .bg-photo{
height:464px;
width:100%
}
.bg-photo-container .bg-photo{
background-position:center;
background-size:cover;
z-index:-1
}
.centered{
margin:0 auto;
position:relative;
width:$(3 * posts.width.stream + 2 * 16px + 15px + sidebar.width)
}
.centered .main,.centered .main-container{
float:$startSide
}
.centered .main{
padding-bottom:1em
}
.centered .centered-bottom::after{
clear:both;
content:"";
display:table
}
@media (min-width:$(3 * posts.width.stream + 2 * 16px + 143px + 15px + sidebar.width + 1px)){
.page_body.has-vertical-ads .centered{
width:$(3 * posts.width.stream + 2 * 16px + 143px + 15px + sidebar.width)
}
}
@media (min-width:$(2 * posts.width.stream + 1 * 16px + 143px + 15px + sidebar.width + 1px)) and (max-width:$(3 * posts.width.stream + 2 * 16px + 15px + sidebar.width)){
.centered{
width:$(2 * posts.width.stream + 1 * 16px + 15px + sidebar.width)
}
}
@media (min-width:$(2 * posts.width.stream + 1 * 16px + 143px + 15px + sidebar.width + 1px)) and (max-width:$(3 * posts.width.stream + 2 * 16px + 143px + 15px + sidebar.width)){
.page_body.has-vertical-ads .centered{
width:$(2 * posts.width.stream + 1 * 16px + 143px + 15px + sidebar.width)
}
}
@media (max-width:$(2 * posts.width.stream + 1 * 16px + 143px + 15px + sidebar.width)){
.centered{
width:$(posts.width.stream + 15px + sidebar.width)
}
}
@media (max-width:$(posts.width.stream + 15px + sidebar.width)){
.centered{
max-width:600px;
width:100%
}
}
.feed-view .post-wrapper.hero,.main,.main-container,.post-filter-message,.top-nav .section{
width:$(3 * posts.width.stream + 2 * 16px)
}
@media (min-width:$(2 * posts.width.stream + 1 * 16px + 143px + 15px + sidebar.width + 1px)) and (max-width:$(3 * posts.width.stream + 2 * 16px + 15px + sidebar.width)){
.feed-view .post-wrapper.hero,.main,.main-container,.post-filter-message,.top-nav .section{
width:$(2 * posts.width.stream + 1 * 16px)
}
}
@media (min-width:$(2 * posts.width.stream + 1 * 16px + 143px + 15px + sidebar.width + 1px)) and (max-width:$(3 * posts.width.stream + 2 * 16px + 143px + 15px + sidebar.width)){
.feed-view .page_body.has-vertical-ads .post-wrapper.hero,.page_body.has-vertical-ads .feed-view .post-wrapper.hero,.page_body.has-vertical-ads .main,.page_body.has-vertical-ads .main-container,.page_body.has-vertical-ads .post-filter-message,.page_body.has-vertical-ads .top-nav .section{
width:$(2 * posts.width.stream + 1 * 16px)
}
}
@media (max-width:$(2 * posts.width.stream + 1 * 16px + 143px + 15px + sidebar.width)){
.feed-view .post-wrapper.hero,.main,.main-container,.post-filter-message,.top-nav .section{
width:auto
}
}
.widget .title{
font-size:$(body.text.font.size * 1.125);
line-height:$(body.text.font.size * 1.75);
margin:$(body.text.font.size * 1.125) 0
}
.extendable .show-less,.extendable .show-more{
color:$(body.button.color);
font:$(body.button.font);
cursor:pointer;
text-transform:uppercase;
margin:0 -16px;
padding:16px
}
.widget.Profile{
font:$(body.text.font)
}
.sidebar-container .widget.Profile{
padding:16px
}
.widget.Profile h2{
display:none
}
.widget.Profile .title{
margin:16px 32px
}
.widget.Profile .profile-img{
border-radius:50%
}
.widget.Profile .individual{
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex
}
.widget.Profile .individual .profile-info{
-webkit-align-self:center;
-ms-flex-item-align:center;
align-self:center;
margin-$startSide:16px
}
.widget.Profile .profile-datablock{
margin-top:0;
margin-bottom:.75em
}
.widget.Profile .profile-link{
background-image:none!important;
font-family:inherit;
overflow:hidden;
max-width:100%
}
.widget.Profile .individual .profile-link{
margin:0 -10px;
padding:0 10px;
display:block
}
.widget.Profile .individual .profile-data a.profile-link.g-profile,.widget.Profile .team a.profile-link.g-profile .profile-name{
font:$(widget.title.font);
color:$(widget.title.color);
margin-bottom:.75em
}
.widget.Profile .individual .profile-data a.profile-link.g-profile{
line-height:1.25
}
.widget.Profile .individual>a:first-child{
-webkit-flex-shrink:0;
-ms-flex-negative:0;
flex-shrink:0
}
.widget.Profile dd{
margin:0
}
.widget.Profile ul{
list-style:none;
padding:0
}
.widget.Profile ul li{
margin:10px 0 30px
}
.widget.Profile .team .extendable,.widget.Profile .team .extendable .first-items,.widget.Profile .team .extendable .remaining-items{
margin:0;
padding:0;
max-width:100%
}
.widget.Profile .team-member .profile-name-container{
-webkit-box-flex:0;
-webkit-flex:0 1 auto;
-ms-flex:0 1 auto;
flex:0 1 auto
}
.widget.Profile .team .extendable .show-less,.widget.Profile .team .extendable .show-more{
position:relative;
$startSide:56px
}
#comments a,.post-wrapper a{
color:$(posts.link.color)
}
div.widget.Blog .blog-posts .post-outer{
border:0
}
div.widget.Blog .post-outer{
padding-bottom:0
}
.post .thumb{
float:left;
height:20%;
width:20%
}
.no-posts-message,.status-msg-body{
margin:10px 0
}
.blog-pager{
text-align:center
}
.post-title{
margin:0
}
.post-title,.post-title a{
font:$(posts.title.font)
}
.post-body{
color:$(posts.text.color);
display:block;
font:$(posts.text.font);
line-height:$(posts.text.lineHeight);
margin:0
}
.post-snippet{
color:$(posts.text.color);
font:$(posts.snippet.text.font);
line-height:$(posts.snippet.text.lineHeight);
margin:8px 0;
max-height:$(posts.snippet.text.lineHeight * 3)
}
.post-snippet .snippet-fade{
background:-webkit-linear-gradient($startSide,$(posts.background.color) 0,$(posts.background.color) 20%,$(posts.background.color.transparent) 100%);
background:linear-gradient(to $startSide,$(posts.background.color) 0,$(posts.background.color) 20%,$(posts.background.color.transparent) 100%);
color:$(posts.text.color);
bottom:0;
position:absolute
}
.post-body img{
height:inherit;
max-width:100%
}
.byline,.byline.post-author a,.byline.post-timestamp a{
color:$(posts.byline.color);
font:$(posts.byline.font)
}
.byline.post-author{
text-transform:lowercase
}
.byline.post-author a{
text-transform:none
}
.item-byline .byline,.post-header .byline{
margin-$endSide:0
}
.post-share-buttons .share-buttons{
background:$(sharing.background.color);
color:$(sharing.text.color);
font:$(sharing.text.font)
}
.tr-caption{
color:$(picture.caption.text.color);
font:$(picture.caption.font);
font-size:1.1em;
font-style:italic
}
.post-filter-message{
background-color:$(postFilter.background.color);
box-sizing:border-box;
color:$(postFilter.message.color);
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
font:$(postFilter.message.font);
margin-bottom:16px;
margin-top:32px;
padding:12px 16px
}
.post-filter-message>div:first-child{
-webkit-box-flex:1;
-webkit-flex:1 0 auto;
-ms-flex:1 0 auto;
flex:1 0 auto
}
.post-filter-message a{
color:$(body.button.color);
font:$(body.button.font);
cursor:pointer;
text-transform:uppercase;
color:$(postFilter.message.link.color);
padding-$startSide:30px;
white-space:nowrap
}
.post-filter-message .search-label,.post-filter-message .search-query{
font-style:italic;
quotes:"\201c" "\201d" "\2018" "\2019"
}
.post-filter-message .search-label::before,.post-filter-message .search-query::before{
content:open-quote
}
.post-filter-message .search-label::after,.post-filter-message .search-query::after{
content:close-quote
}
#blog-pager{
margin-top:2em;
margin-bottom:1em
}
#blog-pager a{
color:$(body.button.color);
font:$(body.button.font);
cursor:pointer;
text-transform:uppercase
}
.Label{
overflow-x:hidden
}
.Label ul{
list-style:none;
padding:0
}
.Label li{
display:inline-block;
overflow:hidden;
max-width:100%;
text-overflow:ellipsis;
white-space:nowrap
}
.Label .first-ten{
margin-top:16px
}
.Label .show-all{
border-color:$(body.link.color);
color:$(body.link.color);
cursor:pointer;
display:inline-block;
font-style:normal;
margin-top:8px;
text-transform:uppercase
}
.Label .show-all.hidden{
display:inline-block
}
.Label li a,.Label span.label-size,.byline.post-labels a{
background-color:rgba($(sidebar.link.color.red),$(sidebar.link.color.green),$(sidebar.link.color.blue),.1);
border-radius:2px;
color:$(sidebar.link.color);
cursor:pointer;
display:inline-block;
font:$(labels.font);
line-height:1.5;
margin:4px 4px 4px 0;
padding:4px 8px;
text-transform:uppercase;
vertical-align:middle
}
body.item-view .byline.post-labels a{
background-color:rgba($(posts.link.color.red),$(posts.link.color.green),$(posts.link.color.blue),.1);
color:$(posts.link.color)
}
.FeaturedPost .item-thumbnail img{
max-width:100%
}
.sidebar-container .FeaturedPost .post-title a{
color:$(sidebar.link.color);
font:$(sidebar.posts.title.font)
}
body.item-view .PopularPosts{
display:inline-block;
overflow-y:auto;
vertical-align:top;
width:280px
}
.PopularPosts h3.title{
font:$(widget.title.font)
}
.PopularPosts .post-title{
margin:0 0 16px
}
.PopularPosts .post-title a{
color:$(sidebar.link.color);
font:$(sidebar.posts.title.font);
line-height:$(sidebar.posts.text.font.size * 12 / 7)
}
.PopularPosts .item-thumbnail{
clear:both;
height:152px;
overflow-y:hidden;
width:100%
}
.PopularPosts .item-thumbnail img{
padding:0;
width:100%
}
.PopularPosts .popular-posts-snippet{
color:$(sidebar.posts.text.color);
font:$(sidebar.posts.text.font);
line-height:$(sidebar.posts.text.font.size * 12 / 7);
max-height:calc($(sidebar.posts.text.font.size * 12 / 7) * 4);
overflow:hidden
}
.PopularPosts .popular-posts-snippet .snippet-fade{
color:$(sidebar.posts.text.color)
}
.PopularPosts .post{
margin:30px 0;
position:relative
}
.PopularPosts .post+.post{
padding-top:1em
}
.popular-posts-snippet .snippet-fade{
background:-webkit-linear-gradient($startSide,$(sidebar.background.color) 0,$(sidebar.background.color) 20%,$(sidebar.background.color.transparent) 100%);
background:linear-gradient(to $startSide,$(sidebar.background.color) 0,$(sidebar.background.color) 20%,$(sidebar.background.color.transparent) 100%);
$endSide:0;
height:$(sidebar.posts.text.font.size * 12 / 7);
line-height:$(sidebar.posts.text.font.size * 12 / 7);
position:absolute;
top:calc($(sidebar.posts.text.font.size * 12 / 7) * 3);
width:96px
}
.Attribution{
color:$(attribution.text.color)
}
.Attribution a,.Attribution a:hover,.Attribution a:visited{
color:$(attribution.link.color)
}
.Attribution svg{
fill:$(attribution.icon.color)
}
.inline-ad{
margin-bottom:16px
}
.item-view .inline-ad{
display:block
}
.vertical-ad-container{
float:$startSide;
margin-$startSide:15px;
min-height:1px;
width:128px
}
.item-view .vertical-ad-container{
margin-top:30px
}
.inline-ad-placeholder,.vertical-ad-placeholder{
background:$(posts.background.color);
border:1px solid #000;
opacity:.9;
vertical-align:middle;
text-align:center
}
.inline-ad-placeholder span,.vertical-ad-placeholder span{
margin-top:290px;
display:block;
text-transform:uppercase;
font-weight:700;
color:$(posts.title.color)
}
.vertical-ad-placeholder{
height:600px
}
.vertical-ad-placeholder span{
margin-top:290px;
padding:0 40px
}
.inline-ad-placeholder{
height:90px
}
.inline-ad-placeholder span{
margin-top:35px
}
.centered-top-container.sticky,.sticky .centered-top{
background-color:$(header.background.color)
}
.centered-top{
-webkit-box-align:start;
-webkit-align-items:flex-start;
-ms-flex-align:start;
align-items:flex-start;
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
-webkit-flex-wrap:wrap;
-ms-flex-wrap:wrap;
flex-wrap:wrap;
margin:0 auto;
padding-top:40px;
max-width:$(3 * posts.width.stream + 2 * 16px + 15px + sidebar.width)
}
.page_body.has-vertical-ads .centered-top{
max-width:$(3 * posts.width.stream + 2 * 16px + 143px + 15px + sidebar.width)
}
.centered-top .blog-name,.centered-top .hamburger-section,.centered-top .search{
margin-$startSide:16px
}
.centered-top .return_link{
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto;
height:24px;
-webkit-box-ordinal-group:1;
-webkit-order:0;
-ms-flex-order:0;
order:0;
width:24px
}
.centered-top .blog-name{
-webkit-box-flex:1;
-webkit-flex:1 1 0;
-ms-flex:1 1 0px;
flex:1 1 0;
-webkit-box-ordinal-group:2;
-webkit-order:1;
-ms-flex-order:1;
order:1
}
.centered-top .search{
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto;
-webkit-box-ordinal-group:3;
-webkit-order:2;
-ms-flex-order:2;
order:2
}
.centered-top .hamburger-section{
display:none;
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto;
-webkit-box-ordinal-group:4;
-webkit-order:3;
-ms-flex-order:3;
order:3
}
.centered-top .subscribe-section-container{
-webkit-box-flex:1;
-webkit-flex:1 0 100%;
-ms-flex:1 0 100%;
flex:1 0 100%;
-webkit-box-ordinal-group:5;
-webkit-order:4;
-ms-flex-order:4;
order:4
}
.centered-top .top-nav{
-webkit-box-flex:1;
-webkit-flex:1 0 100%;
-ms-flex:1 0 100%;
flex:1 0 100%;
margin-top:32px;
-webkit-box-ordinal-group:6;
-webkit-order:5;
-ms-flex-order:5;
order:5
}
.sticky .centered-top{
-webkit-box-align:center;
-webkit-align-items:center;
-ms-flex-align:center;
align-items:center;
box-sizing:border-box;
-webkit-flex-wrap:nowrap;
-ms-flex-wrap:nowrap;
flex-wrap:nowrap;
padding:0 16px
}
.sticky .centered-top .blog-name{
-webkit-box-flex:0;
-webkit-flex:0 1 auto;
-ms-flex:0 1 auto;
flex:0 1 auto;
max-width:none;
min-width:0
}
.sticky .centered-top .subscribe-section-container{
border-$startSide:1px solid $(header.separator.color);
-webkit-box-flex:1;
-webkit-flex:1 0 auto;
-ms-flex:1 0 auto;
flex:1 0 auto;
margin:0 16px;
-webkit-box-ordinal-group:3;
-webkit-order:2;
-ms-flex-order:2;
order:2
}
.sticky .centered-top .search{
-webkit-box-flex:1;
-webkit-flex:1 0 auto;
-ms-flex:1 0 auto;
flex:1 0 auto;
-webkit-box-ordinal-group:4;
-webkit-order:3;
-ms-flex-order:3;
order:3
}
.sticky .centered-top .hamburger-section{
-webkit-box-ordinal-group:5;
-webkit-order:4;
-ms-flex-order:4;
order:4
}
.sticky .centered-top .top-nav{
display:none
}
.search{
position:relative;
width:250px
}
.search,.search .search-expand,.search .section{
height:48px
}
.search .search-expand{
background:0 0;
border:0;
margin:0;
outline:0;
padding:0;
display:none;
margin-$startSide:auto
}
.search .search-expand-text{
display:none
}
.search .search-expand .svg-icon-24,.search .search-submit-container .svg-icon-24{
fill:$(search.icon.color);
-webkit-transition:.3s fill cubic-bezier(.4,0,.2,1);
transition:.3s fill cubic-bezier(.4,0,.2,1)
}
.search h3{
display:none
}
.search .section{
background-color:$(search.background.color);
box-sizing:border-box;
$endSide:0;
line-height:24px;
overflow-x:hidden;
position:absolute;
top:0;
-webkit-transition-duration:.3s;
transition-duration:.3s;
-webkit-transition-property:background-color,width;
transition-property:background-color,width;
-webkit-transition-timing-function:cubic-bezier(.4,0,.2,1);
transition-timing-function:cubic-bezier(.4,0,.2,1);
width:250px;
z-index:8
}
.search.focused .section{
background-color:$(search.background.color)
}
.search form{
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex
}
.search form .search-submit-container{
-webkit-box-align:center;
-webkit-align-items:center;
-ms-flex-align:center;
align-items:center;
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto;
height:48px;
-webkit-box-ordinal-group:1;
-webkit-order:0;
-ms-flex-order:0;
order:0
}
.search form .search-input{
-webkit-box-flex:1;
-webkit-flex:1 1 auto;
-ms-flex:1 1 auto;
flex:1 1 auto;
-webkit-box-ordinal-group:2;
-webkit-order:1;
-ms-flex-order:1;
order:1
}
.search form .search-input input{
box-sizing:border-box;
height:48px;
width:100%
}
.search .search-submit-container input[type=submit]{
display:none
}
.search .search-submit-container .search-icon{
margin:0;
padding:12px 8px
}
.search .search-input input{
background:0 0;
border:0;
color:$(search.text.color);
font:$(search.font);
outline:0;
padding:0 8px
}
.search .search-input input::-webkit-input-placeholder{
color:$(search.placeholder.color);
font:$(search.placeholder.font);
line-height:48px
}
.search .search-input input::-moz-placeholder{
color:$(search.placeholder.color);
font:$(search.placeholder.font);
line-height:48px
}
.search .search-input input:-ms-input-placeholder{
color:$(search.placeholder.color);
font:$(search.placeholder.font);
line-height:48px
}
.search .search-input input::-ms-input-placeholder{
color:$(search.placeholder.color);
font:$(search.placeholder.font);
line-height:48px
}
.search .search-input input::placeholder{
color:$(search.placeholder.color);
font:$(search.placeholder.font);
line-height:48px
}
.search .dim-overlay{
background-color:transparent
}
.centered-top .Header h1{
box-sizing:border-box;
color:$(blog.title.color);
font:$(blog.title.font);
margin:0;
padding:0
}
.centered-top .Header h1 a,.centered-top .Header h1 a:hover,.centered-top .Header h1 a:visited{
color:inherit;
font-size:inherit
}
.centered-top .Header p{
color:$(blog.description.color);
font:$(blog.description.font);
line-height:1.7;
margin:16px 0;
padding:0
}
.sticky .centered-top .Header h1{
color:$(blog.collapsed.title.color);
font-size:32px;
margin:16px 0;
padding:0;
overflow:hidden;
text-overflow:ellipsis;
white-space:nowrap
}
.sticky .centered-top .Header p{
display:none
}
.subscribe-section-container{
border-left:0;
margin:0
}
.subscribe-section-container .subscribe-button{
background:0 0;
border:0;
margin:0;
outline:0;
padding:0;
color:$(body.button.color);
cursor:pointer;
display:inline-block;
font:$(tabs.text.font);
margin:0 auto;
padding:16px;
text-transform:uppercase;
white-space:nowrap
}
.top-nav .PageList h3{
margin-$startSide:16px
}
.top-nav .PageList ul{
list-style:none;
margin:0;
padding:0
}
.top-nav .PageList ul li{
color:$(body.button.color);
font:$(body.button.font);
cursor:pointer;
text-transform:uppercase;
font:$(tabs.text.font)
}
.top-nav .PageList ul li a{
background-color:$(tabs.background.color);
color:$(tabs.text.color);
display:block;
height:$(tabs.text.font.size + 2 * 16px);
line-height:$(tabs.text.font.size + 2 * 16px);
overflow:hidden;
padding:0 22px;
text-overflow:ellipsis;
vertical-align:middle
}
.top-nav .PageList ul li.selected a{
color:$(tabs.selected.color)
}
.top-nav .PageList ul li:first-child a{
padding-left:16px
}
.top-nav .PageList ul li:last-child a{
padding-right:16px
}
.top-nav .PageList .dim-overlay{
opacity:0
}
.top-nav .overflowable-contents li{
float:$startSide;
max-width:100%
}
.top-nav .overflow-button{
-webkit-box-align:center;
-webkit-align-items:center;
-ms-flex-align:center;
align-items:center;
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
height:$(tabs.text.font.size + 2 * 16px);
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto;
padding:0 16px;
position:relative;
-webkit-transition:opacity .3s cubic-bezier(.4,0,.2,1);
transition:opacity .3s cubic-bezier(.4,0,.2,1);
width:24px
}
.top-nav .overflow-button.hidden{
display:none
}
.top-nav .overflow-button svg{
margin-top:0
}
@media (max-width:$(2 * posts.width.stream + 1 * 16px + 143px + 15px + sidebar.width)){
.search{
width:24px
}
.search .search-expand{
display:block;
position:relative;
z-index:8
}
.search .search-expand .search-expand-icon{
fill:transparent
}
.search .section{
background-color:$(search.background.color.transparent);
width:32px;
z-index:7
}
.search.focused .section{
width:250px;
z-index:8
}
.search .search-submit-container .svg-icon-24{
fill:$(header.icons.color)
}
.search.focused .search-submit-container .svg-icon-24{
fill:$(search.icon.color)
}
.blog-name,.return_link,.subscribe-section-container{
opacity:1;
-webkit-transition:opacity .3s cubic-bezier(.4,0,.2,1);
transition:opacity .3s cubic-bezier(.4,0,.2,1)
}
.centered-top.search-focused .blog-name,.centered-top.search-focused .return_link,.centered-top.search-focused .subscribe-section-container{
opacity:0
}
body.search-view .centered-top.search-focused .blog-name .section,body.search-view .centered-top.search-focused .subscribe-section-container{
display:none
}
}
@media (max-width:745px){
.top-nav .section.no-items#page_list_top{
display:none
}
.centered-top{
padding-top:16px
}
.centered-top .header_container{
margin:0 auto;
max-width:600px
}
.centered-top .hamburger-section{
-webkit-box-align:center;
-webkit-align-items:center;
-ms-flex-align:center;
align-items:center;
display:-webkit-box;
display:-webkit-flex;
display:-ms-flexbox;
display:flex;
height:48px;
margin-$endSide:24px
}
.widget.Header h1{
font:$(blog.collapsed.title.font);
padding:0
}
.top-nav .PageList{
max-width:100%;
overflow-x:auto
}
.centered-top-container.sticky .centered-top{
-webkit-flex-wrap:wrap;
-ms-flex-wrap:wrap;
flex-wrap:wrap
}
.centered-top-container.sticky .blog-name{
-webkit-box-flex:1;
-webkit-flex:1 1 0;
-ms-flex:1 1 0px;
flex:1 1 0
}
.centered-top-container.sticky .search{
-webkit-box-flex:0;
-webkit-flex:0 0 auto;
-ms-flex:0 0 auto;
flex:0 0 auto
}
.centered-top-container.sticky .hamburger-section,.centered-top-container.sticky .search{
margin-bottom:8px;
margin-top:8px
}
.centered-top-container.sticky .subscribe-section-container{
border:0;
-webkit-box-flex:1;
-webkit-flex:1 0 100%;
-ms-flex:1 0 100%;
flex:1 0 100%;
margin:-16px 0 0;
-webkit-box-ordinal-group:6;
-webkit-order:5;
-ms-flex-order:5;
order:5
}
body.item-view .centered-top-container.sticky .subscribe-section-container{
margin-$startSide:24px
}
.centered-top-container.sticky .subscribe-button{
padding:8px 16px 16px;
margin-bottom:0
}
.centered-top-container.sticky .widget.Header h1{
font-size:16px;
margin:0
}
}
body.sidebar-visible .page{
overflow-y:scroll
}
.sidebar-container{
float:$startSide;
margin-$startSide:15px
}
.sidebar-container a{
font:$(sidebar.link.font);
color:$(sidebar.link.color)
}
.sidebar-container .sidebar-back{
float:$endSide
}
.sidebar-container .navigation{
display:none
}
.sidebar-container .widget{
margin:auto 0;
padding:24px
}
.sidebar-container .widget .title{
font:$(widget.title.font)
}
@media (min-width:$(posts.width.stream + 15px + sidebar.width + 1px)) and (max-width:$(2 * posts.width.stream + 1 * 16px + 143px + 15px + sidebar.width)){
.error-view .sidebar-container{
display:none
}
}
@media (max-width:$(posts.width.stream + 15px + sidebar.width)){
.sidebar-container{
margin-$startSide:0;
max-width:none;
width:100%
}
.sidebar-container .navigation{
display:block;
padding:24px
}
.sidebar-container .navigation+.sidebar.section{
clear:both
}
.sidebar-container .widget{
padding-$startSide:32px
}
.sidebar-container .widget.Profile{
padding-$startSide:24px
}
}
.post-wrapper{
background-color:$(posts.background.color);
position:relative
}
.feed-view .blog-posts{
margin-$endSide:-15px;
width:calc(100% + 15px)
}
.feed-view .post-wrapper{
border-radius:$(posts.border.radius);
float:$startSide;
overflow:hidden;
-webkit-transition:.3s box-shadow cubic-bezier(.4,0,.2,1);
transition:.3s box-shadow cubic-bezier(.4,0,.2,1);
width:$(posts.width.stream)
}
.feed-view .post-wrapper:hover{
box-shadow:0 4px 5px 0 rgba(0,0,0,.14),0 1px 10px 0 rgba(0,0,0,.12),0 2px 4px -1px rgba(0,0,0,.2)
}
.feed-view .post-wrapper.hero{
background-position:center;
background-size:cover;
position:relative
}
.feed-view .post-wrapper .post,.feed-view .post-wrapper .post .snippet-thumbnail{
background-color:$(posts.background.color);
padding:24px 16px
}
.feed-view .post-wrapper .snippet-thumbnail{
-webkit-transition:.3s opacity cubic-bezier(.4,0,.2,1);
transition:.3s opacity cubic-bezier(.4,0,.2,1)
}
.feed-view .post-wrapper.has-labels.image .snippet-thumbnail-container{
background-color:$(posts.background.color.inverse)
}
.feed-view .post-wrapper.has-labels:hover .snippet-thumbnail{
opacity:.7
}
.feed-view .inline-ad,.feed-view .post-wrapper{
margin-bottom:15px;
margin-top:0;
margin-$endSide:15px;
margin-$startSide:0
}
.feed-view .post-wrapper.hero .post-title a{
font-size:$(posts.title.font.size * 5 / 6);
line-height:$(posts.title.font.size)
}
.feed-view .post-wrapper.not-hero .post-title a{
font-size:$(posts.title.font.size * 2 / 3);
line-height:$(posts.title.font.size)
}
.feed-view .post-wrapper .post-title a{
display:block;
margin:-296px -16px;
padding:296px 16px;
position:relative;
text-overflow:ellipsis;
z-index:2
}
.feed-view .post-wrapper .byline,.feed-view .post-wrapper .comment-link{
position:relative;
z-index:3
}
.feed-view .not-hero.post-wrapper.no-image .post-title-container{
position:relative;
top:-90px
}
.feed-view .post-wrapper .post-header{
padding:5px 0
}
.feed-view .byline{
line-height:$(posts.byline.font.size)
}
.feed-view .hero .byline{
line-height:$(posts.byline.font.size * 1.3)
}
.feed-view .hero .byline,.feed-view .hero .byline.post-author a,.feed-view .hero .byline.post-timestamp a{
font-size:$(posts.byline.font.size + 2px)
}
.feed-view .post-comment-link{
float:$startSide
}
.feed-view .post-share-buttons{
float:$endSide
}
.feed-view .header-buttons-byline{
margin-top:16px;
height:24px
}
.feed-view .header-buttons-byline .byline{
height:24px
}
.feed-view .post-header-right-buttons .post-comment-link,.feed-view .post-header-right-buttons .post-jump-link{
display:block;
float:left;
margin-left:16px
}
.feed-view .post .num_comments{
display:inline-block;
font:$(posts.title.font);
font-size:$(posts.title.font.size / 2);
margin:-14px 6px 0;
vertical-align:middle
}
.feed-view .post-wrapper .post-jump-link{
float:right
}
.feed-view .post-wrapper .post-footer{
margin-top:15px
}
.feed-view .post-wrapper .snippet-thumbnail,.feed-view .post-wrapper .snippet-thumbnail-container{
height:184px;
overflow-y:hidden
}
.feed-view .post-wrapper .snippet-thumbnail{
display:block;
background-position:center;
background-size:cover;
width:100%
}
.feed-view .post-wrapper.hero .snippet-thumbnail,.feed-view .post-wrapper.hero .snippet-thumbnail-container{
height:272px;
overflow-y:hidden
}
@media (min-width:$(posts.width.stream + 15px + sidebar.width + 1px)){
.feed-view .post-title a .snippet-container{
height:$(posts.title.font.size * 2);
max-height:$(posts.title.font.size * 2)
}
.feed-view .post-title a .snippet-fade{
background:-webkit-linear-gradient($startSide,$(posts.background.color) 0,$(posts.background.color) 20%,$(posts.background.color.transparent) 100%);
background:linear-gradient(to $startSide,$(posts.background.color) 0,$(posts.background.color) 20%,$(posts.background.color.transparent) 100%);
color:transparent;
height:$(posts.title.font.size);
width:96px
}
.feed-view .hero .post-title-container .post-title a .snippet-container{
height:$(posts.title.font.size);
max-height:$(posts.title.font.size)
}
.feed-view .hero .post-title a .snippet-fade{
height:$(posts.title.font.size)
}
.feed-view .post-header-left-buttons{
position:relative
}
.feed-view .post-header-left-buttons:hover .touch-icon{
opacity:1
}
.feed-view .hero.post-wrapper.no-image .post-authordate,.feed-view .hero.post-wrapper.no-image .post-title-container{
position:relative;
top:-150px
}
.feed-view .hero.post-wrapper.no-image .post-title-container{
text-align:center
}
.feed-view .hero.post-wrapper.no-image .post-authordate{
-webkit-box-pack:center;
-webkit-justify-content:center;
-ms-flex-pack:center;
justify-content:center
}
.feed-view .labels-outer-container{
margin:0 -4px;
opacity:0;
position:absolute;
top:20px;
-webkit-transition:.2s opacity;
transition:.2s opacity;
width:calc(100% - 2 * 16px)
}
.feed-view .post-wrapper.has-labels:hover .labels-outer-container{
opacity:1
}
.feed-view .labels-container{
max-height:calc($(labels.font.size * 1.5 + 8px) + 2 * 4px);
overflow:hidden
}
.feed-view .labels-container .labels-more,.feed-view .labels-container .overflow-button-container{
display:inline-block;
float:$endSide
}
.feed-view .labels-items{
padding:0 4px
}
.feed-view .labels-container a{
display:inline-block;
max-width:calc(100% - 16px);
overflow-x:hidden;
text-overflow:ellipsis;
white-space:nowrap;
vertical-align:top
}
.feed-view .labels-more{
min-width:$(labels.font.size * 1.5 + 8px);
padding:0;
width:$(labels.font.size * 1.5 + 8px)
}
.feed-view .labels-more{
margin-$startSide:8px
}
.feed-view .byline.post-labels{
margin:0
}
.feed-view .byline.post-labels a,.feed-view .labels-more a{
background-color:$(posts.background.color);
color:$(posts.link.color);
box-shadow:0 0 2px 0 rgba(0,0,0,.18);
opacity:.9
}
.feed-view .labels-more a{
border-radius:50%;
display:inline-block;
font:$(labels.font);
line-height:$(labels.font.size * 1.5 + 8px);
height:$(labels.font.size * 1.5 + 8px);
padding:0;
text-align:center;
width:$(labels.font.size * 1.5 + 8px);
max-width:$(labels.font.size * 1.5 + 8px)
}
}
@media (max-width:$(2 * posts.width.stream + 1 * 16px + 143px + 15px + sidebar.width)){
.feed-view .centered{
padding-right:0
}
.feed-view .centered .main-container{
float:none
}
.feed-view .blog-posts{
margin-$endSide:0;
width:auto
}
.feed-view .post-wrapper{
float:none
}
.feed-view .post-wrapper.hero{
width:$(posts.width.stream + 15px + sidebar.width)
}
.feed-view .page_body .centered div.widget.FeaturedPost,.feed-view div.widget.Blog{
width:$(posts.width.stream)
}
.post-filter-message,.top-nav{
margin-top:32px
}
.widget.Header h1{
font:$(blog.collapsed.title.font)
}
.post-filter-message{
display:block
}
.post-filter-message a{
display:block;
margin-top:8px;
padding-left:0
}
.feed-view .not-hero .post-title-container .post-title a .snippet-container{
height:auto
}
.feed-view .vertical-ad-container{
display:none
}
.feed-view .blog-posts .inline-ad{
display:block
}
}
@media (max-width:$(posts.width.stream + 15px + sidebar.width)){
.feed-view .centered .main{
float:none;
width:100%
}
.feed-view .centered .centered-bottom{
max-width:600px;
width:auto
}
.feed-view .centered-bottom .hero.post-wrapper,.feed-view .centered-bottom .post-wrapper{
max-width:600px;
width:auto
}
.feed-view #header{
width:auto
}
.feed-view .page_body .centered div.widget.FeaturedPost,.feed-view div.widget.Blog{
top:50px;
width:100%;
z-index:6
}
.feed-view .main>.widget .title,.feed-view .post-filter-message{
margin-left:8px;
margin-right:8px
}
.feed-view .hero.post-wrapper{
background-color:$(posts.link.color);
border-radius:0;
height:416px
}
.feed-view .hero.post-wrapper .post{
bottom:0;
box-sizing:border-box;
margin:16px;
position:absolute;
width:calc(100% - 32px)
}
.feed-view .hero.no-image.post-wrapper .post{
box-shadow:0 0 16px rgba(0,0,0,.2);
padding-top:120px;
top:0
}
.feed-view .hero.no-image.post-wrapper .post-footer{
position:absolute;
bottom:16px;
width:calc(100% - 32px)
}
.hero.post-wrapper h3{
white-space:normal
}
.feed-view .post-wrapper h3,.feed-view .post-wrapper:hover h3{
width:auto
}
.feed-view .hero.post-wrapper{
margin:0 0 15px 0
}
.feed-view .inline-ad,.feed-view .post-wrapper{
margin:0 8px 16px
}
.feed-view .post-labels{
display:none
}
.feed-view .post-wrapper .snippet-thumbnail{
background-size:cover;
display:block;
height:184px;
margin:0;
max-height:184px;
width:100%
}
.feed-view .post-wrapper.hero .snippet-thumbnail,.feed-view .post-wrapper.hero .snippet-thumbnail-container{
height:416px;
max-height:416px
}
.feed-view .header-author-byline{
display:none
}
.feed-view .hero .header-author-byline{
display:block
}
}
.item-view .page_body{
padding-top:70px
}
.item-view .centered,.item-view .centered .main,.item-view .centered .main-container,.item-view .page_body.has-vertical-ads .centered,.item-view .page_body.has-vertical-ads .centered .main,.item-view .page_body.has-vertical-ads .centered .main-container{
width:100%
}
.item-view .main-container{
max-width:890px;
margin-$endSide:15px
}
.item-view .centered-bottom{
max-width:1185px;
margin-left:auto;
margin-right:auto;
padding-right:0;
padding-top:0;
width:100%
}
.item-view .page_body.has-vertical-ads .centered-bottom{
max-width:1328px;
width:100%
}
.item-view .bg-photo{
-webkit-filter:blur(12px);
filter:blur(12px);
-webkit-transform:scale(1.05);
-ms-transform:scale(1.05);
transform:scale(1.05)
}
.item-view .bg-photo-container+.centered .centered-bottom{
margin-top:0
}
.item-view .bg-photo-container+.centered .centered-bottom .post-wrapper{
margin-top:-368px
}
.item-view .bg-photo-container+.centered-bottom{
margin-top:0
}
.item-view .inline-ad{
margin-bottom:0;
margin-top:30px;
padding-bottom:16px
}
.item-view .post-wrapper{
border-radius:$(posts.border.radius) $(posts.border.radius) 0 0;
float:none;
height:auto;
margin:0;
padding:32px;
width:auto
}
.item-view .post-outer{
padding:8px
}
.item-view .comments{
border-radius:0 0 $(posts.border.radius) $(posts.border.radius);
color:$(posts.text.color);
margin:0 8px 8px
}
.item-view .post-title{
font:$(posts.title.font)
}
.item-view .post-header{
display:block;
width:auto
}
.item-view .post-share-buttons{
display:block;
margin-bottom:40px;
margin-top:20px
}
.item-view .post-footer{
display:block
}
.item-view .post-footer a{
color:$(body.button.color);
font:$(body.button.font);
cursor:pointer;
text-transform:uppercase;
color:$(posts.link.color)
}
.item-view .post-footer-line{
border:0
}
.item-view .sidebar-container{
box-sizing:border-box;
margin-$startSide:0;
margin-top:15px;
max-width:280px;
padding:0;
width:280px
}
.item-view .sidebar-container .widget{
padding:15px 0
}
@media (max-width:1328px){
.item-view .centered{
width:100%
}
.item-view .centered .centered-bottom{
margin-left:auto;
margin-right:auto;
padding-right:0;
padding-top:0;
width:100%
}
.item-view .centered .main-container{
float:none;
margin:0 auto
}
.item-view div.section.main div.widget.PopularPosts{
margin:0 2.5%;
position:relative;
top:0;
width:95%
}
.item-view .bg-photo-container+.centered .main{
margin-top:0
}
.item-view div.widget.Blog{
margin:auto;
width:100%
}
.item-view .post-share-buttons{
margin-bottom:32px
}
.item-view .sidebar-container{
float:none;
margin:0;
max-height:none;
max-width:none;
padding:0 15px;
position:static;
width:100%
}
.item-view .sidebar-container .section{
margin:15px auto;
max-width:480px
}
.item-view .sidebar-container .section .widget{
position:static;
width:100%
}
.item-view .vertical-ad-container{
display:none
}
.item-view .blog-posts .inline-ad{
display:block
}
}
@media (max-width:745px){
.item-view.has-subscribe .bg-photo-container,.item-view.has-subscribe .centered-bottom{
padding-top:88px
}
.item-view .bg-photo,.item-view .bg-photo-container{
width:auto;
height:296px
}
.item-view .bg-photo-container+.centered .centered-bottom .post-wrapper{
margin-top:-240px
}
.item-view .bg-photo-container+.centered .centered-bottom,.item-view .page_body.has-subscribe .bg-photo-container+.centered .centered-bottom{
margin-top:0
}
.item-view .post-outer{
background:$(posts.background.color)
}
.item-view .post-outer .post-wrapper{
padding:16px
}
.item-view .comments{
margin:0
}
}
#comments{
background:$(posts.background.color);
border-top:1px solid $(sidebar.separator.color);
margin-top:0;
padding:32px
}
#comments .comment-form .title,#comments h3.title{
position:absolute;
clip:rect(1px,1px,1px,1px);
padding:0;
border:0;
height:1px;
width:1px;
overflow:hidden
}
#comments .comment-form{
border-bottom:1px solid $(sidebar.separator.color);
border-top:1px solid $(sidebar.separator.color)
}
.item-view #comments .comment-form h4{
position:absolute;
clip:rect(1px,1px,1px,1px);
padding:0;
border:0;
height:1px;
width:1px;
overflow:hidden
}
#comment-holder .continue{
display:none
}
]]></b:skin>

    <b:template-skin>
      <![CDATA[
      body#layout .hidden,
      body#layout .invisible {
        display: inherit;
      }
      body#layout .centered-bottom {
        position: relative;
      }
      body#layout .section.featured-post,
      body#layout .section.main,
      body#layout .section.vertical-ad-container {
        float: left;
        width: 55%;
      }
      body#layout .sidebar-container {
        display: inline-block;
        width: 39%;
      }
      body#layout .centered-bottom:after {
        clear: both;
        content: "";
        display: table;
      }
      body#layout .hamburger-menu,
      body#layout .search {
        display: none;
      }
      ]]>
    </b:template-skin>

    <b:if cond='data:skin.vars.body_background.image.isResizable'>
      <b:include cond='not data:view.isPreview' data='{                          image: data:skin.vars.body_background.image,                          selector: &quot;body&quot;                        }' name='responsiveImageStyle'/>
    </b:if>

    <b:defaultmarkups>
      <b:defaultmarkup type='Common'>
        <b:includable id='standardPostImageStyle'>
          <b:with value='&quot;post-thumb-&quot; + data:post.id' var='thumbClassName'>
            <style>
              .<data:thumbClassName/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 385, &quot;385:184&quot;).cssEscaped'/>);}
            </style>
          </b:with>
        </b:includable>
        <b:includable id='feedPostImage'>
          <div class='snippet-thumbnail-container'>
            <div expr:class='&quot;snippet-thumbnail &quot; + data:thumbClassName'/>
          </div>
        </b:includable>
        <b:includable id='widgetNotAvailableInPreview'>
          <b:if cond='data:widget.type == &quot;AdSense&quot;'>
            <div class='vertical-ad-placeholder'>
              <span><b:message name='messages.adsGoHere'/></span>
            </div>
          <b:else/>
            <b:include name='super.widgetNotAvailableInPreview'/>
          </b:if>
        </b:includable>
      </b:defaultmarkup>
      <b:defaultmarkup type='BlogSearch'>
        <b:includable id='searchSubmit'>
          <b:if cond='data:widget.sectionId == &quot;search_top&quot;'>
            <label class='search-submit-container'>
              <input type='submit'/>
              <b:include data='{ iconClass: &quot;touch-icon search-icon&quot; }' name='searchIcon'/>
            </label>
          <b:else/>
            <b:include name='super.searchSubmit'/>
          </b:if>
        </b:includable>
      </b:defaultmarkup>
      <b:defaultmarkup type='AdSense,Blog'>
        <b:includable id='defaultAdUnit'>
          <!-- Clear out style (need non-empty string) -->
          <b:with value='&quot;/* Done in css. */&quot;' var='style'>
            <b:include name='super.defaultAdUnit'/>
          </b:with>
        </b:includable>
      </b:defaultmarkup>
      <b:defaultmarkup type='Blog,FeaturedPost,PopularPosts'>
        <b:includable id='commentsLink'>
          <a class='comment-link' expr:href='data:post.commentsUrl ?: data:post.url' expr:onclick='data:post.commentsUrlOnclick'>
            <b:include name='commentIcon'/>
            <span class='num_comments'>
              <data:post.numberOfComments/>
            </span>
          </a>
        </b:includable>
        <b:includable id='snippetedPostThumbnail'>
          <div class='item-thumbnail'>
            <a expr:href='data:post.url'>
              <b:include data='{                                  image: data:post.featuredImage,                                  imageSizes: [280,560,840,1120,1400]                                }' name='responsiveImage'/>
            </a>
          </div>
        </b:includable>
      </b:defaultmarkup>
      <b:defaultmarkup type='Blog,FeaturedPost'>
        <b:includable id='postShareButtons' var='post'>
          <!-- We call super.postShareButtons from the migrated positions. -->
        </b:includable>
        <b:includable id='headerByline'>
          <b:if cond='data:view.isSingleItem and data:widget.type == &quot;Blog&quot;'>
            <b:include name='super.headerByline'/>
          <b:else/>
            <b:include data='{ items: [&quot;author&quot;, &quot;timestamp&quot;, &quot;labels&quot;] }' name='headerBylineOverride'/>
          </b:if>
          <b:include cond='data:view.isSingleItem and data:widget.type == &quot;Blog&quot;' data='{ shareButtonClass: &quot;post-share-buttons-top&quot;, overridden: true }' name='maybeAddShareButtons'/>
        </b:includable>
        <b:includable id='footerBylines'>
          <!-- Set the calling parent element to be a container. -->
          <b:class name='container'/>

          <b:if cond='data:view.isSingleItem and data:widget.type == &quot;Blog&quot;'>
            <b:include name='super.footerBylines'/>
          <b:else/>
            <b:include data='{ items: [[&quot;comments&quot;]] }' name='footerBylinesOverride'/>
          </b:if>
          <b:include data='{ shareButtonClass: &quot;post-share-buttons-bottom&quot;, overridden: true }' name='maybeAddShareButtons'/>
        </b:includable>
        <b:includable id='postTitle' var='post'>
          <!-- Snippetize the post title -->
          <div class='post-title-container'>
            <a expr:name='data:post.id'/>
            <h3 class='post-title entry-title'>
              <b:if cond='data:post.link or (data:post.url and data:view.url != data:post.url)'>
                <a expr:href='data:post.link ?: data:post.url'>
                  <div class='snippet-container r-snippet-container'>
                    <div class='r-snippetized'>
                      <data:post.title/>
                    </div>
                    <b:if cond='data:post.title != &quot;&quot;'>
                      <div class='snippet-fade r-snippet-fade hidden'/>
                    </b:if>
                  </div>
                </a>
              <b:else/>
                <data:post.title/>
              </b:if>
            </h3>
          </div>
        </b:includable>
        <b:includable id='postLabels'>
          <b:if cond='data:view.isMultipleItems'>
           <div class='labels-outer-container'>
              <div class='labels-container overflowable-container overflowable-no-popup'>
                <div class='labels-items overflowable-contents byline post-labels'>
                  <b:loop index='i' values='data:post.labels' var='label'>
                    <span class='overflowable-item'>
                      <a expr:href='data:label.url' rel='tag'><data:label.name/></a>
                    </span>
                  </b:loop>
                </div>
                <span class='labels-more overflow-button hidden'>
                  <a expr:href='data:post.link ?: data:post.url'>+<span class='overflow-count'/></a>
                </span>
              </div>
            </div>
          <b:else/>
            <b:include name='super.postLabels'/>
          </b:if>
        </b:includable>
        <b:includable id='postWrapperClasses'>
          <b:class cond='data:post.featuredImage' name='image'/>
          <b:class cond='not data:post.featuredImage' name='no-image'/>
          <b:class cond='data:post.labels and not data:post.labels.empty' name='has-labels'/>
        </b:includable>
      </b:defaultmarkup>
      <b:defaultmarkup type='Blog'>
        <b:includable id='feedLinks'>
          <!-- Don't show feed links. -->
        </b:includable>
        <b:includable id='main'>
          <b:include name='noContentPlaceholder'/>
          <b:include name='super.main'/>
        </b:includable>
        <b:includable id='inlineAd' var='post'>
          <!-- Cap the total number of ads (widgets and inline ads). -->
          <b:include cond='data:post.adNumber lt 3' data='post' name='super.inlineAd'/>
        </b:includable>
        <b:includable id='postCommentsAndAd'>
          <b:include cond='not data:view.isHomepage or                            data:widgets.FeaturedPost none (w =&gt; w.sectionId == &quot;featured_post&quot; and w.postId == data:post.id)' name='super.postCommentsAndAd'/>
        </b:includable>
        <b:includable id='post' var='post'>
          <b:with value='&quot;post-thumb-&quot; + data:post.id' var='thumbClassName'>
            <div expr:class='&quot;post-wrapper not-hero post-&quot; + data:post.id'>
              <b:include name='postWrapperClasses'/>

              <!-- Standard feed thumbs always added, as they're needed for mobile view. -->
              <b:include cond='data:post.featuredImage and data:view.isMultipleItems' name='standardPostImageStyle'/>
              <b:include name='feedPostImage'/>

              <div class='slide'>
                <b:include data='post' name='super.post'/>
              </div>
            </div>
          </b:with>
        </b:includable>
        <b:includable id='postBodySnippet' var='post'>
          <div class='post-body entry-content' expr:id='&quot;post-snippet-&quot; + data:post.id'>
            <b:if cond='data:post.featuredImage and not data:view.isMultipleItems'>
              <b:with value='&quot;post-&quot; + data:post.id' var='className'>
                <style>
                  .<data:className/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 385, &quot;385:185&quot;).cssEscaped'/>);}
                  @media (max-width: 285px) { .<data:className/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 285, &quot;285:185&quot;).cssEscaped'/>);} }
                  @media (max-width: 385px) and (min-width: 286px) { .<data:className/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 385, &quot;385:185&quot;).cssEscaped'/>);} }
                  @media (max-width: 485px) and (min-width: 386px) { .<data:className/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 485, &quot;485:185&quot;).cssEscaped'/>);} }
                  @media (max-width: 745px) and (min-width: 486px) { .<data:className/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 585, &quot;585:185&quot;).cssEscaped'/>);} }
                </style>
                <div class='snippet-thumbnail-container'>
                  <div expr:class='&quot;snippet-thumbnail &quot; + data:className'/>
                </div>
              </b:with>
            </b:if>
            <div style='clear: both;'/>
          </div>
        </b:includable>
        <b:includable id='postJumpLink' var='post'>
          <b:comment>We don&#39;t show &#39;read more&#39; links in Emporio.</b:comment>
        </b:includable>
        <b:includable id='previousPageLink'>
          <b:comment>We don&#39;t show previeus page links in Emporio.</b:comment>
        </b:includable>
        <b:includable id='homePageLink'>
          <b:comment>We don&#39;t show home page links in Emporio.</b:comment>
        </b:includable>
        <b:includable id='nextPageLink'>
          <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:title='data:messages.morePosts'>
            <data:messages.morePosts/>
          </a>
        </b:includable>
      </b:defaultmarkup>
      <b:defaultmarkup type='BlogArchive'>
        <b:includable id='main' var='this'>
          <details class='collapsible extendable'>
            <b:attr cond='data:view.isArchive' name='open' value='open'/>
            <b:with value='true' var='renderAsDetails'>
            <b:with value='data:messages.archive' var='defaultTitle'>
              <b:include name='super.main'/>
            </b:with>
            </b:with>
          </details>
        </b:includable>
        <b:includable id='flat'>
          <b:include data='{                               buttonClass: &quot;flat-button&quot;,                               items: data:this.data,                               itemSet: &quot;data&quot;,                               itemsMarkup: &quot;super.flat&quot;                             }' name='extendableItems'/>
        </b:includable>
        <b:includable id='hierarchy'>
          <b:include data='{                               buttonClass: &quot;flat-button&quot;,                               limit: 1,                               items: data:this.data,                               itemSet: &quot;data&quot;,                               itemsMarkup: &quot;super.hierarchy&quot;                             }' name='extendableItems'/>
        </b:includable>
      </b:defaultmarkup>
      <b:defaultmarkup type='Label'>
        <b:includable id='main' var='this'>
          <details class='collapsible extendable'>
            <b:attr cond='data:view.isLabelSearch' name='open' value='open'/>
            <b:with value='true' var='renderAsDetails'>
            <b:with value='data:messages.labels' var='defaultTitle'>
              <b:include name='super.main'/>
            </b:with>
            </b:with>
          </details>
        </b:includable>
        <b:includable id='list'>
          <b:include data='{                               buttonClass: &quot;flat-button&quot;,                               items: data:this.labels,                               itemSet: &quot;labels&quot;,                               itemsMarkup: &quot;super.list&quot;                             }' name='extendableItems'/>
        </b:includable>
        <b:includable id='cloud'>
          <b:include data='{                               buttonClass: &quot;flat-button&quot;,                               items: data:this.labels,                               itemSet: &quot;labels&quot;,                               itemsMarkup: &quot;super.cloud&quot;                             }' name='extendableItems'/>
        </b:includable>
      </b:defaultmarkup>
      <b:defaultmarkup type='FeaturedPost'>
        <b:includable id='snippetedPostContent'>
          <b:if cond='data:widget.sectionId != &quot;featured_post&quot;'>
            <b:include name='super.snippetedPostContent'/>
          <b:else/>
            <b:with value='&quot;post-thumb-&quot; + data:post.id' var='thumbClassName'>
              <b:if cond='data:post.featuredImage'>
                <style>
                  @media (min-width: 746px) { .hero .<data:thumbClassName/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 800, &quot;800:272&quot;).cssEscaped'/>);} }
                  @media (min-width: 1545px) { .hero .<data:thumbClassName/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 1185, &quot;1185:272&quot;).cssEscaped'/>);} }
                  @media (max-width: 400px) { .hero .<data:thumbClassName/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 400, &quot;1:1&quot;).cssEscaped'/>); } }
                  @media (min-width: 401px) and (max-width: 745px) { .hero .<data:thumbClassName/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 745, &quot;745:400&quot;).cssEscaped'/>); } }
                </style>
              </b:if>

              <div expr:class='&quot;post-wrapper hero post-&quot; + data:post.id'>
                <b:include name='postWrapperClasses'/>
                <b:include name='feedPostImage'/>

                <div class='slide'>
                  <div class='post hentry'>
                    <b:include cond='data:postDisplay.showTitle' data='post' name='postTitle'/>
                    <b:include name='headerByline'/>
                    <b:include cond='data:postDisplay.showSnippet' data='post' name='postSnippet'/>
                    <div class='post-footer'>
                      <b:include name='footerBylines'/>
                    </div>
                  </div>
                </div>
              </div>
            </b:with>
          </b:if>
        </b:includable>
      </b:defaultmarkup>
      <b:defaultmarkup type='Header'>
        <b:includable id='description'>
          <!-- Don't show description on the item page -->
          <b:include cond='not data:view.isSingleItem' name='super.description'/>
        </b:includable>
        <b:includable id='image'>
          <b:include name='super.image'/>
          <!-- If we are replacing the title, force it to render anyway, and it'll be hidden in CSS. -->
          <b:include cond='data:this.imagePlacement == &quot;REPLACE&quot;' name='title'/>
        </b:includable>
        <b:includable id='title'>
          <div>
            <b:class cond='data:this.imagePlacement == &quot;REPLACE&quot;' name='replaced'/>
            <b:include name='super.title'/>
          </div>
        </b:includable>
      </b:defaultmarkup>
      <b:defaultmarkup type='PageList'>
        <b:includable id='content'>
          <div class='widget-content'>
            <b:include cond='data:widget.sectionId == &quot;page_list_top&quot;' name='overflowablePageList'/>
            <b:include cond='data:widget.sectionId != &quot;page_list_top&quot;' name='pageList'/>
          </div>
        </b:includable>
      </b:defaultmarkup>
      <b:defaultmarkup type='PopularPosts'>
        <b:includable id='snippetedPostContent'>
          <b:comment>Move the thumbnail outside of the body and above the title</b:comment>
          <b:include cond='data:postDisplay.showFeaturedImage and data:post.featuredImage.isResizable' data='post' name='snippetedPostThumbnail'/>
          <b:include data='post' name='snippetedPostTitle'/>
          <b:include data='post' name='itemBody'/>
        </b:includable>
        <b:includable id='itemBody' var='post'>
          <div class='item-content'>
            <b:with value='&quot;popular-posts&quot;' var='snippetPrefix'>
              <b:include cond='data:postDisplay.showSnippet' data='post' name='postSnippet'/>
            </b:with>
          </div>
        </b:includable>
        <b:includable id='main'>
          <b:comment>Default the title to &#39;Postingan populer&#39;.</b:comment>
          <b:with value='data:messages.popularPosts' var='defaultTitle'>
            <b:include name='super.main'/>
          </b:with>
        </b:includable>
      </b:defaultmarkup>
      <b:defaultmarkup type='Profile'>
        <b:includable id='main'>
          <b:include name='content'/>
        </b:includable>
        <b:includable id='defaultProfileImage'>
          <div class='default-avatar-wrapper'>
            <b:include data='{ iconClass: &quot;avatar-icon&quot; }' name='defaultAvatarIcon'/>
          </div>
        </b:includable>
        <b:includable id='viewProfileLink'>
          <!-- Change single profile link message to 'Visit profile' -->
          <a class='profile-link' expr:href='data:userUrl' rel='author'><data:messages.visitProfile/></a>
        </b:includable>
        <b:includable id='teamProfile'>
          <div class='extendable'>
            <b:include data='{                                 items: data:authors,                                 itemSet: &quot;authors&quot;,                                 itemsMarkup: &quot;super.teamProfile&quot;,                                 limit: 4                               }' name='extendableItems'/>
          </div>
        </b:includable>
        <b:includable id='teamProfileLink'>
          <!-- Add an extra 'Visit profile' link -->
          <a class='profile-link g-profile' expr:href='data:author.userUrl'>
            <b:include name='profileImage'/>
            <div class='profile-name-container'>
              <span class='profile-name'><data:author.display-name/></span>
              <data:messages.visitProfile/>
            </div>
          </a>
        </b:includable>
      </b:defaultmarkup>
    </b:defaultmarkups>

    <b:if cond='data:blog.adsenseClientId and !data:widgets.AdSense.empty and not data:blog.adsenseAutoAds'>
      <script async='async' src='//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js'/>
    </b:if>
    <b:include data='blog' name='google-analytics'/>

    <script async='async' src='//www.gstatic.com/external_hosted/clipboardjs/clipboard.min.js'/>
  </head>

  <body>
    <b:class cond='data:view.isPreview' name='preview'/>
    <b:class cond='data:view.isMultipleItems' name='feed-view'/>
    <b:class cond='data:view.isSingleItem' name='item-view'/>
    <b:class cond='data:view.isArchive' name='archive-view'/>
    <b:class cond='data:view.isLabelSearch' name='label-view'/>
    <b:class cond='data:view.isSearch and !data:view.isLabelSearch' name='search-view'/>
    <b:class cond='data:view.isError' name='error-view'/>
    <b:class name='version-1-3-3'/>

    <b:include name='skipNavigation'/>
    <div class='page'>
      <b:with value='data:widgets.AdSense any (w =&gt; w.sectionId == &quot;ads&quot;)' var='hasVerticalAds'>
        <div class='page_body'>
          <b:class cond='data:hasVerticalAds' name='has-vertical-ads'/>

          <b:if cond='data:view.isSingleItem'>
            <b:if cond='data:widgets.Blog.first.posts.first.featuredImage'>
              <b:include data='{                                  image: data:widgets.Blog.first.posts.first.featuredImage,                                  selector: &quot;.bg-photo&quot;                                }' name='responsiveImageStyle'/>
              <div class='bg-photo-container'>
                <div class='bg-photo'/>
              </div>
            </b:if>
          </b:if>
          <div class='centered'>
            <b:if cond='not data:view.isSingleItem'>
              <div class='centered-top-placeholder'/>
            </b:if>
            <header class='centered-top-container' role='banner'>
              <b:class cond='data:view.isSingleItem' name='sticky'/>
              <div class='centered-top'>
                <b:class cond='data:view.isSearch and data:view.search.query' name='search-focused'/>

                <b:if cond='data:view.isSingleItem'>
                  <a class='return_link' expr:href='data:blog.homepageUrl'>
                    <b:include data='{ iconClass: &quot;touch-icon back-button rtl-reversible-icon&quot; }' name='backArrowIcon'/>
                  </a>
                <b:else/>
                  <div class='hamburger-section'>
                    <b:include data='{ iconClass: &quot;touch-icon hamburger-menu&quot; }' name='menuIcon'/>
                  </div>
                </b:if>

                <div class='blog-name'>
                  <b:section id='header' name='Judul1' showaddelement='yes'>
                    <b:widget id='Header1' locked='false' title='RIFKI BLOGGERS (Header)' type='Header' visible='true'>
                      <b:widget-settings>
                        <b:widget-setting name='displayUrl'/>
                        <b:widget-setting name='displayHeight'>0</b:widget-setting>
                        <b:widget-setting name='sectionWidth'>-1</b:widget-setting>
                        <b:widget-setting name='useImage'>false</b:widget-setting>
                        <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
                        <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
                        <b:widget-setting name='displayWidth'>0</b:widget-setting>
                      </b:widget-settings>
                      <b:includable id='main' var='this'>
    <div class='header-widget'>
      <b:include cond='data:imagePlacement in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='image'/>
      <b:include cond='data:imagePlacement not in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='title'/>
      <b:include cond='data:imagePlacement != &quot;REPLACE&quot;' name='description'/>
    </div>
    <b:include cond='data:imagePlacement == &quot;BEHIND&quot;' name='behindImageStyle'/>
  </b:includable>
                      <b:includable id='behindImageStyle'>
    <b:if cond='data:sourceUrl'>
      <b:include cond='data:this.image' data='{                    image: data:this.image,                    selector: &quot;.header-widget&quot;                  }' name='responsiveImageStyle'/>
      <style type='text/css'>
        .header-widget {
          background-position: <data:blog.locale.languageAlignment/>;
          background-repeat: no-repeat;
          background-size: cover;
        }
      </style>
    </b:if>
  </b:includable>
                      <b:includable id='description'>
          <!-- Don't show description on the item page -->
          <b:include cond='not data:view.isSingleItem' name='super.description'/>
        </b:includable>
                      <b:includable id='image'>
          <b:include name='super.image'/>
          <!-- If we are replacing the title, force it to render anyway, and it'll be hidden in CSS. -->
          <b:include cond='data:this.imagePlacement == &quot;REPLACE&quot;' name='title'/>
        </b:includable>
                      <b:includable id='title'>
          <div>
            <b:class cond='data:this.imagePlacement == &quot;REPLACE&quot;' name='replaced'/>
            <b:include name='super.title'/>
          </div>
        </b:includable>
                    </b:widget>
                  </b:section>
                </div>

                <b:if cond='data:view.isLayoutMode or data:widgets any (w =&gt; w.sectionId == &quot;search_top&quot;)'>
                  <div class='search'>
                    <b:class cond='data:view.isSearch and data:view.search.query' name='focused'/>
                    <button class='search-expand touch-icon-button' expr:aria-label='data:messages.search.escaped'>
                      <div class='search-expand-text'><data:messages.search/></div>
                      <b:include data='{ iconClass: &quot;touch-icon search-expand-icon&quot; }' name='searchIcon'/>
                    </button>
                    <b:section id='search_top' name='Pencarian' showaddelement='yes'>
                      <b:widget id='BlogSearch1' locked='false' title='Cari Blog Ini' type='BlogSearch' visible='true'>
                        <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
                        <b:includable id='content'>
  <div class='widget-content' role='search'>
    <b:include name='searchForm'/>
  </div>
</b:includable>
                        <b:includable id='searchForm'>
  <form expr:action='data:blog.searchUrl'>
    <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
    <b:include name='urlParamsAsFormInput'/>
    <div class='search-input'>
      <input autocomplete='off' expr:aria-label='data:messages.searchThisBlog' expr:placeholder='data:messages.searchThisBlog' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q'/>
    </div>
    <b:include name='searchSubmit'/>
  </form>
</b:includable>
                        <b:includable id='searchSubmit'>
          <b:if cond='data:widget.sectionId == &quot;search_top&quot;'>
            <label class='search-submit-container'>
              <input type='submit'/>
              <b:include data='{ iconClass: &quot;touch-icon search-icon&quot; }' name='searchIcon'/>
            </label>
          <b:else/>
            <b:include name='super.searchSubmit'/>
          </b:if>
        </b:includable>
                      </b:widget>
                    </b:section>
                  </div>
                </b:if>

                <b:if cond='data:view.isLayoutMode or not data:view.isSingleItem'>
                  <nav class='top-nav' role='navigation'>
                    <b:section id='page_list_top' name='Halaman atas' showaddelement='yes'/>
                  </nav>
                </b:if>
              </div>

            </header>
            <div class='centered-bottom'>
              <b:if cond='data:view.isArchive or (data:view.isSearch and data:view.search.resultsMessage)'>
                <div class='post-filter-message'>
                  <div>
                    <b:if cond='data:view.isArchive'>
                      <data:view.archive.rangeMessage/>
                    <b:elseif cond='data:view.isSearch and data:view.search.resultsMessage'/>
                      <data:view.search.resultsMessageHtml/>
                    </b:if>
                  </div>
                  <div>
                    <a expr:href='data:blog.homepageUrl'><data:messages.viewAll/></a>
                  </div>
                </div>
              </b:if>

              <main class='main-container' id='main' role='main' tabindex='-1'>
                <b:if cond='data:view.isMultipleItems'>
                  <h2 class='main-heading'><data:messages.posts/></h2>
                </b:if>

                <b:section class='featured-post' id='featured_post' name='Unggulan' showaddelement='yes'/>

                <b:section class='main' id='page_body' name='Page Body' showaddelement='yes'>
                  <b:widget id='Blog1' locked='false' title='Postingan Blog' type='Blog' version='2' visible='true'>
                    <b:widget-settings>
                      <b:widget-setting name='commentLabel'>Komentar</b:widget-setting>
                      <b:widget-setting name='showShareButtons'>false</b:widget-setting>
                      <b:widget-setting name='authorLabel'/>
                      <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                      <b:widget-setting name='timestampLabel'/>
                      <b:widget-setting name='reactionsLabel'/>
                      <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
                      <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                      <b:widget-setting name='showLocation'>false</b:widget-setting>
                      <b:widget-setting name='showTimestamp'>true</b:widget-setting>
                      <b:widget-setting name='postsPerAd'>1</b:widget-setting>
                      <b:widget-setting name='style.bordercolor'>#000000</b:widget-setting>
                      <b:widget-setting name='showDateHeader'>false</b:widget-setting>
                      <b:widget-setting name='style.textcolor'>#0f9d58</b:widget-setting>
                      <b:widget-setting name='showCommentLink'>false</b:widget-setting>
                      <b:widget-setting name='style.urlcolor'>#eeeeee</b:widget-setting>
                      <b:widget-setting name='postLocationLabel'>Location:</b:widget-setting>
                      <b:widget-setting name='showAuthor'>false</b:widget-setting>
                      <b:widget-setting name='style.linkcolor'>#ffffff</b:widget-setting>
                      <b:widget-setting name='style.bgcolor'>#000000</b:widget-setting>
                      <b:widget-setting name='showLabels'>false</b:widget-setting>
                      <b:widget-setting name='postLabelsLabel'/>
                      <b:widget-setting name='showBacklinks'>false</b:widget-setting>
                      <b:widget-setting name='showInlineAds'>false</b:widget-setting>
                      <b:widget-setting name='showReactions'>false</b:widget-setting>
                    </b:widget-settings>
                    <b:includable id='main'>
          <b:include name='noContentPlaceholder'/>
          <b:include name='super.main'/>
        </b:includable>
                    <b:includable id='aboutPostAuthor'>
  <div class='author-name'>
    <a class='g-profile' expr:href='data:post.author.profileUrl' rel='author' title='author profile'>
      <span>
        <data:post.author.name/>
      </span>
    </a>
  </div>
  <div>
    <span class='author-desc'>
      <data:post.author.aboutMe/>
    </span>
  </div>
</b:includable>
                    <b:includable id='addComments'>
  <a expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:message name='messages.postAComment'/>
  </a>
</b:includable>
                    <b:includable id='blogThisShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
                    <b:includable id='bylineByName' var='byline'>
  <b:switch var='data:byline.name'>
  <b:case value='share'/>
    <b:include cond='data:post.shareUrl' name='postShareButtons'/>
  <b:case value='comments'/>
    <b:include cond='data:post.allowComments' name='postCommentsLink'/>
  <b:case value='location'/>
    <b:include cond='data:post.location' name='postLocation'/>
  <b:case value='timestamp'/>
    <b:include cond='not data:view.isPage' name='postTimestamp'/>
  <b:case value='author'/>
    <b:include name='postAuthor'/>
  <b:case value='labels'/>
    <b:include cond='data:post.labels' name='postLabels'/>
  <b:case value='icons'/>
    <b:include cond='data:post.emailPostUrl' name='emailPostIcon'/>
  </b:switch>
</b:includable>
                    <b:includable id='bylineRegion' var='regionItems'>
  <b:loop values='data:regionItems' var='byline'>
    <b:include data='byline' name='bylineByName'/>
  </b:loop>
</b:includable>
                    <b:includable id='commentAuthorAvatar'>
  <div class='avatar-image-container'>
    <img class='author-avatar' expr:src='data:comment.authorAvatarSrc' height='35' width='35'/>
  </div>
</b:includable>
                    <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:messages.deleteComment'>
        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
                    <b:includable id='commentForm' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <h4 id='comment-post-message'><data:messages.postAComment/></h4>
    <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
      <p><data:this.messages.blogComment/></p>
    </b:if>
    <b:include data='post' name='commentFormIframeSrc'/>
    <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
                    <b:includable id='commentFormIframeSrc' var='post'>
  <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
</b:includable>
                    <b:includable id='commentItem' var='comment'>
  <div class='comment' expr:id='&quot;c&quot; + data:comment.id'>
    <b:include cond='data:blog.enabledCommentProfileImages' name='commentAuthorAvatar'/>

    <div class='comment-block'>
      <div class='comment-author'>
        <b:if cond='data:comment.authorUrl'>
          <b:message name='messages.authorSaidWithLink'>
            <b:param expr:value='data:comment.author' name='authorName'/>
            <b:param expr:value='data:comment.authorUrl' name='authorUrl'/>
          </b:message>
        <b:else/>
          <b:message name='messages.authorSaid'>
            <b:param expr:value='data:comment.author' name='authorName'/>
          </b:message>
        </b:if>
      </div>
      <div expr:class='&quot;comment-body&quot; + (data:comment.isDeleted ? &quot; deleted&quot; : &quot;&quot;)'>
        <data:comment.body/>
      </div>
      <div class='comment-footer'>
        <span class='comment-timestamp'>
          <a expr:href='data:comment.url' title='comment permalink'>
            <data:comment.timestamp/>
          </a>
          <b:include data='comment' name='commentDeleteIcon'/>
        </span>
      </div>
    </div>
  </div>
</b:includable>
                    <b:includable id='commentList' var='comments'>
  <div id='comments-block'>
    <b:loop values='data:comments' var='comment'>
      <b:include data='comment' name='commentItem'/>
    </b:loop>
  </div>
</b:includable>
                    <b:includable id='commentPicker' var='post'>
  <b:if cond='data:post.showThreadedComments'>
    <b:include data='post' name='threadedComments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
                    <b:includable id='comments' var='post'>
  <section expr:class='&quot;comments&quot; + (data:post.embedCommentForm ? &quot; embed&quot; : &quot;&quot;)' expr:data-num-comments='data:post.numberOfComments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>

      <b:include name='commentsTitle'/>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <b:include cond='data:post.comments' data='post.comments' name='commentList'/>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <div class='paging-control-container'>
          <b:if cond='data:post.hasOlderLinks'>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
              <data:messages.oldest/>
            </a>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
              <data:messages.older/>
            </a>
          </b:if>

          <span class='comment-range-text'>
            <data:post.commentRangeText/>
          </span>

          <b:if cond='data:post.hasNewerLinks'>
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
              <data:messages.newer/>
            </a>
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
              <data:messages.newest/>
            </a>
          </b:if>
        </div>
      </b:if>

      <div class='footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='commentForm'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:else/>
          <b:if cond='data:post.allowComments'>
            <b:include data='post' name='addComments'/>
          </b:if>
        </b:if>
      </div>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>
  </section>
</b:includable>
                    <b:includable id='commentsLink'>
          <a class='comment-link' expr:href='data:post.commentsUrl ?: data:post.url' expr:onclick='data:post.commentsUrlOnclick'>
            <b:include name='commentIcon'/>
            <span class='num_comments'>
              <data:post.numberOfComments/>
            </span>
          </a>
        </b:includable>
                    <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
                    <b:includable id='commentsTitle'>
  <h3 class='title'><data:messages.comments/></h3>
</b:includable>
                    <b:includable id='defaultAdUnit'>
          <!-- Clear out style (need non-empty string) -->
          <b:with value='&quot;/* Done in css. */&quot;' var='style'>
            <b:include name='super.defaultAdUnit'/>
          </b:with>
        </b:includable>
                    <b:includable id='emailPostIcon'>
  <span class='byline post-icons'>
    <!-- email post links -->
    <span class='item-action'>
      <a expr:href='data:post.emailPostUrl' expr:title='data:messages.emailPost'>
        <b:include data='{ iconClass: &quot;touch-icon sharing-icon&quot; }' name='emailIcon'/>
      </a>
    </span>
  </span>
</b:includable>
                    <b:includable id='facebookShare'>
  <b:with value='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
                    <b:includable id='feedLinks'>
          <!-- Don't show feed links. -->
        </b:includable>
                    <b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:messages.subscribeTo/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
                    <b:includable id='footerBylines'>
          <!-- Set the calling parent element to be a container. -->
          <b:class name='container'/>

          <b:if cond='data:view.isSingleItem and data:widget.type == &quot;Blog&quot;'>
            <b:include name='super.footerBylines'/>
          <b:else/>
            <b:include data='{ items: [[&quot;comments&quot;]] }' name='footerBylinesOverride'/>
          </b:if>
          <b:include data='{ shareButtonClass: &quot;post-share-buttons-bottom&quot;, overridden: true }' name='maybeAddShareButtons'/>
        </b:includable>
                    <b:includable id='googlePlusShare'>
</b:includable>
                    <b:includable id='headerByline'>
          <b:if cond='data:view.isSingleItem and data:widget.type == &quot;Blog&quot;'>
            <b:include name='super.headerByline'/>
          <b:else/>
            <b:include data='{ items: [&quot;author&quot;, &quot;timestamp&quot;, &quot;labels&quot;] }' name='headerBylineOverride'/>
          </b:if>
          <b:include cond='data:view.isSingleItem and data:widget.type == &quot;Blog&quot;' data='{ shareButtonClass: &quot;post-share-buttons-top&quot;, overridden: true }' name='maybeAddShareButtons'/>
        </b:includable>
                    <b:includable id='homePageLink'>
          <b:comment>We don&#39;t show home page links in Emporio.</b:comment>
        </b:includable>
                    <b:includable id='iframeComments' var='post'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
                    <b:includable id='inlineAd' var='post'>
          <!-- Cap the total number of ads (widgets and inline ads). -->
          <b:include cond='data:post.adNumber lt 3' data='post' name='super.inlineAd'/>
        </b:includable>
                    <b:includable id='linkShare'>
  <b:with value='&quot;window.prompt(\&quot;Copy to clipboard: Ctrl+C, Enter\&quot;, \&quot;&quot; + data:originalUrl + &quot;\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
                    <b:includable id='nextPageLink'>
          <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:title='data:messages.morePosts'>
            <data:messages.morePosts/>
          </a>
        </b:includable>
                    <b:includable id='otherSharingButton'>
  <span class='sharing-platform-button sharing-element-other' expr:aria-label='data:messages.shareToOtherApps.escaped' expr:data-url='data:originalUrl' expr:title='data:messages.shareToOtherApps.escaped' role='menuitem' tabindex='-1'>
    <b:with value='{key: &quot;sharingOther&quot;}' var='platform'>
      <b:include name='sharingPlatformIcon'/>
    </b:with>
    <span class='platform-sharing-text'><data:messages.shareOtherApps.escaped/></span>
  </span>
</b:includable>
                    <b:includable id='platformShare'>
  <a expr:class='&quot;goog-inline-block sharing-&quot; + data:platform.key' expr:data-url='data:originalUrl' expr:href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:onclick='data:onclick ? data:onclick : &quot;&quot;' expr:title='data:platform.shareMessage' target='_blank'>
    <span class='share-button-link-text'>
      <data:platform.shareMessage/>
    </span>
  </a>
</b:includable>
                    <b:includable id='post' var='post'>
          <b:with value='&quot;post-thumb-&quot; + data:post.id' var='thumbClassName'>
            <div expr:class='&quot;post-wrapper not-hero post-&quot; + data:post.id'>
              <b:include name='postWrapperClasses'/>

              <!-- Standard feed thumbs always added, as they're needed for mobile view. -->
              <b:include cond='data:post.featuredImage and data:view.isMultipleItems' name='standardPostImageStyle'/>
              <b:include name='feedPostImage'/>

              <div class='slide'>
                <b:include data='post' name='super.post'/>
              </div>
            </div>
          </b:with>
        </b:includable>
                    <b:includable id='postAuthor'>
  <span class='byline post-author vcard'>
    <span class='post-author-label'>
      <data:byline.label/>
    </span>
    <span class='fn'>
      <b:if cond='data:post.author.profileUrl'>
        <meta expr:content='data:post.author.profileUrl'/>
        <a class='g-profile' expr:href='data:post.author.profileUrl' rel='author' title='author profile'>
          <span><data:post.author.name/></span>
        </a>
      <b:else/>
        <span><data:post.author.name/></span>
      </b:if>
    </span>
  </span>
</b:includable>
                    <b:includable id='postBody' var='post'>
  <!-- If metaDescription is empty, use the post body as the schema.org description too, for G+/FB snippeting. -->
  <div class='post-body entry-content float-container' expr:id='&quot;post-body-&quot; + data:post.id'>
    <data:post.body/>
  </div>
</b:includable>
                    <b:includable id='postBodySnippet' var='post'>
          <div class='post-body entry-content' expr:id='&quot;post-snippet-&quot; + data:post.id'>
            <b:if cond='data:post.featuredImage and not data:view.isMultipleItems'>
              <b:with value='&quot;post-&quot; + data:post.id' var='className'>
                <style>
                  .<data:className/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 385, &quot;385:185&quot;).cssEscaped'/>);}
                  @media (max-width: 285px) { .<data:className/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 285, &quot;285:185&quot;).cssEscaped'/>);} }
                  @media (max-width: 385px) and (min-width: 286px) { .<data:className/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 385, &quot;385:185&quot;).cssEscaped'/>);} }
                  @media (max-width: 485px) and (min-width: 386px) { .<data:className/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 485, &quot;485:185&quot;).cssEscaped'/>);} }
                  @media (max-width: 745px) and (min-width: 486px) { .<data:className/> {background-image:url(<b:eval expr='resizeImage(data:post.featuredImage, 585, &quot;585:185&quot;).cssEscaped'/>);} }
                </style>
                <div class='snippet-thumbnail-container'>
                  <div expr:class='&quot;snippet-thumbnail &quot; + data:className'/>
                </div>
              </b:with>
            </b:if>
            <div style='clear: both;'/>
          </div>
        </b:includable>
                    <b:includable id='postCommentsAndAd'>
          <b:include cond='not data:view.isHomepage or                            data:widgets.FeaturedPost none (w =&gt; w.sectionId == &quot;featured_post&quot; and w.postId == data:post.id)' name='super.postCommentsAndAd'/>
        </b:includable>
                    <b:includable id='postCommentsLink'>
  <b:if cond='data:view.isMultipleItems'>
    <span class='byline post-comment-link container'>
      <b:include cond='data:post.commentSource != 1' name='commentsLink'/>
    </span>
  </b:if>
</b:includable>
                    <b:includable id='postFooter' var='post'>
  <div class='post-footer'>
    <b:include name='footerBylines'/>
    <b:include data='post' name='postFooterAuthorProfile'/>
  </div>
</b:includable>
                    <b:includable id='postFooterAuthorProfile' var='post'>
  <b:if cond='data:post.author.aboutMe and data:view.isPost'>
    <div class='author-profile'>
      <b:if cond='data:post.author.authorPhoto.url'>
        <img class='author-image' expr:src='data:post.author.authorPhoto.url' width='50px'/>
        <div class='author-about'>
          <b:include data='post' name='aboutPostAuthor'/>
        </div>
      <b:else/>
        <b:include data='post' name='aboutPostAuthor'/>
      </b:if>
    </div>
  </b:if>
</b:includable>
                    <b:includable id='postHeader' var='post'>
  <b:include name='headerByline'/>
</b:includable>
                    <b:includable id='postJumpLink' var='post'>
          <b:comment>We don&#39;t show &#39;read more&#39; links in Emporio.</b:comment>
        </b:includable>
                    <b:includable id='postLabels'>
          <b:if cond='data:view.isMultipleItems'>
           <div class='labels-outer-container'>
              <div class='labels-container overflowable-container overflowable-no-popup'>
                <div class='labels-items overflowable-contents byline post-labels'>
                  <b:loop index='i' values='data:post.labels' var='label'>
                    <span class='overflowable-item'>
                      <a expr:href='data:label.url' rel='tag'><data:label.name/></a>
                    </span>
                  </b:loop>
                </div>
                <span class='labels-more overflow-button hidden'>
                  <a expr:href='data:post.link ?: data:post.url'>+<span class='overflow-count'/></a>
                </span>
              </div>
            </div>
          <b:else/>
            <b:include name='super.postLabels'/>
          </b:if>
        </b:includable>
                    <b:includable id='postLocation'>
  <span class='byline post-location'>
    <data:byline.label/>
    <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
  </span>
</b:includable>
                    <b:includable id='postMeta' var='post'>
  <b:include data='post' name='postMetadataJSON'/>
</b:includable>
                    <b:includable id='postMetadataJSONImage'>
  &quot;image&quot;: {
    &quot;@type&quot;: &quot;ImageObject&quot;,
    <b:if cond='data:post.featuredImage.isResizable'>
    &quot;url&quot;: &quot;<b:eval expr='resizeImage(data:post.featuredImage, 1200, &quot;1200:630&quot;)'/>&quot;,
    &quot;height&quot;: 630,
    &quot;width&quot;: 1200
    <b:else/>
    &quot;url&quot;: &quot;https://blogger.googleusercontent.com/img/b/U2hvZWJveA/AVvXsEgfMvYAhAbdHksiBA24JKmb2Tav6K0GviwztID3Cq4VpV96HaJfy0viIu8z1SSw_G9n5FQHZWSRao61M3e58ImahqBtr7LiOUS6m_w59IvDYwjmMcbq3fKW4JSbacqkbxTo8B90dWp0Cese92xfLMPe_tg11g/w1200/&quot;,
    &quot;height&quot;: 348,
    &quot;width&quot;: 1200
    </b:if>
  },
</b:includable>
                    <b:includable id='postMetadataJSONPublisher'>
 &quot;publisher&quot;: {
    &quot;@type&quot;: &quot;Organization&quot;,
    &quot;name&quot;: &quot;Blogger&quot;,
    &quot;logo&quot;: {
      &quot;@type&quot;: &quot;ImageObject&quot;,
      &quot;url&quot;: &quot;https://blogger.googleusercontent.com/img/b/U2hvZWJveA/AVvXsEgfMvYAhAbdHksiBA24JKmb2Tav6K0GviwztID3Cq4VpV96HaJfy0viIu8z1SSw_G9n5FQHZWSRao61M3e58ImahqBtr7LiOUS6m_w59IvDYwjmMcbq3fKW4JSbacqkbxTo8B90dWp0Cese92xfLMPe_tg11g/h60/&quot;,
      &quot;width&quot;: 206,
      &quot;height&quot;: 60
    }
  },
</b:includable>
                    <b:includable id='postPagination'>
  <div class='blog-pager container' id='blog-pager'>
    <b:include cond='data:newerPageUrl' name='previousPageLink'/>
    <b:include cond='data:olderPageUrl' name='nextPageLink'/>
    <b:include cond='data:view.url != data:blog.homepageUrl' name='homePageLink'/>
  </div>
</b:includable>
                    <b:includable id='postReactions'>
  <!-- Reaction feature no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
                    <b:includable id='postShareButtons' var='post'>
          <!-- We call super.postShareButtons from the migrated positions. -->
        </b:includable>
                    <b:includable id='postTimestamp'>
  <span class='byline post-timestamp'>
    <data:byline.label/>
    <b:if cond='data:post.url'>
      <meta expr:content='data:post.url.canonical'/>
      <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'>
        <time class='published' expr:datetime='data:post.date.iso8601' expr:title='data:post.date.iso8601'>
          <data:post.date/>
        </time>
      </a>
    </b:if>
  </span>
</b:includable>
                    <b:includable id='postTitle' var='post'>
          <!-- Snippetize the post title -->
          <div class='post-title-container'>
            <a expr:name='data:post.id'/>
            <h3 class='post-title entry-title'>
              <b:if cond='data:post.link or (data:post.url and data:view.url != data:post.url)'>
                <a expr:href='data:post.link ?: data:post.url'>
                  <div class='snippet-container r-snippet-container'>
                    <div class='r-snippetized'>
                      <data:post.title/>
                    </div>
                    <b:if cond='data:post.title != &quot;&quot;'>
                      <div class='snippet-fade r-snippet-fade hidden'/>
                    </b:if>
                  </div>
                </a>
              <b:else/>
                <data:post.title/>
              </b:if>
            </h3>
          </div>
        </b:includable>
                    <b:includable id='postWrapperClasses'>
          <b:class cond='data:post.featuredImage' name='image'/>
          <b:class cond='not data:post.featuredImage' name='no-image'/>
          <b:class cond='data:post.labels and not data:post.labels.empty' name='has-labels'/>
        </b:includable>
                    <b:includable id='previousPageLink'>
          <b:comment>We don&#39;t show previeus page links in Emporio.</b:comment>
        </b:includable>
                    <b:includable id='sharingButton'>
  <span expr:aria-label='data:platform.shareMessage' expr:class='&quot;sharing-platform-button sharing-element-&quot; + data:platform.key' expr:data-href='data:shareUrl + &quot;&amp;target=&quot; + data:platform.target' expr:data-url='data:originalUrl' expr:title='data:platform.shareMessage' role='menuitem' tabindex='-1'>
    <b:include name='sharingPlatformIcon'/>
    <span class='platform-sharing-text'><data:platform.name/></span>
  </span>
</b:includable>
                    <b:includable id='sharingButtonContent'>
  <div class='flat-icon-button ripple'>
    <b:include name='shareIcon'/>
  </div>
</b:includable>
                    <b:includable id='sharingButtons'>
  <div class='sharing' expr:aria-owns='&quot;sharing-popup-&quot; + data:sharingId' expr:data-title='data:shareTitle'>
    <button class='sharing-button touch-icon-button' expr:aria-controls='&quot;sharing-popup-&quot; + data:sharingId' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-button-&quot; + data:sharingId' role='button'>
      <b:include name='sharingButtonContent'/>
    </button>
    <b:include name='sharingButtonsMenu'/>
  </div>
</b:includable>
                    <b:includable id='sharingButtonsMenu'>
  <div class='share-buttons-container'>
    <ul aria-hidden='true' class='share-buttons hidden' expr:aria-label='data:messages.share.escaped' expr:id='&quot;sharing-popup-&quot; + data:sharingId' role='menu'>
      <b:loop values='(data:platforms ?: data:blog.sharing.platforms) filter (p =&gt; p.key not in {&quot;blogThis&quot;})' var='platform'>
        <li>
          <b:include name='sharingButton'/>
        </li>
      </b:loop>
      <li aria-hidden='true' class='hidden'>
        <b:include name='otherSharingButton'/>
      </li>
    </ul>
  </div>
</b:includable>
                    <b:includable id='sharingPlatformIcon'>
  <b:include data='{ iconClass: (&quot;touch-icon sharing-&quot; + data:platform.key) }' expr:name='data:platform.key + &quot;Icon&quot;'/>
</b:includable>
                    <b:includable id='snippetedPostThumbnail'>
          <div class='item-thumbnail'>
            <a expr:href='data:post.url'>
              <b:include data='{                                  image: data:post.featuredImage,                                  imageSizes: [280,560,840,1120,1400]                                }' name='responsiveImage'/>
            </a>
          </div>
        </b:includable>
                    <b:includable id='threadedCommentForm' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <h4 id='comment-post-message'><data:messages.postAComment/></h4>
    <b:if cond='data:this.messages.blogComment != &quot;&quot;'>
      <p><data:this.messages.blogComment/></p>
    </b:if>
    <b:include data='post' name='commentFormIframeSrc'/>
    <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight ?: &quot;90px&quot;' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
                    <b:includable id='threadedCommentJs' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
  <b:template-script inline='true' name='threaded_comments'/>
  <script type='text/javascript'>
    blogger.widgets.blog.initThreadedComments(
        <data:post.commentJso/>,
        <data:post.commentMsgs/>,
        <data:post.commentConfig/>);
  </script>
</b:includable>
                    <b:includable id='threadedComments' var='post'>
  <section class='comments threaded' expr:data-embed='data:post.embedCommentForm' expr:data-num-comments='data:post.numberOfComments' id='comments'>
    <a name='comments'/>

    <b:include name='commentsTitle'/>

    <div class='comments-content'>
      <b:if cond='data:post.embedCommentForm'>
        <b:include data='post' name='threadedCommentJs'/>
      </b:if>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threadedCommentForm'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
      <b:if cond='data:post.showManageComments'>
        <b:include data='post' name='manageComments'/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='allowtransparency' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>
  </section>
</b:includable>
                  </b:widget>
                </b:section>
              </main>

              <b:section ads='true' class='vertical-ad-container' id='ads' name='Ads' showaddelement='yes'/>

              <aside class='sidebar-container container' role='complementary'>
                <b:class cond='not data:view.isSingleItem' name='sidebar-invisible'/>
                <b:if cond='not data:view.isSingleItem or data:view.isLayoutMode'>
                  <!-- Display different sidebars for feed page / item page. -->
                  <div class='navigation'>
                    <b:include data='{ iconClass: &quot;touch-icon sidebar-back&quot; }' name='closeIcon'/>
                  </div>
                  <b:section class='sidebar' id='sidebar_feed' name='Sidebar' preferred='yes'>
                    <b:widget id='Profile1' locked='false' title='' type='Profile' visible='true'>
                      <b:widget-settings>
                        <b:widget-setting name='showaboutme'>true</b:widget-setting>
                        <b:widget-setting name='showlocation'>true</b:widget-setting>
                      </b:widget-settings>
                      <b:includable id='main'>
          <b:include name='content'/>
        </b:includable>
                      <b:includable id='authorProfileImage'>
  <img class='profile-img' expr:alt='data:messages.myPhoto' expr:height='data:authorPhoto.height' expr:src='data:authorPhoto.image' expr:width='data:authorPhoto.width'/>
</b:includable>
                      <b:includable id='content'>
  <b:if cond='data:team'>
    <div class='widget-content team'>
      <b:include name='teamProfile'/>
    </div>
  <b:else/>
    <div class='widget-content individual'>
      <b:include name='userProfile'/>
    </div>
  </b:if>
</b:includable>
                      <b:includable id='defaultProfileImage'>
          <div class='default-avatar-wrapper'>
            <b:include data='{ iconClass: &quot;avatar-icon&quot; }' name='defaultAvatarIcon'/>
          </div>
        </b:includable>
                      <b:includable id='profileImage'>
  <b:if cond='data:authorPhoto.image'>
    <b:include name='authorProfileImage'/>
  <b:else/>
    <b:include name='defaultProfileImage'/>
  </b:if>
</b:includable>
                      <b:includable id='teamProfile'>
          <div class='extendable'>
            <b:include data='{                                 items: data:authors,                                 itemSet: &quot;authors&quot;,                                 itemsMarkup: &quot;super.teamProfile&quot;,                                 limit: 4                               }' name='extendableItems'/>
          </div>
        </b:includable>
                      <b:includable id='teamProfileLink'>
          <!-- Add an extra 'Visit profile' link -->
          <a class='profile-link g-profile' expr:href='data:author.userUrl'>
            <b:include name='profileImage'/>
            <div class='profile-name-container'>
              <span class='profile-name'><data:author.display-name/></span>
              <data:messages.visitProfile/>
            </div>
          </a>
        </b:includable>
                      <b:includable id='userLocation'>
  <dd class='profile-data location'><data:location/></dd>
</b:includable>
                      <b:includable id='userProfile'>
  <b:include name='userProfileImage'/>
  <b:include name='userProfileInfo'/>
</b:includable>
                      <b:includable id='userProfileData'>
  <dt class='profile-data'>
    <a class='profile-link g-profile' expr:href='data:userUrl' rel='author nofollow'>
      <data:displayname/>
    </a>
  </dt>
</b:includable>
                      <b:includable id='userProfileImage'>
  <a expr:href='data:userUrl' rel='nofollow'>
    <b:include name='profileImage'/>
  </a>
</b:includable>
                      <b:includable id='userProfileInfo'>
  <div class='profile-info'>
    <dl class='profile-datablock'>
      <b:class cond='data:showlocation and data:location != &quot;&quot;' name='has-location'/>

      <b:include name='userProfileData'/>
      <b:include cond='data:showlocation and data:location != &quot;&quot;' name='userLocation'/>
      <b:include cond='data:aboutme != &quot;&quot;' name='userProfileText'/>
    </dl>
    <b:include name='viewProfileLink'/>
  </div>
</b:includable>
                      <b:includable id='userProfileText'>
  <dd class='profile-textblock'>
    <data:aboutme/>
  </dd>
</b:includable>
                      <b:includable id='viewProfileLink'>
          <!-- Change single profile link message to 'Visit profile' -->
          <a class='profile-link' expr:href='data:userUrl' rel='author'><data:messages.visitProfile/></a>
        </b:includable>
                    </b:widget>
                    <b:widget id='Label1' locked='false' title='KATEGORI' type='Label' visible='true'>
                      <b:widget-settings>
                        <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
                        <b:widget-setting name='display'>CLOUD</b:widget-setting>
                        <b:widget-setting name='selectedLabelsList'/>
                        <b:widget-setting name='showType'>ALL</b:widget-setting>
                        <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
                      </b:widget-settings>
                      <b:includable id='main' var='this'>
          <details class='collapsible extendable'>
            <b:attr cond='data:view.isLabelSearch' name='open' value='open'/>
            <b:with value='true' var='renderAsDetails'>
            <b:with value='data:messages.labels' var='defaultTitle'>
              <b:include name='super.main'/>
            </b:with>
            </b:with>
          </details>
        </b:includable>
                      <b:includable id='cloud'>
          <b:include data='{                               buttonClass: &quot;flat-button&quot;,                               items: data:this.labels,                               itemSet: &quot;labels&quot;,                               itemsMarkup: &quot;super.cloud&quot;                             }' name='extendableItems'/>
        </b:includable>
                      <b:includable id='content'>
  <div class='widget-content'>
    <b:class expr:name='data:this.display + &quot;-label-widget-content&quot;'/>
    <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
    <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
  </div>
</b:includable>
                      <b:includable id='list'>
          <b:include data='{                               buttonClass: &quot;flat-button&quot;,                               items: data:this.labels,                               itemSet: &quot;labels&quot;,                               itemsMarkup: &quot;super.list&quot;                             }' name='extendableItems'/>
        </b:includable>
                    </b:widget>
                    <b:widget id='LinkList1' locked='false' title='' type='LinkList' visible='true'>
                      <b:widget-settings>
                        <b:widget-setting name='sorting'>NONE</b:widget-setting>
                        <b:widget-setting name='text-1'>&#8226; &#8206; Tentang Saya</b:widget-setting>
                        <b:widget-setting name='link-1'>https://about.me/saya_rifki</b:widget-setting>
                        <b:widget-setting name='text-0'>&#8226; &#8206; Hubungi Saya</b:widget-setting>
                        <b:widget-setting name='link-0'>https://form.123formbuilder.com/6327126/formulir</b:widget-setting>
                      </b:widget-settings>
                      <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
                      <b:includable id='content'>
 <div class='widget-content'>
   <ul>
     <b:loop values='data:links' var='link'>
       <li><a expr:href='data:link.target'><data:link.name/></a></li>
     </b:loop>
   </ul>
 </div>
</b:includable>
                    </b:widget>
                    <b:widget id='HTML1' locked='false' title='' type='HTML' visible='true'>
                      <b:widget-settings>
                        <b:widget-setting name='content'>&lt;!-- Go to www.addthis.com/dashboard to customize your tools --&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;//s7.addthis.com/js/300/addthis_widget.js#pubid=ra-62d8f22fd45a34cd&quot;&gt;&lt;/script&gt;

                &lt;!-- Go to www.addthis.com/dashboard to customize your tools --&gt;
                &lt;div class=&quot;addthis_inline_follow_toolbox_jlgn&quot;&gt;&lt;/div&gt;</b:widget-setting>
                      </b:widget-settings>
                      <b:includable id='main'>
  <b:include name='widget-title'/>
  <div class='widget-content'>
    <data:content/>
  </div>
</b:includable>
                    </b:widget>
                  </b:section>
                </b:if>
                <b:if cond='data:view.isSingleItem or data:view.isLayoutMode'>
                  <b:section id='sidebar_item' name='Bilah sisi2'>
                    <b:widget id='Profile2' locked='false' title='' type='Profile' visible='true'>
                      <b:widget-settings>
                        <b:widget-setting name='showaboutme'>true</b:widget-setting>
                        <b:widget-setting name='showlocation'>true</b:widget-setting>
                      </b:widget-settings>
                      <b:includable id='main'>
          <b:include name='content'/>
        </b:includable>
                      <b:includable id='authorProfileImage'>
  <img class='profile-img' expr:alt='data:messages.myPhoto' expr:height='data:authorPhoto.height' expr:src='data:authorPhoto.image' expr:width='data:authorPhoto.width'/>
</b:includable>
                      <b:includable id='content'>
  <b:if cond='data:team'>
    <div class='widget-content team'>
      <b:include name='teamProfile'/>
    </div>
  <b:else/>
    <div class='widget-content individual'>
      <b:include name='userProfile'/>
    </div>
  </b:if>
</b:includable>
                      <b:includable id='defaultProfileImage'>
          <div class='default-avatar-wrapper'>
            <b:include data='{ iconClass: &quot;avatar-icon&quot; }' name='defaultAvatarIcon'/>
          </div>
        </b:includable>
                      <b:includable id='profileImage'>
  <b:if cond='data:authorPhoto.image'>
    <b:include name='authorProfileImage'/>
  <b:else/>
    <b:include name='defaultProfileImage'/>
  </b:if>
</b:includable>
                      <b:includable id='teamProfile'>
          <div class='extendable'>
            <b:include data='{                                 items: data:authors,                                 itemSet: &quot;authors&quot;,                                 itemsMarkup: &quot;super.teamProfile&quot;,                                 limit: 4                               }' name='extendableItems'/>
          </div>
        </b:includable>
                      <b:includable id='teamProfileLink'>
          <!-- Add an extra 'Visit profile' link -->
          <a class='profile-link g-profile' expr:href='data:author.userUrl'>
            <b:include name='profileImage'/>
            <div class='profile-name-container'>
              <span class='profile-name'><data:author.display-name/></span>
              <data:messages.visitProfile/>
            </div>
          </a>
        </b:includable>
                      <b:includable id='userLocation'>
  <dd class='profile-data location'><data:location/></dd>
</b:includable>
                      <b:includable id='userProfile'>
  <b:include name='userProfileImage'/>
  <b:include name='userProfileInfo'/>
</b:includable>
                      <b:includable id='userProfileData'>
  <dt class='profile-data'>
    <a class='profile-link g-profile' expr:href='data:userUrl' rel='author nofollow'>
      <data:displayname/>
    </a>
  </dt>
</b:includable>
                      <b:includable id='userProfileImage'>
  <a expr:href='data:userUrl' rel='nofollow'>
    <b:include name='profileImage'/>
  </a>
</b:includable>
                      <b:includable id='userProfileInfo'>
  <div class='profile-info'>
    <dl class='profile-datablock'>
      <b:class cond='data:showlocation and data:location != &quot;&quot;' name='has-location'/>

      <b:include name='userProfileData'/>
      <b:include cond='data:showlocation and data:location != &quot;&quot;' name='userLocation'/>
      <b:include cond='data:aboutme != &quot;&quot;' name='userProfileText'/>
    </dl>
    <b:include name='viewProfileLink'/>
  </div>
</b:includable>
                      <b:includable id='userProfileText'>
  <dd class='profile-textblock'>
    <data:aboutme/>
  </dd>
</b:includable>
                      <b:includable id='viewProfileLink'>
          <!-- Change single profile link message to 'Visit profile' -->
          <a class='profile-link' expr:href='data:userUrl' rel='author'><data:messages.visitProfile/></a>
        </b:includable>
                    </b:widget>
                    <b:widget id='Translate1' locked='false' title='' type='Translate' visible='true'>
                      <b:widget-settings>
                        <b:widget-setting name='displayMode'>VERTICAL</b:widget-setting>
                      </b:widget-settings>
                      <b:includable id='main'>
  <b:include name='widget-title'/>
  <b:include name='content'/>
</b:includable>
                      <b:includable id='content'>
  <div id='google_translate_element'/>
  <script>
    function googleTranslateElementInit() {
      new google.translate.TranslateElement({
        pageLanguage: &#39;<b:eval expr='data:blog.locale.language ?: &quot;auto&quot;'/>&#39;,
        autoDisplay: &#39;true&#39;,
        layout: google.translate.TranslateElement.InlineLayout.<data:layout/>
      }, &#39;google_translate_element&#39;);
    }
  </script>
  <script src='//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit'/>
</b:includable>
                    </b:widget>
                  </b:section>
                </b:if>
              </aside>   <!-- close sidebar-container -->
            </div>  <!-- close centered-bottom -->
          </div>  <!-- close centered -->
        </div>  <!-- close page_body -->
      </b:with>

      <b:section class='footer' id='footer' name='Bawah1' showaddelement='yes' tag='footer'/>
    </div>

    <b:template-script async='true' name='vegeclub' version='1.0.0'/>
    <script type='text/javascript'>
//<![CDATA[
var uri = window.location.toString();
if (uri.indexOf("%3D","%3D") > 0) {
var clean_uri = uri.substring(0, uri.indexOf("%3D"));
window.history.replaceState({}, document.title, clean_uri);
}
var uri = window.location.toString();
if (uri.indexOf("%3D%3D","%3D%3D") > 0) {
var clean_uri = uri.substring(0, uri.indexOf("%3D%3D"));
window.history.replaceState({}, document.title, clean_uri);
}
var uri = window.location.toString();
if (uri.indexOf("&m=1","&m=1") > 0) {
var clean_uri = uri.substring(0, uri.indexOf("&m=1"));
window.history.replaceState({}, document.title, clean_uri);
}
var uri = window.location.toString();
if (uri.indexOf("?m=1","?m=1") > 0) {
var clean_uri = uri.substring(0, uri.indexOf("?m=1"));
window.history.replaceState({}, document.title, clean_uri);
}
//]]>
</script>
</body>
</html>
