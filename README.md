# html-template
 This is meant as a copy-paste quickstart for creating a new static HTML project.
<!--
  In the past, the DOCTYPE was needed to specify HTML versions.
  As of HTML5, providing `html` is sufficient.
  It is somewhere between a proper HTML tag, and an HTML comment.
-->
<!DOCTYPE html>
<!-- Add the appropriate language for your site -->
<html lang="en">
<head>
  <!--
    UTF-8 is a character set including many universal characters.
    This is an essential tag for all websites, to avoid seeing
    weird boxes like ▢▢▢
  -->
  <meta charset="utf-8">
  <!--
    This critical tag ensures that items on the screen scale
    correctly on mobile devices. Without this tag, content may
    appear VERY tiny.
  -->
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!--
    Set your name and a brief description.
    Used by search engines.
  -->
  <meta name="author" content="Your name">
  <meta name="description" content="Brief description">
  <!--
    `og` stands for Open Graph, which is a protocol for how your
    website appears when linked to from another site. These tags
    are critical to ensuring your site gains an appropriate card
    when sharing on social media.
  -->
  <meta property="og:title" content="Your Page Title">
  <meta property="og:description" content="Brief description">
  <meta property="og:image" content="/some-image.png">
  <meta property="og:url" content="/this-page.html">
  <meta property="og:site_name" content="Your Site Name">
  <!--
    `twitter` is similar to Open Graph, but specific to Twitter.
    There are multiple card types you can choose from.
    Learn more on Twitter's documentation:
    https://developer.twitter.com/en/docs/tweets/optimize-with-cards/guides/getting-started
  -->
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image:alt" content="Image descriptipn">
  <!-- Include one or more CSS files -->
  <link href="style.css" rel="stylesheet">
  <!--
    A favicon is the small picture that shows up in the browser's
    tab. Historically, these used a proprietary ".ico" format, and
    you needed to provide many different sizes.
    Happily, you can now provide a single vector graphic in SVG
    format. It will scale to any size, and still look crisp.
  -->
  <link rel="icon" type="image/svg+xml" href="/favicon.svg">
  <!-- This title shows up in the page's tab, next to the favicon -->
  <title>Your Page Title</title>
</head>
<body>
  <h1>Your content here!</h1>
  <!-- If necessary, include JS -->
  <script src="script.js"></script>
</body>
</html>