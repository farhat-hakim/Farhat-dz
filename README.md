<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:defaultwidgetversion='2' b:layoutsVersion='3' b:responsive='true' b:templateUrl='BLoggerSpot' b:templateVersion='1.5.5' expr:dir='data:blog.languageDirection' expr:lang='data:blog.locale.language' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <b:attr name='xmlns' value=''/>
  <b:attr name='xmlns:b' value=''/>
  <b:attr name='xmlns:expr' value=''/>
  <b:attr name='xmlns:data' value=''/>
    
  <!--[ <head> open ]-->
  &lt;head&gt;
    
  <b:if cond='data:view.isMultipleItems'>
    <b:if cond='data:view.isHomepage'>
      <!--[ Homepage title ]-->
      <title><data:blog.title.escaped/></title>
      <b:elseif cond='data:view.search.query'/>
      <!--[ Search title ]-->
      <title><data:messages.search/>: <data:view.search.query/></title>
      <b:elseif cond='data:view.search.label'/>
      <!--[ Label title ]-->
      <title><data:blog.pageName.escaped/> - <data:blog.title.escaped/></title>
      <b:elseif cond='data:view.isArchive'/>
      <!--[ Archive title ]-->
      <title>Blog archive in: <data:blog.pageName.escaped/></title>
      <b:else/>
      <title>Blog: <data:blog.title.escaped/></title>
    </b:if>
    <b:elseif cond='data:view.isError'/>
    <!--[ Error title ]-->
    <title>Error 404: Not Found</title>
    <b:else/>
    <!--[ SingleItem title ]-->
    <title><data:blog.pageName.escaped/> - <data:blog.title.escaped/></title>
  </b:if>
  
    <!--[ Meta for browser ]-->
    <meta charset='UTF-8'/>
    <meta content='width=device-width, initial-scale=1.0' name='viewport'/>
    <meta content='max-image-preview:large' name='robots'/>
    <meta expr:content='true' name='apple-mobile-web-app-capable'/>
    <link as='font' crossorigin='anonymous' href='https://fonts.gstatic.com/s/dmsans/v14/rP2Fp2ywxg089UriCZa4ET-DNl0.woff2' rel='preload' type='font/woff2'/>
    <link as='font' crossorigin='anonymous' href='https://fonts.gstatic.com/s/dmsans/v14/rP2Fp2ywxg089UriCZa4Hz-D.woff2' rel='preload' type='font/woff2'/>
    <link as='font' crossorigin='anonymous' href='https://fonts.gstatic.com/s/dmsans/v14/rP2Fp2ywxg089UriCZa4ET-DNl0.woff2' rel='preload' type='font/woff2'/>
    <link as='font' crossorigin='anonymous' href='https://fonts.gstatic.com/s/dmsans/v14/rP2Fp2ywxg089UriCZa4Hz-D.woff2' rel='preload' type='font/woff2'/>
    <link as='font' crossorigin='anonymous' href='https://fonts.gstatic.com/s/dmsans/v14/rP2Hp2ywxg089UriCZ2IHSeH.woff2' rel='preload' type='font/woff2'/>
    <link as='font' crossorigin='anonymous' href='https://fonts.gstatic.com/s/dmsans/v14/rP2Hp2ywxg089UriCZOIHQ.woff2' rel='preload' type='font/woff2'/>
    <link as='font' crossorigin='anonymous' href='https://fonts.gstatic.com/s/dmsans/v14/rP2Hp2ywxg089UriCZ2IHSeH.woff2' rel='preload' type='font/woff2'/>
    <link as='font' crossorigin='anonymous' href='https://fonts.gstatic.com/s/dmsans/v14/rP2Hp2ywxg089UriCZOIHQ.woff2' rel='preload' type='font/woff2'/>
    <link href='//ajax.googleapis.com' rel='dns-prefetch'/>
    <link href='//apis.google.com' rel='dns-prefetch'/>
    <link href='//fonts.googleapis.com' rel='dns-prefetch'/>
    <link href='//fonts.gstatic.com' rel='dns-prefetch'/>
    <link href='//www.google-analytics.com' rel='dns-prefetch'/>
    <link href='//www.googletagmanager.com' rel='dns-prefetch'/>
    <link href='//www.googletagservices.com' rel='dns-prefetch'/>
    <link href='//adservice.google.com' rel='dns-prefetch'/>
    <link href='//pagead2.googlesyndication.com' rel='dns-prefetch'/>
    <link href='//tpc.googlesyndication.com' rel='dns-prefetch'/>
    <link href='//bp.blogspot.com' rel='dns-prefetch'/>
    <link href='//1.bp.blogspot.com' rel='dns-prefetch'/>
    <link href='//2.bp.blogspot.com' rel='dns-prefetch'/>
    <link href='//3.bp.blogspot.com' rel='dns-prefetch'/>
    <link href='//4.bp.blogspot.com' rel='dns-prefetch'/>
    <link href='//ajax.microsoft.com' rel='dns-prefetch'/>
    <link href='//ajax.aspnetcdn.com' rel='dns-prefetch'/>
    <link href='//s3.amazonaws.com' rel='dns-prefetch'/>
    <link href='//cdnjs.cloudflare.com' rel='dns-prefetch'/>
    <link href='//code.jquery.com' rel='dns-prefetch'/>
    <link href='//stackpath.bootstrapcdn.com' rel='dns-prefetch'/>
    <link href='//use.fontawesome.com' rel='dns-prefetch'/>
    <link href='//connect.facebook.net' rel='dns-prefetch'/>
    <link href='//platform.twitter.com' rel='dns-prefetch'/>
    <link href='//platform.linkedin.com' rel='dns-prefetch'/>
    <link href='//player.vimeo.com' rel='dns-prefetch'/>
    <link href='//github.githubassets.com' rel='dns-prefetch'/>
    <link href='//referrer.disqus.com' rel='dns-prefetch'/>
    <link href='//c.disquscdn.com' rel='dns-prefetch'/>
    <link href='//0.gravatar.com' rel='dns-prefetch'/>
    <link href='//2.gravatar.com' rel='dns-prefetch'/>
    <link href='//1.gravatar.com' rel='dns-prefetch'/>
    <link href='//stats.buysellads.com' rel='dns-prefetch'/>
    <link href='//s3.buysellads.com' rel='dns-prefetch'/>
    <link href='//ad.doubleclick.net' rel='dns-prefetch'/>
    <link href='//googleads.g.doubleclick.net' rel='dns-prefetch'/>
    <link href='//stats.g.doubleclick.net' rel='dns-prefetch'/>
    <link href='//cm.g.doubleclick.net' rel='dns-prefetch'/>
  
  <!-- Link canonical -->
    <link expr:href='data:blog.url.canonical' rel='canonical'/>

    <b:if cond='!data:view.isError'>
      <!--[ Description and keyword ]-->
      <b:if cond='data:blog.metaDescription'>
      <meta expr:content='data:blog.metaDescription.escaped' name='description'/>
      <b:elseif cond='data:view.isSingleItem'/>
      <meta expr:content='data:post.snippet.escaped snippet { length: 147, links: false, linebreaks: false, ellipsis: false }' name='description'/>
      <b:else/>
      <meta expr:content='data:blog.pageName.escaped ? data:blog.pageName.escaped : data:blog.title.escaped' name='description'/>
    </b:if>
      <meta expr:content='data:blog.pageName.escaped ? data:blog.pageName.escaped : data:blog.title.escaped + &quot;, keyword_1, keyword_2, keyword_3 &quot;' name='keywords'/>
      <b:tag cond='data:view.isPost' expr:href='resizeImage(data:blog.postImageUrl, 0)' name='link' rel='image_src'/>
  
      <!--[ Generator and RRS ]-->
      <meta content='blogger' name='generator'/>
      <link expr:href='data:blog.homepageUrl.canonical + &quot;feeds/posts/default&quot;' expr:title='data:blog.title + &quot; - Atom&quot;' rel='alternate' type='application/atom+xml'/>
      <link expr:href='data:blog.homepageUrl.canonical + &quot;feeds/posts/default?alt=rss&quot;' expr:title='data:blog.title + &quot; - Feed&quot;' rel='alternate' type='application/rss+xml'/>
      <link expr:href='data:blog.homepageUrl.canonical + &quot;feeds/comments/default?alt=rss&quot;' expr:title='data:blog.title + &quot; - Comments Feed&quot;' rel='alternate' type='application/rss+xml'/>
  
      <!--[ Favicon ]-->
      <link expr:href='data:blog.blogspotFaviconUrl' rel='apple-touch-icon' sizes='152x152'/>
      <link expr:href='data:blog.blogspotFaviconUrl' rel='icon' type='image/x-icon'/>
      <link expr:href='data:blog.blogspotFaviconUrl' rel='shortcut icon' type='image/x-icon'/>
    
      <!--[ Open graph and Twitter card ]-->
      <meta content='summary_large_image' name='twitter:card'/>
      <meta expr:content='data:blog.pageName.escaped ? data:blog.pageName.escaped : data:blog.title.escaped' property='og:title'/>
      <meta expr:content='data:blog.pageName.escaped ? data:blog.pageName.escaped : data:blog.title.escaped' name='twitter:title'/>
      <meta expr:content='data:blog.url.canonical' property='og:url'/>
      <meta expr:content='data:blog.url.canonical' name='twitter:url'/>
      <meta expr:content='data:blog.title.escaped' property='og:site_name'/>
      <b:if cond='data:view.isMultipleItems'>
        <meta content='website' property='og:type'/>
        <b:if cond='data:blog.metaDescription'>
          <meta expr:content='data:blog.metaDescription.escaped' property='og:description'/>
          <meta expr:content='data:blog.metaDescription.escaped' name='twitter:description'/>
          <b:else/>
          <meta expr:content='data:blog.pageName.escaped ? data:blog.pageName.escaped : data:blog.title.escaped' property='og:description'/>
          <meta expr:content='data:blog.pageName.escaped ? data:blog.pageName.escaped : data:blog.title.escaped' name='twitter:description'/>
        </b:if>
        <b:else/>
        <meta content='article' property='og:type'/>
        <b:if cond='data:blog.metaDescription'>
          <meta expr:content='data:blog.metaDescription.escaped' property='og:description'/>
          <meta expr:content='data:blog.metaDescription.escaped' name='twitter:description'/>
          <b:else/>
          <meta expr:content='data:post.snippet.escaped snippet { length: 147, links: false, linebreaks: false, ellipsis: false }' property='og:description'/>
          <meta expr:content='data:post.snippet.escaped snippet { length: 147, links: false, linebreaks: false, ellipsis: false }' name='twitter:description'/>
        </b:if>
      </b:if>
      <b:if cond='data:blog.postImageUrl'>
        <meta expr:content='resizeImage(data:blog.postImageUrl, 0)' property='og:image'/>
        <meta expr:content='resizeImage(data:blog.postImageUrl, 0)' name='twitter:image:src'/>
      <b:else/>
        
        <meta content='Add_your_image_url_here' property='og:image'/>
        <meta content='Add_your_image_url_here' name='twitter:image:src'/>
      </b:if>
  </b:if>

    <b:if cond='data:view.isLayoutMode'>
    <!--[ CSS Layout ]-->
<b:template-skin><![CDATA[
body#layout:before{content:  'Ultraspeed v0.1'  ;position:absolute;top:15px;right:15px;font-size:.8rem;font-family:Roboto, sans-serif;color:rgba(0,0,0,0.52)}
body#layout{margin:0 !important;padding:60px 0 0 !important;border:0 !important;text-align:left !important;position:relative}
body#layout .hdrMax {display:flex;margin:0 auto !important;}
body#layout .ftrBdy {display:flex;margin:0 auto !important;}
]]></b:template-skin>
  </b:if>
  
<b:skin version='1.3.3'><![CDATA[
/*
<Group description="Theme Colors">
  <Variable name="white" description="White" type="color" default="#fefefe"  value="#fefefe"/>
  <Variable name="matewhite" description="MateWhite" type="color" default="#ffffff"  value="#ffffff"/>
  <Variable name="black" description="Black" type="color" default="#000000"  value="#000000"/>
  <Variable name="mateblack" description="MateBlack" type="color" default="#171717"  value="#171717"/>
</Group>

<Group description="Post Options">
  <Variable name="postSidebar" description="Post sidebar" type="length" default="1px" min="0px" max="1px" value="1px"/>
  <Variable name="postDescription" description="Post description" type="length" default="1px" min="0px" max="1px" value="1px"/>
  <Variable name="postView" description="Post views" type="length" default="1px" min="0px" max="1px" value="1px"/>
  <Variable name="postReadMin" description="Post read min" type="length" default="1px" min="0px" max="1px" value="1px"/>
</Group>
*/

:root {
  /* Colors */
  --white: $(white);
  --matewhite: $(matewhite);
  --black: $(black);
  --mateblack: $(mateblack);
  --color-0: #f8f9fa;
  --gray-1: #f1f3f5;
  --gray-2: #e9ecef;
  --gray-3: #dee2e6;
  --gray-4: #ced4da;
  --gray-5: #adb5bd;
  --gray-6: #868e96;
  --gray-7: #495057;
  --gray-8: #343a40;
  --gray-9: #212529;

  /* Fonts */
  --font-en: "DM Sans", var(--font-ar), sans-serif;
  --fontT-ar: "IBM Plex Sans Arabic", sans-serif;
  --font-ar: "Noto Sans Arabic", sans-serif;
}
]]></b:skin>
<b:if cond='data:blog.languageDirection == &quot;ltr&quot;'><style>/*<![CDATA[*//* Google Fonts (DM Sans) */@font-face{font-family:'DM Sans';font-style:italic;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/dmsans/v14/rP2Fp2ywxg089UriCZa4ET-DNl0.woff2) format('woff2');unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}@font-face{font-family:'DM Sans';font-style:italic;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/dmsans/v14/rP2Fp2ywxg089UriCZa4Hz-D.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}@font-face{font-family:'DM Sans';font-style:italic;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/dmsans/v14/rP2Fp2ywxg089UriCZa4ET-DNl0.woff2) format('woff2');unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}@font-face{font-family:'DM Sans';font-style:italic;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/dmsans/v14/rP2Fp2ywxg089UriCZa4Hz-D.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}@font-face{font-family:'DM Sans';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/dmsans/v14/rP2Hp2ywxg089UriCZ2IHSeH.woff2) format('woff2');unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}@font-face{font-family:'DM Sans';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/dmsans/v14/rP2Hp2ywxg089UriCZOIHQ.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}@font-face{font-family:'DM Sans';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/dmsans/v14/rP2Hp2ywxg089UriCZ2IHSeH.woff2) format('woff2');unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}@font-face{font-family:'DM Sans';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/dmsans/v14/rP2Hp2ywxg089UriCZOIHQ.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}/*]]>*/</style><b:else/><style>/*<![CDATA[*//* Google Fonts (IBM Plex Sans Arabic, Noto Sans Arabic) */@font-face{font-family:'IBM Plex Sans Arabic';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/ibmplexsansarabic/v12/Qw3NZRtWPQCuHme67tEYUIx3Kh0PHR9N6YOG-eCRXMR5Kw.woff2) format('woff2');unicode-range:U+0600-06FF,U+0750-077F,U+0870-088E,U+0890-0891,U+0898-08E1,U+08E3-08FF,U+200C-200E,U+2010-2011,U+204F,U+2E41,U+FB50-FDFF,U+FE70-FE74,U+FE76-FEFC}@font-face{font-family:'IBM Plex Sans Arabic';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/ibmplexsansarabic/v12/Qw3NZRtWPQCuHme67tEYUIx3Kh0PHR9N6YOG-eCZXMR5Kw.woff2) format('woff2');unicode-range:U+0460-052F,U+1C80-1C88,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F}@font-face{font-family:'IBM Plex Sans Arabic';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/ibmplexsansarabic/v12/Qw3NZRtWPQCuHme67tEYUIx3Kh0PHR9N6YOG-eCaXMR5Kw.woff2) format('woff2');unicode-range:U+0100-02AF,U+0304,U+0308,U+0329,U+1E00-1E9F,U+1EF2-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}@font-face{font-family:'IBM Plex Sans Arabic';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/ibmplexsansarabic/v12/Qw3NZRtWPQCuHme67tEYUIx3Kh0PHR9N6YOG-eCUXMQ.woff2) format('woff2');unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}@font-face{font-family:'Noto Sans Arabic';font-style:normal;font-weight:400;font-stretch:100%;font-display:swap;src:url(https://fonts.gstatic.com/s/notosansarabic/v18/nwpCtLGrOAZMl5nJ_wfgRg3DrWFZWsnVBJ_sS6tlqHHFlj4wv4o.woff2) format('woff2');unicode-range:U+0600-06FF,U+0750-077F,U+0870-088E,U+0890-0891,U+0898-08E1,U+08E3-08FF,U+200C-200E,U+2010-2011,U+204F,U+2E41,U+FB50-FDFF,U+FE70-FE74,U+FE76-FEFC,U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}@font-face{font-family:'Noto Sans Arabic';font-style:normal;font-weight:700;font-stretch:100%;font-display:swap;src:url(https://fonts.gstatic.com/s/notosansarabic/v18/nwpCtLGrOAZMl5nJ_wfgRg3DrWFZWsnVBJ_sS6tlqHHFlj4wv4o.woff2) format('woff2');unicode-range:U+0600-06FF,U+0750-077F,U+0870-088E,U+0890-0891,U+0898-08E1,U+08E3-08FF,U+200C-200E,U+2010-2011,U+204F,U+2E41,U+FB50-FDFF,U+FE70-FE74,U+FE76-FEFC,U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+0304,U+0308,U+0329,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}/*]]>*/</style></b:if> 
<style>/*<![CDATA[*/
/*! normalize.css v8.0.1 | MIT License | github.com/necolas/normalize.css */ /*! normalize.css v8.0.1 | MIT License | github.com/necolas/normalize.css */button,hr,input{overflow:visible}progress,sub,sup{vertical-align:baseline}[type=checkbox],[type=radio],legend{box-sizing:border-box;padding:0}html{line-height:1.15;-webkit-text-size-adjust:100%}body{margin:0}details,main{display:block}h1{font-size:2em;margin:.67em 0}hr{box-sizing:content-box;height:0}code,kbd,pre,samp{font-family:monospace,monospace;font-size:1em}a{background-color:transparent}abbr[title]{border-bottom:none;text-decoration:underline;text-decoration:underline dotted}b,strong{font-weight:bolder}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative}sub{bottom:-.25em}sup{top:-.5em}img{border-style:none}button,input,optgroup,select,textarea{font-family:inherit;font-size:100%;line-height:1.15;margin:0}button,select{text-transform:none}[type=button],[type=reset],[type=submit],button{-webkit-appearance:button}[type=button]::-moz-focus-inner,[type=reset]::-moz-focus-inner,[type=submit]::-moz-focus-inner,button::-moz-focus-inner{border-style:none;padding:0}[type=button]:-moz-focusring,[type=reset]:-moz-focusring,[type=submit]:-moz-focusring,button:-moz-focusring{outline:ButtonText dotted 1px}fieldset{padding:.35em .75em .625em}legend{color:inherit;display:table;max-width:100%;white-space:normal}textarea{overflow:auto}[type=number]::-webkit-inner-spin-button,[type=number]::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}[type=search]::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}[hidden],template{display:none}

/* Main CSS */ *,*::after,*::before{margin:0;padding:0;box-sizing:border-box}html{scroll-behavior:smooth}body{background-color:var(--color-0);font-family:var(--font-en)}body::-webkit-scrollbar{width:0}h1,h2,h3,h4,h5,h6{font-family:var(--font-en),var(--fontT-ar)}a{color:var(--gray-9)}.noUnderline{text-decoration:none}.line{width:24px;height:24px;fill:none;stroke:#141b34;stroke-width:1.5}.hide{display:none}
.mnuHeader li,.search-submit,.hdrSearch,img,.bMPPMSItem {cursor: pointer;}
.bMPPSAds{top:6rem;width:100%;height:auto;display:flex;position:sticky;margin-top:1rem;padding:18px 14px;border-radius:12px;align-items:center;justify-content:center;box-shadow:rgba(149, 157, 165, 0.2) 0px 8px 24px;background-color:var(--matewhite)}

/* Header */ .hdr{top:0;z-index:50;position:sticky;width:100%;background-color:var(--matewhite);box-shadow:rgba(149, 157, 165, 0.2) 0px 8px 24px}.hdrMax{display:flex;align-items:center;margin:0 auto;padding:0 1rem;max-width:1200px;min-height:50px;max-height:80px}.hdrTtl{color:var(--gray-9)}@media screen and (min-width:768px){.hdrMenu{display:none}.hdrMnu{display:block}.mnuClose{display:none}.hdrMnu{display:none;margin:0 1rem;display:flex;align-items:center}.mnuHeader{list-style-type:none;display:flex}.hdrIC::after{content:"";width:24px;height:24px;background-size:20px;padding-right:24px}.mnuHeader .hdrMnuLst{display:inline;display:block;color:var(--gray-8);text-align:center;padding:10px 12px;text-decoration:none;display:flex;align-items:center;border-radius:10px}.mnuHeader .hdrMnuLst .line{width:24px;height:24px;stroke:var(--gray-8)}.mnuHeader .hdrMnuDrpdwn{list-style-type:none;display:none;position:absolute;background-color:var(--matewhite);box-shadow:rgba(149, 157, 165, 0.2) 0px 8px 24px}.mnuHeader li:hover .hdrMnuDrpdwn{display:block}.mnuHeader .hdrMnuDrpdwn .hdrMnuLst{display:block}.mnuHeader .hdrMnuDrpdwn .hdrMnuLst{display:block;color:var(--gray-8);padding:12px 16px;text-decoration:none;text-align:left}.hdrMnuLst:hover{background-color:var(--gray-1)}}@media screen and (max-width:768px){.hdrMnu{display:none}.hdrMnu{display:none;position:fixed;overflow-y:scroll;overflow-x:hidden;top:0;bottom:0;z-index:20;margin:.1rem 0;width:100%;height:100%;background-color:var(--white);transition:inherit}.hdrMnu::-webkit-scrollbar{width:0}.mnuHeader{list-style-type:none;margin-top:.5rem;padding:0 15px 20px;display:flex;flex-direction:column;max-width:90%;margin:0 auto}.mnuClose{min-height:50px;max-height:80px;display:flex;padding:2rem;align-items:center;justify-content:end;width:100%}.mnuClose .line{stroke:var(--gray-6)}.mnuClose span{font-size:14px;color:var(--gray-6)}.mnuHeader .hdrMnuLst{display:inline;display:block;color:var(--gray-8);text-decoration:none;display:flex;align-items:center;font-size:16px;border-radius:10px}.mnuHeader .hdrMnuLst .line{width:24px;height:24px;stroke:var(--gray-8)}.mnuHeader .hdrMnuDrpdwn{list-style-type:none;display:none}.mnuHeader .hdrMnuDrpdwn .hdrMnuLst{display:block;color:var(--gray-8);padding:10px 12px;text-decoration:none}.hdrIC{background-size:20px}.hdrMnuLst{display:block;color:var(--gray-8);padding:10px 12px;text-decoration:none}.hdrMnuLst:hover{background-color:var(--gray-1)}.mnuHeader li:hover .hdrMnuDrpdwn{display:block}.mnuHeader .nxt{border-bottom:1px solid var(--gray-2);padding-bottom:12px;margin-bottom:12px}.mChckBx:checked~.hdrMnu{display:block}}

/* Header: Icons */ .hdrIcns{gap:1rem;display:flex;align-items:center;max-height:24px}.hdrIcns .line{width:24px;height:24px;cursor:pointer}

/* Header: Search */ .hdrSrchR{display:none;position:fixed;overflow-y:hidden;overflow-x:hidden;left:0;top:0;bottom:0;right:0;z-index:20;width:100%;height:100%;background-color:var(--color-0);transition:inherit}.srchChckBx:checked~.hdrSrchR{display:block}.hdrsrchCls{min-height:50px;max-height:80px;display:flex;padding:2rem;align-items:center;justify-content:end}.hdrSrchR .hdrsrchBdy{height:70%;display:flex;margin:auto}.hdrSrchR .hdrsrchBdy .di{margin:auto}.search-form{background:var(--white);box-shadow:rgba(149, 157, 165, 0.2) 0px 8px 24px;max-width:100%;height:55px;overflow:hidden;padding:8px;margin:35px auto 0;justify-content:space-between;display:flex;border-radius:10px}.search-field{border:0;width:100%;flex:1;background-color:transparent;font-size:15px;color:var(--gray-8);padding:0 8px}@media screen and (min-width:768px){.search-form{width:500px}}.search-field:focus{outline:none;border:0}.search-field::placeholder{color:var(--gray-8);opacity:.6;border:0;outline:none}.screen-reader-text{position:absolute;visibility:hidden;text-indent:-9999999px}.search-submit{border:0;display:flex;align-items:center;justify-content:center;padding:0 15px;background-color:transparent}

/* Fixed Post */ .fxdPst{display:grid;padding:0 1rem;margin:2rem auto;justify-content:center;grid-template-areas:"stack"}.fxdPst img{width:100%;height:auto;object-fit:cover;aspect-ratio:16/9}.fxdPst>*{grid-area:stack;border-radius:8px}.fxdPst>.fxdPstDsc{display:flex;flex-direction:column;align-items:start;justify-content:end;padding:1.5rem 2rem;background:linear-gradient(180deg,rgba(33,44,55,0) 0%,rgba(33,44,55,.5) 50%,rgba(33,44,55,1) 100%)}.fxdPstDsc .fxdPstMta{display:flex;font-size:15px;color:var(--gray-1);margin-bottom:.4rem}.fxdPstDsc .fxdPstMta .space{margin:0 5px}.fxdPstDsc .fxdPstTtl{font-size:26px;color:var(--gray-2);text-decoration:none}.fxdPstDsc h2{margin-bottom:.3rem}.fxdPstDsc .fxdPstTtl:hover{text-decoration:underline}.fxdPstDsc .fxdPstTxt{color:var(--gray-3);margin-bottom:1.1rem}@media (max-width:480px){.fxdPstDsc .fxdPstTxt{display:none}.fxdPst>.fxdPstDsc{padding:1rem 1.5rem}}.fxdPstDsc .fxdPstTgs .listTgs{display:flex;gap:.6rem;list-style-type:none}.fxdPstDsc .fxdPstTgs .listTgs .tgs{font-size:14px;color:var(--gray-4);text-decoration:none;padding:4px 8px;border:1px solid var(--gray-6);border-radius:3px}@media (max-width:480px){.fxdPstDsc .fxdPstTgs{display:none}}

/* Blog */ .blgMinConrt{margin:0 auto;padding:0 1rem;max-width:1200px}.blgMinTtl{display:flex;align-items:center;margin:1rem 0}.blgMinTtl .blgManTtl{font-size:20px}.blgMinTtl .blgManTxt{display:flex;align-items:center;font-size:16px;text-decoration:none;color:var(--gray-8)}.blgMinTtl .blgManTxt .line{width:18px;height:18px;stroke:var(--gray-8)}.blgMinTtl .blgManTxt:hover{text-decoration:underline}.blgMrPsts{width:100%;margin:3rem 0;display:flex;align-items:center;justify-content:center}.blgMrPsts .blgMrPstNrs{gap:.5rem;display:flex;align-items:center}.blgMrPsts .blgMrPstNr{height:38px;width:auto;display:flex;align-items:center;justify-content:center;padding:18px;color:var(--color-0);background-color:var(--gray-9);border-radius:10px}.blgMrPsts .blgMrPstNr .line{stroke:var(--color-0)}.blgMrPsts .blgMrPstNxt{text-decoration:none}

/* Blog: Homepage Posts */.blgHmePsts{display:grid;gap:1.5rem;grid-template-columns:repeat(1,minmax(0,1fr))}@media (min-width:480px){.blgHmePsts{grid-template-columns:repeat(2,minmax(0,1fr))}}@media (min-width:1024px){.blgHmePsts{grid-template-columns:repeat(3,minmax(0,1fr))}}.hmePsts{width:100%;height:100%}.hmePsts .hmePstImg img{object-fit:cover;width:100%;height:200px;margin-bottom:.5rem;border-radius:8px}.hmePsts .hmePstMta{display:flex;font-size:15px;color:var(--gray-8);margin-bottom:.4rem}.hmePsts .hmePstMta .space{margin:0 5px}.hmePsts .hmePstTtl{font-size:26px;color:var(--gray-9);text-decoration:none;margin-bottom:.3rem}.hmePsts .hmePstTtl:hover{text-decoration:underline}.hmePsts .hmePstTxt{color:var(--gray-8);margin-bottom:12px}.hmePsts .hmePstTgs .listTgs{display:flex;gap:.6rem;list-style-type:none}.hmePsts .hmePstTgs .listTgs .tgs{font-size:14px;color:var(--gray-8);text-decoration:none;padding:4px 8px;border:1px solid var(--gray-8);border-radius:4px}

/* Footer */ .ftr{margin-top:2rem;background-color:var(--gray-2)}.ftrBdy,.ftrScl{margin:0 auto;max-width:1200px}.ftrScl{padding:1rem 0}.ftrScl .ftrSclLst{gap:1rem;display:flex;flex-wrap:wrap;align-items:center;justify-content:center;list-style-type:none;padding-bottom:1rem;border-bottom:1px solid;border-color:var(--gray-4)}.ftrScl .ftrSclLst .ftrSclLsti{width:48px;height:48px;text-decoration:none;padding:8px;stroke:var(--gray-9);display:flex;align-items:center;justify-content:center;border-radius:10px}.ftrScl .ftrSclLst .ftrSclLsti:hover{background-color:var(--gray-4)}.ftrScl .ftrSclLst .ftrSclLsti .line{width:24px;height:24px}.ftrBdy{gap:2rem;display:flex;justify-content:center;padding:1rem}@media (max-width:768px){.ftrBdy{flex-direction:column}}.ftrBdy h3{font-size:20px;color:var(--gray-8)}.ftrBdy ul{display:flex;flex-direction:column;gap:.25rem;margin-top:.5rem;list-style-type:"> "}.ftrBdy ul:hover>:hover{color:var(--gray-5)}.ftrBdy .ftrBdyW1{width:100%}@media (min-width:768px){.ftrBdy .ftrBdyW1{width:24rem}}.ftrBdy .ftrBdyW1 .ftrBdyW1Txt{font-size:18px;color:var(--gray-7);margin-top:.5rem}.ftrBdy .ftrBdyW1 .ftrBdyW1Txt a{color:var(--gray-7)}.ftrBdy .ftrBdyW2,.ftrBdy .ftrBdyW3{width:auto}.ftrBdy .ftrBdyW2 .ftrBdyW2Lst .ftrBdyW2LstI,.ftrBdy .ftrBdyW3 .ftrBdyW3Lst .ftrBdyW3LstI{font-size:18px;color:var(--gray-7);text-decoration:none}.ftrBtm{display:flex;align-items:center;justify-content:center;max-width:1200px;padding:1rem 0;margin:1rem auto 0;border-top:1px solid;border-color:var(--gray-4)}.ftrBtmTxt{gap:.2rem;display:flex;align-items:center;text-align:center;color:var(--gray-8)}.ftrBtmTxt a{color:var(--gray-9)}/*]]>*/</style>
  
  <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'><style>/*<![CDATA[*//* LTR */@media screen and (min-width:768px){.hdrIC::after{background:url("data:image/svg+xml,%3Csvg class='line' width='24' height='24' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9' stroke='%23141B34' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E%0A") right center no-repeat}.mnuHeader .hdrMnuLst .line{margin-right:.5rem}.mnuHeader .hdrMnuDrpdwn .hdrMnuLst{text-align:left}}@media screen and (max-width:768px){.hdrMnu{left:0}.mnuHeader .hdrMnuLst .line{margin-right:.5rem}.mnuHeader .hdrMnuDrpdwn{padding-left:2rem}.hdrMnuLst,.mnuHeader .hdrMnuDrpdwn .hdrMnuLst{text-align:left}.hdrIC{background:url("data:image/svg+xml,%3Csvg class='line' width='24' height='24' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9' stroke='%23141B34' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E%0A") right center no-repeat}}.blgMinTtl .blgManTxt,.hdrIcns{margin-left:auto}.blgMinTtl .blgManTxt .line{margin-left:.25rem}.bMPPMDescription{padding-left:25px}.bMPPMDescription::before{right:auto;left:10px}.ftrBdy ul{padding-left:.8rem}.ftrBdy .ftrBdyW1,.ftrBdy .ftrBdyW2,.ftrBdy .ftrBdyW3{margin-right:auto}/*]]>*/</style><b:else/><style>/*<![CDATA[*//* RTL */ @media screen and (min-width:768px){.hdrIC::after{background:url("data:image/svg+xml,%3Csvg class='line' width='24' height='24' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9' stroke='%23141B34' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E%0A") left center no-repeat}.mnuHeader .hdrMnuLst .line{margin-left:.5rem}.mnuHeader .hdrMnuDrpdwn .hdrMnuLst{text-align:right}}@media screen and (max-width:768px){.hdrMnu{right:0}.mnuHeader .hdrMnuLst .line{margin-left:.5rem}.mnuHeader .hdrMnuDrpdwn{padding-right:2rem}.hdrMnuLst,.mnuHeader .hdrMnuDrpdwn .hdrMnuLst{text-align:right}.hdrIC{background:url("data:image/svg+xml,%3Csvg class='line' width='24' height='24' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9' stroke='%23141B34' stroke-width='1.5' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E%0A") left center no-repeat}}.blgMinTtl .blgManTxt,.hdrIcns{margin-right:auto}.blgMinTtl .blgManTxt .line{margin-right:.25rem}.bMPPMDescription{padding-right:25px}.bMPPMDescription::before{left:auto;right:10px}.ftrBdy ul{padding-right:.8rem}.ftrBdy .ftrBdyW1,.ftrBdy .ftrBdyW2,.ftrBdy .ftrBdyW3{margin-left:auto}/*]]>*/</style></b:if>
  
  <style>/*<![CDATA[*//* Blog Post */ @media screen and (min-width:768px){.bMPPMMeta,.bMPPMPost{border-bottom:1px solid var(--gray-3)}.bMPPMMeta .bMPPMMAutor,.bMPPMShareText{font-weight:700}.bMPPosts{display:flex;width:100%;gap:1rem;margin-top:1.5rem}.bMPPMain{padding:18px 14px;background-color:var(--matewhite);flex-grow:1;width:calc(100% - (var(280px) + var(40px)));min-width:500px;height:100%;border-radius:12px;box-shadow:rgba(149, 157, 165, 0.2) 0px 8px 24px}.bMPPMLabel{font-size:16px;color:var(--gray-7);text-decoration:none}.bMPPMLabel:hover,.bMPPMProfileCard .bMPPMPCMain .bMPPMPCMTitle a:hover,.bMPPSPPBITitle:hover{text-decoration:underline}.bMPPMProfileCard .bMPPMPCMain .bMPPMPCMTitle a,.bMPPMShare .bMPPMSItem,.bMPPSPPBITitle{text-decoration:none}.bMPPMTitle{font-size:33px;line-height:.8;color:var(--gray-9)}.bMPPMDescription{font-size:16px;display:block;font-style:italic;margin-bottom:15px;position:relative;color:var(--gray-8)}.bMPPMDescription::before{content:"";width:2px;display:block;position:absolute;top:5px;bottom:5px;background-color:var(--gray-4)}.bMPPMMeta{display:flex;align-items:center;font-size:14px;padding-bottom:1.1rem;margin-bottom:1rem;color:var(--gray-9)}.bMPPMMeta .bMPPMMComment,.bMPPMMeta .bMPPMMTime,.bMPPMMeta .bMPPMMViews,.bMPPMTags{color:var(--gray-8)}.bMPPMMeta .bMPPMMComment::before,.bMPPMMeta .bMPPMMTime::before,.bMPPMMeta .bMPPMMViews::before{border:.5px solid var(--gray-7);content:"";height:4px;letter-spacing:0;margin:0 .5rem;opacity:.2;width:0}.bMPPMThumbnail img{width:100%;height:auto;object-fit:cover;aspect-ratio:16/9;margin:0 auto 1rem}.bMPPMPost{padding-bottom:1.5rem}.bMPPMTags{margin:1rem 0;font-size:16px;font-style:italic}.bMPPMTags b{color:var(--gray-9);font-style:normal}.bMPPMShare{gap:.5rem;display:flex;align-items:center;margin-bottom:2rem;margin-top:.2rem}.bMPPMShareText{font-size:15px;color:var(--gray-9)}.bMPPMShare .bMPPMSItem{gap:.2rem;display:flex;align-items:center;justify-content:center;padding:10px;border-radius:6px;background-color:var(--gray-2)}.bMPPMShare .bMPPMSItem:hover,.bMPPSLebels .bMPPSLBody .bMPPSLBItem:hover{background-color:var(--gray-3)}.bMPPMShare .bMPPMSItem svg{width:18px;height:18px;stroke:var(--gray-9)}.bMPPMShare .facebook svg{stroke:#364fc7}.bMPPMShare .facebook{color:#364fc7;background-color:#dbe4ff}.bMPPMProfileCard,.bMPPMShare .x{color:#212529;background-color:var(--gray-2)}.bMPPMShare .x svg{stroke:#212529}.bMPPMShare .whatsapp svg{stroke:#2b8a3e}.bMPPMShare .whatsapp{color:#2b8a3e;background-color:#d3f9d8}.bMPPMShare .pinterest svg{stroke:#c92a2a}.bMPPMShare .pinterest{color:#c92a2a;background-color:#ffe3e3}.bMPPMProfileCard{border-radius:22px;display:flex;align-items:center;width:100%;max-width:500px;height:auto;max-height:150px}.bMPPSLebels,.bMPPSPopularPosts{width:100%;height:auto;padding:18px 14px;border-radius:12px;box-shadow:vrgba(149, 157, 165, 0.2) 0px 8px 24px;background-color:var(--matewhite)}.bMPPMProfileCard .bMPPMPCImage{padding:10px}.bMPPMProfileCard .bMPPMPCImage img{width:80px;height:auto;margin:0 auto;object-fit:cover;aspect-ratio:1/1;border-radius:12px}.bMPPMProfileCard .bMPPMPCMain{margin:auto 0}.bMPPMProfileCard .bMPPMPCMain .bMPPMPCMTitle{display:flex;align-items:center;font-size:20px;color:var(--gray-9);margin-bottom:.5rem}.bMPPMProfileCard .bMPPMPCMain .bMPPMPCMTitle svg{stroke:#364fc7;width:20px;height:20px;margin-left:3px}.bMPPMProfileCard .bMPPMPCMain .bMPPMPCMP{padding-right:.5rem;color:var(--gray-7)}.bMPPSidebar{width:100%;max-width:333px}.bMPPSLebels .bbMPPSLTitle,.bMPPSPopularPosts .bMPPSPPTitle{font-size:20px;color:var(--gray-9)}.bMPPSPopularPosts .bMPPSPPBody{gap:1rem;display:grid;grid-template-columns:repeat(2,minmax(0,1fr));margin-top:1rem}.bMPPSPopularPosts .bMPPSPPBody .bMPPSPPBItem{width:100%}.bMPPSPopularPosts .bMPPSPPBody .bMPPSPPBItem a img{width:100%;height:auto;object-fit:cover;aspect-ratio:16/9;margin:0 auto}.bMPPSPPBITitle{font-size:16px;color:var(--gray-8)!important}.bMPPSLebels{margin-top:1rem}.bMPPSLebels .bMPPSLBody{margin-top:1rem;gap:.3rem;display:flex;flex-wrap:wrap}.bMPPSLebels .bMPPSLBody .bMPPSLBItem{padding:6px;font-size:16px;color:var(--gray-8);background-color:var(--gray-2);border-radius:6px;text-decoration:none}}@media screen and (max-width:768px){.bMPPMMeta,.bMPPMPost{border-bottom:1px solid var(--gray-3)}.bMPPMMeta .bMPPMMAutor,.bMPPMShareText{font-weight:700}.bMPPosts{display:flex;flex-direction:column;width:100%;gap:1rem;margin-top:1.5rem}.bMPPMain{padding:18px 14px;background-color:var(--matewhite);width:100%;height:100%;border-radius:12px;box-shadow:rgba(149, 157, 165, 0.2) 0px 8px 24px}.bMPPMLabel{font-size:16px;color:var(--gray-7);text-decoration:none}.bMPPMLabel:hover{text-decoration:underline;color:var(--gray-9)}.bMPPMProfileCard .bMPPMPCMain .bMPPMPCMTitle a,.bMPPMShare .bMPPMSItem,.bMPPSPPBITitle{text-decoration:none}.bMPPMTitle{font-size:26px;line-height:1;color:var(--gray-9)}.bMPPMDescription{font-size:16px;display:block;font-style:italic;margin-bottom:15px;position:relative;color:var(--gray-8)}.bMPPMDescription::before{content:"";width:2px;display:block;position:absolute;top:5px;bottom:5px;background-color:var(--gray-4)}.bMPPMMeta{gap:.1rem;display:flex;align-items:center;font-size:12px;padding-bottom:1.1rem;margin-bottom:1rem;color:var(--gray-9)}.bMPPMMeta .bMPPMMComment,.bMPPMMeta .bMPPMMTime,.bMPPMMeta .bMPPMMViews,.bMPPMTags{color:var(--gray-8)}.bMPPMMeta .bMPPMMComment::before,.bMPPMMeta .bMPPMMTime::before,.bMPPMMeta .bMPPMMViews::before{border:.5px solid var(--gray-7);content:"";height:5px;letter-spacing:0;margin-left:7px;margin-right:7px;opacity:.2;width:0}.bMPPMThumbnail img{width:100%;height:auto;object-fit:cover;aspect-ratio:16/9;margin:0 auto 1rem}.bMPPMPost{padding-bottom:1.5rem}.bMPPMTags{margin:1rem 0;font-size:16px;font-style:italic}.bMPPMTags b{color:var(--gray-9);font-style:normal}.bMPPMShare{gap:.25rem;display:flex;align-items:center;margin-bottom:2rem}.bMPPMShareText{font-size:15px;color:var(--gray-9)}.bMPPMShare .bMPPMSItem{width:100px;gap:.2rem;font-size:12px;display:flex;align-items:center;justify-content:center;padding:10px;border-radius:6px;background-color:var(--gray-2)}.bMPPMShare .bMPPMSItem:hover,.bMPPSLebels .bMPPSLBody .bMPPSLBItem:hover{background-color:var(--gray-3)}.bMPPMShare .bMPPMSItem svg{width:18px;height:18px;stroke:var(--gray-9)}.bMPPMShare .facebook svg{stroke:#364fc7}.bMPPMShare .facebook{color:#364fc7;background-color:#dbe4ff}.bMPPMProfileCard,.bMPPMShare .x{color:#212529;background-color:var(--gray-2)}.bMPPMShare .x svg{stroke:#212529}.bMPPMShare .whatsapp svg{stroke:#2b8a3e}.bMPPMShare .whatsapp{color:#2b8a3e;background-color:#d3f9d8}.bMPPMShare .pinterest svg{stroke:#c92a2a}.bMPPMShare .pinterest{color:#c92a2a;background-color:#ffe3e3}.bMPPMProfileCard{border-radius:22px;min-height:100px;display:flex;align-items:center;width:100%;max-width:500px;height:auto;max-height:150px}.bMPPSLebels,.bMPPSPopularPosts{width:100%;height:auto;padding:18px 14px;border-radius:12px;box-shadow:rgba(149, 157, 165, 0.2) 0px 8px 24px;background-color:var(--matewhite)}.bMPPMProfileCard .bMPPMPCImage{padding:10px}.bMPPMProfileCard .bMPPMPCImage img{width:80px;height:auto;margin:0 auto;object-fit:cover;aspect-ratio:1/1;border-radius:12px}.bMPPMProfileCard .bMPPMPCMain{margin:auto 0}.bMPPMProfileCard .bMPPMPCMain .bMPPMPCMTitle{display:flex;align-items:center;font-size:20px;color:var(--gray-9);margin-bottom:.5rem}.bMPPMProfileCard .bMPPMPCMain .bMPPMPCMTitle a:hover,.bMPPSPPBITitle:hover{text-decoration:underline}.bMPPMProfileCard .bMPPMPCMain .bMPPMPCMTitle svg{stroke:#364fc7;width:20px;height:20px;margin-left:3px}.bMPPMProfileCard .bMPPMPCMain .bMPPMPCMP{padding-right:.5rem;color:var(--gray-7)}.bMPPSPopularPosts .bMPPSPPBody .bMPPSPPBItem,.bMPPSidebar{width:100%}.bMPPSLebels .bbMPPSLTitle,.bMPPSPopularPosts .bMPPSPPTitle{font-size:20px;color:var(--gray-9)}.bMPPSPopularPosts .bMPPSPPBody{gap:1rem;display:grid;grid-template-columns:repeat(2,minmax(0,1fr));margin-top:1rem;color:var(--gray-8)}.bMPPSPopularPosts .bMPPSPPBody .bMPPSPPBItem a img{width:100%;height:auto;object-fit:cover;aspect-ratio:16/9;margin:0 auto}.bMPPSPPBITitle{font-size:16px;color:var(--gray-8)!important}.bMPPSLebels{margin-top:1rem}.bMPPSLebels .bMPPSLBody{margin-top:1rem;gap:.3rem;display:flex;flex-wrap:wrap}.bMPPSLebels .bMPPSLBody .bMPPSLBItem{padding:6px;font-size:16px;color:var(--gray-8);background-color:var(--gray-2);border-radius:6px;text-decoration:none}.bMPPSAds{display:none}}
.bMPPMPost{word-break:break-word}.bMPPMPost hr{-moz-box-sizing:content-box;box-sizing:content-box;border:none;height:auto;margin:30px 0;display:block;unicode-bidi:isolate;margin-block-start:.5em;margin-block-end:.5em;margin-inline-start:auto;margin-inline-end:auto;overflow:hidden}.bMPPMPost hr:before{content:'\2027 \2027 \2027';display:block;text-align:center;letter-spacing:.5em;font-size:35px;opacity:.5}img{display:block;margin:0 auto;border-radius:8px;aspect-ratio:auto 720 / 480;width:720px;max-width:100%;height:auto;border:0;overflow-clip-margin:content-box;overflow:clip}.bMPPMPost p{color:var(--gray-8);display:block;margin-block-start:1em;margin-block-end:1em;margin-inline-start:0;margin-inline-end:0}.bMPPMPost h1,.bMPPMPost h2,.bMPPMPost h3,.bMPPMPost h4,.bMPPMPost h5,.bMPPMPost h6{font-weight:700;margin:30px 0 15px;display:block;font-size:1.5em;margin-block-start:.83em;margin-block-end:.83em;margin-inline-start:0;margin-inline-end:0;font-weight:700}.bMPPMPost blockquote{border-left:3px solid;border-color:var(--gray-5);margin:15px 0;padding:7.5px;display:block;margin-block-start:1em;margin-block-end:1em;margin-inline-start:40px;margin-inline-end:40px}/*]]>*/</style>
  
  <!--[ timeAgo.js by github.com/Farhat-top/timeAgo.js ]-->
  <script>/*<![CDATA[*/ function TimeAgo(r){let n={second:{ar:"ثانية",de:"Sekunde",en:"second",ku_sorani:"چرک",ku_kurmanji:"\xe7ax"},minute:{ar:"دقيقة",de:"Minute",en:"minute",ku_sorani:"خولك",ku_kurmanji:"xulkek"},hour:{ar:"ساعة",de:"Stunde",en:"hour",ku_sorani:"كاتژم\xear",ku_kurmanji:"katj\xee"},day:{ar:"يوم",de:"Tag",en:"day",ku_sorani:"ڕۆژ",ku_kurmanji:"roj"},month:{ar:"شهر",de:"Monat",en:"month",ku_sorani:"مانگ",ku_kurmanji:"meh"},year:{ar:"عام",de:"Jahr",en:"year",ku_sorani:"ساڵ",ku_kurmanji:"sal"},justNow:{ar:"الآن",de:"soeben",en:"just now",ku_sorani:"نیو",ku_kurmanji:"n\xfb"},ago:{ar:"",de:"vor",en:"ago",ku_sorani:"",ku_kurmanji:"ber"}};this.format=function(e){let o=new Date,u=Math.floor((o-e)/1e3),a=Math.floor(u/60),i=Math.floor(a/60),k=Math.floor(i/24),t=Math.floor(k/30),s=Math.floor(t/12);if(s>0)return s+" "+n.year[r]+" "+n.ago[r];if(t>0)return t+" "+n.month[r]+" "+n.ago[r];if(k>0)return k+" "+n.day[r]+" "+n.ago[r];if(i>0)return i+" "+n.hour[r]+" "+n.ago[r];if(a>0)return a+" "+n.minute[r]+" "+n.ago[r];else if(u>0)return u+" "+n.second[r]+" "+n.ago[r];else return n.justNow[r]}} /*]]>*/</script><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'><script>const timeago = new TimeAgo(&quot;<data:blog.locale.language/>&quot;);</script><b:else/><script>const timeago = new TimeAgo(&quot;<data:blog.locale.language/>&quot;);</script></b:if>
  
  <!--[ Copyright ]-->
  <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
    <script>/*<![CDATA[*/setTimeout(function(){var t='.ftrBtmTxt{padding-left:1.8rem}.ftrBtmTxt::before {position: absolute;content: "";height: 24px;width: 24px;background-image: url("https://raw.githubusercontent.com/Farhat-top/Farhat-top/main/icons/Farhat.png");background-position: center;background-repeat: no-repeat;background-size: cover;border-radius: 3px;margin-left: -1.8rem;box-shadow:rgba(149, 157, 165, 0.2) 0px 8px 24px;cursor: pointer;}',n=document.createElement('style');n.appendChild(document.createTextNode(t)),document.head.appendChild(n),setTimeout(function(){document.querySelector('.ftrBtmTxt').addEventListener('click',function(){window.open('https://Farhat.top/','_blank')})},0)},3e3);/*]]>*/</script>
    <b:else/>
    <script>/*<![CDATA[*/setTimeout(function(){var t='.ftrBtmTxt{padding-right:1.8rem}.ftrBtmTxt::before {position: absolute;content: "";height: 24px;width: 24px;background-image: url("https://raw.githubusercontent.com/Farhat-top/Farhat-top/main/icons/Farhat.png");background-position: center;background-repeat: no-repeat;background-size: cover;border-radius: 3px;margin-right: -1.8rem;box-shadow:rgba(149, 157, 165, 0.2) 0px 8px 24px;cursor: pointer;}',n=document.createElement('style');n.appendChild(document.createTextNode(t)),document.head.appendChild(n),setTimeout(function(){document.querySelector('.ftrBtmTxt').addEventListener('click',function(){window.open('https://Farhat.top/','_blank')})},0)},3e3);/*]]>*/</script>
  </b:if>

  <script>/*<![CDATA[*/
  // Lazyload Image @shinsenter/defer.js@2.6.0
!function(r,i,t){var u,o=/^data-(.+)/,a='IntersectionObserver',s='deferjs',n='load',e='pageshow',f='forEach',c='shift',l=/p/.test(i.readyState),d=[],h=d.slice;function m(e){i.head.appendChild(e)}function v(e,n){h.call(e.attributes)[f](n)}function p(e,n,t,o){return o=(n?i.getElementById(n):o)||i.createElement(e),n&&(o.id=n),t&&(o.onload=t),o}function y(e,n){return h.call((n||i).querySelectorAll(e))}function b(t,e){y('source',t)[f](b),v(t,function(e,n){(n=o.exec(e.name))&&(t[n[1]]=e.value)}),e&&(t.className+=' '+e),n in t&&t[n]()}function I(e){u(function(o){o=y(e||'[type=deferjs]'),function e(n,t){(n=o[c]())&&(n.parentNode.removeChild(n),(t=p(n.nodeName)).text=n.text,v(n,function(e){'type'!=e.name&&t.setAttribute(e.name,e.value)}),t.src&&!t.hasAttribute('async')?(t.onload=t.onerror=e,m(t)):(m(t),e()))}()})}(u=function(e,n){l?t(e,n):d.push(e,n)}).all=I,u.js=function(n,t,e,o){u(function(e){(e=p('SCRIPT',t,o)).src=n,m(e)},e)},u.css=function(n,t,e,o){u(function(e){(e=p('LINK',t,o)).rel='stylesheet',e.href=n,m(e)},e)},u.dom=function(e,n,t,o,i){function c(e){o&&!1===o(e)||b(e,t)}u(function(t){t=a in r&&new r[a](function(e){e[f](function(e,n){e.isIntersecting&&(n=e.target)&&(t.unobserve(n),c(n))})},i),y(e||'[data-src]')[f](function(e){s in e||(e[s]=1,t?t.observe(e):c(e))})},n)},u.reveal=b,r.Defer=u,r.addEventListener('on'+e in r?e:n,function(){for(I();d[0];t(d[c](),d[c]()))l=1})}(this,document,setTimeout);
Defer.dom("img.lazyload",500,"loaded",null,{rootMargin:"1px"});
  /*]]>*/</script>
  
  <!--[ Highlight.js v11.9.0 ]-->
  <b:if cond='data:view.isPost'><style>pre code.hljs{display:block;overflow-x:auto;padding:1em}code.hljs{padding:3px 5px}.hljs{color:#abb2bf;background:#282c34}.hljs-comment,.hljs-quote{color:#5c6370;font-style:italic}.hljs-doctag,.hljs-formula,.hljs-keyword{color:#c678dd}.hljs-deletion,.hljs-name,.hljs-section,.hljs-selector-tag,.hljs-subst{color:#e06c75}.hljs-literal{color:#56b6c2}.hljs-addition,.hljs-attribute,.hljs-meta .hljs-string,.hljs-regexp,.hljs-string{color:#98c379}.hljs-attr,.hljs-number,.hljs-selector-attr,.hljs-selector-class,.hljs-selector-pseudo,.hljs-template-variable,.hljs-type,.hljs-variable{color:#d19a66}.hljs-bullet,.hljs-link,.hljs-meta,.hljs-selector-id,.hljs-symbol,.hljs-title{color:#61aeee}.hljs-built_in,.hljs-class .hljs-title,.hljs-title.class_{color:#e6c07b}.hljs-emphasis{font-style:italic}.hljs-strong{font-weight:700}.hljs-link{text-decoration:underline}</style><script>/*<![CDATA[*/
/*!
  Highlight.js v11.9.0 (git: f47103d4f1)
  (c) 2006-2023 undefined and other contributors
  License: BSD-3-Clause
 */
var hljs=function(){"use strict";function e(n){return n instanceof Map?n.clear=n.delete=n.set=()=>{throw Error("map is read-only")}:n instanceof Set&&(n.add=n.clear=n.delete=()=>{throw Error("set is read-only")}),Object.freeze(n),Object.getOwnPropertyNames(n).forEach(t=>{let a=n[t],i=typeof a;"object"!==i&&"function"!==i||Object.isFrozen(a)||e(a)}),n}class n{constructor(e){void 0===e.data&&(e.data={}),this.data=e.data,this.isMatchIgnored=!1}ignoreMatch(){this.isMatchIgnored=!0}}function t(e){return e.replace(/&/g,"&amp;").replace(/</g,"&lt;").replace(/>/g,"&gt;").replace(/"/g,"&quot;").replace(/'/g,"&#x27;")}function a(e,...n){let t=Object.create(null);for(let a in e)t[a]=e[a];return n.forEach(e=>{for(let n in e)t[n]=e[n]}),t}let i=e=>!!e.scope;class r{constructor(e,n){this.buffer="",this.classPrefix=n.classPrefix,e.walk(this)}addText(e){this.buffer+=t(e)}openNode(e){if(!i(e))return;let n=((e,{prefix:n})=>{if(e.startsWith("language:"))return e.replace("language:","language-");if(e.includes(".")){let t=e.split(".");return[`${n}${t.shift()}`,...t.map((e,n)=>`${e}${"_".repeat(n+1)}`)].join(" ")}return`${n}${e}`})(e.scope,{prefix:this.classPrefix});this.span(n)}closeNode(e){i(e)&&(this.buffer+="</span>")}value(){return this.buffer}span(e){this.buffer+=`<span class="${e}">`}}let s=(e={})=>{let n={children:[]};return Object.assign(n,e),n};class o{constructor(){this.rootNode=s(),this.stack=[this.rootNode]}get top(){return this.stack[this.stack.length-1]}get root(){return this.rootNode}add(e){this.top.children.push(e)}openNode(e){let n=s({scope:e});this.add(n),this.stack.push(n)}closeNode(){if(this.stack.length>1)return this.stack.pop()}closeAllNodes(){for(;this.closeNode(););}toJSON(){return JSON.stringify(this.rootNode,null,4)}walk(e){return this.constructor._walk(e,this.rootNode)}static _walk(e,n){return"string"==typeof n?e.addText(n):n.children&&(e.openNode(n),n.children.forEach(n=>this._walk(e,n)),e.closeNode(n)),e}static _collapse(e){"string"!=typeof e&&e.children&&(e.children.every(e=>"string"==typeof e)?e.children=[e.children.join("")]:e.children.forEach(e=>{o._collapse(e)}))}}class l extends o{constructor(e){super(),this.options=e}addText(e){""!==e&&this.add(e)}startScope(e){this.openNode(e)}endScope(){this.closeNode()}__addSublanguage(e,n){let t=e.root;n&&(t.scope="language:"+n),this.add(t)}toHTML(){return new r(this,this.options).value()}finalize(){return this.closeAllNodes(),!0}}function c(e){return e?"string"==typeof e?e:e.source:null}function d(e){return b("(?=",e,")")}function g(e){return b("(?:",e,")*")}function u(e){return b("(?:",e,")?")}function b(...e){return e.map(e=>c(e)).join("")}function m(...e){let n=(e=>{let n=e[e.length-1];return"object"==typeof n&&n.constructor===Object?(e.splice(e.length-1,1),n):{}})(e);return"("+(n.capture?"":"?:")+e.map(e=>c(e)).join("|")+")"}function p(e){return RegExp(e.toString()+"|").exec("").length-1}let h=/\[(?:[^\\\]]|\\.)*\]|\(\??|\\([1-9][0-9]*)|\\./;function f(e,{joinWith:n}){let t=0;return e.map(e=>{t+=1;let n=t,a=c(e),i="";for(;a.length>0;){let r=h.exec(a);if(!r){i+=a;break}i+=a.substring(0,r.index),a=a.substring(r.index+r[0].length),"\\"===r[0][0]&&r[1]?i+="\\"+(Number(r[1])+n):(i+=r[0],"("===r[0]&&t++)}return i}).map(e=>`(${e})`).join(n)}let E="[a-zA-Z]\\w*",$="[a-zA-Z_]\\w*",y="\\b\\d+(\\.\\d+)?",N="(-?)(\\b0[xX][a-fA-F0-9]+|(\\b\\d+(\\.\\d*)?|\\.\\d+)([eE][-+]?\\d+)?)",w="\\b(0b[01]+)",v={begin:"\\\\[\\s\\S]",relevance:0},k=(e,n,t={})=>{let i=a({scope:"comment",begin:e,end:n,contains:[]},t);i.contains.push({scope:"doctag",begin:"[ ]*(?=(TODO|FIXME|NOTE|BUG|OPTIMIZE|HACK|XXX):)",end:/(TODO|FIXME|NOTE|BUG|OPTIMIZE|HACK|XXX):/,excludeBegin:!0,relevance:0});let r=m("I","a","is","so","us","to","at","if","in","it","on",/[A-Za-z]+['](d|ve|re|ll|t|s|n)/,/[A-Za-z]+[-][a-z]+/,/[A-Za-z][a-z]{2,}/);return i.contains.push({begin:b(/[ ]+/,"(",r,/[.]?[:]?([.][ ]|[ ])/,"){3}")}),i},x=k("//","$"),M=k("/\\*","\\*/"),O=k("#","$");var S=Object.freeze({__proto__:null,APOS_STRING_MODE:{scope:"string",begin:"'",end:"'",illegal:"\\n",contains:[v]},BACKSLASH_ESCAPE:v,BINARY_NUMBER_MODE:{scope:"number",begin:w,relevance:0},BINARY_NUMBER_RE:w,COMMENT:k,C_BLOCK_COMMENT_MODE:M,C_LINE_COMMENT_MODE:x,C_NUMBER_MODE:{scope:"number",begin:N,relevance:0},C_NUMBER_RE:N,END_SAME_AS_BEGIN:e=>Object.assign(e,{"on:begin"(e,n){n.data._beginMatch=e[1]},"on:end"(e,n){n.data._beginMatch!==e[1]&&n.ignoreMatch()}}),HASH_COMMENT_MODE:O,IDENT_RE:E,MATCH_NOTHING_RE:/\b\B/,METHOD_GUARD:{begin:"\\.\\s*"+$,relevance:0},NUMBER_MODE:{scope:"number",begin:y,relevance:0},NUMBER_RE:y,PHRASAL_WORDS_MODE:{begin:/\b(a|an|the|are|I'm|isn't|don't|doesn't|won't|but|just|should|pretty|simply|enough|gonna|going|wtf|so|such|will|you|your|they|like|more)\b/},QUOTE_STRING_MODE:{scope:"string",begin:'"',end:'"',illegal:"\\n",contains:[v]},REGEXP_MODE:{scope:"regexp",begin:/\/(?=[^/\n]*\/)/,end:/\/[gimuy]*/,contains:[v,{begin:/\[/,end:/\]/,relevance:0,contains:[v]}]},RE_STARTERS_RE:"!|!=|!==|%|%=|&|&&|&=|\\*|\\*=|\\+|\\+=|,|-|-=|/=|/|:|;|<<|<<=|<=|<|===|==|=|>>>=|>>=|>=|>>>|>>|>|\\?|\\[|\\{|\\(|\\^|\\^=|\\||\\|=|\\|\\||~",SHEBANG(e={}){let n=/^#![ ]*\//;return e.binary&&(e.begin=b(n,/.*\b/,e.binary,/\b.*/)),a({scope:"meta",begin:n,end:/$/,relevance:0,"on:begin"(e,n){0!==e.index&&n.ignoreMatch()}},e)},TITLE_MODE:{scope:"title",begin:E,relevance:0},UNDERSCORE_IDENT_RE:$,UNDERSCORE_TITLE_MODE:{scope:"title",begin:$,relevance:0}});function A(e,n){"."===e.input[e.index-1]&&n.ignoreMatch()}function C(e,n){void 0!==e.className&&(e.scope=e.className,delete e.className)}function T(e,n){n&&e.beginKeywords&&(e.begin="\\b("+e.beginKeywords.split(" ").join("|")+")(?!\\.)(?=\\b|\\s)",e.__beforeBegin=A,e.keywords=e.keywords||e.beginKeywords,delete e.beginKeywords,void 0===e.relevance&&(e.relevance=0))}function R(e,n){Array.isArray(e.illegal)&&(e.illegal=m(...e.illegal))}function D(e,n){if(e.match){if(e.begin||e.end)throw Error("begin & end are not supported with match");e.begin=e.match,delete e.match}}function I(e,n){void 0===e.relevance&&(e.relevance=1)}let L=(e,n)=>{if(!e.beforeMatch)return;if(e.starts)throw Error("beforeMatch cannot be used with starts");let t=Object.assign({},e);Object.keys(e).forEach(n=>{delete e[n]}),e.keywords=t.keywords,e.begin=b(t.beforeMatch,d(t.begin)),e.starts={relevance:0,contains:[Object.assign(t,{endsParent:!0})]},e.relevance=0,delete t.beforeMatch},B=["of","and","for","in","not","or","if","then","parent","list","value"],_={},z=e=>{console.error(e)},F=(e,...n)=>{console.log("WARN: "+e,...n)},U=(e,n)=>{_[`${e}/${n}`]||(console.log(`Deprecated as of ${e}. ${n}`),_[`${e}/${n}`]=!0)},P=Error();function j(e,n,{key:t}){let a=0,i=e[t],r={},s={};for(let o=1;o<=n.length;o++)s[o+a]=i[o],r[o+a]=!0,a+=p(n[o-1]);e[t]=s,e[t]._emit=r,e[t]._multi=!0}function K(e){var n;(n=e).scope&&"object"==typeof n.scope&&null!==n.scope&&(n.beginScope=n.scope,delete n.scope),"string"==typeof e.beginScope&&(e.beginScope={_wrap:e.beginScope}),"string"==typeof e.endScope&&(e.endScope={_wrap:e.endScope}),(e=>{if(Array.isArray(e.begin)){if(e.skip||e.excludeBegin||e.returnBegin)throw z("skip, excludeBegin, returnBegin not compatible with beginScope: {}"),P;if("object"!=typeof e.beginScope||null===e.beginScope)throw z("beginScope must be object"),P;j(e,e.begin,{key:"beginScope"}),e.begin=f(e.begin,{joinWith:""})}})(e),(e=>{if(Array.isArray(e.end)){if(e.skip||e.excludeEnd||e.returnEnd)throw z("skip, excludeEnd, returnEnd not compatible with endScope: {}"),P;if("object"!=typeof e.endScope||null===e.endScope)throw z("endScope must be object"),P;j(e,e.end,{key:"endScope"}),e.end=f(e.end,{joinWith:""})}})(e)}class H extends Error{constructor(e,n){super(e),this.name="HTMLInjectionError",this.html=n}}let q=t,G=a,Z=Symbol("nomatch"),W=t=>{let i=Object.create(null),r=Object.create(null),s=[],o=!0,h="Could not find the language '{}', did you forget to load/include a language module?",E={disableAutodetect:!0,name:"Plain text",contains:[]},$={ignoreUnescapedHTML:!1,throwUnescapedHTML:!1,noHighlightRe:/^(no-?highlight)$/i,languageDetectRe:/\blang(?:uage)?-([\w-]+)\b/i,classPrefix:"hljs-",cssSelector:"pre code",languages:null,__emitter:l};function y(e){return $.noHighlightRe.test(e)}function N(e,n,t){let a="",i="";"object"==typeof n?(a=e,t=n.ignoreIllegals,i=n.language):(U("10.7.0","highlight(lang, code, ...args) has been deprecated."),U("10.7.0","Please use highlight(code, options) instead.\nhttps://github.com/highlightjs/highlight.js/issues/2277"),i=e,a=n),void 0===t&&(t=!0);let r={code:a,language:i};P("before:highlight",r);let s=r.result?r.result:w(r.language,r.code,t);return s.code=r.code,P("after:highlight",s),s}function w(e,t,r,s){let l=Object.create(null);function d(){var e;if(!S.keywords)return void _.addText(F);let n=0;S.keywordPatternRe.lastIndex=0;let t=S.keywordPatternRe.exec(F),a="";for(;t;){a+=F.substring(n,t.index);let i=k.case_insensitive?t[0].toLowerCase():t[0],r=(e=i,S.keywords[e]);if(r){let[s,o]=r;if(_.addText(a),a="",l[i]=(l[i]||0)+1,l[i]<=7&&(U+=o),s.startsWith("_"))a+=t[0];else{let c=k.classNameAliases[s]||s;u(t[0],c)}}else a+=t[0];n=S.keywordPatternRe.lastIndex,t=S.keywordPatternRe.exec(F)}a+=F.substring(n),_.addText(a)}function g(){null!=S.subLanguage?(()=>{if(""===F)return;let e=null;if("string"==typeof S.subLanguage){if(!i[S.subLanguage])return void _.addText(F);e=w(S.subLanguage,F,!0,A[S.subLanguage]),A[S.subLanguage]=e._top}else e=v(F,S.subLanguage.length?S.subLanguage:null);S.relevance>0&&(U+=e.relevance),_.__addSublanguage(e._emitter,e.language)})():d(),F=""}function u(e,n){""!==e&&(_.startScope(n),_.addText(e),_.endScope())}function b(e,n){let t=1,a=n.length-1;for(;t<=a;){if(!e._emit[t]){t++;continue}let i=k.classNameAliases[e[t]]||e[t],r=n[t];i?u(r,i):(F=r,d(),F=""),t++}}function m(e,n){return e.scope&&"string"==typeof e.scope&&_.openNode(k.classNameAliases[e.scope]||e.scope),e.beginScope&&(e.beginScope._wrap?(u(F,k.classNameAliases[e.beginScope._wrap]||e.beginScope._wrap),F=""):e.beginScope._multi&&(b(e.beginScope,n),F="")),S=Object.create(e,{parent:{value:S}})}function E(e){return 0===S.matcher.regexIndex?(F+=e[0],1):(H=!0,0)}let y={};function N(a,i){let s=i&&i[0];if(F+=a,null==s)return g(),0;if("begin"===y.type&&"end"===i.type&&y.index===i.index&&""===s){if(F+=t.slice(i.index,i.index+1),!o){let l=Error(`0 width match regex (${e})`);throw l.languageName=e,l.badRule=y.rule,l}return 1}if(y=i,"begin"===i.type)return(e=>{let t=e[0],a=e.rule,i=new n(a),r=[a.__beforeBegin,a["on:begin"]];for(let s of r)if(s&&(s(e,i),i.isMatchIgnored))return E(t);return a.skip?F+=t:(a.excludeBegin&&(F+=t),g(),a.returnBegin||a.excludeBegin||(F=t)),m(a,e),a.returnBegin?0:t.length})(i);if("illegal"===i.type&&!r){let c=Error('Illegal lexeme "'+s+'" for mode "'+(S.scope||"<unnamed>")+'"');throw c.mode=S,c}if("end"===i.type){let d=function e(a){let i=a[0],r=t.substring(a.index),s=function e(t,a,i){let r=((e,n)=>{let t=e&&e.exec(n);return t&&0===t.index})(t.endRe,i);if(r){if(t["on:end"]){let s=new n(t);t["on:end"](a,s),s.isMatchIgnored&&(r=!1)}if(r){for(;t.endsParent&&t.parent;)t=t.parent;return t}}if(t.endsWithParent)return e(t.parent,a,i)}(S,a,r);if(!s)return Z;let o=S;S.endScope&&S.endScope._wrap?(g(),u(i,S.endScope._wrap)):S.endScope&&S.endScope._multi?(g(),b(S.endScope,a)):o.skip?F+=i:(o.returnEnd||o.excludeEnd||(F+=i),g(),o.excludeEnd&&(F=i));do S.scope&&_.closeNode(),S.skip||S.subLanguage||(U+=S.relevance),S=S.parent;while(S!==s.parent);return s.starts&&m(s.starts,a),o.returnEnd?0:i.length}(i);if(d!==Z)return d}if("illegal"===i.type&&""===s)return 1;if(j>1e5&&j>3*i.index)throw Error("potential infinite loop, way more iterations than matches");return F+=s,s.length}let k=O(e);if(!k)throw z(h.replace("{}",e)),Error('Unknown language: "'+e+'"');let x=function e(n){function t(e,t){return RegExp(c(e),"m"+(n.case_insensitive?"i":"")+(n.unicodeRegex?"u":"")+(t?"g":""))}class i{constructor(){this.matchIndexes={},this.regexes=[],this.matchAt=1,this.position=0}addRule(e,n){n.position=this.position++,this.matchIndexes[this.matchAt]=n,this.regexes.push([n,e]),this.matchAt+=p(e)+1}compile(){0===this.regexes.length&&(this.exec=()=>null);let e=this.regexes.map(e=>e[1]);this.matcherRe=t(f(e,{joinWith:"|"}),!0),this.lastIndex=0}exec(e){this.matcherRe.lastIndex=this.lastIndex;let n=this.matcherRe.exec(e);if(!n)return null;let t=n.findIndex((e,n)=>n>0&&void 0!==e),a=this.matchIndexes[t];return n.splice(0,t),Object.assign(n,a)}}class r{constructor(){this.rules=[],this.multiRegexes=[],this.count=0,this.lastIndex=0,this.regexIndex=0}getMatcher(e){if(this.multiRegexes[e])return this.multiRegexes[e];let n=new i;return this.rules.slice(e).forEach(([e,t])=>n.addRule(e,t)),n.compile(),this.multiRegexes[e]=n,n}resumingScanAtSamePosition(){return 0!==this.regexIndex}considerAll(){this.regexIndex=0}addRule(e,n){this.rules.push([e,n]),"begin"===n.type&&this.count++}exec(e){let n=this.getMatcher(this.regexIndex);n.lastIndex=this.lastIndex;let t=n.exec(e);if(this.resumingScanAtSamePosition()){if(t&&t.index===this.lastIndex);else{let a=this.getMatcher(0);a.lastIndex=this.lastIndex+1,t=a.exec(e)}}return t&&(this.regexIndex+=t.position+1,this.regexIndex===this.count&&this.considerAll()),t}}if(n.compilerExtensions||(n.compilerExtensions=[]),n.contains&&n.contains.includes("self"))throw Error("ERR: contains `self` is not supported at the top-level of a language.  See documentation.");return n.classNameAliases=a(n.classNameAliases||{}),function e(i,s){let o=i;if(i.isCompiled)return o;[C,D,K,L].forEach(e=>e(i,s)),n.compilerExtensions.forEach(e=>e(i,s)),i.__beforeBegin=null,[T,R,I].forEach(e=>e(i,s)),i.isCompiled=!0;let l=null;return"object"==typeof i.keywords&&i.keywords.$pattern&&(i.keywords=Object.assign({},i.keywords),l=i.keywords.$pattern,delete i.keywords.$pattern),l=l||/\w+/,i.keywords&&(i.keywords=function e(n,t,a="keyword"){let i=Object.create(null);return"string"==typeof n?r(a,n.split(" ")):Array.isArray(n)?r(a,n):Object.keys(n).forEach(a=>{Object.assign(i,e(n[a],t,a))}),i;function r(e,n){t&&(n=n.map(e=>e.toLowerCase())),n.forEach(n=>{var t,a,r;let s=n.split("|");i[s[0]]=[e,(t=s[0],a=s[1],a?Number(a):(r=t,B.includes(r.toLowerCase()))?0:1)]})}}(i.keywords,n.case_insensitive)),o.keywordPatternRe=t(l,!0),s&&(i.begin||(i.begin=/\B|\b/),o.beginRe=t(o.begin),i.end||i.endsWithParent||(i.end=/\B|\b/),i.end&&(o.endRe=t(o.end)),o.terminatorEnd=c(o.end)||"",i.endsWithParent&&s.terminatorEnd&&(o.terminatorEnd+=(i.end?"|":"")+s.terminatorEnd)),i.illegal&&(o.illegalRe=t(i.illegal)),i.contains||(i.contains=[]),i.contains=[].concat(...i.contains.map(e=>{var n;return(n="self"===e?i:e).variants&&!n.cachedVariants&&(n.cachedVariants=n.variants.map(e=>a(n,{variants:null},e))),n.cachedVariants?n.cachedVariants:!function e(n){return!!n&&(n.endsWithParent||e(n.starts))}(n)?Object.isFrozen(n)?a(n):n:a(n,{starts:n.starts?a(n.starts):null})})),i.contains.forEach(n=>{e(n,o)}),i.starts&&e(i.starts,s),o.matcher=(e=>{let n=new r;return e.contains.forEach(e=>n.addRule(e.begin,{rule:e,type:"begin"})),e.terminatorEnd&&n.addRule(e.terminatorEnd,{type:"end"}),e.illegal&&n.addRule(e.illegal,{type:"illegal"}),n})(o),o}(n)}(k),M="",S=s||x,A={},_=new $.__emitter($);(()=>{let e=[];for(let n=S;n!==k;n=n.parent)n.scope&&e.unshift(n.scope);e.forEach(e=>_.openNode(e))})();let F="",U=0,P=0,j=0,H=!1;try{if(k.__emitTokens)k.__emitTokens(t,_);else{for(S.matcher.considerAll();;){j++,H?H=!1:S.matcher.considerAll(),S.matcher.lastIndex=P;let G=S.matcher.exec(t);if(!G)break;let W=N(t.substring(P,G.index),G);P=G.index+W}N(t.substring(P))}return _.finalize(),M=_.toHTML(),{language:e,value:M,relevance:U,illegal:!1,_emitter:_,_top:S}}catch(Q){if(Q.message&&Q.message.includes("Illegal"))return{language:e,value:q(t),illegal:!0,relevance:0,_illegalBy:{message:Q.message,index:P,context:t.slice(P-100,P+100),mode:Q.mode,resultSoFar:M},_emitter:_};if(o)return{language:e,value:q(t),illegal:!1,relevance:0,errorRaised:Q,_emitter:_,_top:S};throw Q}}function v(e,n){n=n||$.languages||Object.keys(i);let t=(e=>{let n={value:q(e),illegal:!1,relevance:0,_top:E,_emitter:new $.__emitter($)};return n._emitter.addText(e),n})(e),a=n.filter(O).filter(_).map(n=>w(n,e,!1));a.unshift(t);let r=a.sort((e,n)=>{if(e.relevance!==n.relevance)return n.relevance-e.relevance;if(e.language&&n.language){if(O(e.language).supersetOf===n.language)return 1;if(O(n.language).supersetOf===e.language)return -1}return 0}),[s,o]=r,l=s;return l.secondBest=o,l}function k(e){let n=null,t=(e=>{let n=e.className+" ";n+=e.parentNode?e.parentNode.className:"";let t=$.languageDetectRe.exec(n);if(t){let a=O(t[1]);return a||(F(h.replace("{}",t[1])),F("Falling back to no-highlight mode for this block.",e)),a?t[1]:"no-highlight"}return n.split(/\s+/).find(e=>y(e)||O(e))})(e);if(y(t))return;if(P("before:highlightElement",{el:e,language:t}),e.dataset.highlighted)return void console.log("Element previously highlighted. To highlight again, first unset `dataset.highlighted`.",e);if(e.children.length>0&&($.ignoreUnescapedHTML||(console.warn("One of your code blocks includes unescaped HTML. This is a potentially serious security risk."),console.warn("https://github.com/highlightjs/highlight.js/wiki/security"),console.warn("The element with unescaped HTML:"),console.warn(e)),$.throwUnescapedHTML))throw new H("One of your code blocks includes unescaped HTML.",e.innerHTML);n=e;let a=n.textContent,i=t?N(a,{language:t,ignoreIllegals:!0}):v(a);e.innerHTML=i.value,e.dataset.highlighted="yes",((e,n,t)=>{let a=n&&r[n]||t;e.classList.add("hljs"),e.classList.add("language-"+a)})(e,t,i.language),e.result={language:i.language,re:i.relevance,relevance:i.relevance},i.secondBest&&(e.secondBest={language:i.secondBest.language,relevance:i.secondBest.relevance}),P("after:highlightElement",{el:e,result:i,text:a})}let x=!1;function M(){"loading"!==document.readyState?document.querySelectorAll($.cssSelector).forEach(k):x=!0}function O(e){return i[e=(e||"").toLowerCase()]||i[r[e]]}function A(e,{languageName:n}){"string"==typeof e&&(e=[e]),e.forEach(e=>{r[e.toLowerCase()]=n})}function _(e){let n=O(e);return n&&!n.disableAutodetect}function P(e,n){let t=e;s.forEach(e=>{e[t]&&e[t](n)})}for(let j in"undefined"!=typeof window&&window.addEventListener&&window.addEventListener("DOMContentLoaded",()=>{x&&M()},!1),Object.assign(t,{highlight:N,highlightAuto:v,highlightAll:M,highlightElement:k,highlightBlock:e=>(U("10.7.0","highlightBlock will be removed entirely in v12.0"),U("10.7.0","Please use highlightElement now."),k(e)),configure(e){$=G($,e)},initHighlighting(){M(),U("10.6.0","initHighlighting() deprecated.  Use highlightAll() now.")},initHighlightingOnLoad(){M(),U("10.6.0","initHighlightingOnLoad() deprecated.  Use highlightAll() now.")},registerLanguage(e,n){let a=null;try{a=n(t)}catch(r){if(z("Language definition for '{}' could not be registered.".replace("{}",e)),!o)throw r;z(r),a=E}a.name||(a.name=e),i[e]=a,a.rawDefinition=n.bind(null,t),a.aliases&&A(a.aliases,{languageName:e})},unregisterLanguage(e){for(let n of(delete i[e],Object.keys(r)))r[n]===e&&delete r[n]},listLanguages:()=>Object.keys(i),getLanguage:O,registerAliases:A,autoDetection:_,inherit:G,addPlugin(e){var n;(n=e)["before:highlightBlock"]&&!n["before:highlightElement"]&&(n["before:highlightElement"]=e=>{n["before:highlightBlock"](Object.assign({block:e.el},e))}),n["after:highlightBlock"]&&!n["after:highlightElement"]&&(n["after:highlightElement"]=e=>{n["after:highlightBlock"](Object.assign({block:e.el},e))}),s.push(e)},removePlugin(e){let n=s.indexOf(e);-1!==n&&s.splice(n,1)}}),t.debugMode=()=>{o=!1},t.safeMode=()=>{o=!0},t.versionString="11.9.0",t.regex={concat:b,lookahead:d,either:m,optional:u,anyNumberOfTimes:g},S)"object"==typeof S[j]&&e(S[j]);return Object.assign(t,S),t},Q=W({});Q.newInstance=()=>W({});let X=e=>({IMPORTANT:{scope:"meta",begin:"!important"},BLOCK_COMMENT:e.C_BLOCK_COMMENT_MODE,HEXCOLOR:{scope:"number",begin:/#(([0-9a-fA-F]{3,4})|(([0-9a-fA-F]{2}){3,4}))\b/},FUNCTION_DISPATCH:{className:"built_in",begin:/[\w-]+(?=\()/},ATTRIBUTE_SELECTOR_MODE:{scope:"selector-attr",begin:/\[/,end:/\]/,illegal:"$",contains:[e.APOS_STRING_MODE,e.QUOTE_STRING_MODE]},CSS_NUMBER_MODE:{scope:"number",begin:e.NUMBER_RE+"(%|em|ex|ch|rem|vw|vh|vmin|vmax|cm|mm|in|pt|pc|px|deg|grad|rad|turn|s|ms|Hz|kHz|dpi|dpcm|dppx)?",relevance:0},CSS_VARIABLE:{className:"attr",begin:/--[A-Za-z_][A-Za-z0-9_-]*/}}),V=["a","abbr","address","article","aside","audio","b","blockquote","body","button","canvas","caption","cite","code","dd","del","details","dfn","div","dl","dt","em","fieldset","figcaption","figure","footer","form","h1","h2","h3","h4","h5","h6","header","hgroup","html","i","iframe","img","input","ins","kbd","label","legend","li","main","mark","menu","nav","object","ol","p","q","quote","samp","section","span","strong","summary","sup","table","tbody","td","textarea","tfoot","th","thead","time","tr","ul","var","video"],J=["any-hover","any-pointer","aspect-ratio","color","color-gamut","color-index","device-aspect-ratio","device-height","device-width","display-mode","forced-colors","grid","height","hover","inverted-colors","monochrome","orientation","overflow-block","overflow-inline","pointer","prefers-color-scheme","prefers-contrast","prefers-reduced-motion","prefers-reduced-transparency","resolution","scan","scripting","update","width","min-width","max-width","min-height","max-height"],Y=["active","any-link","blank","checked","current","default","defined","dir","disabled","drop","empty","enabled","first","first-child","first-of-type","fullscreen","future","focus","focus-visible","focus-within","has","host","host-context","hover","indeterminate","in-range","invalid","is","lang","last-child","last-of-type","left","link","local-link","not","nth-child","nth-col","nth-last-child","nth-last-col","nth-last-of-type","nth-of-type","only-child","only-of-type","optional","out-of-range","past","placeholder-shown","read-only","read-write","required","right","root","scope","target","target-within","user-invalid","valid","visited","where"],ee=["after","backdrop","before","cue","cue-region","first-letter","first-line","grammar-error","marker","part","placeholder","selection","slotted","spelling-error"],en=["align-content","align-items","align-self","all","animation","animation-delay","animation-direction","animation-duration","animation-fill-mode","animation-iteration-count","animation-name","animation-play-state","animation-timing-function","backface-visibility","background","background-attachment","background-blend-mode","background-clip","background-color","background-image","background-origin","background-position","background-repeat","background-size","block-size","border","border-block","border-block-color","border-block-end","border-block-end-color","border-block-end-style","border-block-end-width","border-block-start","border-block-start-color","border-block-start-style","border-block-start-width","border-block-style","border-block-width","border-bottom","border-bottom-color","border-bottom-left-radius","border-bottom-right-radius","border-bottom-style","border-bottom-width","border-collapse","border-color","border-image","border-image-outset","border-image-repeat","border-image-slice","border-image-source","border-image-width","border-inline","border-inline-color","border-inline-end","border-inline-end-color","border-inline-end-style","border-inline-end-width","border-inline-start","border-inline-start-color","border-inline-start-style","border-inline-start-width","border-inline-style","border-inline-width","border-left","border-left-color","border-left-style","border-left-width","border-radius","border-right","border-right-color","border-right-style","border-right-width","border-spacing","border-style","border-top","border-top-color","border-top-left-radius","border-top-right-radius","border-top-style","border-top-width","border-width","bottom","box-decoration-break","box-shadow","box-sizing","break-after","break-before","break-inside","caption-side","caret-color","clear","clip","clip-path","clip-rule","color","column-count","column-fill","column-gap","column-rule","column-rule-color","column-rule-style","column-rule-width","column-span","column-width","columns","contain","content","content-visibility","counter-increment","counter-reset","cue","cue-after","cue-before","cursor","direction","display","empty-cells","filter","flex","flex-basis","flex-direction","flex-flow","flex-grow","flex-shrink","flex-wrap","float","flow","font","font-display","font-family","font-feature-settings","font-kerning","font-language-override","font-size","font-size-adjust","font-smoothing","font-stretch","font-style","font-synthesis","font-variant","font-variant-caps","font-variant-east-asian","font-variant-ligatures","font-variant-numeric","font-variant-position","font-variation-settings","font-weight","gap","glyph-orientation-vertical","grid","grid-area","grid-auto-columns","grid-auto-flow","grid-auto-rows","grid-column","grid-column-end","grid-column-start","grid-gap","grid-row","grid-row-end","grid-row-start","grid-template","grid-template-areas","grid-template-columns","grid-template-rows","hanging-punctuation","height","hyphens","icon","image-orientation","image-rendering","image-resolution","ime-mode","inline-size","isolation","justify-content","left","letter-spacing","line-break","line-height","list-style","list-style-image","list-style-position","list-style-type","margin","margin-block","margin-block-end","margin-block-start","margin-bottom","margin-inline","margin-inline-end","margin-inline-start","margin-left","margin-right","margin-top","marks","mask","mask-border","mask-border-mode","mask-border-outset","mask-border-repeat","mask-border-slice","mask-border-source","mask-border-width","mask-clip","mask-composite","mask-image","mask-mode","mask-origin","mask-position","mask-repeat","mask-size","mask-type","max-block-size","max-height","max-inline-size","max-width","min-block-size","min-height","min-inline-size","min-width","mix-blend-mode","nav-down","nav-index","nav-left","nav-right","nav-up","none","normal","object-fit","object-position","opacity","order","orphans","outline","outline-color","outline-offset","outline-style","outline-width","overflow","overflow-wrap","overflow-x","overflow-y","padding","padding-block","padding-block-end","padding-block-start","padding-bottom","padding-inline","padding-inline-end","padding-inline-start","padding-left","padding-right","padding-top","page-break-after","page-break-before","page-break-inside","pause","pause-after","pause-before","perspective","perspective-origin","pointer-events","position","quotes","resize","rest","rest-after","rest-before","right","row-gap","scroll-margin","scroll-margin-block","scroll-margin-block-end","scroll-margin-block-start","scroll-margin-bottom","scroll-margin-inline","scroll-margin-inline-end","scroll-margin-inline-start","scroll-margin-left","scroll-margin-right","scroll-margin-top","scroll-padding","scroll-padding-block","scroll-padding-block-end","scroll-padding-block-start","scroll-padding-bottom","scroll-padding-inline","scroll-padding-inline-end","scroll-padding-inline-start","scroll-padding-left","scroll-padding-right","scroll-padding-top","scroll-snap-align","scroll-snap-stop","scroll-snap-type","scrollbar-color","scrollbar-gutter","scrollbar-width","shape-image-threshold","shape-margin","shape-outside","speak","speak-as","src","tab-size","table-layout","text-align","text-align-all","text-align-last","text-combine-upright","text-decoration","text-decoration-color","text-decoration-line","text-decoration-style","text-emphasis","text-emphasis-color","text-emphasis-position","text-emphasis-style","text-indent","text-justify","text-orientation","text-overflow","text-rendering","text-shadow","text-transform","text-underline-position","top","transform","transform-box","transform-origin","transform-style","transition","transition-delay","transition-duration","transition-property","transition-timing-function","unicode-bidi","vertical-align","visibility","voice-balance","voice-duration","voice-family","voice-pitch","voice-range","voice-rate","voice-stress","voice-volume","white-space","widows","width","will-change","word-break","word-spacing","word-wrap","writing-mode","z-index"].reverse(),et=Y.concat(ee);var ea="[0-9](_*[0-9])*",ei=`\\.(${ea})`,er="[0-9a-fA-F](_*[0-9a-fA-F])*",es={className:"number",variants:[{begin:`(\\b(${ea})((${ei})|\\.)?|(${ei}))[eE][+-]?(${ea})[fFdD]?\\b`},{begin:`\\b(${ea})((${ei})[fFdD]?\\b|\\.([fFdD]\\b)?)`},{begin:`(${ei})[fFdD]?\\b`},{begin:`\\b(${ea})[fFdD]\\b`},{begin:`\\b0[xX]((${er})\\.?|(${er})?\\.(${er}))[pP][+-]?(${ea})[fFdD]?\\b`},{begin:"\\b(0|[1-9](_*[0-9])*)[lL]?\\b"},{begin:`\\b0[xX](${er})[lL]?\\b`},{begin:"\\b0(_*[0-7])*[lL]?\\b"},{begin:"\\b0[bB][01](_*[01])*[lL]?\\b"}],relevance:0};let eo="[A-Za-z$_][0-9A-Za-z$_]*",el=["as","in","of","if","for","while","finally","var","new","function","do","return","void","else","break","catch","instanceof","with","throw","case","default","try","switch","continue","typeof","delete","let","yield","const","class","debugger","async","await","static","import","from","export","extends"],ec=["true","false","null","undefined","NaN","Infinity"],ed=["Object","Function","Boolean","Symbol","Math","Date","Number","BigInt","String","RegExp","Array","Float32Array","Float64Array","Int8Array","Uint8Array","Uint8ClampedArray","Int16Array","Int32Array","Uint16Array","Uint32Array","BigInt64Array","BigUint64Array","Set","Map","WeakSet","WeakMap","ArrayBuffer","SharedArrayBuffer","Atomics","DataView","JSON","Promise","Generator","GeneratorFunction","AsyncFunction","Reflect","Proxy","Intl","WebAssembly"],eg=["Error","EvalError","InternalError","RangeError","ReferenceError","SyntaxError","TypeError","URIError"],eu=["setInterval","setTimeout","clearInterval","clearTimeout","require","exports","eval","isFinite","isNaN","parseFloat","parseInt","decodeURI","decodeURIComponent","encodeURI","encodeURIComponent","escape","unescape"],eb=["arguments","this","super","console","window","document","localStorage","sessionStorage","module","global"],em=[].concat(eu,ed,eg);function ep(e){var n;let t=e.regex,a=eo,i={begin:/<[A-Za-z0-9\\._:-]+/,end:/\/[A-Za-z0-9\\._:-]+>|\/>/,isTrulyOpeningTag(e,n){let t=e[0].length+e.index,a=e.input[t];if("<"===a||","===a)return void n.ignoreMatch();let i;">"===a&&(((e,{after:n})=>{let t="</"+e[0].slice(1);return -1!==e.input.indexOf(t,n)})(e,{after:t})||n.ignoreMatch());let r=e.input.substring(t);((i=r.match(/^\s*=/))||(i=r.match(/^\s+extends\s+/))&&0===i.index)&&n.ignoreMatch()}},r={$pattern:eo,keyword:el,literal:ec,built_in:em,"variable.language":eb},s="[0-9](_?[0-9])*",o=`\\.(${s})`,l="0|[1-9](_?[0-9])*|0[0-7]*[89][0-9]*",c={className:"number",variants:[{begin:`(\\b(${l})((${o})|\\.)?|(${o}))[eE][+-]?(${s})\\b`},{begin:`\\b(${l})\\b((${o})\\b|\\.)?|(${o})\\b`},{begin:"\\b(0|[1-9](_?[0-9])*)n\\b"},{begin:"\\b0[xX][0-9a-fA-F](_?[0-9a-fA-F])*n?\\b"},{begin:"\\b0[bB][0-1](_?[0-1])*n?\\b"},{begin:"\\b0[oO][0-7](_?[0-7])*n?\\b"},{begin:"\\b0[0-7]+n?\\b"}],relevance:0},d={className:"subst",begin:"\\$\\{",end:"\\}",keywords:r,contains:[]},g={begin:"html`",end:"",starts:{end:"`",returnEnd:!1,contains:[e.BACKSLASH_ESCAPE,d],subLanguage:"xml"}},u={begin:"css`",end:"",starts:{end:"`",returnEnd:!1,contains:[e.BACKSLASH_ESCAPE,d],subLanguage:"css"}},b={begin:"gql`",end:"",starts:{end:"`",returnEnd:!1,contains:[e.BACKSLASH_ESCAPE,d],subLanguage:"graphql"}},m={className:"string",begin:"`",end:"`",contains:[e.BACKSLASH_ESCAPE,d]},p={className:"comment",variants:[e.COMMENT(/\/\*\*(?!\/)/,"\\*/",{relevance:0,contains:[{begin:"(?=@[A-Za-z]+)",relevance:0,contains:[{className:"doctag",begin:"@[A-Za-z]+"},{className:"type",begin:"\\{",end:"\\}",excludeEnd:!0,excludeBegin:!0,relevance:0},{className:"variable",begin:a+"(?=\\s*(-)|$)",endsParent:!0,relevance:0},{begin:/(?=[^\n])\s/,relevance:0}]}]}),e.C_BLOCK_COMMENT_MODE,e.C_LINE_COMMENT_MODE]},h=[e.APOS_STRING_MODE,e.QUOTE_STRING_MODE,g,u,b,m,{match:/\$\d+/},c];d.contains=h.concat({begin:/\{/,end:/\}/,keywords:r,contains:["self"].concat(h)});let f=[].concat(p,d.contains),E=f.concat([{begin:/\(/,end:/\)/,keywords:r,contains:["self"].concat(f)}]),$={className:"params",begin:/\(/,end:/\)/,excludeBegin:!0,excludeEnd:!0,keywords:r,contains:E},y={variants:[{match:[/class/,/\s+/,a,/\s+/,/extends/,/\s+/,t.concat(a,"(",t.concat(/\./,a),")*")],scope:{1:"keyword",3:"title.class",5:"keyword",7:"title.class.inherited"}},{match:[/class/,/\s+/,a],scope:{1:"keyword",3:"title.class"}}]},N={relevance:0,match:t.either(/\bJSON/,/\b[A-Z][a-z]+([A-Z][a-z]*|\d)*/,/\b[A-Z]{2,}([A-Z][a-z]+|\d)+([A-Z][a-z]*)*/,/\b[A-Z]{2,}[a-z]+([A-Z][a-z]+|\d)*([A-Z][a-z]*)*/),className:"title.class",keywords:{_:[...ed,...eg]}},w={match:t.concat(/\b/,(n=[...eu,"super","import"],t.concat("(?!",n.join("|"),")")),a,t.lookahead(/\(/)),className:"title.function",relevance:0},v={begin:t.concat(/\./,t.lookahead(t.concat(a,/(?![0-9A-Za-z$_(])/))),end:a,excludeBegin:!0,keywords:"prototype",className:"property",relevance:0},k="(\\([^()]*(\\([^()]*(\\([^()]*\\)[^()]*)*\\)[^()]*)*\\)|"+e.UNDERSCORE_IDENT_RE+")\\s*=>",x={match:[/const|var|let/,/\s+/,a,/\s*/,/=\s*/,/(async\s*)?/,t.lookahead(k)],keywords:"async",className:{1:"keyword",3:"title.function"},contains:[$]};return{name:"JavaScript",aliases:["js","jsx","mjs","cjs"],keywords:r,exports:{PARAMS_CONTAINS:E,CLASS_REFERENCE:N},illegal:/#(?![$_A-z])/,contains:[e.SHEBANG({label:"shebang",binary:"node",relevance:5}),{label:"use_strict",className:"meta",relevance:10,begin:/^\s*['"]use (strict|asm)['"]/},e.APOS_STRING_MODE,e.QUOTE_STRING_MODE,g,u,b,m,p,{match:/\$\d+/},c,N,{className:"attr",begin:a+t.lookahead(":"),relevance:0},x,{begin:"("+e.RE_STARTERS_RE+"|\\b(case|return|throw)\\b)\\s*",keywords:"return throw case",relevance:0,contains:[p,e.REGEXP_MODE,{className:"function",begin:k,returnBegin:!0,end:"\\s*=>",contains:[{className:"params",variants:[{begin:e.UNDERSCORE_IDENT_RE,relevance:0},{className:null,begin:/\(\s*\)/,skip:!0},{begin:/\(/,end:/\)/,excludeBegin:!0,excludeEnd:!0,keywords:r,contains:E}]}]},{begin:/,/,relevance:0},{match:/\s+/,relevance:0},{variants:[{begin:"<>",end:"</>"},{match:/<[A-Za-z0-9\\._:-]+\s*\/>/},{begin:i.begin,"on:begin":i.isTrulyOpeningTag,end:i.end}],subLanguage:"xml",contains:[{begin:i.begin,end:i.end,skip:!0,contains:["self"]}]}]},{variants:[{match:[/function/,/\s+/,a,/(?=\s*\()/]},{match:[/function/,/\s*(?=\()/]}],className:{1:"keyword",3:"title.function"},label:"func.def",contains:[$],illegal:/%/},{beginKeywords:"while if switch catch for"},{begin:"\\b(?!function)"+e.UNDERSCORE_IDENT_RE+"\\([^()]*(\\([^()]*(\\([^()]*\\)[^()]*)*\\)[^()]*)*\\)\\s*\\{",returnBegin:!0,label:"func.def",contains:[$,e.inherit(e.TITLE_MODE,{begin:a,className:"title.function"})]},{match:/\.\.\./,relevance:0},v,{match:"\\$"+a,relevance:0},{match:[/\bconstructor(?=\s*\()/],className:{1:"title.function"},contains:[$]},w,{relevance:0,match:/\b[A-Z][A-Z_0-9]+\b/,className:"variable.constant"},y,{match:[/get|set/,/\s+/,a,/(?=\()/],className:{1:"keyword",3:"title.function"},contains:[{begin:/\(\)/},$]},{match:/\$[(.]/}]}}let e8=e=>b(/\b/,e,/\w$/.test(e)?/\b/:/\B/),eh=["Protocol","Type"].map(e8),ef=["init","self"].map(e8),eE=["Any","Self"],e$=["actor","any","associatedtype","async","await",/as\?/,/as!/,"as","borrowing","break","case","catch","class","consume","consuming","continue","convenience","copy","default","defer","deinit","didSet","distributed","do","dynamic","each","else","enum","extension","fallthrough",/fileprivate\(set\)/,"fileprivate","final","for","func","get","guard","if","import","indirect","infix",/init\?/,/init!/,"inout",/internal\(set\)/,"internal","in","is","isolated","nonisolated","lazy","let","macro","mutating","nonmutating",/open\(set\)/,"open","operator","optional","override","postfix","precedencegroup","prefix",/private\(set\)/,"private","protocol",/public\(set\)/,"public","repeat","required","rethrows","return","set","some","static","struct","subscript","super","switch","throws","throw",/try\?/,/try!/,"try","typealias",/unowned\(safe\)/,/unowned\(unsafe\)/,"unowned","var","weak","where","while","willSet"],ey=["false","nil","true"],eN=["assignment","associativity","higherThan","left","lowerThan","none","right"],ew=["#colorLiteral","#column","#dsohandle","#else","#elseif","#endif","#error","#file","#fileID","#fileLiteral","#filePath","#function","#if","#imageLiteral","#keyPath","#line","#selector","#sourceLocation","#warning"],ev=["abs","all","any","assert","assertionFailure","debugPrint","dump","fatalError","getVaList","isKnownUniquelyReferenced","max","min","numericCast","pointwiseMax","pointwiseMin","precondition","preconditionFailure","print","readLine","repeatElement","sequence","stride","swap","swift_unboxFromSwiftValueWithType","transcode","type","unsafeBitCast","unsafeDowncast","withExtendedLifetime","withUnsafeMutablePointer","withUnsafePointer","withVaList","withoutActuallyEscaping","zip"],ek=m(/[/=\-+!*%<>&|^~?]/,/[\u00A1-\u00A7]/,/[\u00A9\u00AB]/,/[\u00AC\u00AE]/,/[\u00B0\u00B1]/,/[\u00B6\u00BB\u00BF\u00D7\u00F7]/,/[\u2016-\u2017]/,/[\u2020-\u2027]/,/[\u2030-\u203E]/,/[\u2041-\u2053]/,/[\u2055-\u205E]/,/[\u2190-\u23FF]/,/[\u2500-\u2775]/,/[\u2794-\u2BFF]/,/[\u2E00-\u2E7F]/,/[\u3001-\u3003]/,/[\u3008-\u3020]/,/[\u3030]/),ex=m(ek,/[\u0300-\u036F]/,/[\u1DC0-\u1DFF]/,/[\u20D0-\u20FF]/,/[\uFE00-\uFE0F]/,/[\uFE20-\uFE2F]/),eM=b(ek,ex,"*"),eO=m(/[a-zA-Z_]/,/[\u00A8\u00AA\u00AD\u00AF\u00B2-\u00B5\u00B7-\u00BA]/,/[\u00BC-\u00BE\u00C0-\u00D6\u00D8-\u00F6\u00F8-\u00FF]/,/[\u0100-\u02FF\u0370-\u167F\u1681-\u180D\u180F-\u1DBF]/,/[\u1E00-\u1FFF]/,/[\u200B-\u200D\u202A-\u202E\u203F-\u2040\u2054\u2060-\u206F]/,/[\u2070-\u20CF\u2100-\u218F\u2460-\u24FF\u2776-\u2793]/,/[\u2C00-\u2DFF\u2E80-\u2FFF]/,/[\u3004-\u3007\u3021-\u302F\u3031-\u303F\u3040-\uD7FF]/,/[\uF900-\uFD3D\uFD40-\uFDCF\uFDF0-\uFE1F\uFE30-\uFE44]/,/[\uFE47-\uFEFE\uFF00-\uFFFD]/),eS=m(eO,/\d/,/[\u0300-\u036F\u1DC0-\u1DFF\u20D0-\u20FF\uFE20-\uFE2F]/),eA=b(eO,eS,"*"),eC=b(/[A-Z]/,eS,"*"),eT=["attached","autoclosure",b(/convention\(/,m("swift","block","c"),/\)/),"discardableResult","dynamicCallable","dynamicMemberLookup","escaping","freestanding","frozen","GKInspectable","IBAction","IBDesignable","IBInspectable","IBOutlet","IBSegueAction","inlinable","main","nonobjc","NSApplicationMain","NSCopying","NSManaged",b(/objc\(/,eA,/\)/),"objc","objcMembers","propertyWrapper","requires_stored_property_inits","resultBuilder","Sendable","testable","UIApplicationMain","unchecked","unknown","usableFromInline","warn_unqualified_access"],eR=["iOS","iOSApplicationExtension","macOS","macOSApplicationExtension","macCatalyst","macCatalystApplicationExtension","watchOS","watchOSApplicationExtension","tvOS","tvOSApplicationExtension","swift"];var eD=Object.freeze({__proto__:null,grmr_bash(e){let n=e.regex,t={};Object.assign(t,{className:"variable",variants:[{begin:n.concat(/\$[\w\d#@][\w\d_]*/,"(?![\\w\\d])(?![$])")},{begin:/\$\{/,end:/\}/,contains:["self",{begin:/:-/,contains:[t]}]}]});let a={className:"subst",begin:/\$\(/,end:/\)/,contains:[e.BACKSLASH_ESCAPE]},i={begin:/<<-?\s*(?=\w+)/,starts:{contains:[e.END_SAME_AS_BEGIN({begin:/(\w+)/,end:/(\w+)/,className:"string"})]}},r={className:"string",begin:/"/,end:/"/,contains:[e.BACKSLASH_ESCAPE,t,a]};a.contains.push(r);let s={begin:/\$?\(\(/,end:/\)\)/,contains:[{begin:/\d+#[0-9a-f]+/,className:"number"},e.NUMBER_MODE,t]},o=e.SHEBANG({binary:"(fish|bash|zsh|sh|csh|ksh|tcsh|dash|scsh)",relevance:10}),l={className:"function",begin:/\w[\w\d_]*\s*\(\s*\)\s*\{/,returnBegin:!0,contains:[e.inherit(e.TITLE_MODE,{begin:/\w[\w\d_]*/})],relevance:0};return{name:"Bash",aliases:["sh"],keywords:{$pattern:/\b[a-z][a-z0-9._-]+\b/,keyword:["if","then","else","elif","fi","for","while","until","in","do","done","case","esac","function","select"],literal:["true","false"],built_in:["break","cd","continue","eval","exec","exit","export","getopts","hash","pwd","readonly","return","shift","test","times","trap","umask","unset","alias","bind","builtin","caller","command","declare","echo","enable","help","let","local","logout","mapfile","printf","read","readarray","source","type","typeset","ulimit","unalias","set","shopt","autoload","bg","bindkey","bye","cap","chdir","clone","comparguments","compcall","compctl","compdescribe","compfiles","compgroups","compquote","comptags","comptry","compvalues","dirs","disable","disown","echotc","echoti","emulate","fc","fg","float","functions","getcap","getln","history","integer","jobs","kill","limit","log","noglob","popd","print","pushd","pushln","rehash","sched","setcap","setopt","stat","suspend","ttyctl","unfunction","unhash","unlimit","unsetopt","vared","wait","whence","where","which","zcompile","zformat","zftp","zle","zmodload","zparseopts","zprof","zpty","zregexparse","zsocket","zstyle","ztcp","chcon","chgrp","chown","chmod","cp","dd","df","dir","dircolors","ln","ls","mkdir","mkfifo","mknod","mktemp","mv","realpath","rm","rmdir","shred","sync","touch","truncate","vdir","b2sum","base32","base64","cat","cksum","comm","csplit","cut","expand","fmt","fold","head","join","md5sum","nl","numfmt","od","paste","ptx","pr","sha1sum","sha224sum","sha256sum","sha384sum","sha512sum","shuf","sort","split","sum","tac","tail","tr","tsort","unexpand","uniq","wc","arch","basename","chroot","date","dirname","du","echo","env","expr","factor","groups","hostid","id","link","logname","nice","nohup","nproc","pathchk","pinky","printenv","printf","pwd","readlink","runcon","seq","sleep","stat","stdbuf","stty","tee","test","timeout","tty","uname","unlink","uptime","users","who","whoami","yes"]},contains:[o,e.SHEBANG(),l,s,e.HASH_COMMENT_MODE,i,{match:/(\/[a-z._-]+)+/},r,{match:/\\"/},{className:"string",begin:/'/,end:/'/},{match:/\\'/},t]}},grmr_c(e){let n=e.regex,t=e.COMMENT("//","$",{contains:[{begin:/\\\n/}]}),a="decltype\\(auto\\)",i="[a-zA-Z_]\\w*::",r="("+a+"|"+n.optional(i)+"[a-zA-Z_]\\w*"+n.optional("<[^<>]+>")+")",s={className:"type",variants:[{begin:"\\b[a-z\\d_]*_t\\b"},{match:/\batomic_[a-z]{3,6}\b/}]},o={className:"string",variants:[{begin:'(u8?|U|L)?"',end:'"',illegal:"\\n",contains:[e.BACKSLASH_ESCAPE]},{begin:"(u8?|U|L)?'(\\\\(x[0-9A-Fa-f]{2}|u[0-9A-Fa-f]{4,8}|[0-7]{3}|\\S)|.)",end:"'",illegal:"."},e.END_SAME_AS_BEGIN({begin:/(?:u8?|U|L)?R"([^()\\ ]{0,16})\(/,end:/\)([^()\\ ]{0,16})"/})]},l={className:"number",variants:[{begin:"\\b(0b[01']+)"},{begin:"(-?)\\b([\\d']+(\\.[\\d']*)?|\\.[\\d']+)((ll|LL|l|L)(u|U)?|(u|U)(ll|LL|l|L)?|f|F|b|B)"},{begin:"(-?)(\\b0[xX][a-fA-F0-9']+|(\\b[\\d']+(\\.[\\d']*)?|\\.[\\d']+)([eE][-+]?[\\d']+)?)"}],relevance:0},c={className:"meta",begin:/#\s*[a-z]+\b/,end:/$/,keywords:{keyword:"if else elif endif define undef warning error line pragma _Pragma ifdef ifndef include"},contains:[{begin:/\\\n/,relevance:0},e.inherit(o,{className:"string"}),{className:"string",begin:/<.*?>/},t,e.C_BLOCK_COMMENT_MODE]},d={className:"title",begin:n.optional(i)+e.IDENT_RE,relevance:0},g=n.optional(i)+e.IDENT_RE+"\\s*\\(",u={keyword:["asm","auto","break","case","continue","default","do","else","enum","extern","for","fortran","goto","if","inline","register","restrict","return","sizeof","struct","switch","typedef","union","volatile","while","_Alignas","_Alignof","_Atomic","_Generic","_Noreturn","_Static_assert","_Thread_local","alignas","alignof","noreturn","static_assert","thread_local","_Pragma"],type:["float","double","signed","unsigned","int","short","long","char","void","_Bool","_Complex","_Imaginary","_Decimal32","_Decimal64","_Decimal128","const","static","complex","bool","imaginary"],literal:"true false NULL",built_in:"std string wstring cin cout cerr clog stdin stdout stderr stringstream istringstream ostringstream auto_ptr deque list queue stack vector map set pair bitset multiset multimap unordered_set unordered_map unordered_multiset unordered_multimap priority_queue make_pair array shared_ptr abort terminate abs acos asin atan2 atan calloc ceil cosh cos exit exp fabs floor fmod fprintf fputs free frexp fscanf future isalnum isalpha iscntrl isdigit isgraph islower isprint ispunct isspace isupper isxdigit tolower toupper labs ldexp log10 log malloc realloc memchr memcmp memcpy memset modf pow printf putchar puts scanf sinh sin snprintf sprintf sqrt sscanf strcat strchr strcmp strcpy strcspn strlen strncat strncmp strncpy strpbrk strrchr strspn strstr tanh tan vfprintf vprintf vsprintf endl initializer_list unique_ptr"},b=[c,s,t,e.C_BLOCK_COMMENT_MODE,l,o],m={variants:[{begin:/=/,end:/;/},{begin:/\(/,end:/\)/},{beginKeywords:"new throw return else",end:/;/}],keywords:u,contains:b.concat([{begin:/\(/,end:/\)/,keywords:u,contains:b.concat(["self"]),relevance:0}]),relevance:0},p={begin:"("+r+"[\\*&\\s]+)+"+g,returnBegin:!0,end:/[{;=]/,excludeEnd:!0,keywords:u,illegal:/[^\w\s\*&:<>.]/,contains:[{begin:a,keywords:u,relevance:0},{begin:g,returnBegin:!0,contains:[e.inherit(d,{className:"title.function"})],relevance:0},{relevance:0,match:/,/},{className:"params",begin:/\(/,end:/\)/,keywords:u,relevance:0,contains:[t,e.C_BLOCK_COMMENT_MODE,o,l,s,{begin:/\(/,end:/\)/,keywords:u,relevance:0,contains:["self",t,e.C_BLOCK_COMMENT_MODE,o,l,s]}]},s,t,e.C_BLOCK_COMMENT_MODE,c]};return{name:"C",aliases:["h"],keywords:u,disableAutodetect:!0,illegal:"</",contains:[].concat(m,p,b,[c,{begin:e.IDENT_RE+"::",keywords:u},{className:"class",beginKeywords:"enum class struct union",end:/[{;:<>=]/,contains:[{beginKeywords:"final class struct"},e.TITLE_MODE]}]),exports:{preprocessor:c,strings:o,keywords:u}}},grmr_cpp(e){let n=e.regex,t=e.COMMENT("//","$",{contains:[{begin:/\\\n/}]}),a="decltype\\(auto\\)",i="[a-zA-Z_]\\w*::",r="(?!struct)("+a+"|"+n.optional(i)+"[a-zA-Z_]\\w*"+n.optional("<[^<>]+>")+")",s={className:"type",begin:"\\b[a-z\\d_]*_t\\b"},o={className:"string",variants:[{begin:'(u8?|U|L)?"',end:'"',illegal:"\\n",contains:[e.BACKSLASH_ESCAPE]},{begin:"(u8?|U|L)?'(\\\\(x[0-9A-Fa-f]{2}|u[0-9A-Fa-f]{4,8}|[0-7]{3}|\\S)|.)",end:"'",illegal:"."},e.END_SAME_AS_BEGIN({begin:/(?:u8?|U|L)?R"([^()\\ ]{0,16})\(/,end:/\)([^()\\ ]{0,16})"/})]},l={className:"number",variants:[{begin:"\\b(0b[01']+)"},{begin:"(-?)\\b([\\d']+(\\.[\\d']*)?|\\.[\\d']+)((ll|LL|l|L)(u|U)?|(u|U)(ll|LL|l|L)?|f|F|b|B)"},{begin:"(-?)(\\b0[xX][a-fA-F0-9']+|(\\b[\\d']+(\\.[\\d']*)?|\\.[\\d']+)([eE][-+]?[\\d']+)?)"}],relevance:0},c={className:"meta",begin:/#\s*[a-z]+\b/,end:/$/,keywords:{keyword:"if else elif endif define undef warning error line pragma _Pragma ifdef ifndef include"},contains:[{begin:/\\\n/,relevance:0},e.inherit(o,{className:"string"}),{className:"string",begin:/<.*?>/},t,e.C_BLOCK_COMMENT_MODE]},d={className:"title",begin:n.optional(i)+e.IDENT_RE,relevance:0},g=n.optional(i)+e.IDENT_RE+"\\s*\\(",u={type:["bool","char","char16_t","char32_t","char8_t","double","float","int","long","short","void","wchar_t","unsigned","signed","const","static"],keyword:["alignas","alignof","and","and_eq","asm","atomic_cancel","atomic_commit","atomic_noexcept","auto","bitand","bitor","break","case","catch","class","co_await","co_return","co_yield","compl","concept","const_cast|10","consteval","constexpr","constinit","continue","decltype","default","delete","do","dynamic_cast|10","else","enum","explicit","export","extern","false","final","for","friend","goto","if","import","inline","module","mutable","namespace","new","noexcept","not","not_eq","nullptr","operator","or","or_eq","override","private","protected","public","reflexpr","register","reinterpret_cast|10","requires","return","sizeof","static_assert","static_cast|10","struct","switch","synchronized","template","this","thread_local","throw","transaction_safe","transaction_safe_dynamic","true","try","typedef","typeid","typename","union","using","virtual","volatile","while","xor","xor_eq"],literal:["NULL","false","nullopt","nullptr","true"],built_in:["_Pragma"],_type_hints:["any","auto_ptr","barrier","binary_semaphore","bitset","complex","condition_variable","condition_variable_any","counting_semaphore","deque","false_type","future","imaginary","initializer_list","istringstream","jthread","latch","lock_guard","multimap","multiset","mutex","optional","ostringstream","packaged_task","pair","promise","priority_queue","queue","recursive_mutex","recursive_timed_mutex","scoped_lock","set","shared_future","shared_lock","shared_mutex","shared_timed_mutex","shared_ptr","stack","string_view","stringstream","timed_mutex","thread","true_type","tuple","unique_lock","unique_ptr","unordered_map","unordered_multimap","unordered_multiset","unordered_set","variant","vector","weak_ptr","wstring","wstring_view"]},b={className:"function.dispatch",relevance:0,keywords:{_hint:["abort","abs","acos","apply","as_const","asin","atan","atan2","calloc","ceil","cerr","cin","clog","cos","cosh","cout","declval","endl","exchange","exit","exp","fabs","floor","fmod","forward","fprintf","fputs","free","frexp","fscanf","future","invoke","isalnum","isalpha","iscntrl","isdigit","isgraph","islower","isprint","ispunct","isspace","isupper","isxdigit","labs","launder","ldexp","log","log10","make_pair","make_shared","make_shared_for_overwrite","make_tuple","make_unique","malloc","memchr","memcmp","memcpy","memset","modf","move","pow","printf","putchar","puts","realloc","scanf","sin","sinh","snprintf","sprintf","sqrt","sscanf","std","stderr","stdin","stdout","strcat","strchr","strcmp","strcpy","strcspn","strlen","strncat","strncmp","strncpy","strpbrk","strrchr","strspn","strstr","swap","tan","tanh","terminate","to_underlying","tolower","toupper","vfprintf","visit","vprintf","vsprintf"]},begin:n.concat(/\b/,/(?!decltype)/,/(?!if)/,/(?!for)/,/(?!switch)/,/(?!while)/,e.IDENT_RE,n.lookahead(/(<[^<>]+>|)\s*\(/))},m=[b,c,s,t,e.C_BLOCK_COMMENT_MODE,l,o],p={variants:[{begin:/=/,end:/;/},{begin:/\(/,end:/\)/},{beginKeywords:"new throw return else",end:/;/}],keywords:u,contains:m.concat([{begin:/\(/,end:/\)/,keywords:u,contains:m.concat(["self"]),relevance:0}]),relevance:0},h={className:"function",begin:"("+r+"[\\*&\\s]+)+"+g,returnBegin:!0,end:/[{;=]/,excludeEnd:!0,keywords:u,illegal:/[^\w\s\*&:<>.]/,contains:[{begin:a,keywords:u,relevance:0},{begin:g,returnBegin:!0,contains:[d],relevance:0},{begin:/::/,relevance:0},{begin:/:/,endsWithParent:!0,contains:[o,l]},{relevance:0,match:/,/},{className:"params",begin:/\(/,end:/\)/,keywords:u,relevance:0,contains:[t,e.C_BLOCK_COMMENT_MODE,o,l,s,{begin:/\(/,end:/\)/,keywords:u,relevance:0,contains:["self",t,e.C_BLOCK_COMMENT_MODE,o,l,s]}]},s,t,e.C_BLOCK_COMMENT_MODE,c]};return{name:"C++",aliases:["cc","c++","h++","hpp","hh","hxx","cxx"],keywords:u,illegal:"</",classNameAliases:{"function.dispatch":"built_in"},contains:[].concat(p,h,b,m,[c,{begin:"\\b(deque|list|queue|priority_queue|pair|stack|vector|map|set|bitset|multiset|multimap|unordered_map|unordered_set|unordered_multiset|unordered_multimap|array|tuple|optional|variant|function)\\s*<(?!<)",end:">",keywords:u,contains:["self",s]},{begin:e.IDENT_RE+"::",keywords:u},{match:[/\b(?:enum(?:\s+(?:class|struct))?|class|struct|union)/,/\s+/,/\w+/],className:{1:"keyword",3:"title.class"}}])}},grmr_csharp(e){let n={keyword:["abstract","as","base","break","case","catch","class","const","continue","do","else","event","explicit","extern","finally","fixed","for","foreach","goto","if","implicit","in","interface","internal","is","lock","namespace","new","operator","out","override","params","private","protected","public","readonly","record","ref","return","scoped","sealed","sizeof","stackalloc","static","struct","switch","this","throw","try","typeof","unchecked","unsafe","using","virtual","void","volatile","while"].concat(["add","alias","and","ascending","async","await","by","descending","equals","from","get","global","group","init","into","join","let","nameof","not","notnull","on","or","orderby","partial","remove","select","set","unmanaged","value|0","var","when","where","with","yield"]),built_in:["bool","byte","char","decimal","delegate","double","dynamic","enum","float","int","long","nint","nuint","object","sbyte","short","string","ulong","uint","ushort"],literal:["default","false","null","true"]},t=e.inherit(e.TITLE_MODE,{begin:"[a-zA-Z](\\.?\\w)*"}),a={className:"number",variants:[{begin:"\\b(0b[01']+)"},{begin:"(-?)\\b([\\d']+(\\.[\\d']*)?|\\.[\\d']+)(u|U|l|L|ul|UL|f|F|b|B)"},{begin:"(-?)(\\b0[xX][a-fA-F0-9']+|(\\b[\\d']+(\\.[\\d']*)?|\\.[\\d']+)([eE][-+]?[\\d']+)?)"}],relevance:0},i={className:"string",begin:'@"',end:'"',contains:[{begin:'""'}]},r=e.inherit(i,{illegal:/\n/}),s={className:"subst",begin:/\{/,end:/\}/,keywords:n},o=e.inherit(s,{illegal:/\n/}),l={className:"string",begin:/\$"/,end:'"',illegal:/\n/,contains:[{begin:/\{\{/},{begin:/\}\}/},e.BACKSLASH_ESCAPE,o]},c={className:"string",begin:/\$@"/,end:'"',contains:[{begin:/\{\{/},{begin:/\}\}/},{begin:'""'},s]},d=e.inherit(c,{illegal:/\n/,contains:[{begin:/\{\{/},{begin:/\}\}/},{begin:'""'},o]});s.contains=[c,l,i,e.APOS_STRING_MODE,e.QUOTE_STRING_MODE,a,e.C_BLOCK_COMMENT_MODE],o.contains=[d,l,r,e.APOS_STRING_MODE,e.QUOTE_STRING_MODE,a,e.inherit(e.C_BLOCK_COMMENT_MODE,{illegal:/\n/})];let g={variants:[c,l,i,e.APOS_STRING_MODE,e.QUOTE_STRING_MODE]},u={begin:"<",end:">",contains:[{beginKeywords:"in out"},t]},b=e.IDENT_RE+"(<"+e.IDENT_RE+"(\\s*,\\s*"+e.IDENT_RE+")*>)?(\\[\\])?",m={begin:"@"+e.IDENT_RE,relevance:0};return{name:"C#",aliases:["cs","c#"],keywords:n,illegal:/::/,contains:[e.COMMENT("///","$",{returnBegin:!0,contains:[{className:"doctag",variants:[{begin:"///",relevance:0},{begin:"<!--|-->"},{begin:"</?",end:">"}]}]}),e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE,{className:"meta",begin:"#",end:"$",keywords:{keyword:"if else elif endif define undef warning error line region endregion pragma checksum"}},g,a,{beginKeywords:"class interface",relevance:0,end:/[{;=]/,illegal:/[^\s:,]/,contains:[{beginKeywords:"where class"},t,u,e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE]},{beginKeywords:"namespace",relevance:0,end:/[{;=]/,illegal:/[^\s:]/,contains:[t,e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE]},{beginKeywords:"record",relevance:0,end:/[{;=]/,illegal:/[^\s:]/,contains:[t,u,e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE]},{className:"meta",begin:"^\\s*\\[(?=[\\w])",excludeBegin:!0,end:"\\]",excludeEnd:!0,contains:[{className:"string",begin:/"/,end:/"/}]},{beginKeywords:"new return throw await else",relevance:0},{className:"function",begin:"("+b+"\\s+)+"+e.IDENT_RE+"\\s*(<[^=]+>\\s*)?\\(",returnBegin:!0,end:/\s*[{;=]/,excludeEnd:!0,keywords:n,contains:[{beginKeywords:"public private protected static internal protected abstract async extern override unsafe virtual new sealed partial",relevance:0},{begin:e.IDENT_RE+"\\s*(<[^=]+>\\s*)?\\(",returnBegin:!0,contains:[e.TITLE_MODE,u],relevance:0},{match:/\(\)/},{className:"params",begin:/\(/,end:/\)/,excludeBegin:!0,excludeEnd:!0,keywords:n,relevance:0,contains:[g,a,e.C_BLOCK_COMMENT_MODE]},e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE]},m]}},grmr_css(e){let n=e.regex,t=X(e),a=[e.APOS_STRING_MODE,e.QUOTE_STRING_MODE];return{name:"CSS",case_insensitive:!0,illegal:/[=|'\$]/,keywords:{keyframePosition:"from to"},classNameAliases:{keyframePosition:"selector-tag"},contains:[t.BLOCK_COMMENT,{begin:/-(webkit|moz|ms|o)-(?=[a-z])/},t.CSS_NUMBER_MODE,{className:"selector-id",begin:/#[A-Za-z0-9_-]+/,relevance:0},{className:"selector-class",begin:"\\.[a-zA-Z-][a-zA-Z0-9_-]*",relevance:0},t.ATTRIBUTE_SELECTOR_MODE,{className:"selector-pseudo",variants:[{begin:":("+Y.join("|")+")"},{begin:":(:)?("+ee.join("|")+")"}]},t.CSS_VARIABLE,{className:"attribute",begin:"\\b("+en.join("|")+")\\b"},{begin:/:/,end:/[;}{]/,contains:[t.BLOCK_COMMENT,t.HEXCOLOR,t.IMPORTANT,t.CSS_NUMBER_MODE,...a,{begin:/(url|data-uri)\(/,end:/\)/,relevance:0,keywords:{built_in:"url data-uri"},contains:[...a,{className:"string",begin:/[^)]/,endsWithParent:!0,excludeEnd:!0}]},t.FUNCTION_DISPATCH]},{begin:n.lookahead(/@/),end:"[{;]",relevance:0,illegal:/:/,contains:[{className:"keyword",begin:/@-?\w[\w]*(-\w+)*/},{begin:/\s/,endsWithParent:!0,excludeEnd:!0,relevance:0,keywords:{$pattern:/[a-z-]+/,keyword:"and or not only",attribute:J.join(" ")},contains:[{begin:/[a-z-]+(?=:)/,className:"attribute"},...a,t.CSS_NUMBER_MODE]}]},{className:"selector-tag",begin:"\\b("+V.join("|")+")\\b"}]}},grmr_diff(e){let n=e.regex;return{name:"Diff",aliases:["patch"],contains:[{className:"meta",relevance:10,match:n.either(/^@@ +-\d+,\d+ +\+\d+,\d+ +@@/,/^\*\*\* +\d+,\d+ +\*\*\*\*$/,/^--- +\d+,\d+ +----$/)},{className:"comment",variants:[{begin:n.either(/Index: /,/^index/,/={3,}/,/^-{3}/,/^\*{3} /,/^\+{3}/,/^diff --git/),end:/$/},{match:/^\*{15}$/}]},{className:"addition",begin:/^\+/,end:/$/},{className:"deletion",begin:/^-/,end:/$/},{className:"addition",begin:/^!/,end:/$/}]}},grmr_go(e){let n={keyword:["break","case","chan","const","continue","default","defer","else","fallthrough","for","func","go","goto","if","import","interface","map","package","range","return","select","struct","switch","type","var"],type:["bool","byte","complex64","complex128","error","float32","float64","int8","int16","int32","int64","string","uint8","uint16","uint32","uint64","int","uint","uintptr","rune"],literal:["true","false","iota","nil"],built_in:["append","cap","close","complex","copy","imag","len","make","new","panic","print","println","real","recover","delete"]};return{name:"Go",aliases:["golang"],keywords:n,illegal:"</",contains:[e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE,{className:"string",variants:[e.QUOTE_STRING_MODE,e.APOS_STRING_MODE,{begin:"`",end:"`"}]},{className:"number",variants:[{begin:e.C_NUMBER_RE+"[i]",relevance:1},e.C_NUMBER_MODE]},{begin:/:=/},{className:"function",beginKeywords:"func",end:"\\s*(\\{|$)",excludeEnd:!0,contains:[e.TITLE_MODE,{className:"params",begin:/\(/,end:/\)/,endsParent:!0,keywords:n,illegal:/["']/}]}]}},grmr_graphql(e){let n=e.regex;return{name:"GraphQL",aliases:["gql"],case_insensitive:!0,disableAutodetect:!1,keywords:{keyword:["query","mutation","subscription","type","input","schema","directive","interface","union","scalar","fragment","enum","on"],literal:["true","false","null"]},contains:[e.HASH_COMMENT_MODE,e.QUOTE_STRING_MODE,e.NUMBER_MODE,{scope:"punctuation",match:/[.]{3}/,relevance:0},{scope:"punctuation",begin:/[\!\(\)\:\=\[\]\{\|\}]{1}/,relevance:0},{scope:"variable",begin:/\$/,end:/\W/,excludeEnd:!0,relevance:0},{scope:"meta",match:/@\w+/,excludeEnd:!0},{scope:"symbol",begin:n.concat(/[_A-Za-z][_0-9A-Za-z]*/,n.lookahead(/\s*:/)),relevance:0}],illegal:[/[;<']/,/BEGIN/]}},grmr_ini(e){let n=e.regex,t={className:"number",relevance:0,variants:[{begin:/([+-]+)?[\d]+_[\d_]+/},{begin:e.NUMBER_RE}]},a=e.COMMENT();a.variants=[{begin:/;/,end:/$/},{begin:/#/,end:/$/}];let i={className:"variable",variants:[{begin:/\$[\w\d"][\w\d_]*/},{begin:/\$\{(.*?)\}/}]},r={className:"literal",begin:/\bon|off|true|false|yes|no\b/},s={className:"string",contains:[e.BACKSLASH_ESCAPE],variants:[{begin:"'''",end:"'''",relevance:10},{begin:'"""',end:'"""',relevance:10},{begin:'"',end:'"'},{begin:"'",end:"'"}]},o=n.either(/[A-Za-z0-9_-]+/,/"(\\"|[^"])*"/,/'[^']*'/);return{name:"TOML, also INI",aliases:["toml"],case_insensitive:!0,illegal:/\S/,contains:[a,{className:"section",begin:/\[+/,end:/\]+/},{begin:n.concat(o,"(\\s*\\.\\s*",o,")*",n.lookahead(/\s*=\s*[^#\s]/)),className:"attr",starts:{end:/$/,contains:[a,{begin:/\[/,end:/\]/,contains:[a,r,i,s,t,"self"],relevance:0},r,i,s,t]}}]}},grmr_java(e){let n=e.regex,t="[\xc0-ʸa-zA-Z_$][\xc0-ʸa-zA-Z_$0-9]*",a=t+function e(n,t,a){return -1===a?"":n.replace(t,i=>e(n,t,a-1))}("(?:<"+t+"~~~(?:\\s*,\\s*"+t+"~~~)*>)?",/~~~/g,2),i={keyword:["synchronized","abstract","private","var","static","if","const ","for","while","strictfp","finally","protected","import","native","final","void","enum","else","break","transient","catch","instanceof","volatile","case","assert","package","default","public","try","switch","continue","throws","protected","public","private","module","requires","exports","do","sealed","yield","permits"],literal:["false","true","null"],type:["char","boolean","long","float","int","byte","short","double"],built_in:["super","this"]},r={className:"meta",begin:"@"+t,contains:[{begin:/\(/,end:/\)/,contains:["self"]}]},s={className:"params",begin:/\(/,end:/\)/,keywords:i,relevance:0,contains:[e.C_BLOCK_COMMENT_MODE],endsParent:!0};return{name:"Java",aliases:["jsp"],keywords:i,illegal:/<\/|#/,contains:[e.COMMENT("/\\*\\*","\\*/",{relevance:0,contains:[{begin:/\w+@/,relevance:0},{className:"doctag",begin:"@[A-Za-z]+"}]}),{begin:/import java\.[a-z]+\./,keywords:"import",relevance:2},e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE,{begin:/"""/,end:/"""/,className:"string",contains:[e.BACKSLASH_ESCAPE]},e.APOS_STRING_MODE,e.QUOTE_STRING_MODE,{match:[/\b(?:class|interface|enum|extends|implements|new)/,/\s+/,t],className:{1:"keyword",3:"title.class"}},{match:/non-sealed/,scope:"keyword"},{begin:[n.concat(/(?!else)/,t),/\s+/,t,/\s+/,/=(?!=)/],className:{1:"type",3:"variable",5:"operator"}},{begin:[/record/,/\s+/,t],className:{1:"keyword",3:"title.class"},contains:[s,e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE]},{beginKeywords:"new throw return else",relevance:0},{begin:["(?:"+a+"\\s+)",e.UNDERSCORE_IDENT_RE,/\s*(?=\()/],className:{2:"title.function"},keywords:i,contains:[{className:"params",begin:/\(/,end:/\)/,keywords:i,relevance:0,contains:[r,e.APOS_STRING_MODE,e.QUOTE_STRING_MODE,es,e.C_BLOCK_COMMENT_MODE]},e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE]},es,r]}},grmr_javascript:ep,grmr_json(e){let n=["true","false","null"],t={scope:"literal",beginKeywords:n.join(" ")};return{name:"JSON",keywords:{literal:n},contains:[{className:"attr",begin:/"(\\.|[^\\"\r\n])*"(?=\s*:)/,relevance:1.01},{match:/[{}[\],:]/,className:"punctuation",relevance:0},e.QUOTE_STRING_MODE,t,e.C_NUMBER_MODE,e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE],illegal:"\\S"}},grmr_kotlin(e){let n={keyword:"abstract as val var vararg get set class object open private protected public noinline crossinline dynamic final enum if else do while for when throw try catch finally import package is in fun override companion reified inline lateinit init interface annotation data sealed internal infix operator out by constructor super tailrec where const inner suspend typealias external expect actual",built_in:"Byte Short Char Int Long Boolean Float Double Void Unit Nothing",literal:"true false null"},t={className:"symbol",begin:e.UNDERSCORE_IDENT_RE+"@"},a={className:"subst",begin:/\$\{/,end:/\}/,contains:[e.C_NUMBER_MODE]},i={className:"variable",begin:"\\$"+e.UNDERSCORE_IDENT_RE},r={className:"string",variants:[{begin:'"""',end:'"""(?=[^"])',contains:[i,a]},{begin:"'",end:"'",illegal:/\n/,contains:[e.BACKSLASH_ESCAPE]},{begin:'"',end:'"',illegal:/\n/,contains:[e.BACKSLASH_ESCAPE,i,a]}]};a.contains.push(r);let s={className:"meta",begin:"@(?:file|property|field|get|set|receiver|param|setparam|delegate)\\s*:(?:\\s*"+e.UNDERSCORE_IDENT_RE+")?"},o={className:"meta",begin:"@"+e.UNDERSCORE_IDENT_RE,contains:[{begin:/\(/,end:/\)/,contains:[e.inherit(r,{className:"string"}),"self"]}]},l=e.COMMENT("/\\*","\\*/",{contains:[e.C_BLOCK_COMMENT_MODE]}),c={variants:[{className:"type",begin:e.UNDERSCORE_IDENT_RE},{begin:/\(/,end:/\)/,contains:[]}]},d=c;return d.variants[1].contains=[c],c.variants[1].contains=[d],{name:"Kotlin",aliases:["kt","kts"],keywords:n,contains:[e.COMMENT("/\\*\\*","\\*/",{relevance:0,contains:[{className:"doctag",begin:"@[A-Za-z]+"}]}),e.C_LINE_COMMENT_MODE,l,{className:"keyword",begin:/\b(break|continue|return|this)\b/,starts:{contains:[{className:"symbol",begin:/@\w+/}]}},t,s,o,{className:"function",beginKeywords:"fun",end:"[(]|$",returnBegin:!0,excludeEnd:!0,keywords:n,relevance:5,contains:[{begin:e.UNDERSCORE_IDENT_RE+"\\s*\\(",returnBegin:!0,relevance:0,contains:[e.UNDERSCORE_TITLE_MODE]},{className:"type",begin:/</,end:/>/,keywords:"reified",relevance:0},{className:"params",begin:/\(/,end:/\)/,endsParent:!0,keywords:n,relevance:0,contains:[{begin:/:/,end:/[=,\/]/,endsWithParent:!0,contains:[c,e.C_LINE_COMMENT_MODE,l],relevance:0},e.C_LINE_COMMENT_MODE,l,s,o,r,e.C_NUMBER_MODE]},l]},{begin:[/class|interface|trait/,/\s+/,e.UNDERSCORE_IDENT_RE],beginScope:{3:"title.class"},keywords:"class interface trait",end:/[:\{(]|$/,excludeEnd:!0,illegal:"extends implements",contains:[{beginKeywords:"public protected internal private constructor"},e.UNDERSCORE_TITLE_MODE,{className:"type",begin:/</,end:/>/,excludeBegin:!0,excludeEnd:!0,relevance:0},{className:"type",begin:/[,:]\s*/,end:/[<\(,){\s]|$/,excludeBegin:!0,returnEnd:!0},s,o]},r,{className:"meta",begin:"^#!/usr/bin/env",end:"$",illegal:"\n"},es]}},grmr_less(e){let n=X(e),t="[\\w-]+",a="("+t+"|@\\{"+t+"\\})",i=[],r=[],s=e=>({className:"string",begin:"~?"+e+".*?"+e}),o=(e,n,t)=>({className:e,begin:n,relevance:t}),l={$pattern:/[a-z-]+/,keyword:"and or not only",attribute:J.join(" ")};r.push(e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE,s("'"),s('"'),n.CSS_NUMBER_MODE,{begin:"(url|data-uri)\\(",starts:{className:"string",end:"[\\)\\n]",excludeEnd:!0}},n.HEXCOLOR,{begin:"\\(",end:"\\)",contains:r,keywords:l,relevance:0},o("variable","@@?"+t,10),o("variable","@\\{"+t+"\\}"),o("built_in","~?`[^`]*?`"),{className:"attribute",begin:t+"\\s*:",end:":",returnBegin:!0,excludeEnd:!0},n.IMPORTANT,{beginKeywords:"and not"},n.FUNCTION_DISPATCH);let c=r.concat({begin:/\{/,end:/\}/,contains:i}),d={beginKeywords:"when",endsWithParent:!0,contains:[{beginKeywords:"and not"}].concat(r)},g={begin:a+"\\s*:",returnBegin:!0,end:/[;}]/,relevance:0,contains:[{begin:/-(webkit|moz|ms|o)-/},n.CSS_VARIABLE,{className:"attribute",begin:"\\b("+en.join("|")+")\\b",end:/(?=:)/,starts:{endsWithParent:!0,illegal:"[<=$]",relevance:0,contains:r}}]},u={variants:[{begin:"[\\.#:&\\[>]",end:"[;{}]"},{begin:a,end:/\{/}],returnBegin:!0,returnEnd:!0,illegal:"[<='$\"]",relevance:0,contains:[e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE,d,o("keyword","all\\b"),o("variable","@\\{"+t+"\\}"),{begin:"\\b("+V.join("|")+")\\b",className:"selector-tag"},n.CSS_NUMBER_MODE,o("selector-tag",a,0),o("selector-id","#"+a),o("selector-class","\\."+a,0),o("selector-tag","&",0),n.ATTRIBUTE_SELECTOR_MODE,{className:"selector-pseudo",begin:":("+Y.join("|")+")"},{className:"selector-pseudo",begin:":(:)?("+ee.join("|")+")"},{begin:/\(/,end:/\)/,relevance:0,contains:c},{begin:"!important"},n.FUNCTION_DISPATCH]},b={begin:t+":(:)?"+`(${et.join("|")})`,returnBegin:!0,contains:[u]};return i.push(e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE,{className:"keyword",begin:"@(import|media|charset|font-face|(-[a-z]+-)?keyframes|supports|document|namespace|page|viewport|host)\\b",starts:{end:"[;{}]",keywords:l,returnEnd:!0,contains:r,relevance:0}},{className:"variable",variants:[{begin:"@"+t+"\\s*:",relevance:15},{begin:"@"+t}],starts:{end:"[;}]",returnEnd:!0,contains:c}},b,g,u,d,n.FUNCTION_DISPATCH),{name:"Less",case_insensitive:!0,illegal:"[=>'/<($\"]",contains:i}},grmr_lua(e){let n="\\[=*\\[",t="\\]=*\\]",a={begin:n,end:t,contains:["self"]},i=[e.COMMENT("--(?!"+n+")","$"),e.COMMENT("--"+n,t,{contains:[a],relevance:10})];return{name:"Lua",keywords:{$pattern:e.UNDERSCORE_IDENT_RE,literal:"true false nil",keyword:"and break do else elseif end for goto if in local not or repeat return then until while",built_in:"_G _ENV _VERSION __index __newindex __mode __call __metatable __tostring __len __gc __add __sub __mul __div __mod __pow __concat __unm __eq __lt __le assert collectgarbage dofile error getfenv getmetatable ipairs load loadfile loadstring module next pairs pcall print rawequal rawget rawset require select setfenv setmetatable tonumber tostring type unpack xpcall arg self coroutine resume yield status wrap create running debug getupvalue debug sethook getmetatable gethook setmetatable setlocal traceback setfenv getinfo setupvalue getlocal getregistry getfenv io lines write close flush open output type read stderr stdin input stdout popen tmpfile math log max acos huge ldexp pi cos tanh pow deg tan cosh sinh random randomseed frexp ceil floor rad abs sqrt modf asin min mod fmod log10 atan2 exp sin atan os exit setlocale date getenv difftime remove time clock tmpname rename execute package preload loadlib loaded loaders cpath config path seeall string sub upper len gfind rep find match char dump gmatch reverse byte format gsub lower table setn insert getn foreachi maxn foreach concat sort remove"},contains:i.concat([{className:"function",beginKeywords:"function",end:"\\)",contains:[e.inherit(e.TITLE_MODE,{begin:"([_a-zA-Z]\\w*\\.)*([_a-zA-Z]\\w*:)?[_a-zA-Z]\\w*"}),{className:"params",begin:"\\(",endsWithParent:!0,contains:i}].concat(i)},e.C_NUMBER_MODE,e.APOS_STRING_MODE,e.QUOTE_STRING_MODE,{className:"string",begin:n,end:t,contains:[a],relevance:5}])}},grmr_makefile(e){let n={className:"variable",variants:[{begin:"\\$\\("+e.UNDERSCORE_IDENT_RE+"\\)",contains:[e.BACKSLASH_ESCAPE]},{begin:/\$[@%<?\^\+\*]/}]},t={className:"string",begin:/"/,end:/"/,contains:[e.BACKSLASH_ESCAPE,n]},a={begin:"^"+e.UNDERSCORE_IDENT_RE+"\\s*(?=[:+?]?=)"};return{name:"Makefile",aliases:["mk","mak","make"],keywords:{$pattern:/[\w-]+/,keyword:"define endef undefine ifdef ifndef ifeq ifneq else endif include -include sinclude override export unexport private vpath"},contains:[e.HASH_COMMENT_MODE,n,t,{className:"variable",begin:/\$\([\w-]+\s/,end:/\)/,keywords:{built_in:"subst patsubst strip findstring filter filter-out sort word wordlist firstword lastword dir notdir suffix basename addsuffix addprefix join wildcard realpath abspath error warning shell origin flavor foreach if or and call eval file value"},contains:[n]},a,{className:"meta",begin:/^\.PHONY:/,end:/$/,keywords:{$pattern:/[\.\w]+/,keyword:".PHONY"}},{className:"section",begin:/^[^\s]+:/,end:/$/,contains:[n]}]}},grmr_markdown(e){let n={begin:/<\/?[A-Za-z_]/,end:">",subLanguage:"xml",relevance:0},t={variants:[{begin:/\[.+?\]\[.*?\]/,relevance:0},{begin:/\[.+?\]\(((data|javascript|mailto):|(?:http|ftp)s?:\/\/).*?\)/,relevance:2},{begin:e.regex.concat(/\[.+?\]\(/,/[A-Za-z][A-Za-z0-9+.-]*/,/:\/\/.*?\)/),relevance:2},{begin:/\[.+?\]\([./?&#].*?\)/,relevance:1},{begin:/\[.*?\]\(.*?\)/,relevance:0}],returnBegin:!0,contains:[{match:/\[(?=\])/},{className:"string",relevance:0,begin:"\\[",end:"\\]",excludeBegin:!0,returnEnd:!0},{className:"link",relevance:0,begin:"\\]\\(",end:"\\)",excludeBegin:!0,excludeEnd:!0},{className:"symbol",relevance:0,begin:"\\]\\[",end:"\\]",excludeBegin:!0,excludeEnd:!0}]},a={className:"strong",contains:[],variants:[{begin:/_{2}(?!\s)/,end:/_{2}/},{begin:/\*{2}(?!\s)/,end:/\*{2}/}]},i={className:"emphasis",contains:[],variants:[{begin:/\*(?![*\s])/,end:/\*/},{begin:/_(?![_\s])/,end:/_/,relevance:0}]},r=e.inherit(a,{contains:[]}),s=e.inherit(i,{contains:[]});a.contains.push(s),i.contains.push(r);let o=[n,t];return[a,i,r,s].forEach(e=>{e.contains=e.contains.concat(o)}),{name:"Markdown",aliases:["md","mkdown","mkd"],contains:[{className:"section",variants:[{begin:"^#{1,6}",end:"$",contains:o=o.concat(a,i)},{begin:"(?=^.+?\\n[=-]{2,}$)",contains:[{begin:"^[=-]*$"},{begin:"^",end:"\\n",contains:o}]}]},n,{className:"bullet",begin:"^[ 	]*([*+-]|(\\d+\\.))(?=\\s+)",end:"\\s+",excludeEnd:!0},a,i,{className:"quote",begin:"^>\\s+",contains:o,end:"$"},{className:"code",variants:[{begin:"(`{3,})[^`](.|\\n)*?\\1`*[ ]*"},{begin:"(~{3,})[^~](.|\\n)*?\\1~*[ ]*"},{begin:"```",end:"```+[ ]*$"},{begin:"~~~",end:"~~~+[ ]*$"},{begin:"`.+?`"},{begin:"(?=^( {4}|\\t))",contains:[{begin:"^( {4}|\\t)",end:"(\\n)$"}],relevance:0}]},{begin:"^[-\\*]{3,}",end:"$"},t,{begin:/^\[[^\n]+\]:/,returnBegin:!0,contains:[{className:"symbol",begin:/\[/,end:/\]/,excludeBegin:!0,excludeEnd:!0},{className:"link",begin:/:\s*/,end:/$/,excludeBegin:!0}]}]}},grmr_objectivec(e){let n=/[a-zA-Z@][a-zA-Z0-9_]*/,t={$pattern:n,keyword:["@interface","@class","@protocol","@implementation"]};return{name:"Objective-C",aliases:["mm","objc","obj-c","obj-c++","objective-c++"],keywords:{"variable.language":["this","super"],$pattern:n,keyword:["while","export","sizeof","typedef","const","struct","for","union","volatile","static","mutable","if","do","return","goto","enum","else","break","extern","asm","case","default","register","explicit","typename","switch","continue","inline","readonly","assign","readwrite","self","@synchronized","id","typeof","nonatomic","IBOutlet","IBAction","strong","weak","copy","in","out","inout","bycopy","byref","oneway","__strong","__weak","__block","__autoreleasing","@private","@protected","@public","@try","@property","@end","@throw","@catch","@finally","@autoreleasepool","@synthesize","@dynamic","@selector","@optional","@required","@encode","@package","@import","@defs","@compatibility_alias","__bridge","__bridge_transfer","__bridge_retained","__bridge_retain","__covariant","__contravariant","__kindof","_Nonnull","_Nullable","_Null_unspecified","__FUNCTION__","__PRETTY_FUNCTION__","__attribute__","getter","setter","retain","unsafe_unretained","nonnull","nullable","null_unspecified","null_resettable","class","instancetype","NS_DESIGNATED_INITIALIZER","NS_UNAVAILABLE","NS_REQUIRES_SUPER","NS_RETURNS_INNER_POINTER","NS_INLINE","NS_AVAILABLE","NS_DEPRECATED","NS_ENUM","NS_OPTIONS","NS_SWIFT_UNAVAILABLE","NS_ASSUME_NONNULL_BEGIN","NS_ASSUME_NONNULL_END","NS_REFINED_FOR_SWIFT","NS_SWIFT_NAME","NS_SWIFT_NOTHROW","NS_DURING","NS_HANDLER","NS_ENDHANDLER","NS_VALUERETURN","NS_VOIDRETURN"],literal:["false","true","FALSE","TRUE","nil","YES","NO","NULL"],built_in:["dispatch_once_t","dispatch_queue_t","dispatch_sync","dispatch_async","dispatch_once"],type:["int","float","char","unsigned","signed","short","long","double","wchar_t","unichar","void","bool","BOOL","id|0","_Bool"]},illegal:"</",contains:[{className:"built_in",begin:"\\b(AV|CA|CF|CG|CI|CL|CM|CN|CT|MK|MP|MTK|MTL|NS|SCN|SK|UI|WK|XC)\\w+"},e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE,e.C_NUMBER_MODE,e.QUOTE_STRING_MODE,e.APOS_STRING_MODE,{className:"string",variants:[{begin:'@"',end:'"',illegal:"\\n",contains:[e.BACKSLASH_ESCAPE]}]},{className:"meta",begin:/#\s*[a-z]+\b/,end:/$/,keywords:{keyword:"if else elif endif define undef warning error line pragma ifdef ifndef include"},contains:[{begin:/\\\n/,relevance:0},e.inherit(e.QUOTE_STRING_MODE,{className:"string"}),{className:"string",begin:/<.*?>/,end:/$/,illegal:"\\n"},e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE]},{className:"class",begin:"("+t.keyword.join("|")+")\\b",end:/(\{|$)/,excludeEnd:!0,keywords:t,contains:[e.UNDERSCORE_TITLE_MODE]},{begin:"\\."+e.UNDERSCORE_IDENT_RE,relevance:0}]}},grmr_perl(e){let n=e.regex,t=/[dualxmsipngr]{0,12}/,a={$pattern:/[\w.]+/,keyword:"abs accept alarm and atan2 bind binmode bless break caller chdir chmod chomp chop chown chr chroot close closedir connect continue cos crypt dbmclose dbmopen defined delete die do dump each else elsif endgrent endhostent endnetent endprotoent endpwent endservent eof eval exec exists exit exp fcntl fileno flock for foreach fork format formline getc getgrent getgrgid getgrnam gethostbyaddr gethostbyname gethostent getlogin getnetbyaddr getnetbyname getnetent getpeername getpgrp getpriority getprotobyname getprotobynumber getprotoent getpwent getpwnam getpwuid getservbyname getservbyport getservent getsockname getsockopt given glob gmtime goto grep gt hex if index int ioctl join keys kill last lc lcfirst length link listen local localtime log lstat lt ma map mkdir msgctl msgget msgrcv msgsnd my ne next no not oct open opendir or ord our pack package pipe pop pos print printf prototype push q|0 qq quotemeta qw qx rand read readdir readline readlink readpipe recv redo ref rename require reset return reverse rewinddir rindex rmdir say scalar seek seekdir select semctl semget semop send setgrent sethostent setnetent setpgrp setpriority setprotoent setpwent setservent setsockopt shift shmctl shmget shmread shmwrite shutdown sin sleep socket socketpair sort splice split sprintf sqrt srand stat state study sub substr symlink syscall sysopen sysread sysseek system syswrite tell telldir tie tied time times tr truncate uc ucfirst umask undef unless unlink unpack unshift untie until use utime values vec wait waitpid wantarray warn when while write x|0 xor y|0"},i={className:"subst",begin:"[$@]\\{",end:"\\}",keywords:a},r={begin:/->\{/,end:/\}/},s={variants:[{begin:/\$\d/},{begin:n.concat(/[$%@](\^\w\b|#\w+(::\w+)*|\{\w+\}|\w+(::\w*)*)/,"(?![A-Za-z])(?![@$%])")},{begin:/[$%@][^\s\w{]/,relevance:0}]},o=[e.BACKSLASH_ESCAPE,i,s],l=[/!/,/\//,/\|/,/\?/,/'/,/"/,/#/],c=(e,a,i="\\1")=>{let r="\\1"===i?i:n.concat(i,a);return n.concat(n.concat("(?:",e,")"),a,/(?:\\.|[^\\\/])*?/,r,/(?:\\.|[^\\\/])*?/,i,t)},d=(e,a,i)=>n.concat(n.concat("(?:",e,")"),a,/(?:\\.|[^\\\/])*?/,i,t),g=[s,e.HASH_COMMENT_MODE,e.COMMENT(/^=\w/,/=cut/,{endsWithParent:!0}),r,{className:"string",contains:o,variants:[{begin:"q[qwxr]?\\s*\\(",end:"\\)",relevance:5},{begin:"q[qwxr]?\\s*\\[",end:"\\]",relevance:5},{begin:"q[qwxr]?\\s*\\{",end:"\\}",relevance:5},{begin:"q[qwxr]?\\s*\\|",end:"\\|",relevance:5},{begin:"q[qwxr]?\\s*<",end:">",relevance:5},{begin:"qw\\s+q",end:"q",relevance:5},{begin:"'",end:"'",contains:[e.BACKSLASH_ESCAPE]},{begin:'"',end:'"'},{begin:"`",end:"`",contains:[e.BACKSLASH_ESCAPE]},{begin:/\{\w+\}/,relevance:0},{begin:"-?\\w+\\s*=>",relevance:0}]},{className:"number",begin:"(\\b0[0-7_]+)|(\\b0x[0-9a-fA-F_]+)|(\\b[1-9][0-9_]*(\\.[0-9_]+)?)|[0_]\\b",relevance:0},{begin:"(\\/\\/|"+e.RE_STARTERS_RE+"|\\b(split|return|print|reverse|grep)\\b)\\s*",keywords:"split return print reverse grep",relevance:0,contains:[e.HASH_COMMENT_MODE,{className:"regexp",variants:[{begin:c("s|tr|y",n.either(...l,{capture:!0}))},{begin:c("s|tr|y","\\(","\\)")},{begin:c("s|tr|y","\\[","\\]")},{begin:c("s|tr|y","\\{","\\}")}],relevance:2},{className:"regexp",variants:[{begin:/(m|qr)\/\//,relevance:0},{begin:d("(?:m|qr)?",/\//,/\//)},{begin:d("m|qr",n.either(...l,{capture:!0}),/\1/)},{begin:d("m|qr",/\(/,/\)/)},{begin:d("m|qr",/\[/,/\]/)},{begin:d("m|qr",/\{/,/\}/)}]}]},{className:"function",beginKeywords:"sub",end:"(\\s*\\(.*?\\))?[;{]",excludeEnd:!0,relevance:5,contains:[e.TITLE_MODE]},{begin:"-\\w\\b",relevance:0},{begin:"^__DATA__$",end:"^__END__$",subLanguage:"mojolicious",contains:[{begin:"^@@.*",end:"$",className:"comment"}]}];return i.contains=g,r.contains=g,{name:"Perl",aliases:["pl","pm"],keywords:a,contains:g}},grmr_php(e){let n=e.regex,t=/(?![A-Za-z0-9])(?![$])/,a=n.concat(/[a-zA-Z_\x7f-\xff][a-zA-Z0-9_\x7f-\xff]*/,t),i=n.concat(/(\\?[A-Z][a-z0-9_\x7f-\xff]+|\\?[A-Z]+(?=[A-Z][a-z0-9_\x7f-\xff])){1,}/,t),r={scope:"variable",match:"\\$+"+a},s={scope:"subst",variants:[{begin:/\$\w+/},{begin:/\{\$/,end:/\}/}]},o=e.inherit(e.APOS_STRING_MODE,{illegal:null}),l="[ 	\n]",c={scope:"string",variants:[e.inherit(e.QUOTE_STRING_MODE,{illegal:null,contains:e.QUOTE_STRING_MODE.contains.concat(s)}),o,{begin:/<<<[ \t]*(?:(\w+)|"(\w+)")\n/,end:/[ \t]*(\w+)\b/,contains:e.QUOTE_STRING_MODE.contains.concat(s),"on:begin"(e,n){n.data._beginMatch=e[1]||e[2]},"on:end"(e,n){n.data._beginMatch!==e[1]&&n.ignoreMatch()}},e.END_SAME_AS_BEGIN({begin:/<<<[ \t]*'(\w+)'\n/,end:/[ \t]*(\w+)\b/})]},d={scope:"number",variants:[{begin:"\\b0[bB][01]+(?:_[01]+)*\\b"},{begin:"\\b0[oO][0-7]+(?:_[0-7]+)*\\b"},{begin:"\\b0[xX][\\da-fA-F]+(?:_[\\da-fA-F]+)*\\b"},{begin:"(?:\\b\\d+(?:_\\d+)*(\\.(?:\\d+(?:_\\d+)*))?|\\B\\.\\d+)(?:[eE][+-]?\\d+)?"}],relevance:0},g=["false","null","true"],u=["__CLASS__","__DIR__","__FILE__","__FUNCTION__","__COMPILER_HALT_OFFSET__","__LINE__","__METHOD__","__NAMESPACE__","__TRAIT__","die","echo","exit","include","include_once","print","require","require_once","array","abstract","and","as","binary","bool","boolean","break","callable","case","catch","class","clone","const","continue","declare","default","do","double","else","elseif","empty","enddeclare","endfor","endforeach","endif","endswitch","endwhile","enum","eval","extends","final","finally","float","for","foreach","from","global","goto","if","implements","instanceof","insteadof","int","integer","interface","isset","iterable","list","match|0","mixed","new","never","object","or","private","protected","public","readonly","real","return","string","switch","throw","trait","try","unset","use","var","void","while","xor","yield"],b=["Error|0","AppendIterator","ArgumentCountError","ArithmeticError","ArrayIterator","ArrayObject","AssertionError","BadFunctionCallException","BadMethodCallException","CachingIterator","CallbackFilterIterator","CompileError","Countable","DirectoryIterator","DivisionByZeroError","DomainException","EmptyIterator","ErrorException","Exception","FilesystemIterator","FilterIterator","GlobIterator","InfiniteIterator","InvalidArgumentException","IteratorIterator","LengthException","LimitIterator","LogicException","MultipleIterator","NoRewindIterator","OutOfBoundsException","OutOfRangeException","OuterIterator","OverflowException","ParentIterator","ParseError","RangeException","RecursiveArrayIterator","RecursiveCachingIterator","RecursiveCallbackFilterIterator","RecursiveDirectoryIterator","RecursiveFilterIterator","RecursiveIterator","RecursiveIteratorIterator","RecursiveRegexIterator","RecursiveTreeIterator","RegexIterator","RuntimeException","SeekableIterator","SplDoublyLinkedList","SplFileInfo","SplFileObject","SplFixedArray","SplHeap","SplMaxHeap","SplMinHeap","SplObjectStorage","SplObserver","SplPriorityQueue","SplQueue","SplStack","SplSubject","SplTempFileObject","TypeError","UnderflowException","UnexpectedValueException","UnhandledMatchError","ArrayAccess","BackedEnum","Closure","Fiber","Generator","Iterator","IteratorAggregate","Serializable","Stringable","Throwable","Traversable","UnitEnum","WeakReference","WeakMap","Directory","__PHP_Incomplete_Class","parent","php_user_filter","self","static","stdClass"],m={keyword:u,literal:(e=>{let n=[];return e.forEach(e=>{n.push(e),e.toLowerCase()===e?n.push(e.toUpperCase()):n.push(e.toLowerCase())}),n})(g),built_in:b},p=e=>e.map(e=>e.replace(/\|\d+$/,"")),h={variants:[{match:[/new/,n.concat(l,"+"),n.concat("(?!",p(b).join("\\b|"),"\\b)"),i],scope:{1:"keyword",4:"title.class"}}]},f=n.concat(a,"\\b(?!\\()"),E={variants:[{match:[n.concat(/::/,n.lookahead(/(?!class\b)/)),f],scope:{2:"variable.constant"}},{match:[/::/,/class/],scope:{2:"variable.language"}},{match:[i,n.concat(/::/,n.lookahead(/(?!class\b)/)),f],scope:{1:"title.class",3:"variable.constant"}},{match:[i,n.concat("::",n.lookahead(/(?!class\b)/))],scope:{1:"title.class"}},{match:[i,/::/,/class/],scope:{1:"title.class",3:"variable.language"}}]},$={scope:"attr",match:n.concat(a,n.lookahead(":"),n.lookahead(/(?!::)/))},y={relevance:0,begin:/\(/,end:/\)/,keywords:m,contains:[$,r,E,e.C_BLOCK_COMMENT_MODE,c,d,h]},N={relevance:0,match:[/\b/,n.concat("(?!fn\\b|function\\b|",p(u).join("\\b|"),"|",p(b).join("\\b|"),"\\b)"),a,n.concat(l,"*"),n.lookahead(/(?=\()/)],scope:{3:"title.function.invoke"},contains:[y]};y.contains.push(N);let w=[$,E,e.C_BLOCK_COMMENT_MODE,c,d,h];return{case_insensitive:!1,keywords:m,contains:[{begin:n.concat(/#\[\s*/,i),beginScope:"meta",end:/]/,endScope:"meta",keywords:{literal:g,keyword:["new","array"]},contains:[{begin:/\[/,end:/]/,keywords:{literal:g,keyword:["new","array"]},contains:["self",...w]},...w,{scope:"meta",match:i}]},e.HASH_COMMENT_MODE,e.COMMENT("//","$"),e.COMMENT("/\\*","\\*/",{contains:[{scope:"doctag",match:"@[A-Za-z]+"}]}),{match:/__halt_compiler\(\);/,keywords:"__halt_compiler",starts:{scope:"comment",end:e.MATCH_NOTHING_RE,contains:[{match:/\?>/,scope:"meta",endsParent:!0}]}},{scope:"meta",variants:[{begin:/<\?php/,relevance:10},{begin:/<\?=/},{begin:/<\?/,relevance:.1},{begin:/\?>/}]},{scope:"variable.language",match:/\$this\b/},r,N,E,{match:[/const/,/\s/,a],scope:{1:"keyword",3:"variable.constant"}},h,{scope:"function",relevance:0,beginKeywords:"fn function",end:/[;{]/,excludeEnd:!0,illegal:"[$%\\[]",contains:[{beginKeywords:"use"},e.UNDERSCORE_TITLE_MODE,{begin:"=>",endsParent:!0},{scope:"params",begin:"\\(",end:"\\)",excludeBegin:!0,excludeEnd:!0,keywords:m,contains:["self",r,E,e.C_BLOCK_COMMENT_MODE,c,d]}]},{scope:"class",variants:[{beginKeywords:"enum",illegal:/[($"]/},{beginKeywords:"class interface trait",illegal:/[:($"]/}],relevance:0,end:/\{/,excludeEnd:!0,contains:[{beginKeywords:"extends implements"},e.UNDERSCORE_TITLE_MODE]},{beginKeywords:"namespace",relevance:0,end:";",illegal:/[.']/,contains:[e.inherit(e.UNDERSCORE_TITLE_MODE,{scope:"title.class"})]},{beginKeywords:"use",relevance:0,end:";",contains:[{match:/\b(as|const|function)\b/,scope:"keyword"},e.UNDERSCORE_TITLE_MODE]},c,d]}},grmr_php_template:e=>({name:"PHP template",subLanguage:"xml",contains:[{begin:/<\?(php|=)?/,end:/\?>/,subLanguage:"php",contains:[{begin:"/\\*",end:"\\*/",skip:!0},{begin:'b"',end:'"',skip:!0},{begin:"b'",end:"'",skip:!0},e.inherit(e.APOS_STRING_MODE,{illegal:null,className:null,contains:null,skip:!0}),e.inherit(e.QUOTE_STRING_MODE,{illegal:null,className:null,contains:null,skip:!0})]}]}),grmr_plaintext:e=>({name:"Plain text",aliases:["text","txt"],disableAutodetect:!0}),grmr_python(e){let n=e.regex,t=/[\p{XID_Start}_]\p{XID_Continue}*/u,a=["and","as","assert","async","await","break","case","class","continue","def","del","elif","else","except","finally","for","from","global","if","import","in","is","lambda","match","nonlocal|10","not","or","pass","raise","return","try","while","with","yield"],i={$pattern:/[A-Za-z]\w+|__\w+__/,keyword:a,built_in:["__import__","abs","all","any","ascii","bin","bool","breakpoint","bytearray","bytes","callable","chr","classmethod","compile","complex","delattr","dict","dir","divmod","enumerate","eval","exec","filter","float","format","frozenset","getattr","globals","hasattr","hash","help","hex","id","input","int","isinstance","issubclass","iter","len","list","locals","map","max","memoryview","min","next","object","oct","open","ord","pow","print","property","range","repr","reversed","round","set","setattr","slice","sorted","staticmethod","str","sum","super","tuple","type","vars","zip"],literal:["__debug__","Ellipsis","False","None","NotImplemented","True"],type:["Any","Callable","Coroutine","Dict","List","Literal","Generic","Optional","Sequence","Set","Tuple","Type","Union"]},r={className:"meta",begin:/^(>>>|\.\.\.) /},s={className:"subst",begin:/\{/,end:/\}/,keywords:i,illegal:/#/},o={begin:/\{\{/,relevance:0},l={className:"string",contains:[e.BACKSLASH_ESCAPE],variants:[{begin:/([uU]|[bB]|[rR]|[bB][rR]|[rR][bB])?'''/,end:/'''/,contains:[e.BACKSLASH_ESCAPE,r],relevance:10},{begin:/([uU]|[bB]|[rR]|[bB][rR]|[rR][bB])?"""/,end:/"""/,contains:[e.BACKSLASH_ESCAPE,r],relevance:10},{begin:/([fF][rR]|[rR][fF]|[fF])'''/,end:/'''/,contains:[e.BACKSLASH_ESCAPE,r,o,s]},{begin:/([fF][rR]|[rR][fF]|[fF])"""/,end:/"""/,contains:[e.BACKSLASH_ESCAPE,r,o,s]},{begin:/([uU]|[rR])'/,end:/'/,relevance:10},{begin:/([uU]|[rR])"/,end:/"/,relevance:10},{begin:/([bB]|[bB][rR]|[rR][bB])'/,end:/'/},{begin:/([bB]|[bB][rR]|[rR][bB])"/,end:/"/},{begin:/([fF][rR]|[rR][fF]|[fF])'/,end:/'/,contains:[e.BACKSLASH_ESCAPE,o,s]},{begin:/([fF][rR]|[rR][fF]|[fF])"/,end:/"/,contains:[e.BACKSLASH_ESCAPE,o,s]},e.APOS_STRING_MODE,e.QUOTE_STRING_MODE]},c="[0-9](_?[0-9])*",d=`(\\b(${c}))?\\.(${c})|\\b(${c})\\.`,g="\\b|"+a.join("|"),u={className:"number",relevance:0,variants:[{begin:`(\\b(${c})|(${d}))[eE][+-]?(${c})[jJ]?(?=${g})`},{begin:`(${d})[jJ]?`},{begin:`\\b([1-9](_?[0-9])*|0+(_?0)*)[lLjJ]?(?=${g})`},{begin:`\\b0[bB](_?[01])+[lL]?(?=${g})`},{begin:`\\b0[oO](_?[0-7])+[lL]?(?=${g})`},{begin:`\\b0[xX](_?[0-9a-fA-F])+[lL]?(?=${g})`},{begin:`\\b(${c})[jJ](?=${g})`}]},b={className:"comment",begin:n.lookahead(/# type:/),end:/$/,keywords:i,contains:[{begin:/# type:/},{begin:/#/,end:/\b\B/,endsWithParent:!0}]},m={className:"params",variants:[{className:"",begin:/\(\s*\)/,skip:!0},{begin:/\(/,end:/\)/,excludeBegin:!0,excludeEnd:!0,keywords:i,contains:["self",r,u,l,e.HASH_COMMENT_MODE]}]};return s.contains=[l,u,r],{name:"Python",aliases:["py","gyp","ipython"],unicodeRegex:!0,keywords:i,illegal:/(<\/|\?)|=>/,contains:[r,u,{begin:/\bself\b/},{beginKeywords:"if",relevance:0},l,b,e.HASH_COMMENT_MODE,{match:[/\bdef/,/\s+/,t],scope:{1:"keyword",3:"title.function"},contains:[m]},{variants:[{match:[/\bclass/,/\s+/,t,/\s*/,/\(\s*/,t,/\s*\)/]},{match:[/\bclass/,/\s+/,t]}],scope:{1:"keyword",3:"title.class",6:"title.class.inherited"}},{className:"meta",begin:/^[\t ]*@/,end:/(?=#)|$/,contains:[u,m,l]}]}},grmr_python_repl:e=>({aliases:["pycon"],contains:[{className:"meta.prompt",starts:{end:/ |$/,starts:{end:"$",subLanguage:"python"}},variants:[{begin:/^>>>(?=[ ]|$)/},{begin:/^\.\.\.(?=[ ]|$)/}]}]}),grmr_r(e){let n=e.regex,t=/(?:(?:[a-zA-Z]|\.[._a-zA-Z])[._a-zA-Z0-9]*)|\.(?!\d)/,a=n.either(/0[xX][0-9a-fA-F]+\.[0-9a-fA-F]*[pP][+-]?\d+i?/,/0[xX][0-9a-fA-F]+(?:[pP][+-]?\d+)?[Li]?/,/(?:\d+(?:\.\d*)?|\.\d+)(?:[eE][+-]?\d+)?[Li]?/),i=/[=!<>:]=|\|\||&&|:::?|<-|<<-|->>|->|\|>|[-+*\/?!$&|:<=>@^~]|\*\*/,r=n.either(/[()]/,/[{}]/,/\[\[/,/[[\]]/,/\\/,/,/);return{name:"R",keywords:{$pattern:t,keyword:"function if in break next repeat else for while",literal:"NULL NA TRUE FALSE Inf NaN NA_integer_|10 NA_real_|10 NA_character_|10 NA_complex_|10",built_in:"LETTERS letters month.abb month.name pi T F abs acos acosh all any anyNA Arg as.call as.character as.complex as.double as.environment as.integer as.logical as.null.default as.numeric as.raw asin asinh atan atanh attr attributes baseenv browser c call ceiling class Conj cos cosh cospi cummax cummin cumprod cumsum digamma dim dimnames emptyenv exp expression floor forceAndCall gamma gc.time globalenv Im interactive invisible is.array is.atomic is.call is.character is.complex is.double is.environment is.expression is.finite is.function is.infinite is.integer is.language is.list is.logical is.matrix is.na is.name is.nan is.null is.numeric is.object is.pairlist is.raw is.recursive is.single is.symbol lazyLoadDBfetch length lgamma list log max min missing Mod names nargs nzchar oldClass on.exit pos.to.env proc.time prod quote range Re rep retracemem return round seq_along seq_len seq.int sign signif sin sinh sinpi sqrt standardGeneric substitute sum switch tan tanh tanpi tracemem trigamma trunc unclass untracemem UseMethod xtfrm"},contains:[e.COMMENT(/#'/,/$/,{contains:[{scope:"doctag",match:/@examples/,starts:{end:n.lookahead(n.either(/\n^#'\s*(?=@[a-zA-Z]+)/,/\n^(?!#')/)),endsParent:!0}},{scope:"doctag",begin:"@param",end:/$/,contains:[{scope:"variable",variants:[{match:t},{match:/`(?:\\.|[^`\\])+`/}],endsParent:!0}]},{scope:"doctag",match:/@[a-zA-Z]+/},{scope:"keyword",match:/\\[a-zA-Z]+/}]}),e.HASH_COMMENT_MODE,{scope:"string",contains:[e.BACKSLASH_ESCAPE],variants:[e.END_SAME_AS_BEGIN({begin:/[rR]"(-*)\(/,end:/\)(-*)"/}),e.END_SAME_AS_BEGIN({begin:/[rR]"(-*)\{/,end:/\}(-*)"/}),e.END_SAME_AS_BEGIN({begin:/[rR]"(-*)\[/,end:/\](-*)"/}),e.END_SAME_AS_BEGIN({begin:/[rR]'(-*)\(/,end:/\)(-*)'/}),e.END_SAME_AS_BEGIN({begin:/[rR]'(-*)\{/,end:/\}(-*)'/}),e.END_SAME_AS_BEGIN({begin:/[rR]'(-*)\[/,end:/\](-*)'/}),{begin:'"',end:'"',relevance:0},{begin:"'",end:"'",relevance:0}]},{relevance:0,variants:[{scope:{1:"operator",2:"number"},match:[i,a]},{scope:{1:"operator",2:"number"},match:[/%[^%]*%/,a]},{scope:{1:"punctuation",2:"number"},match:[r,a]},{scope:{2:"number"},match:[/[^a-zA-Z0-9._]|^/,a]}]},{scope:{3:"operator"},match:[t,/\s+/,/<-/,/\s+/]},{scope:"operator",relevance:0,variants:[{match:i},{match:/%[^%]*%/}]},{scope:"punctuation",relevance:0,match:r},{begin:"`",end:"`",contains:[{begin:/\\./}]}]}},grmr_ruby(e){let n=e.regex,t="([a-zA-Z_]\\w*[!?=]?|[-+~]@|<<|>>|=~|===?|<=>|[<>]=?|\\*\\*|[-/+%^&*~`|]|\\[\\]=?)",a=n.either(/\b([A-Z]+[a-z0-9]+)+/,/\b([A-Z]+[a-z0-9]+)+[A-Z]+/),i=n.concat(a,/(::\w+)*/),r={"variable.constant":["__FILE__","__LINE__","__ENCODING__"],"variable.language":["self","super"],keyword:["alias","and","begin","BEGIN","break","case","class","defined","do","else","elsif","end","END","ensure","for","if","in","module","next","not","or","redo","require","rescue","retry","return","then","undef","unless","until","when","while","yield","include","extend","prepend","public","private","protected","raise","throw"],built_in:["proc","lambda","attr_accessor","attr_reader","attr_writer","define_method","private_constant","module_function"],literal:["true","false","nil"]},s={className:"doctag",begin:"@[A-Za-z]+"},o={begin:"#<",end:">"},l=[e.COMMENT("#","$",{contains:[s]}),e.COMMENT("^=begin","^=end",{contains:[s],relevance:10}),e.COMMENT("^__END__",e.MATCH_NOTHING_RE)],c={className:"subst",begin:/#\{/,end:/\}/,keywords:r},d={className:"string",contains:[e.BACKSLASH_ESCAPE,c],variants:[{begin:/'/,end:/'/},{begin:/"/,end:/"/},{begin:/`/,end:/`/},{begin:/%[qQwWx]?\(/,end:/\)/},{begin:/%[qQwWx]?\[/,end:/\]/},{begin:/%[qQwWx]?\{/,end:/\}/},{begin:/%[qQwWx]?</,end:/>/},{begin:/%[qQwWx]?\//,end:/\//},{begin:/%[qQwWx]?%/,end:/%/},{begin:/%[qQwWx]?-/,end:/-/},{begin:/%[qQwWx]?\|/,end:/\|/},{begin:/\B\?(\\\d{1,3})/},{begin:/\B\?(\\x[A-Fa-f0-9]{1,2})/},{begin:/\B\?(\\u\{?[A-Fa-f0-9]{1,6}\}?)/},{begin:/\B\?(\\M-\\C-|\\M-\\c|\\c\\M-|\\M-|\\C-\\M-)[\x20-\x7e]/},{begin:/\B\?\\(c|C-)[\x20-\x7e]/},{begin:/\B\?\\?\S/},{begin:n.concat(/<<[-~]?'?/,n.lookahead(/(\w+)(?=\W)[^\n]*\n(?:[^\n]*\n)*?\s*\1\b/)),contains:[e.END_SAME_AS_BEGIN({begin:/(\w+)/,end:/(\w+)/,contains:[e.BACKSLASH_ESCAPE,c]})]}]},g="[0-9](_?[0-9])*",u={className:"number",relevance:0,variants:[{begin:`\\b([1-9](_?[0-9])*|0)(\\.(${g}))?([eE][+-]?(${g})|r)?i?\\b`},{begin:"\\b0[dD][0-9](_?[0-9])*r?i?\\b"},{begin:"\\b0[bB][0-1](_?[0-1])*r?i?\\b"},{begin:"\\b0[oO][0-7](_?[0-7])*r?i?\\b"},{begin:"\\b0[xX][0-9a-fA-F](_?[0-9a-fA-F])*r?i?\\b"},{begin:"\\b0(_?[0-7])+r?i?\\b"}]},b={variants:[{match:/\(\)/},{className:"params",begin:/\(/,end:/(?=\))/,excludeBegin:!0,endsParent:!0,keywords:r}]},m=[d,{variants:[{match:[/class\s+/,i,/\s+<\s+/,i]},{match:[/\b(class|module)\s+/,i]}],scope:{2:"title.class",4:"title.class.inherited"},keywords:r},{match:[/(include|extend)\s+/,i],scope:{2:"title.class"},keywords:r},{relevance:0,match:[i,/\.new[. (]/],scope:{1:"title.class"}},{relevance:0,match:/\b[A-Z][A-Z_0-9]+\b/,className:"variable.constant"},{relevance:0,match:a,scope:"title.class"},{match:[/def/,/\s+/,t],scope:{1:"keyword",3:"title.function"},contains:[b]},{begin:e.IDENT_RE+"::"},{className:"symbol",begin:e.UNDERSCORE_IDENT_RE+"(!|\\?)?:",relevance:0},{className:"symbol",begin:":(?!\\s)",contains:[d,{begin:t}],relevance:0},u,{className:"variable",begin:"(\\$\\W)|((\\$|@@?)(\\w+))(?=[^@$?])(?![A-Za-z])(?![@$?'])"},{className:"params",begin:/\|/,end:/\|/,excludeBegin:!0,excludeEnd:!0,relevance:0,keywords:r},{begin:"("+e.RE_STARTERS_RE+"|unless)\\s*",keywords:"unless",contains:[{className:"regexp",contains:[e.BACKSLASH_ESCAPE,c],illegal:/\n/,variants:[{begin:"/",end:"/[a-z]*"},{begin:/%r\{/,end:/\}[a-z]*/},{begin:"%r\\(",end:"\\)[a-z]*"},{begin:"%r!",end:"![a-z]*"},{begin:"%r\\[",end:"\\][a-z]*"}]}].concat(o,l),relevance:0}].concat(o,l);return c.contains=m,b.contains=m,l.unshift(o),{name:"Ruby",aliases:["rb","gemspec","podspec","thor","irb"],keywords:r,illegal:/\/\*/,contains:[e.SHEBANG({binary:"ruby"})].concat([{begin:/^\s*=>/,starts:{end:"$",contains:m}},{className:"meta.prompt",begin:"^([>?]>|[\\w#]+\\(\\w+\\):\\d+:\\d+[>*]|(\\w+-)?\\d+\\.\\d+\\.\\d+(p\\d+)?[^\\d][^>]+>)(?=[ ])",starts:{end:"$",keywords:r,contains:m}}]).concat(l).concat(m)}},grmr_rust(e){let n=e.regex,t={className:"title.function.invoke",relevance:0,begin:n.concat(/\b/,/(?!let|for|while|if|else|match\b)/,e.IDENT_RE,n.lookahead(/\s*\(/))},a="([ui](8|16|32|64|128|size)|f(32|64))?",i=["drop ","Copy","Send","Sized","Sync","Drop","Fn","FnMut","FnOnce","ToOwned","Clone","Debug","PartialEq","PartialOrd","Eq","Ord","AsRef","AsMut","Into","From","Default","Iterator","Extend","IntoIterator","DoubleEndedIterator","ExactSizeIterator","SliceConcatExt","ToString","assert!","assert_eq!","bitflags!","bytes!","cfg!","col!","concat!","concat_idents!","debug_assert!","debug_assert_eq!","env!","eprintln!","panic!","file!","format!","format_args!","include_bytes!","include_str!","line!","local_data_key!","module_path!","option_env!","print!","println!","select!","stringify!","try!","unimplemented!","unreachable!","vec!","write!","writeln!","macro_rules!","assert_ne!","debug_assert_ne!"],r=["i8","i16","i32","i64","i128","isize","u8","u16","u32","u64","u128","usize","f32","f64","str","char","bool","Box","Option","Result","String","Vec"];return{name:"Rust",aliases:["rs"],keywords:{$pattern:e.IDENT_RE+"!?",type:r,keyword:["abstract","as","async","await","become","box","break","const","continue","crate","do","dyn","else","enum","extern","false","final","fn","for","if","impl","in","let","loop","macro","match","mod","move","mut","override","priv","pub","ref","return","self","Self","static","struct","super","trait","true","try","type","typeof","unsafe","unsized","use","virtual","where","while","yield"],literal:["true","false","Some","None","Ok","Err"],built_in:i},illegal:"</",contains:[e.C_LINE_COMMENT_MODE,e.COMMENT("/\\*","\\*/",{contains:["self"]}),e.inherit(e.QUOTE_STRING_MODE,{begin:/b?"/,illegal:null}),{className:"string",variants:[{begin:/b?r(#*)"(.|\n)*?"\1(?!#)/},{begin:/b?'\\?(x\w{2}|u\w{4}|U\w{8}|.)'/}]},{className:"symbol",begin:/'[a-zA-Z_][a-zA-Z0-9_]*/},{className:"number",variants:[{begin:"\\b0b([01_]+)"+a},{begin:"\\b0o([0-7_]+)"+a},{begin:"\\b0x([A-Fa-f0-9_]+)"+a},{begin:"\\b(\\d[\\d_]*(\\.[0-9_]+)?([eE][+-]?[0-9_]+)?)"+a}],relevance:0},{begin:[/fn/,/\s+/,e.UNDERSCORE_IDENT_RE],className:{1:"keyword",3:"title.function"}},{className:"meta",begin:"#!?\\[",end:"\\]",contains:[{className:"string",begin:/"/,end:/"/}]},{begin:[/let/,/\s+/,/(?:mut\s+)?/,e.UNDERSCORE_IDENT_RE],className:{1:"keyword",3:"keyword",4:"variable"}},{begin:[/for/,/\s+/,e.UNDERSCORE_IDENT_RE,/\s+/,/in/],className:{1:"keyword",3:"variable",5:"keyword"}},{begin:[/type/,/\s+/,e.UNDERSCORE_IDENT_RE],className:{1:"keyword",3:"title.class"}},{begin:[/(?:trait|enum|struct|union|impl|for)/,/\s+/,e.UNDERSCORE_IDENT_RE],className:{1:"keyword",3:"title.class"}},{begin:e.IDENT_RE+"::",keywords:{keyword:"Self",built_in:i,type:r}},{className:"punctuation",begin:"->"},t]}},grmr_scss(e){let n=X(e),t="@[a-z-]+",a={className:"variable",begin:"(\\$[a-zA-Z-][a-zA-Z0-9_-]*)\\b",relevance:0};return{name:"SCSS",case_insensitive:!0,illegal:"[=/|']",contains:[e.C_LINE_COMMENT_MODE,e.C_BLOCK_COMMENT_MODE,n.CSS_NUMBER_MODE,{className:"selector-id",begin:"#[A-Za-z0-9_-]+",relevance:0},{className:"selector-class",begin:"\\.[A-Za-z0-9_-]+",relevance:0},n.ATTRIBUTE_SELECTOR_MODE,{className:"selector-tag",begin:"\\b("+V.join("|")+")\\b",relevance:0},{className:"selector-pseudo",begin:":("+Y.join("|")+")"},{className:"selector-pseudo",begin:":(:)?("+ee.join("|")+")"},a,{begin:/\(/,end:/\)/,contains:[n.CSS_NUMBER_MODE]},n.CSS_VARIABLE,{className:"attribute",begin:"\\b("+en.join("|")+")\\b"},{begin:"\\b(whitespace|wait|w-resize|visible|vertical-text|vertical-ideographic|uppercase|upper-roman|upper-alpha|underline|transparent|top|thin|thick|text|text-top|text-bottom|tb-rl|table-header-group|table-footer-group|sw-resize|super|strict|static|square|solid|small-caps|separate|se-resize|scroll|s-resize|rtl|row-resize|ridge|right|repeat|repeat-y|repeat-x|relative|progress|pointer|overline|outside|outset|oblique|nowrap|not-allowed|normal|none|nw-resize|no-repeat|no-drop|newspaper|ne-resize|n-resize|move|middle|medium|ltr|lr-tb|lowercase|lower-roman|lower-alpha|loose|list-item|line|line-through|line-edge|lighter|left|keep-all|justify|italic|inter-word|inter-ideograph|inside|inset|inline|inline-block|inherit|inactive|ideograph-space|ideograph-parenthesis|ideograph-numeric|ideograph-alpha|horizontal|hidden|help|hand|groove|fixed|ellipsis|e-resize|double|dotted|distribute|distribute-space|distribute-letter|distribute-all-lines|disc|disabled|default|decimal|dashed|crosshair|collapse|col-resize|circle|char|center|capitalize|break-word|break-all|bottom|both|bolder|bold|block|bidi-override|below|baseline|auto|always|all-scroll|absolute|table|table-cell)\\b"},{begin:/:/,end:/[;}{]/,relevance:0,contains:[n.BLOCK_COMMENT,a,n.HEXCOLOR,n.CSS_NUMBER_MODE,e.QUOTE_STRING_MODE,e.APOS_STRING_MODE,n.IMPORTANT,n.FUNCTION_DISPATCH]},{begin:"@(page|font-face)",keywords:{$pattern:t,keyword:"@page @font-face"}},{begin:"@",end:"[{;]",returnBegin:!0,keywords:{$pattern:/[a-z-]+/,keyword:"and or not only",attribute:J.join(" ")},contains:[{begin:t,className:"keyword"},{begin:/[a-z-]+(?=:)/,className:"attribute"},a,e.QUOTE_STRING_MODE,e.APOS_STRING_MODE,n.HEXCOLOR,n.CSS_NUMBER_MODE]},n.FUNCTION_DISPATCH]}},grmr_shell:e=>({name:"Shell Session",aliases:["console","shellsession"],contains:[{className:"meta.prompt",begin:/^\s{0,3}[/~\w\d[\]()@-]*[>%$#][ ]?/,starts:{end:/[^\\](?=\s*$)/,subLanguage:"bash"}}]}),grmr_sql(e){let n=e.regex,t=e.COMMENT("--","$"),a=["true","false","unknown"],i=["bigint","binary","blob","boolean","char","character","clob","date","dec","decfloat","decimal","float","int","integer","interval","nchar","nclob","national","numeric","real","row","smallint","time","timestamp","varchar","varying","varbinary"],r=["abs","acos","array_agg","asin","atan","avg","cast","ceil","ceiling","coalesce","corr","cos","cosh","count","covar_pop","covar_samp","cume_dist","dense_rank","deref","element","exp","extract","first_value","floor","json_array","json_arrayagg","json_exists","json_object","json_objectagg","json_query","json_table","json_table_primitive","json_value","lag","last_value","lead","listagg","ln","log","log10","lower","max","min","mod","nth_value","ntile","nullif","percent_rank","percentile_cont","percentile_disc","position","position_regex","power","rank","regr_avgx","regr_avgy","regr_count","regr_intercept","regr_r2","regr_slope","regr_sxx","regr_sxy","regr_syy","row_number","sin","sinh","sqrt","stddev_pop","stddev_samp","substring","substring_regex","sum","tan","tanh","translate","translate_regex","treat","trim","trim_array","unnest","upper","value_of","var_pop","var_samp","width_bucket"],s=["create table","insert into","primary key","foreign key","not null","alter table","add constraint","grouping sets","on overflow","character set","respect nulls","ignore nulls","nulls first","nulls last","depth first","breadth first"],o=r,l=["abs","acos","all","allocate","alter","and","any","are","array","array_agg","array_max_cardinality","as","asensitive","asin","asymmetric","at","atan","atomic","authorization","avg","begin","begin_frame","begin_partition","between","bigint","binary","blob","boolean","both","by","call","called","cardinality","cascaded","case","cast","ceil","ceiling","char","char_length","character","character_length","check","classifier","clob","close","coalesce","collate","collect","column","commit","condition","connect","constraint","contains","convert","copy","corr","corresponding","cos","cosh","count","covar_pop","covar_samp","create","cross","cube","cume_dist","current","current_catalog","current_date","current_default_transform_group","current_path","current_role","current_row","current_schema","current_time","current_timestamp","current_path","current_role","current_transform_group_for_type","current_user","cursor","cycle","date","day","deallocate","dec","decimal","decfloat","declare","default","define","delete","dense_rank","deref","describe","deterministic","disconnect","distinct","double","drop","dynamic","each","element","else","empty","end","end_frame","end_partition","end-exec","equals","escape","every","except","exec","execute","exists","exp","external","extract","false","fetch","filter","first_value","float","floor","for","foreign","frame_row","free","from","full","function","fusion","get","global","grant","group","grouping","groups","having","hold","hour","identity","in","indicator","initial","inner","inout","insensitive","insert","int","integer","intersect","intersection","interval","into","is","join","json_array","json_arrayagg","json_exists","json_object","json_objectagg","json_query","json_table","json_table_primitive","json_value","lag","language","large","last_value","lateral","lead","leading","left","like","like_regex","listagg","ln","local","localtime","localtimestamp","log","log10","lower","match","match_number","match_recognize","matches","max","member","merge","method","min","minute","mod","modifies","module","month","multiset","national","natural","nchar","nclob","new","no","none","normalize","not","nth_value","ntile","null","nullif","numeric","octet_length","occurrences_regex","of","offset","old","omit","on","one","only","open","or","order","out","outer","over","overlaps","overlay","parameter","partition","pattern","per","percent","percent_rank","percentile_cont","percentile_disc","period","portion","position","position_regex","power","precedes","precision","prepare","primary","procedure","ptf","range","rank","reads","real","recursive","ref","references","referencing","regr_avgx","regr_avgy","regr_count","regr_intercept","regr_r2","regr_slope","regr_sxx","regr_sxy","regr_syy","release","result","return","returns","revoke","right","rollback","rollup","row","row_number","rows","running","savepoint","scope","scroll","search","second","seek","select","sensitive","session_user","set","show","similar","sin","sinh","skip","smallint","some","specific","specifictype","sql","sqlexception","sqlstate","sqlwarning","sqrt","start","static","stddev_pop","stddev_samp","submultiset","subset","substring","substring_regex","succeeds","sum","symmetric","system","system_time","system_user","table","tablesample","tan","tanh","then","time","timestamp","timezone_hour","timezone_minute","to","trailing","translate","translate_regex","translation","treat","trigger","trim","trim_array","true","truncate","uescape","union","unique","unknown","unnest","update","upper","user","using","value","values","value_of","var_pop","var_samp","varbinary","varchar","varying","versioning","when","whenever","where","width_bucket","window","with","within","without","year","add","asc","collation","desc","final","first","last","view"].filter(e=>!r.includes(e)),c={begin:n.concat(/\b/,n.either(...o),/\s*\(/),relevance:0,keywords:{built_in:o}};return{name:"SQL",case_insensitive:!0,illegal:/[{}]|<\//,keywords:{$pattern:/\b[\w\.]+/,keyword:((e,{exceptions:n,when:t}={})=>{let a=t;return n=n||[],e.map(e=>e.match(/\|\d+$/)||n.includes(e)?e:a(e)?e+"|0":e)})(l,{when:e=>e.length<3}),literal:a,type:i,built_in:["current_catalog","current_date","current_default_transform_group","current_path","current_role","current_schema","current_transform_group_for_type","current_user","session_user","system_time","system_user","current_time","localtime","current_timestamp","localtimestamp"]},contains:[{begin:n.either(...s),relevance:0,keywords:{$pattern:/[\w\.]+/,keyword:l.concat(s),literal:a,type:i}},{className:"type",begin:n.either("double precision","large object","with timezone","without timezone")},c,{className:"variable",begin:/@[a-z0-9][a-z0-9_]*/},{className:"string",variants:[{begin:/'/,end:/'/,contains:[{begin:/''/}]}]},{begin:/"/,end:/"/,contains:[{begin:/""/}]},e.C_NUMBER_MODE,e.C_BLOCK_COMMENT_MODE,t,{className:"operator",begin:/[-+*/=%^~]|&&?|\|\|?|!=?|<(?:=>?|<|>)?|>[>=]?/,relevance:0}]}},grmr_swift(e){let n={match:/\s+/,relevance:0},t=e.COMMENT("/\\*","\\*/",{contains:["self"]}),a=[e.C_LINE_COMMENT_MODE,t],i={match:[/\./,m(...eh,...ef)],className:{2:"keyword"}},r={match:b(/\./,m(...e$)),relevance:0},s=e$.filter(e=>"string"==typeof e).concat(["_|0"]),o={variants:[{className:"keyword",match:m(...e$.filter(e=>"string"!=typeof e).concat(eE).map(e8),...ef)}]},l={$pattern:m(/\b\w+/,/#\w+/),keyword:s.concat(ew),literal:ey},c=[i,r,o],g=[{match:b(/\./,m(...ev)),relevance:0},{className:"built_in",match:b(/\b/,m(...ev),/(?=\()/)}],u={match:/->/,relevance:0},p=[u,{className:"operator",relevance:0,variants:[{match:eM},{match:`\\.(\\.|${ex})+`}]}],h="([0-9]_*)+",f="([0-9a-fA-F]_*)+",E={className:"number",relevance:0,variants:[{match:`\\b(${h})(\\.(${h}))?([eE][+-]?(${h}))?\\b`},{match:`\\b0x(${f})(\\.(${f}))?([pP][+-]?(${h}))?\\b`},{match:/\b0o([0-7]_*)+\b/},{match:/\b0b([01]_*)+\b/}]},$=(e="")=>({className:"subst",variants:[{match:b(/\\/,e,/[0\\tnr"']/)},{match:b(/\\/,e,/u\{[0-9a-fA-F]{1,8}\}/)}]}),y=(e="")=>({className:"subst",match:b(/\\/,e,/[\t ]*(?:[\r\n]|\r\n)/)}),N=(e="")=>({className:"subst",label:"interpol",begin:b(/\\/,e,/\(/),end:/\)/}),w=(e="")=>({begin:b(e,/"""/),end:b(/"""/,e),contains:[$(e),y(e),N(e)]}),v=(e="")=>({begin:b(e,/"/),end:b(/"/,e),contains:[$(e),N(e)]}),k={className:"string",variants:[w(),w("#"),w("##"),w("###"),v(),v("#"),v("##"),v("###")]},x=[e.BACKSLASH_ESCAPE,{begin:/\[/,end:/\]/,relevance:0,contains:[e.BACKSLASH_ESCAPE]}],M=e=>{let n=b(e,/\//),t=b(/\//,e);return{begin:n,end:t,contains:[...x,{scope:"comment",begin:`#(?!.*${t})`,end:/$/}]}},O={scope:"regexp",variants:[M("###"),M("##"),M("#"),{begin:/\/[^\s](?=[^/\n]*\/)/,end:/\//,contains:x}]},S={match:b(/`/,eA,/`/)},A=[S,{className:"variable",match:/\$\d+/},{className:"variable",match:`\\$${eS}+`}],C=[{match:/(@|#(un)?)available/,scope:"keyword",starts:{contains:[{begin:/\(/,end:/\)/,keywords:eR,contains:[...p,E,k]}]}},{scope:"keyword",match:b(/@/,m(...eT))},{scope:"meta",match:b(/@/,eA)}],T={match:d(/\b[A-Z]/),relevance:0,contains:[{className:"type",match:b(/(AV|CA|CF|CG|CI|CL|CM|CN|CT|MK|MP|MTK|MTL|NS|SCN|SK|UI|WK|XC)/,eS,"+")},{className:"type",match:eC,relevance:0},{match:/[?!]+/,relevance:0},{match:/\.\.\./,relevance:0},{match:b(/\s+&\s+/,d(eC)),relevance:0}]};T.contains.push({begin:/</,end:/>/,keywords:l,contains:[...a,...c,...C,u,T]});let R={begin:/\(/,end:/\)/,relevance:0,keywords:l,contains:["self",{match:b(eA,/\s*:/),keywords:"_|0",relevance:0},...a,O,...c,...g,...p,E,k,...A,...C,T]},D={begin:/</,end:/>/,keywords:"repeat each",contains:[...a,T]},I={begin:/\(/,end:/\)/,keywords:l,contains:[{begin:m(d(b(eA,/\s*:/)),d(b(eA,/\s+/,eA,/\s*:/))),end:/:/,relevance:0,contains:[{className:"keyword",match:/\b_\b/},{className:"params",match:eA}]},...a,...c,...p,E,k,...C,T,R],endsParent:!0,illegal:/["']/},L={match:[/(func|macro)/,/\s+/,m(S.match,eA,eM)],className:{1:"keyword",3:"title.function"},contains:[D,I,n],illegal:[/\[/,/%/]};for(let B of k.variants){let _=B.contains.find(e=>"interpol"===e.label);_.keywords=l;let z=[...c,...g,...p,E,k,...A];_.contains=[...z,{begin:/\(/,end:/\)/,contains:["self",...z]}]}return{name:"Swift",keywords:l,contains:[...a,L,{match:[/\b(?:subscript|init[?!]?)/,/\s*(?=[<(])/],className:{1:"keyword"},contains:[D,I,n],illegal:/\[|%/},{beginKeywords:"struct protocol class extension enum actor",end:"\\{",excludeEnd:!0,keywords:l,contains:[e.inherit(e.TITLE_MODE,{className:"title.class",begin:/[A-Za-z$_][\u00C0-\u02B80-9A-Za-z$_]*/}),...c]},{match:[/operator/,/\s+/,eM],className:{1:"keyword",3:"title"}},{begin:[/precedencegroup/,/\s+/,eC],className:{1:"keyword",3:"title"},contains:[T],keywords:[...eN,...ey],end:/}/},{beginKeywords:"import",end:/$/,contains:[...a],relevance:0},O,...c,...g,...p,E,k,...A,...C,T,R]}},grmr_typescript(e){let n=ep(e),t=["any","void","number","boolean","string","object","never","symbol","bigint","unknown"],a={beginKeywords:"namespace",end:/\{/,excludeEnd:!0,contains:[n.exports.CLASS_REFERENCE]},i={beginKeywords:"interface",end:/\{/,excludeEnd:!0,keywords:{keyword:"interface extends",built_in:t},contains:[n.exports.CLASS_REFERENCE]},r={$pattern:eo,keyword:el.concat(["type","namespace","interface","public","private","protected","implements","declare","abstract","readonly","enum","override"]),literal:ec,built_in:em.concat(t),"variable.language":eb},s={className:"meta",begin:"@"+eo},o=(e,n,t)=>{let a=e.contains.findIndex(e=>e.label===n);if(-1===a)throw Error("can not find mode to replace");e.contains.splice(a,1,t)};return Object.assign(n.keywords,r),n.exports.PARAMS_CONTAINS.push(s),n.contains=n.contains.concat([s,a,i]),o(n,"shebang",e.SHEBANG()),o(n,"use_strict",{className:"meta",relevance:10,begin:/^\s*['"]use strict['"]/}),n.contains.find(e=>"func.def"===e.label).relevance=0,Object.assign(n,{name:"TypeScript",aliases:["ts","tsx","mts","cts"]}),n},grmr_vbnet(e){let n=e.regex,t=/\d{1,2}\/\d{1,2}\/\d{4}/,a=/\d{4}-\d{1,2}-\d{1,2}/,i=/(\d|1[012])(:\d+){0,2} *(AM|PM)/,r=/\d{1,2}(:\d{1,2}){1,2}/,s={className:"literal",variants:[{begin:n.concat(/# */,n.either(a,t),/ *#/)},{begin:n.concat(/# */,r,/ *#/)},{begin:n.concat(/# */,i,/ *#/)},{begin:n.concat(/# */,n.either(a,t),/ +/,n.either(i,r),/ *#/)}]},o=e.COMMENT(/'''/,/$/,{contains:[{className:"doctag",begin:/<\/?/,end:/>/}]}),l=e.COMMENT(null,/$/,{variants:[{begin:/'/},{begin:/([\t ]|^)REM(?=\s)/}]});return{name:"Visual Basic .NET",aliases:["vb"],case_insensitive:!0,classNameAliases:{label:"symbol"},keywords:{keyword:"addhandler alias aggregate ansi as async assembly auto binary by byref byval call case catch class compare const continue custom declare default delegate dim distinct do each equals else elseif end enum erase error event exit explicit finally for friend from function get global goto group handles if implements imports in inherits interface into iterator join key let lib loop me mid module mustinherit mustoverride mybase myclass namespace narrowing new next notinheritable notoverridable of off on operator option optional order overloads overridable overrides paramarray partial preserve private property protected public raiseevent readonly redim removehandler resume return select set shadows shared skip static step stop structure strict sub synclock take text then throw to try unicode until using when where while widening with withevents writeonly yield",built_in:"addressof and andalso await directcast gettype getxmlnamespace is isfalse isnot istrue like mod nameof new not or orelse trycast typeof xor cbool cbyte cchar cdate cdbl cdec cint clng cobj csbyte cshort csng cstr cuint culng cushort",type:"boolean byte char date decimal double integer long object sbyte short single string uinteger ulong ushort",literal:"true false nothing"},illegal:"//|\\{|\\}|endif|gosub|variant|wend|^\\$ ",contains:[{className:"string",begin:/"(""|[^/n])"C\b/},{className:"string",begin:/"/,end:/"/,illegal:/\n/,contains:[{begin:/""/}]},s,{className:"number",relevance:0,variants:[{begin:/\b\d[\d_]*((\.[\d_]+(E[+-]?[\d_]+)?)|(E[+-]?[\d_]+))[RFD@!#]?/},{begin:/\b\d[\d_]*((U?[SIL])|[%&])?/},{begin:/&H[\dA-F_]+((U?[SIL])|[%&])?/},{begin:/&O[0-7_]+((U?[SIL])|[%&])?/},{begin:/&B[01_]+((U?[SIL])|[%&])?/}]},{className:"label",begin:/^\w+:/},o,l,{className:"meta",begin:/[\t ]*#(const|disable|else|elseif|enable|end|externalsource|if|region)\b/,end:/$/,keywords:{keyword:"const disable else elseif enable end externalsource if region then"},contains:[l]}]}},grmr_wasm(e){e.regex;let n=e.COMMENT(/\(;/,/;\)/);return n.contains.push("self"),{name:"WebAssembly",keywords:{$pattern:/[\w.]+/,keyword:["anyfunc","block","br","br_if","br_table","call","call_indirect","data","drop","elem","else","end","export","func","global.get","global.set","local.get","local.set","local.tee","get_global","get_local","global","if","import","local","loop","memory","memory.grow","memory.size","module","mut","nop","offset","param","result","return","select","set_global","set_local","start","table","tee_local","then","type","unreachable"]},contains:[e.COMMENT(/;;/,/$/),n,{match:[/(?:offset|align)/,/\s*/,/=/],className:{1:"keyword",3:"operator"}},{className:"variable",begin:/\$[\w_]+/},{match:/(\((?!;)|\))+/,className:"punctuation",relevance:0},{begin:[/(?:func|call|call_indirect)/,/\s+/,/\$[^\s)]+/],className:{1:"keyword",3:"title.function"}},e.QUOTE_STRING_MODE,{match:/(i32|i64|f32|f64)(?!\.)/,className:"type"},{className:"keyword",match:/\b(f32|f64|i32|i64)(?:\.(?:abs|add|and|ceil|clz|const|convert_[su]\/i(?:32|64)|copysign|ctz|demote\/f64|div(?:_[su])?|eqz?|extend_[su]\/i32|floor|ge(?:_[su])?|gt(?:_[su])?|le(?:_[su])?|load(?:(?:8|16|32)_[su])?|lt(?:_[su])?|max|min|mul|nearest|neg?|or|popcnt|promote\/f32|reinterpret\/[fi](?:32|64)|rem_[su]|rot[lr]|shl|shr_[su]|store(?:8|16|32)?|sqrt|sub|trunc(?:_[su]\/f(?:32|64))?|wrap\/i64|xor))\b/},{className:"number",relevance:0,match:/[+-]?\b(?:\d(?:_?\d)*(?:\.\d(?:_?\d)*)?(?:[eE][+-]?\d(?:_?\d)*)?|0x[\da-fA-F](?:_?[\da-fA-F])*(?:\.[\da-fA-F](?:_?[\da-fA-D])*)?(?:[pP][+-]?\d(?:_?\d)*)?)\b|\binf\b|\bnan(?::0x[\da-fA-F](?:_?[\da-fA-D])*)?\b/}]}},grmr_xml(e){let n=e.regex,t=n.concat(/[\p{L}_]/u,n.optional(/[\p{L}0-9_.-]*:/u),/[\p{L}0-9_.-]*/u),a={className:"symbol",begin:/&[a-z]+;|&#[0-9]+;|&#x[a-f0-9]+;/},i={begin:/\s/,contains:[{className:"keyword",begin:/#?[a-z_][a-z1-9_-]+/,illegal:/\n/}]},r=e.inherit(i,{begin:/\(/,end:/\)/}),s=e.inherit(e.APOS_STRING_MODE,{className:"string"}),o=e.inherit(e.QUOTE_STRING_MODE,{className:"string"}),l={endsWithParent:!0,illegal:/</,relevance:0,contains:[{className:"attr",begin:/[\p{L}0-9._:-]+/u,relevance:0},{begin:/=\s*/,relevance:0,contains:[{className:"string",endsParent:!0,variants:[{begin:/"/,end:/"/,contains:[a]},{begin:/'/,end:/'/,contains:[a]},{begin:/[^\s"'=<>`]+/}]}]}]};return{name:"HTML, XML",aliases:["html","xhtml","rss","atom","xjb","xsd","xsl","plist","wsf","svg"],case_insensitive:!0,unicodeRegex:!0,contains:[{className:"meta",begin:/<![a-z]/,end:/>/,relevance:10,contains:[i,o,s,r,{begin:/\[/,end:/\]/,contains:[{className:"meta",begin:/<![a-z]/,end:/>/,contains:[i,r,o,s]}]}]},e.COMMENT(/<!--/,/-->/,{relevance:10}),{begin:/<!\[CDATA\[/,end:/\]\]>/,relevance:10},a,{className:"meta",end:/\?>/,variants:[{begin:/<\?xml/,relevance:10,contains:[o]},{begin:/<\?[a-z][a-z0-9]+/}]},{className:"tag",begin:/<style(?=\s|>)/,end:/>/,keywords:{name:"style"},contains:[l],starts:{end:/<\/style>/,returnEnd:!0,subLanguage:["css","xml"]}},{className:"tag",begin:/<script(?=\s|>)/,end:/>/,keywords:{name:"script"},contains:[l],starts:{end:/<\/script>/,returnEnd:!0,subLanguage:["javascript","handlebars","xml"]}},{className:"tag",begin:/<>|<\/>/},{className:"tag",begin:n.concat(/</,n.lookahead(n.concat(t,n.either(/\/>/,/>/,/\s/)))),end:/\/?>/,contains:[{className:"name",begin:t,relevance:0,starts:l}]},{className:"tag",begin:n.concat(/<\//,n.lookahead(n.concat(t,/>/))),contains:[{className:"name",begin:t,relevance:0},{begin:/>/,relevance:0,endsParent:!0}]}]}},grmr_yaml(e){let n="true false yes no null",t="[\\w#;/?:@&=+$,.~*'()[\\]]+",a={className:"string",relevance:0,variants:[{begin:/'/,end:/'/},{begin:/"/,end:/"/},{begin:/\S+/}],contains:[e.BACKSLASH_ESCAPE,{className:"template-variable",variants:[{begin:/\{\{/,end:/\}\}/},{begin:/%\{/,end:/\}/}]}]},i=e.inherit(a,{variants:[{begin:/'/,end:/'/},{begin:/"/,end:/"/},{begin:/[^\s,{}[\]]+/}]}),r={end:",",endsWithParent:!0,excludeEnd:!0,keywords:n,relevance:0},s=[{className:"attr",variants:[{begin:"\\w[\\w :\\/.-]*:(?=[ 	]|$)"},{begin:'"\\w[\\w :\\/.-]*":(?=[ 	]|$)'},{begin:"'\\w[\\w :\\/.-]*':(?=[ 	]|$)"}]},{className:"meta",begin:"^---\\s*$",relevance:10},{className:"string",begin:"[\\|>]([1-9]?[+-])?[ ]*\\n( +)[^ ][^\\n]*\\n(\\2[^\\n]+\\n?)*"},{begin:"<%[%=-]?",end:"[%-]?%>",subLanguage:"ruby",excludeBegin:!0,excludeEnd:!0,relevance:0},{className:"type",begin:"!\\w+!"+t},{className:"type",begin:"!<"+t+">"},{className:"type",begin:"!"+t},{className:"type",begin:"!!"+t},{className:"meta",begin:"&"+e.UNDERSCORE_IDENT_RE+"$"},{className:"meta",begin:"\\*"+e.UNDERSCORE_IDENT_RE+"$"},{className:"bullet",begin:"-(?=[ ]|$)",relevance:0},e.HASH_COMMENT_MODE,{beginKeywords:n,keywords:{literal:n}},{className:"number",begin:"\\b[0-9]{4}(-[0-9][0-9]){0,2}([Tt \\t][0-9][0-9]?(:[0-9][0-9]){2})?(\\.[0-9]*)?([ \\t])*(Z|[-+][0-9][0-9]?(:[0-9][0-9])?)?\\b"},{className:"number",begin:e.C_NUMBER_RE+"\\b",relevance:0},{begin:/\{/,end:/\}/,contains:[r],illegal:"\\n",relevance:0},{begin:"\\[",end:"\\]",contains:[r],illegal:"\\n",relevance:0},a],o=[...s];return o.pop(),o.push(i),r.contains=o,{name:"YAML",case_insensitive:!0,aliases:["yml"],contains:s}}});let eI=Q;for(let eL of Object.keys(eD)){let eB=eL.replace("grmr_","").replace("_","-");eI.registerLanguage(eB,eD[eL])}return eI}();"object"==typeof exports&&"undefined"!=typeof module&&(module.exports=hljs);
hljs.highlightAll(); /*]]>*/</script></b:if>
  
  <!--[ Schema.org WebSite ]-->
  <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;name&quot;:&quot;<data:view.title.escaped/>&quot;,&quot;url&quot;:&quot;<data:view.url.canonical/>&quot;,&quot;potentialAction&quot;:{&quot;@type&quot;:&quot;SearchAction&quot;,&quot;target&quot;:&quot;<data:view.url.canonical/>search?q={search_term_string}&quot;,&quot;query-input&quot;:&quot;required name=search_term_string&quot;}}</script>
  
  <!--[ </head> close ]-->
  &lt;!--<head/><b:if cond='!data:blog.adsenseClientId'>--&gt;&lt;/head&gt;</b:if>
  <body>
    
    <!--[ Header ]-->
    <div class='minWb'>
      <header class='hdr'>
        <div class='hdrMax'>
          
          <!--[ Header Name ]-->
          <b:section id='Header: Name'>
            <b:widget id='Header1' locked='false' title='UltraSpeed (Header)' type='Header' version='2' visible='true'>
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
              <div class='hdrTtl'>
                <b:if cond='!data:view.isHomepage'>
                  <h1><a expr:href='data:blog.homepageUrl'><data:title/></a></h1>
                  <b:else/>
                  <h1><data:title/></h1>
                </b:if>
              </div>
            </b:includable>
              <b:includable id='behindImageStyle'/>
              <b:includable id='description'/>
              <b:includable id='image'/>
              <b:includable id='title'/>
            </b:widget>
          </b:section>
          
          <!--[ Header Menu ]-->
          <b:section id='Header: Menu'>
            <b:widget id='HTML1' locked='false' title='Menu' type='HTML' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='content'><![CDATA[<!-- Edit in HTML -->]]></b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
              <input class='mChckBx hide' id='hdrMenu' type='checkbox'/>
              <div class='hdrMnu'>
                <label class='mnuClose' for='hdrMenu'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M19 5L5 19M5 5L19 19'/></svg></label>
                
                <ul class='mnuHeader'>
                  
                  <b:if cond='!data:view.isHomepage'>
                    <li>
                      <a class='hdrMnuLst' expr:href='data:blog.homepageUrl'>
                        <svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M9 22L9.00335 16L15 16V22'/><path d='M19.5016 22L22.0017 9L12.0017 2L2 9L4.50161 22H19.5016Z'/></svg> <data:messages.home/>
                      </a>
                    </li>
                  </b:if>
                  
                  
                  <li class='nxt'>
                    <span class='hdrMnuLst hdrIC'>
                      <svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M3 3V21L21 21V3H3Z'/><path d='M3 9H21'/><path d='M12 13H18M12 17H15'/><path d='M7 6H7.00898M11 6H11.009'/><path d='M9 9V21'/></svg> Pages
                    </span>
                    <ul class='hdrMnuDrpdwn'>
                      <li><a class='hdrMnuLst' href='/search'>Archive Page</a></li>
                      <li><a class='hdrMnuLst' href='/search/label/Blogger'>Label Page</a></li>
                      <li><a class='hdrMnuLst' href='/search?q='>Search Page</a></li>
                      <li><a class='hdrMnuLst' href='/404'>Error Page</a></li>
                    </ul>
                  </li>
                  
                  <li>
                    <span class='hdrMnuLst hdrIC'>
                      <svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M5 6.32759H7.7M11 6.32759H9.5M7.7 6.32759H9.5M7.7 6.32759V4.5M9.5 6.32759C9.18351 7.45937 8.52075 8.52923 7.76429 9.46946M5.83571 11.5C6.44723 10.9377 7.13788 10.248 7.76429 9.46946M7.76429 9.46946C7.37857 9.01724 6.83857 8.28558 6.68429 7.95455M7.76429 9.46946L8.92143 10.6724'/><path d='M13.5 19.5L14.3333 17M18.5 19.5L17.6667 17M14.3333 17L15.5 13.5H16.5L17.6667 17M14.3333 17H17.6667'/><path d='M14 10V2H2V14H10'/><path d='M22 22V10H14L10 14V22L22 22Z'/><path d='M20 7.5L19.9999 4L16.5 4'/><path d='M3.9999 16.5L4 20H7.4999'/></svg> Direction
                    </span>
                    <ul class='hdrMnuDrpdwn'>
                      <li><a class='hdrMnuLst' href='?hl=en'>LTR</a></li>
                      <li><a class='hdrMnuLst' href='?hl=ar'>RTL</a></li>
                    </ul>
                  </li>
                  
                  <li>
                    <a class='hdrMnuLst' href='https://Farhat.top'>
                      <svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M12 14.5L12 4.5M12 14.5L9 11.4998M12 14.5L15 11.4998'/><path d='M20 16.5L19 19.5H5L4 16.5'/></svg> Download this template
                    </a>
                  </li>
                </ul>
              </div>
            </b:includable>
            </b:widget>
          </b:section>
          
          <!--[ Header Icons ]-->
          <div class='hdrIcns'>
          <b:section id='Header: Icons'>
            <b:widget id='TextList1' locked='false' title='Icons' type='TextList' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='shownum'/>
                <b:widget-setting name='sorting'>NONE</b:widget-setting>
                <b:widget-setting name='item-1'>Menu</b:widget-setting>
                <b:widget-setting name='item-0'>Search</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
                <b:include name='content'/>
              </b:includable>
              <b:includable id='content'>
                <b:loop values='data:items' var='item'>
                  <b:if cond='data:item == &quot;Search&quot;'>
                    <label class='hdrSearch' for='hdrSearch'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M17.5 17.5L22 22'/><path d='M20 11C20 6.02944 15.9706 2 11 2C6.02944 2 2 6.02944 2 11C2 15.9706 6.02944 20 11 20C15.9706 20 20 15.9706 20 11Z'/></svg></label>
                    
                    <b:elseif cond='data:item == &quot;Menu&quot;'/>
                    <label class='hdrMenu' for='hdrMenu'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M4 8.5L20 8.5'/><path d='M4 15.5L20 15.5'/></svg></label>
                  </b:if>
                </b:loop>
              </b:includable>
            </b:widget>
          </b:section>
        </div>
          
        <!--[ Header Search ]-->
        <input class='srchChckBx hide' id='hdrSearch' type='checkbox'/>
        <div class='hdrSrchR'>
          <div class='hdrsrchCls'>
            <label class='hdrSearch' for='hdrSearch'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M19 5L5 19M5 5L19 19'/></svg></label>
          </div>
          <div class='hdrsrchBdy'>
            <div class='di'>
              <form action='/search' class='search-form' method='get' role='search'>
                <label class='screen-reader-text' for='search-form-2'>Search</label>
                <input class='search-field' expr:placeholder='data:messages.searchThisBlog' expr:value='data:view.search.query' id='search-form-2' name='q' oninput='this.setCustomValidity(&quot;&quot;)' oninvalid='this.setCustomValidity(&quot;&quot;)' required='' type='search'/>
                <button class='search-submit btn' title='Search' type='submit' value=''><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M17.5 17.5L22 22'/><path d='M20 11C20 6.02944 15.9706 2 11 2C6.02944 2 2 6.02944 2 11C2 15.9706 6.02944 20 11 20C15.9706 20 20 15.9706 20 11Z'/></svg></button>
              </form>
            </div>
          </div>
        </div>
        </div>
      </header>
      
      <!--[ Fixed Post ]-->
      <b:section id='Fixed Post'>
        <b:widget cond='data:view.isHomepage' id='FeaturedPost1' locked='false' title='Fixed Post' type='FeaturedPost' version='2' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='showSnippet'>true</b:widget-setting>
            <b:widget-setting name='showPostTitle'>true</b:widget-setting>
            <b:widget-setting name='postId'>0</b:widget-setting>
            <b:widget-setting name='showFirstImage'>true</b:widget-setting>
            <b:widget-setting name='useMostRecentPost'>true</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main' var='this'>
            <div role='feed'>
              
              <!-- Don't render the post that we're currently already looking at. -->
              <b:loop values='data:posts filter (p =&gt; p.id != data:view.postId)' var='post'>
                <article class='post' role='article'>
                  <div class='hroFxdPst'>
                    <figure class='fxdPst'>
                      <b:if cond='data:post.featuredImage'>
                        <img class='fxdPstImg lazyload' expr:alt='data:post.title' expr:data-src='data:post.featuredImage' expr:title='data:post.title' height='720' src='data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==' width='1280'/>
                        <b:else/>
                        <img class='fxdPstImg lazyload' data-src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEh-A3Fz4T-QNjIkUipAj3b9i_PGGXW4b9DJnyKDBVrDanUj4dg69yauY7PMsMqPWznnl2BuQ7iQtqfboIKQQm_vVsTFXjH_ifigorE-5SpwTqUajxWE_Z92Avu_P3a7BZgm0pokj8r7DUtfDBJJt1G1CPotR6mzv7-35LhZRoxZw2h8T2mCBofffSsoXu9P/s1280/404.webp' expr:alt='data:post.title' expr:title='data:post.title' height='720' src='data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==' width='1280'/>
                      </b:if>
                      <figcaption class='fxdPstDsc'>
                        <div class='fxdPstMta'>
                          <b:if cond='data:post.author.name'><data:post.author.name/><b:else/>Admin</b:if>
                          <span class='space'>&#8231;</span>
                          <time class='time' expr:datetime='data:post.date.iso8601' id='timeAgoR'/>
                        </div>
                        <b:if cond='data:post.title'>
                          <h2><a class='fxdPstTtl' expr:href='data:post.url' expr:title='data:post.title'><b:eval expr='snippet(data:post.title, {length: 66, links: false, linebreaks: false})'/></a></h2>
                          <b:else/>
                          <h2><a class='fxdPstTtl' expr:href='data:post.url' title='No Title'>No Title</a></h2>
                        </b:if>
                        <b:if cond='data:post.body'><p class='fxdPstTxt'><b:eval expr='snippet(data:post.body, {length: 60, links: false, linebreaks: false})'/></p></b:if>
                        <b:if cond='data:post.labels'>
                          <div class='fxdPstTgs'>
                            <ul class='listTgs'>
                              <b:loop values='data:post.labels' var='label'>
                                <li><a class='tgs' expr:href='data:label.url'><data:label.name/></a></li>
                              </b:loop>
                            </ul>
                          </div>
                        </b:if>
                      </figcaption>
                    </figure>
                  </div>
                </article>
              </b:loop>
            </div>
          </b:includable>
          <b:includable id='blogThisShare'/>
          <b:includable id='bylineByName' var='byline'/>
          <b:includable id='bylineRegion' var='regionItems'/>
          <b:includable id='commentsLink'/>
          <b:includable id='commentsLinkIframe'/>
          <b:includable id='emailPostIcon'/>
          <b:includable id='facebookShare'/>
          <b:includable id='footerBylines'/>
          <b:includable id='googlePlusShare'/>
          <b:includable id='headerByline'/>
          <b:includable id='linkShare'/>
          <b:includable id='otherSharingButton'/>
          <b:includable id='platformShare'/>
          <b:includable id='postAuthor'/>
          <b:includable id='postCommentsLink'/>
          <b:includable id='postJumpLink' var='post'/>
          <b:includable id='postLabels'/>
          <b:includable id='postLocation'/>
          <b:includable id='postReactions'/>
          <b:includable id='postShareButtons'/>
          <b:includable id='postTimestamp'/>
          <b:includable id='sharingButton'/>
          <b:includable id='sharingButtonContent'/>
          <b:includable id='sharingButtons'/>
          <b:includable id='sharingButtonsMenu'/>
          <b:includable id='sharingPlatformIcon'/>
          <b:includable id='snippetedPostByline'/>
          <b:includable id='snippetedPostContent'/>
          <b:includable id='snippetedPostThumbnail'/>
          <b:includable id='snippetedPostTitle'/>
          <b:includable id='snippetedPosts'/>
        </b:widget>
      </b:section>
      
      <!--[ Blog Post ]-->
      <div class='blgMinConrt'>
        <div class='bMPPosts'>
          <b:section id='Blog' showaddelement='true'>
            <b:widget id='HTML5' locked='false' title='Ads before Post' type='HTML' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='content'/>
              </b:widget-settings>
              <b:includable id='main'>
                <center>
                  <b:if cond='data:view.isPost'>
                    <b:if cond='data:content == &quot;&quot;'>
                      <div style='width: 100%;display: flex;align-items: center;justify-content: center;background-color: var(--gray-2);color: var(--gray-9);text-align: center;height: 100px;'><b:message name='messages.adsGoHere'/></div>
                      <b:else/>
                      <data:content/>
                    </b:if>
                  </b:if>
                </center><br/>
              </b:includable>
            </b:widget>
            <b:widget id='HTML8' locked='false' title='Ads In Before Post Body' type='HTML' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='content'/>
              </b:widget-settings>
              <b:includable id='main'>
                <center>
                  <b:if cond='data:view.isPost'>
                    <b:if cond='data:content == &quot;&quot;'>
                      <div style='width: 100%;display: flex;align-items: center;justify-content: center;background-color: var(--gray-2);color: var(--gray-9);text-align: center;height: 100px;'><b:message name='messages.adsGoHere'/></div>
                      <b:else/>
                      <data:content/>
                    </b:if>
                  </b:if>
                </center><br/>
              </b:includable>
            </b:widget>
            <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='showDateHeader'>false</b:widget-setting>
                <b:widget-setting name='style.textcolor'>#ffffff</b:widget-setting>
                <b:widget-setting name='showShareButtons'>true</b:widget-setting>
                <b:widget-setting name='showCommentLink'>true</b:widget-setting>
                <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
                <b:widget-setting name='showAuthor'>true</b:widget-setting>
                <b:widget-setting name='style.linkcolor'>#ffffff</b:widget-setting>
                <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                <b:widget-setting name='reactionsLabel'/>
                <b:widget-setting name='showAuthorProfile'>true</b:widget-setting>
                <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                <b:widget-setting name='showLabels'>true</b:widget-setting>
                <b:widget-setting name='showLocation'>false</b:widget-setting>
                <b:widget-setting name='showTimestamp'>true</b:widget-setting>
                <b:widget-setting name='postsPerAd'>1</b:widget-setting>
                <b:widget-setting name='showBacklinks'>false</b:widget-setting>
                <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                <b:widget-setting name='showInlineAds'>false</b:widget-setting>
                <b:widget-setting name='showReactions'>false</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main' var='this'>
              
              <!--[ Title ]-->
              <b:if cond='!data:view.isPost and !data:view.isPage'>
                <div class='blgMinTtl'>
                  <b:if cond='data:view.isHomepage'>
                   <h3 class='blgManTtl'><data:messages.latestPosts/></h3>
                    <a class='blgManTxt' href='/search'>All Posts <svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M12 3H3V21H21V12'/><path d='M21 3H21.75V2.25H21V3ZM20.4697 2.46967L10.4697 12.4697L11.5303 13.5303L21.5303 3.53033L20.4697 2.46967ZM21 2.25H15V3.75H21V2.25ZM21.75 9V3H20.25V9H21.75Z'/></svg></a>
                    <b:elseif cond='data:blog.searchLabel'/>
                    <p class='blgManTtl'><data:messages.labels/>: <b><data:blog.searchLabel/></b></p>
                    <b:elseif cond='data:blog.searchQuery'/>
                    <p class='blgManTtl'><data:messages.search/>: <b><data:blog.searchQuery/></b></p>
                    <b:else/>
                    <h3 class='blgManTtl'><data:messages.latestPosts/></h3>
                  </b:if>
                </div>
              </b:if>
              
              <!--[ Homepage Posts ]-->
              <b:if cond='!data:view.isPost and !data:view.isPage'>
                <b:if cond='data:posts'>
                  <div class='blgHmePsts'>
                    <b:loop index='i' values='data:posts' var='post'>
                      <b:if cond='data:view.isHomepage or data:view.search or data:view.isArchive'>
                        <b:include data='post' name='homePagePostsR'/>
                      </b:if>
                    </b:loop>
                  </div>
                  <b:else/><p>Not found</p>
                </b:if>
              </b:if>
              <b:if cond='!data:view.isPost and !data:view.isPage'>
                <b:include cond='data:view.isMultipleItems' name='postPagination'/>
              </b:if>
              
              <!--[ Posts and Pages ]-->
              <b:if cond='data:view.isPost or data:view.isPage'>
                <b:loop index='i' values='data:posts' var='post'>
                  <b:include data='post' name='postsR'/>
                </b:loop>
              </b:if>
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
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
              <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
              <b:includable id='commentsTitle'>
              <h3 class='title'><data:messages.comments/></h3>
            </b:includable>
              <b:includable id='defaultAdUnit'>
  <ins class='adsbygoogle' data-ad-format='auto' expr:data-ad-client='data:adClientId ?: data:blog.adsenseClientId' expr:data-ad-host='data:blog.adsenseHostId' expr:style='data:style ?: &quot;display: block;&quot;'>
    <b:attr cond='not data:blog.analytics4' expr:value='data:blog.analyticsAccountNumber' name='data-analytics-uacct'/>
  </ins>
  <script>
   (adsbygoogle = window.adsbygoogle || []).push({});
  </script>
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
              <b:includable id='feedLinks'/>
              <b:includable id='feedLinksBody' var='links'/>
              <b:includable id='footerBylines'>
  <b:if cond='data:widgets.Blog.first.footerBylines'>
    <b:loop index='i' values='data:widgets.Blog.first.footerBylines' var='region'>
      <b:if cond='not data:region.items.empty'>
        <div expr:class='&quot;post-footer-line post-footer-line-&quot; + (data:i + 1)'>
          <b:with value='&quot;footer-&quot; + (data:i + 1)' var='regionName'>
            <b:include data='region.items' name='bylineRegion'/>
          </b:with>
        </div>
      </b:if>
    </b:loop>
  </b:if>
</b:includable>
              <b:includable id='googlePlusShare'>
</b:includable>
              <b:includable id='headerByline'>
  <b:if cond='data:widgets.Blog.first.headerByline'>
    <div class='post-header'>
      <div class='post-header-line-1'>
        <b:with value='&quot;header-1&quot;' var='regionName'>
          <b:include data='data:widgets.Blog.first.headerByline.items' name='bylineRegion'/>
        </b:with>
      </div>
    </div>
  </b:if>
</b:includable>
              <b:includable id='homePageLink'>
                <a class='blgMrPstNr blgMrPstNxt' expr:href='data:blog.homepageUrl' expr:title='data:messages.home'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M12 18L12 14'/><path d='M19.5016 22L22.0017 9L12.0017 2L2 9L4.50161 22H19.5016Z'/></svg></a>
              </b:includable>
              <b:includable id='homePagePostsR'>
                <div class='hmePsts'>
                  <a class='hmePstImg' expr:href='data:post.url'>
                    <b:if cond='data:post.featuredImage'>
                      <img class='lazyload' expr:alt='data:post.title' expr:data-src='data:post.featuredImage' expr:title='data:post.title' height='720' src='data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==' width='1280'/>
                      <b:else/>
                      <img class='lazyload' data-src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEh-A3Fz4T-QNjIkUipAj3b9i_PGGXW4b9DJnyKDBVrDanUj4dg69yauY7PMsMqPWznnl2BuQ7iQtqfboIKQQm_vVsTFXjH_ifigorE-5SpwTqUajxWE_Z92Avu_P3a7BZgm0pokj8r7DUtfDBJJt1G1CPotR6mzv7-35LhZRoxZw2h8T2mCBofffSsoXu9P/s1280/404.webp' expr:alt='data:post.title' expr:title='data:post.title' height='720' src='data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==' width='1280'/>
                  </b:if>
                </a>
                <div class='hmePstMta'>
                  <p class='user'><data:post.author.name/></p>
                  <span class='space'>&#8231;</span>
                  <time class='time' expr:datetime='data:post.date.iso8601' id='timeAgoR'/>
                  <b:if cond='data:post.numberOfComments == &quot;0&quot;'><b:else/><span class='space'>&#8231;</span><data:post.numberOfComments/> <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>commnets<b:else/>تعليقات</b:if></b:if>
                </div>
                <b:if cond='data:post.title'>
                  <h2><a class='hmePstTtl' expr:href='data:post.url' expr:title='data:post.title'><data:post.title/></a></h2>
                  <b:else/>
                  <h2><a class='hmePstTtl' expr:href='data:post.url' title='No Title'>No Title</a></h2>
                </b:if>
                <b:if cond='data:post.body'><p class='hmePstTxt'><b:eval expr='snippet(data:post.body, {length: 77, links: false, linebreaks: false})'/></p></b:if>
                <b:if cond='data:post.labels'>
                  <div class='hmePstTgs'>
                    <ul class='listTgs' is='postLblHme'>
                      <b:loop index='i' values='data:post.labels' var='label'>
                        <b:if cond='data:i &lt;= 2'>
                          <li><a class='tgs' expr:href='data:label.url' rel='tag'><data:label.name/></a></li>
                        </b:if>
                      </b:loop>
                    </ul>
                  </div>
                </b:if>
              </div>
            </b:includable>
              <b:includable id='iframeComments' var='post'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
              <b:includable id='inlineAd' var='post'>
  <b:if cond='!data:view.isPreview'>
    <b:if cond='data:this.adCode or data:this.adClientId or data:blog.adsenseClientId'>
      <!-- Ad -->
      <div class='inline-ad'>
        <b:if cond='data:this.adCode != &quot;&quot;'>
          <data:this.adCode/>
        <b:else/>
          <b:include cond='data:this.adClientId or data:blog.adsenseClientId' name='defaultAdUnit'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <div class='inline-ad'>
      <div class='inline-ad-placeholder'>
        <span><b:message name='messages.adsGoHere'/></span>
      </div>
    </div>
  </b:if>
</b:includable>
              <b:includable id='linkShare'>
  <b:with value='&quot;window.prompt(\&quot;Copy to clipboard: Ctrl+C, Enter\&quot;, \&quot;&quot; + data:originalUrl + &quot;\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
</b:includable>
              <b:includable id='nextPageLink'>
              <a class='blgMrPstNr blgMrPstNxt' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:messages.olderPosts'><data:messages.olderPosts/>
                <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M19 12L4 12'/><path d='M15 7L19.2929 11.2929C19.6262 11.6262 19.7929 11.7929 19.7929 12C19.7929 12.2071 19.6262 12.3738 19.2929 12.7071L15 17'/></svg><b:else/><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M5 12L20 11.9998'/><path d='M9 7L4.70711 11.2929C4.37377 11.6262 4.20711 11.7929 4.20711 12C4.20711 12.2071 4.37377 12.3738 4.70711 12.7071L9 17'/></svg></b:if></a>
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
  <div class='post'>
    <b:include data='post' name='postMeta'/>
    <b:include data='post' name='postTitle'/>
    <b:include name='headerByline'/>
    <b:if cond='data:view.isSingleItem'>
      <b:include data='post' name='postBody'/>
    <b:else/>
      <b:include data='post' name='postBodySnippet'/>
      <b:include data='post' name='postJumpLink'/>
    </b:if>
    <b:include data='post' name='postFooter'/>
  </div>
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
  <b:include data='post' name='postBody'/>
</b:includable>
              <b:includable id='postCommentsAndAd' var='post'>
  <article class='post-outer-container'>
    <!-- Post title and body -->
    <div class='post-outer'>
      <b:include data='post' name='post'/>
    </div>

    <!-- Comments -->
    <b:include cond='data:view.isSingleItem' data='post' name='commentPicker'/>

    <!-- Show ad inside post container, after comments, if single item. -->
    <b:include cond='data:view.isSingleItem and data:post.includeAd' data='post' name='inlineAd'/>
  </article>

  <!-- Show ad outside post container (between posts) for feed pages. -->
  <b:include cond='data:view.isMultipleItems and data:post.includeAd' data='post' name='inlineAd'/>
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
  <div class='jump-link flat-button'>
    <a expr:href='data:post.url fragment &quot;more&quot;' expr:title='data:post.title'>
      <b:eval expr='data:blog.jumpLinkMessage'/>
    </a>
  </div>
</b:includable>
              <b:includable id='postLabels'>
  <span class='byline post-labels'>
    <span class='byline-label'><data:byline.label/></span>
    <b:loop index='i' values='data:post.labels' var='label'>
      <a expr:href='data:label.url' rel='tag'>
        <data:label.name/>
      </a>
    </b:loop>
  </span>
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
              <b:includable id='postMetadataJSON' var='post'> 
              <script type='application/ld+json'>{
    &quot;@context&quot;: &quot;https://schema.org&quot;,
    &quot;@type&quot;: &quot;BlogPosting&quot;,
    &quot;mainEntityOfPage&quot;: &quot;<data:post.url/>&quot;,
    &quot;headline&quot;: &quot;<data:post.title/>&quot;,
    &quot;description&quot;: &quot;<data:blog.metaDescription/>&quot;,
    &quot;author&quot;: {
      &quot;@type&quot;: &quot;Person&quot;,
      &quot;name&quot;: &quot;<data:post.author.name/>&quot;,
      &quot;url&quot;: &quot;<data:blog.homepageUrl.jsonEscaped/>&quot;
    },
    &quot;publisher&quot;: {
      &quot;@type&quot;: &quot;Organization&quot;,
      &quot;name&quot;: &quot;<data:blog.title/>&quot;,
      &quot;url&quot;: &quot;<data:blog.homepageUrl.jsonEscaped/>&quot;
    },
    &quot;datePublished&quot;: &quot;<data:post.date.iso8601/>&quot;,
    &quot;dateModified&quot;: &quot;<data:post.date.iso8601/>&quot;,
    &quot;keywords&quot;: [&quot;<data:post.title/>&quot;, &quot;<data:blog.title/>&quot;, &quot;<data:post.author.name/>&quot;],
    &quot;image&quot;: [
      {
        &quot;@type&quot;: &quot;ImageObject&quot;,
        &quot;url&quot;: &quot;<data:post.featuredImage/>&quot;,
        &quot;width&quot;: 1200,
        &quot;height&quot;: 600
      }
    ]}}</script>
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
              <div class='blgMrPsts'>
                <div class='blgMrPstNrs'>
                  <b:if cond='data:newerPageUrl or data:olderPageUrl'>
                  <b:include cond='data:newerPageUrl' name='previousPageLink'/>
                  <b:include cond='data:view.url != data:blog.homepageUrl' name='homePageLink'/>
                  <b:include cond='data:olderPageUrl' name='nextPageLink'/>
                <b:else/>
                <p class='blgMrPstNr' title='data:messages.newerPosts'>
                  <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>No results found<b:else/>لم يتم العثور على نتائج</b:if>
                </p>
              </b:if>
              </div>
              </div>
            </b:includable>
              <b:includable id='postReactions'>
  <!-- Reaction feature no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
              <b:includable id='postShareButtons'>
  <div class='byline post-share-buttons goog-inline-block'>
    <b:with value='data:sharingId ?: ((data:widget.instanceId ?: &quot;sharing&quot;) + &quot;-&quot; + (data:regionName ?: &quot;byline&quot;) + &quot;-&quot; + data:post.id)' var='sharingId'>
      <!-- Note: 'sharingButtons' includable is from the default Sharing widget markup. -->
      <b:include data='{                                                sharingId: data:sharingId,                                                originalUrl: data:post.url,                                                platforms: data:this.sharing.platforms,                                                shareUrl: data:post.shareUrl,                                                shareTitle: data:post.title,                                              }' name='sharingButtons'/>
    </b:with>
  </div>
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
  <a expr:name='data:post.id'/>
  <b:if cond='data:post.title != &quot;&quot;'>
    <h3 class='post-title entry-title'>
      <b:if cond='data:post.link or (data:post.url and data:view.url != data:post.url)'>
        <a expr:href='data:post.link ?: data:post.url'><data:post.title/></a>
      <b:else/>
        <data:post.title/>
      </b:if>
    </h3>
  </b:if>
</b:includable>
              <b:includable id='postsR'>
                <!--[ Post Article ]-->
                <article class='bMPPMain'>
                  
                  <!--[ Schema.org BreadcrumbList ]-->
                  <div itemscope='' itemtype='http://schema.org/BreadcrumbList'>
                    <b:if cond='data:blog.languageDirection == &quot;ltr&quot;'>
                      <span itemprop='itemListElement' itemscope='' itemtype='https://schema.org/ListItem'>
                        <a class='bMPPMLabel' expr:href='data:blog.homepageUrl' itemprop='item'>
                          <span itemprop='name'><data:messages.home/></span>
                        </a>
                        <meta content='1' itemprop='position'/>
                      </span> &gt;
                      <span itemprop='itemListElement' itemscope='' itemtype='https://schema.org/ListItem'>
                        <a class='bMPPMLabel' expr:href='data:post.labels.first.url' itemprop='item'>
                          <span itemprop='name'><data:post.labels.first.name/></span>
                        </a>
                        <meta content='2' itemprop='position'/>
                      </span> &gt;
                      <span itemprop='itemListElement' itemscope='' itemtype='https://schema.org/ListItem'>
                        <a class='bMPPMLabel' expr:href='data:post.url' itemprop='item'>
                          <span itemprop='name'><data:post.title/></span>
                        </a>
                        <meta content='3' itemprop='position'/>
                      </span>
                      <b:else/>
                      <span itemprop='itemListElement' itemscope='' itemtype='https://schema.org/ListItem'>
                        <a class='bMPPMLabel' expr:href='data:blog.homepageUrl' itemprop='item'>
                          <span itemprop='name'><data:messages.home/></span>
                        </a>
                        <meta content='1' itemprop='position'/>
                      </span> &lt;
                      <span itemprop='itemListElement' itemscope='' itemtype='https://schema.org/ListItem'>
                        <a class='bMPPMLabel' expr:href='data:post.labels.first.url' itemprop='item'>
                          <span itemprop='name'><data:post.labels.first.name/></span>
                        </a>
                        <meta content='2' itemprop='position'/>
                      </span> &lt;
                      <span itemprop='itemListElement' itemscope='' itemtype='https://schema.org/ListItem'>
                        <a class='bMPPMLabel' expr:href='data:post.url' itemprop='item'>
                          <span itemprop='name'><data:post.title/></span>
                        </a>
                        <meta content='3' itemprop='position'/>
                      </span>
                    </b:if>
                  </div>
                  
                  <!--[ Post Title and Description ]-->
                  <h1 class='bMPPMTitle'><data:post.title/></h1>
                  <b:if cond='data:skin.vars.postDescription == &quot;1px&quot;'>
                    <b:if cond='data:blog.metaDescription'><p class='bMPPMDescription'><data:blog.metaDescription/></p></b:if>
                  </b:if>
                  
                  <!--[ Post Meta ]-->
                  <div class='bMPPMMeta'>
                    
                    <!--[ Post Meta: Author ]-->
                    <span class='bMPPMMAutor'><data:post.author.name/></span>
                    
                    <!--[ Post Meta: Published and Updated date ]-->
                    <b:if cond='data:post.lastUpdated == data:post.createdDate'>
                      <span class='bMPPMMTime'>
                        <b>Updated:</b> <time expr:datetime='data:post.date.iso8601' id='timeAgoR'><data:post.lastUpdated/></time>
                      </span>
                      <b:else/>
                      <time class='bMPPMMTime' expr:datetime='data:post.date.iso8601' id='timeAgoR'><data:post.createdDate/></time>
                    </b:if>
                    
                    <!--[ Post Meta: Comments ]-->
                    <b:if cond='!data:post.numberOfComments == &quot;0&quot;'><span class='bMPPMMComment'><data:post.numberOfComments/> Comments</span></b:if>
                    
                    <!--[ Post Meta: Reading Time ]-->
                    <b:if cond='data:skin.vars.postReadMin == &quot;1px&quot;'><span class='bMPPMMViews readingTime'><span class='readTime' id='readTime'/></span></b:if>
                  </div>
                  
                  <!--[ Post Body ]-->
                  <div class='bMPPMPost'>
                    <div id='AdsInBeforePostBody'/>
                    <data:post.body/>
                    <div id='AdsInAfterPostBody'/>
                  </div>
                  
                  <!--[ Post Tags ]-->
                  <div class='bMPPMTags'>
                    <b><data:messages.labels/>:</b>
                    <b:loop index='i' values='data:post.labels' var='label'>
                      <b:if cond='data:i &lt;= 6'><a class='bMPPMTagsItem' expr:href='data:label.url' expr:title='data:label.name'>#<data:label.name/></a></b:if>
                    </b:loop>
                  </div>
                  
                  <!--[ Post Share ]-->
                  <p class='bMPPMShareText'><data:messages.share/>:</p>
                  <div class='bMPPMShare'>
                    <!--[ Post Share: Facebook ]--><a class='bMPPMSItem facebook' expr:href='&quot;https://www.facebook.com/sharer.php?u=&quot; + data:post.url'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M5 14.2222V10.3333H8.54545V2H19V6.44444H13.2727V10.3333H18L16.5 14.2222H13.2727V22H8.54545V14.2222H5Z'/></svg> Facebook</a>
                    <!--[ Post Share: X (Twitter) ]--><a class='bMPPMSItem x' expr:href='&quot;https://twitter.com/share?url=&quot; + data:post.url'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M3 21L10.5484 13.4516M21 3L13.4516 10.5484M13.4516 10.5484L8 3H3L10.5484 13.4516M13.4516 10.5484L21 21H16L10.5484 13.4516'/></svg></a>
                    <!--[ Post Share: WhatsApp ]--><a class='bMPPMSItem whatsapp' expr:href='&quot;https://wa.me/?text=&quot;+ data:post.url'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2C6.47715 2 2 6.47715 2 12C2 13.3789 2.27907 14.6926 2.78382 15.8877C3.06278 16.5481 3.20226 16.8784 3.21953 17.128C3.2368 17.3776 3.16334 17.6521 3.01642 18.2012L2 22L5.79877 20.9836C6.34788 20.8367 6.62244 20.7632 6.87202 20.7805C7.12161 20.7977 7.45185 20.9372 8.11235 21.2162C9.30745 21.7209 10.6211 22 12 22Z'/><path d='M8.58815 12.3773L9.45909 11.2956C9.82616 10.8397 10.2799 10.4153 10.3155 9.80826C10.3244 9.65494 10.2166 8.96657 10.0008 7.58986C9.91601 7.04881 9.41086 7 8.97332 7C8.40314 7 8.11805 7 7.83495 7.12931C7.47714 7.29275 7.10979 7.75231 7.02917 8.13733C6.96539 8.44196 7.01279 8.65187 7.10759 9.07169C7.51023 10.8548 8.45481 12.6158 9.91948 14.0805C11.3842 15.5452 13.1452 16.4898 14.9283 16.8924C15.3481 16.9872 15.558 17.0346 15.8627 16.9708C16.2477 16.8902 16.7072 16.5229 16.8707 16.165C17 15.8819 17 15.5969 17 15.0267C17 14.5891 16.9512 14.084 16.4101 13.9992C15.0334 13.7834 14.3451 13.6756 14.1917 13.6845C13.5847 13.7201 13.1603 14.1738 12.7044 14.5409L11.6227 15.4118'/></svg></a>
                    <!--[ Post Share: Pinterest ]--><a class='bMPPMSItem pinterest' expr:href='&quot;https://pinterest.com/pin/create/button/?url=&quot; + data:post.url + &quot;&amp;media=&quot; + data:post.featuredImage'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M12 11L8 21'/><path d='M9.97368 16.5722C10.5931 16.8471 11.2787 16.9999 12 16.9999C14.7614 16.9999 17 14.7613 17 11.9999C17 9.23845 14.7614 6.99988 12 6.99988C9.23858 6.99988 7 9.23845 7 11.9999C7 12.9107 7.24367 13.7645 7.66921 14.4999'/><circle cx='12' cy='12' r='10'/></svg></a>
                    <!--[ Post Share: Copy Link ]--><input expr:value='data:blog.url.canonical' id='getLink' onclick='this.select()' readonly='readonly' style='position:absolute;top:-99999px;left:-99999px;'/><label class='bMPPMSItem' for='getLink' onclick='copyLink()'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M9 15C9 12.1716 9 10.7574 9.87868 9.87868C10.7574 9 12.1716 9 15 9L16 9C18.8284 9 20.2426 9 21.1213 9.87868C22 10.7574 22 12.1716 22 15V16C22 18.8284 22 20.2426 21.1213 21.1213C20.2426 22 18.8284 22 16 22H15C12.1716 22 10.7574 22 9.87868 21.1213C9 20.2426 9 18.8284 9 16L9 15Z'/><path d='M16.9999 9C16.9975 6.04291 16.9528 4.51121 16.092 3.46243C15.9258 3.25989 15.7401 3.07418 15.5376 2.90796C14.4312 2 12.7875 2 9.5 2C6.21252 2 4.56878 2 3.46243 2.90796C3.25989 3.07417 3.07418 3.25989 2.90796 3.46243C2 4.56878 2 6.21252 2 9.5C2 12.7875 2 14.4312 2.90796 15.5376C3.07417 15.7401 3.25989 15.9258 3.46243 16.092C4.51121 16.9528 6.04291 16.9975 9 16.9999'/></svg></label><script>const dc = document, copyLink = () =&gt; { dc.getElementById(&quot;getLink&quot;).select(), dc.execCommand(&quot;copy&quot;), dc.getElementById(&quot;copied&quot;).innerHTML = &quot;<span class='fixN'><data:messages.linkCopiedToClipboard/></span>&quot; };</script>
                  </div>
                  
                  <!--[ Profile card ]-->
                  <div class='bMPPMProfileCard'>
                    
                    <!--[ Profile card: Image ]-->
                    <div class='bMPPMPCImage'>
                      <b:if cond='data:post.author.authorPhoto.image'>
                        <img class='lazyload' expr:alt='data:post.author.name' expr:data-src='data:post.author.authorPhoto.image' expr:title='data:post.author.name' src='data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=='/>
                        <b:else/>
                        <img class='lazyload' data-src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEh-A3Fz4T-QNjIkUipAj3b9i_PGGXW4b9DJnyKDBVrDanUj4dg69yauY7PMsMqPWznnl2BuQ7iQtqfboIKQQm_vVsTFXjH_ifigorE-5SpwTqUajxWE_Z92Avu_P3a7BZgm0pokj8r7DUtfDBJJt1G1CPotR6mzv7-35LhZRoxZw2h8T2mCBofffSsoXu9P/s1280/404.webp' expr:alt='data:post.author.name' expr:title='data:post.author.name' src='data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw=='/>
                      </b:if>
                    </div>
                    
                    <!--[ Profile card: Title, aboutMe ]-->
                    <div class='bMPPMPCMain'>
                      <h3 class='bMPPMPCMTitle'><data:post.author.name/> <svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M18.9905 19H19M18.9905 19C18.3678 19.6175 17.2393 19.4637 16.4479 19.4637C15.4765 19.4637 15.0087 19.6537 14.3154 20.347C13.7251 20.9374 12.9337 22 12 22C11.0663 22 10.2749 20.9374 9.68457 20.347C8.99128 19.6537 8.52349 19.4637 7.55206 19.4637C6.76068 19.4637 5.63218 19.6175 5.00949 19C4.38181 18.3776 4.53628 17.2444 4.53628 16.4479C4.53628 15.4414 4.31616 14.9786 3.59938 14.2618C2.53314 13.1956 2.00002 12.6624 2 12C2.00001 11.3375 2.53312 10.8044 3.59935 9.73817C4.2392 9.09832 4.53628 8.46428 4.53628 7.55206C4.53628 6.76065 4.38249 5.63214 5 5.00944C5.62243 4.38178 6.7556 4.53626 7.55208 4.53626C8.46427 4.53626 9.09832 4.2392 9.73815 3.59937C10.8044 2.53312 11.3375 2 12 2C12.6625 2 13.1956 2.53312 14.2618 3.59937C14.9015 4.23907 15.5355 4.53626 16.4479 4.53626C17.2393 4.53626 18.3679 4.38247 18.9906 5C19.6182 5.62243 19.4637 6.75559 19.4637 7.55206C19.4637 8.55858 19.6839 9.02137 20.4006 9.73817C21.4669 10.8044 22 11.3375 22 12C22 12.6624 21.4669 13.1956 20.4006 14.2618C19.6838 14.9786 19.4637 15.4414 19.4637 16.4479C19.4637 17.2444 19.6182 18.3776 18.9905 19Z'/><path d='M9 12.8929L10.8 14.5L15 9.5'/></svg></h3>
                      <b:if cond='data:post.author.aboutMe'><p class='bMPPMPCMP'><data:post.author.aboutMe/></p></b:if>
                    </div>
                  </div>
                </article>
                <b:include data='post' name='postMetadataJSON'/>
            </b:includable>
              <b:includable id='previousPageLink'>
              <a class='blgMrPstNr blgMrPstNxt' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:messages.newerPosts'><b:if cond='data:blog.languageDirection == &quot;ltr&quot;'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M5 12L20 11.9998'/><path d='M9 7L4.70711 11.2929C4.37377 11.6262 4.20711 11.7929 4.20711 12C4.20711 12.2071 4.37377 12.3738 4.70711 12.7071L9 17'/></svg><b:else/><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M19 12L4 12'/><path d='M15 7L19.2929 11.2929C19.6262 11.6262 19.7929 11.7929 19.7929 12C19.7929 12.2071 19.6262 12.3738 19.2929 12.7071L15 17'/></svg></b:if><data:messages.newerPosts/></a>
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
            <b:widget id='HTML7' locked='false' title='Ads In After Post Body' type='HTML' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='content'/>
              </b:widget-settings>
              <b:includable id='main'>
                <br/><center>
                  <b:if cond='data:view.isPost'>
                    <b:if cond='data:content == &quot;&quot;'>
                      <div style='width: 100%;display: flex;align-items: center;justify-content: center;background-color: var(--gray-2);color: var(--gray-9);text-align: center;height: 100px;'><b:message name='messages.adsGoHere'/></div>
                      <b:else/>
                      <data:content/>
                    </b:if>
                  </b:if>
                </center>
              </b:includable>
            </b:widget>
            <b:widget id='HTML9' locked='false' title='Ads After Post' type='HTML' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='content'/>
              </b:widget-settings>
              <b:includable id='main'>
                <br/><center>
                  <b:if cond='data:view.isPost'>
                    <b:if cond='data:content == &quot;&quot;'>
                      <div style='width: 100%;display: flex;align-items: center;justify-content: center;background-color: var(--gray-2);color: var(--gray-9);text-align: center;height: 100px;'><b:message name='messages.adsGoHere'/></div>
                      <b:else/>
                      <data:content/>
                    </b:if>
                  </b:if>
                </center>
              </b:includable>
            </b:widget>
          </b:section>
    
      
       <!--[ Sidebar ]-->
       <b:if cond='data:skin.vars.postSidebar == &quot;1px&quot; and data:view.isPost'>
       <aside class='bMPPSidebar'>
         
         <!--[ Sidebar ]-->
         <b:section cond='data:view.isPost' id='Sidebar'>
           <b:widget id='PopularPosts1' locked='false' title='Popular Posts' type='PopularPosts' version='2' visible='true'>
             <b:widget-settings>
               <b:widget-setting name='numItemsToShow'>6</b:widget-setting>
               <b:widget-setting name='showThumbnails'>true</b:widget-setting>
               <b:widget-setting name='showSnippets'>false</b:widget-setting>
               <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
             </b:widget-settings>
             <b:includable id='main' var='this'>
               <div class='bMPPSPopularPosts'>
                 <h3 class='bMPPSPPTitle'><b:include name='widget-title'/></h3>
                 <b:include name='snippetedPosts'/>
               </div>
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
             <b:includable id='commentsLink'>
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
             <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
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
             <b:includable id='footerBylines'>
  <b:if cond='data:widgets.Blog.first.footerBylines'>
    <b:loop index='i' values='data:widgets.Blog.first.footerBylines' var='region'>
      <b:if cond='not data:region.items.empty'>
        <div expr:class='&quot;post-footer-line post-footer-line-&quot; + (data:i + 1)'>
          <b:with value='&quot;footer-&quot; + (data:i + 1)' var='regionName'>
            <b:include data='region.items' name='bylineRegion'/>
          </b:with>
        </div>
      </b:if>
    </b:loop>
  </b:if>
</b:includable>
             <b:includable id='googlePlusShare'>
</b:includable>
             <b:includable id='headerByline'>
  <b:if cond='data:widgets.Blog.first.headerByline'>
    <div class='post-header'>
      <div class='post-header-line-1'>
        <b:with value='&quot;header-1&quot;' var='regionName'>
          <b:include data='data:widgets.Blog.first.headerByline.items' name='bylineRegion'/>
        </b:with>
      </div>
    </div>
  </b:if>
</b:includable>
             <b:includable id='linkShare'>
  <b:with value='&quot;window.prompt(\&quot;Copy to clipboard: Ctrl+C, Enter\&quot;, \&quot;&quot; + data:originalUrl + &quot;\&quot;); return false;&quot;' var='onclick'>
    <b:include name='platformShare'/>
  </b:with>
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
             <b:includable id='postCommentsLink'>
  <span class='byline post-comment-link container'>
    <b:include cond='data:post.commentSource != 1' name='commentsLink'/>
  </span>
</b:includable>
             <b:includable id='postJumpLink' var='post'>
  <div class='jump-link flat-button'>
    <a expr:href='data:post.url fragment &quot;more&quot;' expr:title='data:post.title'>
      <b:eval expr='data:blog.jumpLinkMessage'/>
    </a>
  </div>
</b:includable>
             <b:includable id='postLabels'>
  <span class='byline post-labels'>
    <span class='byline-label'><data:byline.label/></span>
    <b:loop index='i' values='data:post.labels' var='label'>
      <a expr:href='data:label.url' rel='tag'>
        <data:label.name/>
      </a>
    </b:loop>
  </span>
</b:includable>
             <b:includable id='postLocation'>
  <span class='byline post-location'>
    <data:byline.label/>
    <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
  </span>
</b:includable>
             <b:includable id='postReactions'>
  <!-- Reaction feature no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
             <b:includable id='postShareButtons'>
  <div class='byline post-share-buttons goog-inline-block'>
    <b:with value='data:sharingId ?: ((data:widget.instanceId ?: &quot;sharing&quot;) + &quot;-&quot; + (data:regionName ?: &quot;byline&quot;) + &quot;-&quot; + data:post.id)' var='sharingId'>
      <!-- Note: 'sharingButtons' includable is from the default Sharing widget markup. -->
      <b:include data='{                                                sharingId: data:sharingId,                                                originalUrl: data:post.url,                                                platforms: data:this.sharing.platforms,                                                shareUrl: data:post.shareUrl,                                                shareTitle: data:post.title,                                              }' name='sharingButtons'/>
    </b:with>
  </div>
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
             <b:includable id='snippetedPostByline'>
  <b:with value='(data:widgets first (w =&gt; w.type == &quot;Blog&quot;)).allBylineItems' var='blogBylines'>
    <div class='item-byline'>
      <b:with value='data:blogBylines first (i =&gt; i.name == &quot;author&quot;)' var='byline'>
        <b:include cond='data:byline and data:this.postDisplay.showAuthor' data='post' name='postAuthor'/>
      </b:with>
      <b:with value='data:blogBylines first (i =&gt; i.name == &quot;timestamp&quot;)' var='byline'>
        <b:include cond='data:byline and data:this.postDisplay.showDate' data='post' name='postTimestamp'/>
      </b:with>
    </div>
  </b:with>
</b:includable>
             <b:includable id='snippetedPostContent'>
               <div class='bMPPSPPBItem'>
                 <b:include cond='data:this.postDisplay.showFeaturedImage and data:post.featuredImage' name='snippetedPostThumbnail'/>
                 <b:include cond='data:this.postDisplay.showTitle' name='snippetedPostTitle'/>
               </div>
             </b:includable>
             <b:includable id='snippetedPostThumbnail'>
               <a expr:href='data:post.url'>
                 <img expr:alt='data:post.title' expr:src='data:post.featuredImage' expr:title='data:post.title'/>
               </a>
             </b:includable>
             <b:includable id='snippetedPostTitle'>
               <b:if cond='data:post.title != &quot;&quot;'>
                 <h3><a class='bMPPSPPBITitle' expr:href='data:post.url'><data:post.title/></a></h3>
               </b:if>
             </b:includable>
             <b:includable id='snippetedPosts'>
               <div role='feed'>
                 <!-- Don't render the post that we're currently already looking at. -->
                 <div class='bMPPSPPBody'>
                   <b:loop values='data:posts filter (p =&gt; p.id != data:view.postId)' var='post'>
                     <article class='post' role='article'>
                       <b:include name='snippetedPostContent'/>
                     </article>
                   </b:loop>
                 </div>
               </div>
             </b:includable>
           </b:widget>
           <b:widget id='Label1' locked='false' title='Labels' type='Label' version='2' visible='true'>
             <b:widget-settings>
               <b:widget-setting name='sorting'>FREQUENCY</b:widget-setting>
               <b:widget-setting name='display'>LIST</b:widget-setting>
               <b:widget-setting name='selectedLabelsList'/>
               <b:widget-setting name='showType'>ALL</b:widget-setting>
               <b:widget-setting name='showFreqNumbers'>true</b:widget-setting>
             </b:widget-settings>
             <b:includable id='main' var='this'>
               <div class='bMPPSLebels'>
                 <h3 class='bbMPPSLTitle'><b:include name='widget-title'/></h3>
                 <b:include name='content'/>
               </div>
             </b:includable>
             <b:includable id='cloud'>
               <b:loop values='data:labels' var='label'>
                 <a class='bMPPSLBItem' expr:href='data:label.url'>#<data:label.name/> (<b:if cond='data:this.showFreqNumbers'><data:label.count/></b:if>)</a>
               </b:loop>
             </b:includable>
             <b:includable id='content'>
               <div class='bMPPSLBody'>
                 <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
                 <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
               </div>
             </b:includable>
             <b:includable id='list'>
               <b:loop values='data:labels' var='label'>
                 <a class='bMPPSLBItem' expr:href='data:label.url'>#<data:label.name/> (<b:if cond='data:this.showFreqNumbers'><data:label.count/></b:if>)</a>
               </b:loop>
             </b:includable>
           </b:widget>
         </b:section>
         
         <!--[ Sidebar Ads ]-->
         <div class='bMPPSAds'>
         <b:section cond='data:view.isPost' id='Sidebar: Ads'>
           <b:widget id='HTML4' locked='false' title='Ads' type='HTML' version='2' visible='true'>
             <b:widget-settings>
               <b:widget-setting name='content'/>
             </b:widget-settings>
             <b:includable id='main'>
                 <b:if cond='data:content == &quot;&quot;'>
                   <div style='width: 100%;display: flex;align-items: center;justify-content: center;color: var(--gray-9);text-align: center;height: 400px;'><b:message name='messages.adsGoHere'/></div>
                   <b:else/>
                   <data:content/>
                 </b:if>
               </b:includable>
           </b:widget>
         </b:section>
         </div>
         </aside>
        </b:if>
      </div>
      </div>
      
      <footer class='ftr'>
        <b:section id='Footer: Social Media Icons'>
          <b:widget id='LinkList1' locked='false' title='' type='LinkList' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='link-7'>https://t.me/</b:widget-setting>
              <b:widget-setting name='link-5'>https://x.com</b:widget-setting>
              <b:widget-setting name='link-6'>https://pinterst.com</b:widget-setting>
              <b:widget-setting name='link-3'>https://youtube.com</b:widget-setting>
              <b:widget-setting name='link-4'>https://dribbble.com</b:widget-setting>
              <b:widget-setting name='text-1'>instagam</b:widget-setting>
              <b:widget-setting name='text-0'>facebook</b:widget-setting>
              <b:widget-setting name='text-3'>youtube</b:widget-setting>
              <b:widget-setting name='text-2'>github</b:widget-setting>
              <b:widget-setting name='text-5'>x</b:widget-setting>
              <b:widget-setting name='text-4'>dribbble</b:widget-setting>
              <b:widget-setting name='text-7'>telegram</b:widget-setting>
              <b:widget-setting name='text-6'>pinterst</b:widget-setting>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='link-1'>https://instagam.com</b:widget-setting>
              <b:widget-setting name='link-2'>https://github.com</b:widget-setting>
              <b:widget-setting name='link-0'>https://facebook.com</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
              <b:include name='content'/>
            </b:includable>
            <b:includable id='content'>
              <div class='ftrScl'>
                <ul class='ftrSclLst'>
                  <b:loop values='data:links' var='link'>
                    <b:if cond='data:link.name == &quot;facebook&quot;'>
                      <li><a class='ftrSclLsti' expr:href='data:link.target' expr:title='data:link.name'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M5 14.2222V10.3333H8.54545V2H19V6.44444H13.2727V10.3333H18L16.5 14.2222H13.2727V22H8.54545V14.2222H5Z'/></svg></a></li>
                      <b:elseif cond='data:link.name == &quot;instagam&quot;'/>
                      <li><a class='ftrSclLsti' expr:href='data:link.target' expr:title='data:link.name'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M21 3V21H3V3H21Z'/><path d='M16.5 12C16.5 14.4853 14.4853 16.5 12 16.5C9.51472 16.5 7.5 14.4853 7.5 12C7.5 9.51472 9.51472 7.5 12 7.5C14.4853 7.5 16.5 9.51472 16.5 12Z'/><path d='M17.5078 6.5L17.4988 6.5'/></svg></a></li>
                      <b:elseif cond='data:link.name == &quot;github&quot;'/>
                      <li><a class='ftrSclLsti' expr:href='data:link.target' expr:title='data:link.name'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M10 20.5675C6.57143 21.7248 3.71429 20.5675 2 17'/><path d='M10 22V18.7579C10 18.1596 10.1839 17.6396 10.4804 17.1699C10.6838 16.8476 10.5445 16.3904 10.1771 16.2894C7.13394 15.4528 5 14.1077 5 9.64606C5 8.48611 5.38005 7.39556 6.04811 6.4464C6.21437 6.21018 6.29749 6.09208 6.31748 5.9851C6.33746 5.87813 6.30272 5.73852 6.23322 5.45932C5.95038 4.32292 5.96871 3.11619 6.39322 2.02823C6.39322 2.02823 7.27042 1.74242 9.26698 2.98969C9.72282 3.27447 9.95075 3.41686 10.1515 3.44871C10.3522 3.48056 10.6206 3.41384 11.1573 3.28041C11.8913 3.09795 12.6476 3 13.5 3C14.3524 3 15.1087 3.09795 15.8427 3.28041C16.3794 3.41384 16.6478 3.48056 16.8485 3.44871C17.0493 3.41686 17.2772 3.27447 17.733 2.98969C19.7296 1.74242 20.6068 2.02823 20.6068 2.02823C21.0313 3.11619 21.0496 4.32292 20.7668 5.45932C20.6973 5.73852 20.6625 5.87813 20.6825 5.9851C20.7025 6.09207 20.7856 6.21019 20.9519 6.4464C21.6199 7.39556 22 8.48611 22 9.64606C22 14.1077 19.8661 15.4528 16.8229 16.2894C16.4555 16.3904 16.3162 16.8476 16.5196 17.1699C16.8161 17.6396 17 18.1596 17 18.7579V22'/></svg></a></li>
                      <b:elseif cond='data:link.name == &quot;youtube&quot;'/>
                      <li><a class='ftrSclLsti' expr:href='data:link.target' expr:title='data:link.name'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M16.0002 12L9 8V16L16.0002 12Z'/><path d='M22 5C19.2145 4.37208 15.752 4 12 4C8.24798 4 4.78554 4.37208 2 5V19C4.78554 19.6279 8.24798 20 12 20C15.752 20 19.2145 19.6279 22 19V5Z'/></svg></a></li>
                      <b:elseif cond='data:link.name == &quot;dribbble&quot;'/>
                      <li><a class='ftrSclLsti' expr:href='data:link.target' expr:title='data:link.name'><svg class='line' fill='none' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><circle cx='12' cy='12' r='10'/><path d='M19 5C15.8705 8.66742 11.1679 11 5.90962 11C4.56437 11 3.25548 10.8473 2 10.5587'/><path d='M14.6178 22C14.8684 20.786 15 19.5287 15 18.2407C15 11.9247 11.8343 6.34645 7 3'/></svg></a></li>
                      <b:elseif cond='data:link.name == &quot;x&quot;'/>
                      <li><a class='ftrSclLsti' expr:href='data:link.target' expr:title='data:link.name'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M3 21L10.5484 13.4516M21 3L13.4516 10.5484M13.4516 10.5484L8 3H3L10.5484 13.4516M13.4516 10.5484L21 21H16L10.5484 13.4516'/></svg></a></li>
                      <b:elseif cond='data:link.name == &quot;telegram&quot;'/>
                      <li><a class='ftrSclLsti' expr:href='data:link.target' expr:title='data:link.name'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M12 11L8 21'/><path d='M9.97368 16.5722C10.5931 16.8471 11.2787 16.9999 12 16.9999C14.7614 16.9999 17 14.7613 17 11.9999C17 9.23845 14.7614 6.99988 12 6.99988C9.23858 6.99988 7 9.23845 7 11.9999C7 12.9107 7.24367 13.7645 7.66921 14.4999'/><circle cx='12' cy='12' r='10'/></svg></a></li>
                      <b:elseif cond='data:link.name == &quot;pinterst&quot;'/>
                      <li><a class='ftrSclLsti' expr:href='data:link.target' expr:title='data:link.name'><svg class='line' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'><path d='M11.9854 15.4083L15.2268 19.0936C16.4277 20.4589 17.0282 21.1416 17.6567 20.9754C18.2852 20.8092 18.5008 19.9108 18.9318 18.1138L21.3229 8.1459C21.9868 5.37832 22.3187 3.99454 21.5808 3.312C20.843 2.62947 19.564 3.13725 17.0061 4.15282L5.13876 8.86449C3.09293 9.67674 2.07001 10.0829 2.00507 10.7808C1.99842 10.8522 1.99831 10.9241 2.00474 10.9955C2.06754 11.6937 3.08921 12.1033 5.13255 12.9223C6.05838 13.2934 6.5213 13.479 6.8532 13.8344C6.89052 13.8743 6.9264 13.9157 6.96078 13.9584C7.26658 14.3384 7.39709 14.8371 7.65808 15.8344L8.14653 17.701C8.4005 18.6715 8.52749 19.1568 8.86008 19.223C9.19267 19.2891 9.48225 18.8867 10.0614 18.0819L11.9854 15.4083ZM11.9854 15.4083L11.6676 15.0771C11.3059 14.7001 11.1251 14.5117 11.1251 14.2775C11.1251 14.0433 11.3059 13.8548 11.6676 13.4778L15.2406 9.75409'/></svg></a></li>
                    </b:if>
                  </b:loop>
                </ul>
              </div>
            </b:includable>
          </b:widget>
        </b:section>
        <div class='ftrBdy'>
          <b:section id='Footer: Widget 1'>
            <b:widget id='HTML2' locked='false' title='BloggerBoost' type='HTML' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='content'><![CDATA[BloggerBoost is the information Hub of Blogging tips, Blogger tutorials, HTML & CSS tricks, etc. We help bloggers run a profitable Blog & earn a handful of money out of it.]]></b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
                <div class='ftrBdyW1'>
                  <h3 class='ftrBdyW1Ttl'><b:include name='widget-title'/></h3>
                  <p class='ftrBdyW1Txt'><data:content/></p>
                </div>
              </b:includable>
            </b:widget>
          </b:section>
          <b:section id='Footer: Widget 2'>
            <b:widget id='PageList1' locked='false' title='Pages' type='PageList' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='pageListJson'><![CDATA[{"link1":{"href":"#","position":1,"title":"Contact Us"},"link0":{"href":"#","position":0,"title":"About Us"},"link4":{"href":"#","position":4,"title":"Terms & Conditions"},"link3":{"href":"#","position":3,"title":"Privacy Policy"},"link2":{"href":"#","position":2,"title":"Disclaimer"}}]]></b:widget-setting>
                <b:widget-setting name='homeTitle'>Home</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
                <div class='ftrBdyW2'>
                  <h3 class='ftrBdyW2Ttl'><b:include name='widget-title'/></h3>
                  <b:include name='content'/>
                </div>
              </b:includable>
              <b:includable id='content'>
                <b:include name='pageList'/>
              </b:includable>
              <b:includable id='overflowButton'/>
              <b:includable id='overflowablePageList'/>
              <b:includable id='pageLink'>
                <li><a class='ftrBdyW2LstI' expr:href='data:link.href'><data:link.title/></a></li>
              </b:includable>
              <b:includable id='pageList'>
                <ul class='ftrBdyW2Lst'>
                  <b:loop values='data:links' var='link'>
                    <b:include name='pageLink'/>
                  </b:loop>
                </ul>
              </b:includable>
            </b:widget>
          </b:section>
          <b:section id='Footer: Widget 3'>
            <b:widget id='LinkList2' locked='false' title='Categorys' type='LinkList' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='link-3'>#</b:widget-setting>
                <b:widget-setting name='sorting'>NONE</b:widget-setting>
                <b:widget-setting name='link-4'>#</b:widget-setting>
                <b:widget-setting name='text-1'>WordPress</b:widget-setting>
                <b:widget-setting name='link-1'>#</b:widget-setting>
                <b:widget-setting name='text-0'>Blogger</b:widget-setting>
                <b:widget-setting name='link-2'>#</b:widget-setting>
                <b:widget-setting name='text-3'>Blogger Themes</b:widget-setting>
                <b:widget-setting name='link-0'>#</b:widget-setting>
                <b:widget-setting name='text-2'>SEO</b:widget-setting>
                <b:widget-setting name='text-4'>Google AdSense</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
                <div class='ftrBdyW3'>
                  <h3 class='ftrBdyW3Ttl'><b:include name='widget-title'/></h3>
                  <b:include name='content'/>
                </div>
              </b:includable>
              <b:includable id='content'>
                <ul class='ftrBdyW3Lst'>
                  <b:loop values='data:links' var='link'>
                    <li><a class='ftrBdyW3LstI' expr:href='data:link.target'><data:link.name/></a></li>
                  </b:loop>
                </ul>
              </b:includable>
            </b:widget>
          </b:section>
        </div>
        
        <div class='ftrBtm'>
          <b:section id='Footer: Copyright'>
            <b:widget id='HTML3' locked='false' title='2023' type='HTML' version='2' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='content'/>
              </b:widget-settings>
              <b:includable id='main'>
                <b:if cond='data:content == &quot;&quot;'>
                  <p class='ftrBtmTxt'>&#169; 2023 &#8231; <b><data:blog.title/></b>.</p>
                  <b:else/>
                  <p class='ftrBtmTxt'><data:content/></p>
                </b:if>
              </b:includable>
            </b:widget>
          </b:section>
        </div>
      </footer>
    </div>
    
    <!--[ Scripts ]-->
    <script>/*<![CDATA[*//* timeAgo.js */document.querySelectorAll("#timeAgoR").forEach((element) => {const timestamp = new Date(element.getAttribute("datetime"));element.innerText = timeago.format(timestamp);});/*]]>*/</script>
    <b:if cond='data:view.isPost'><script>/*<![CDATA[*/ /* Ads */document.getElementById('AdsInBeforePostBody').innerHTML = document.getElementById('HTML8').innerHTML;document.getElementById('AdsInAfterPostBody').innerHTML = document.getElementById('HTML7').innerHTML;document.getElementById('HTML8').innerHTML = '';document.getElementById('HTML7').innerHTML = ''; /* Read Min */function get_text(el) {ret = ""; var length = el.childNodes.length; for(var i = 0; i < length; i++) {var node = el.childNodes[i]; if(node.nodeType != 8) {ret += node.nodeType != 1 ? node.nodeValue : get_text(node);} } return ret;} var words = get_text(document.querySelector('.bMPPMPost')); var count = words.split(' ').length; var avg = 185; var counted = count / avg; var maincount = Math.round(counted); document.querySelector(".readTime").innerHTML = maincount + " min read";/*]]>*/</script></b:if>

    <b:if cond='!data:view.isPreview'>&lt;!--</b:if></body><b:if cond='!data:view.isPreview'>&lt;/body&gt;</b:if>
</html>