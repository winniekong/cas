# Welcome to Youth Code the Future / Cohort 2

## Course Introduction

The 2-hour course will teach how to use **HTML5** (Hypertext Markup Language), **CSS** (Cascading Style Sheets), online tools and resources to build and deploy a website. You will learn to structure, arrange site content and define the content as, for example, headings, paragraphs, or images to tell your story.

## What is the Internet?

The Internet is a network, or system, that connects millions of computers worldwide.

- [The Internet: HTTP & HTML](https://www.youtube.com/watch?v=kBXQZMmiA4s)
- [What is the world wide web? - Twila Camp](https://www.youtube.com/watch?v=J8hzJxb0rpc)

**Black History Month - Philip Emeagwali**

The web owes much of its existence to Philip Emeagwali, a math whiz who came up with the formula for allowing a large number of computers to communicate at once.
[https://en.wikipedia.org/wiki/Philip_Emeagwali](https://en.wikipedia.org/wiki/Philip_Emeagwali)

## What is a web\_\_\_?

A **webpage** is a single page shown in a web browser. A single video page on YouTube.com is a webpage.

A **website** is a collection of webpages under a single URL (Uniform Resource Locator). Youtube (youtube.com) is a website.

A **web host** is the computer which holds the web server and database.

A **web application** is a website which offers advanced functionality like a computer program would. An example of a web application would be a web based calendar, or web based email. Youtube.com is also a web application

### IP Address

IP stands for Internet Protocol and is an address that is assigned to each domain on the web.
Type into the browser address bar
216.58.217.206

### Website

A _website or web site_ is a page or collection of pages on the World Wide Web that contains specific information which was all provided by one person or entity and traces back to a common _Uniform Resource Locator (URL)_.

URL is an acronym for Uniform Resource Locator and is a reference (an
address) to a resource on the Internet.

- For the URL http://example.com , the protocol identifier is http or https.
- For the URL http://example.com , the resource name is example.com
- [Real Talk about HTTPS](https://www.youtube.com/watch?v=iP75a1Y9saY)

### URL

URL is an acronym for Uniform Resource Locator and is a reference (an address) to a resource on the Internet.

For the URL http://example.com , the protocol identifier is http or https.

For the URL http://example.com , the resource name is example.com

Real Talk about HTTPS: https://www.youtube.com/watch?v=iP75a1Y9saY

### SSL or SSL/TLS

SSL (Secure Sockets Layer) and its successor, TLS (Transport Layer Security), are protocols for establishing authenticated and encrypted links between networked computers.

- [https://www.entrepreneur.com/article/281633](https://www.entrepreneur.com/article/281633)
- [https://letsencrypt.org](https://letsencrypt.org)

### What is browser?

A _web browser_ (commonly referred to as a browser) is a software application for accessing information on the World Wide Web.

Most used web browser by country, as of June 2015. Google
Chrome, Firefox, Safari, UC. Iron, Microsoft Edge, Opera and Android.

### Browsers to Install

Google Chrome
[Download](https://www.google.com/chrome/)

Safari - Apple
[Download](https://support.apple.com/downloads/safari)

Firefox browser
[Download](https://www.mozilla.org/en-US/firefox/download/thanks/)

Firefox Quantum: Developer Edition
[Download](https://www.mozilla.org/en-US/firefox/developer/)

Opera browser
[Download](https://www.opera.com/)

Microsoft Edge

- [Download](https://www.microsoft.com/en-us/windows/microsoft-edge)
- [Learn more about Chrome-like Edge browser](https://www.cnet.com/news/microsoft-releases-its-google-chrome-like-edge-browser-for-testing/)

### The Keyboard

![](https://cdn.glitch.com/a813cfc9-cd0e-4e81-9725-c22074e7a34a%2Fkeyboard.svg?v=1591896216657)

The 104-key US QWERTY layout

### Keyboard Symbols

#### HTML

- `<!-- my comment statement in HTML -->` HTML Comment
- `!` exclamation mark
- `<` less than
- `>` greater than
- `/` backslash
- `=` equal
- `' '` single quote
- `" "` double quote
- `-` dash / hyphen
- `_` underscore
- `;` semicolon

#### CSS

- `/* my comment statement in CSS */` CSS Comment
- `@` the at sign used for `@import 'normalize.css';`
- `(` open parenthesis
- `)` close parenthesis
- `.` period
- `#` **pound / number sign** or hashtag
- `{ }` curly brace / bracket
- `{` open curly brace / open bracket
- `}` close curly brace / close bracket
- `-` dash / hyphen
- `_` underscore
- `' '` single quote
- `" "` double quote
- `:` colon
- `;` semicolon

#### Keyboad Commands

![](https://cdn.glitch.com/bc2980dc-21e3-43fc-8c6c-5e88354fe0de%2Fkeyboard-commands.jpg?v=1583946028507)

### Keyboard shortcuts for Windows

Applies to: [Windows 10 Windows 8.1 Windows 7](https://support.microsoft.com/en-us/help/12445/windows-keyboard-shortcuts)

### Keyboard shortcuts for Mac

By pressing certain key combinations, you can do things that normally need a mouse, trackpad, or other input device. [Learn more](https://support.apple.com/en-us/HT201236)

## HTML

HTML stands for _HyperText Markup Language_. Developed by scientist Tim Berners-Lee in 1990, HTML is the "hidden" code that helps us communicate with others on the World Wide Web (WWW).

HTML tags : HTML documents are described by HTML tags. Each HTML tag describes different content element in a document. Here are some examples:

- The text between `<html> and </html>` describes an HTML document
- The text between `<head> and </head>` provides information about the document The text between `<title> and </title>` provides a title for the document
- The text between `<body> and </body>` describes the visible page content
- The text between `<h1> and </h1>` describes a heading
- The text between `<p> and </p>` describes a paragraph

### HTML Template

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>HTML Template</title>
</head>
<body>
  <!-- HTML Element Tags -->
</body>
</html>
```

### Placeholder text and images

- [Lorem Ipsum](https://www.lipsum.com/) Lorem ipsum is a placeholder text commonly used to demonstrate the visual form of a document or a typeface without relying on meaningful content.
- [Lorem Picsum](https://picsum.photos/) Lorem Ipsum for photos.

### Sample Code using HTML5 tags

- Incluces live preview `meta` tags

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Web Development 101</title>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!--     Standard HTML meta tags -->
    <meta property="title" content="Standard Title Element Tags" />
    <meta name="description" content="Standard HTML5 elements to your file" />
    <meta name="keywords" content="HTML, CSS, Glitch, Github, Git" />
    <meta name="author" content="Your Name" />
    <!--     Social Media meta tags -->
    <meta property="og:title" content="Using HTML5 Element Tags" />
    <meta
      property="og:description"
      content="How to add for Facebook HTML5 elements to your file"
    />
    <meta
      property="og:image"
      content="https://cdn.glitch.com/f9cf2342-2a00-49fc-a880-3a7927d94f28%2Fpicsum-landscape.jpg?v=1595267771728"
    />
    <meta
      property="og:url"
      content="https://agvep-yctf-2.glitch.me/index.html"
    />

</head>
  <body>
    <header>
      <nav>
        <menu>
          <ul>
            <li>About</li>
            <li>Portfolio</li>
            <li>Resume</li>
            <li>Contact</li>
          </ul>
        </menu>
      </nav>
    </header>
    <aside>
      <div class="sidebar">
        <h2>Sidebar Header</h2>
        <p>This is the sidebar content.</p>
      </div>
    </aside>
    <main>
      <div class="site-content">
        <h1>Week One: HTML Sample Code</h1>
        <p>This class is awesome!</p>
      </div>
    </main>
    <footer>
      <p>&copy 2020 <br/> Author: First and Last Name</p>
    </footer>
  </body>
</html>
```

## HTML Resources

- [The Essential Meta Tags for Social Media | CSS-Tricks](https://css-tricks.com/essential-meta-tags-social-media/)
- What is a [Favicon](https://en.wikipedia.org/wiki/Favicon)

  - [How to Add a Favicon to your Site](https://www.w3.org/2005/10/howto-favicon)

- [html cheat sheet](https://lifeyourway.net/printables/blogging-html-cheat-sheet.pdf)
- [https://www.w3schools.com/tags/](w3schools.com/tags)
- [developer.mozilla.org/en-US/docs/Learn/HTML](developer.mozilla.org/en-US/docs/Learn/HTML)

## CSS

CSS stands for Cascading Style Sheets and it represents the design conventions that are applied to the display of HTML elements on screen, paper and other media.

CSS syntax is expressed in the form of a rule-set consisting of a selector and a declaration box. Colors are specified using pre-defined color names. CSS can be added to HTML elements in three ways: inline, internal and external.

## CSS: Three Styling Methods

### Inline CSS

- Using the `style` attribute eg.

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Simple HTML and Inline CSS</title>
</head>
<body>
  <h1 style="background-color: yellow; color: black; text-align:center;">My First HTML with Inline CSS</h1>
  <img src="https://picsum.photos/300" alt="Lorem Picsum" style="display: block; margin: 5% auto;">
  <div class="container" style="border: 3px solid red;">
    <p style="background-color: green; color: yellow; padding: 10px 5px 20px 5px; margin: 20px 20px 20px 20px;">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    </p>
  </div>
</body>
</html>
```

### Internal CSS

```
<head>
  <style type="text/css">
    p {
      color: red;
    }
  </style>
</head>
```

### External CSS

```
<head>
  <link rel="stylesheet" href="style.css" />
</head>
```

### Sample Code

```
body {
    background-color: powderblue;
}
h1 {
    color: white;
    text-align: center;
}
p {
    font-family: Verdana;
    font-size: 20px;
}
```

# CSS Resources

- [Normalize.css](https://necolas.github.io/normalize.css/) makes browsers render all elements more consistently and in line with modern standards.

- Learn how to create [tabs](https://www.w3schools.com/howto/howto_js_tabs.asp) with CSS and JavaScript.

- The [World Wide Web Consortium (W3C)](https://www.w3.org/) is an international community that develops open standards to ensure the long-term growth of the Web.

- [Font Awesome](https://fontawesome.com/) vector icons and social logos on your website.

- Creating wireframs with [Adobe XD](https://www.adobe.com/au/creativecloud/business/enterprise/how-to-wireframe-xd.html)

#### Colors Tutorial

[CSS Color Values](https://www.w3schools.com/colors/default.asp) - With CSS, colors can be specified in different ways:

By color names

- As RGB values
- As hexadecimal values
- As HSL values (CSS3)
- As HWB values (CSS4)
- With the `currentcolor` keyword

[W3schools Color Converter](https://www.w3schools.com/colors/colors_converter.asp)

[Adobe Kuler](https://color.adobe.com/explore) - Selecting color palettes

#### CSS @font-face Rule

The `@font-face` rule allows custom fonts to be loaded on a webpage.

- [Learn more](https://css-tricks.com/snippets/css/using-font-face/)

#### CSS @import Rule

The `@import` rule allows you to import a style sheet into another style sheet.

- Using the @import rule to add external font-family from [Google Fonts](https://fonts.google.com/)
- Adding [CSS Web Fonts](https://www.w3schools.com/css/css3_fonts.asp) allows the use of fonts that are not installed on the user's computer/browser.

```
/*
  Google Font - https://fonts.google.com/
*/
@import url('https://fonts.googleapis.com/css?family=Lato|Roboto&display=swap');

body {
    background-color: powderblue;
    font-family: 'Lato', sans-serif;
}
h1 {
    color: white;
    text-align: center;
    font-family: 'Roboto', sans-serif;
}
p {
    font-family: Verdana;
    font-size: 20px;
}
```

#### CSS @media Rule

The [@media rule](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp) is used in media queries to apply different styles for different media types/devices.

- [Media Queries for Standard Devices](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)
- [Understanding Media Types](https://www.w3schools.com/css/css3_mediaqueries.asp)

```
body {
    background-color: powderblue;
    font-family: 'Lato', sans-serif;
}
h1 {
    color: white;
    text-align: center;
    font-family: 'Roboto', sans-serif;
}
p {
    font-family: Verdana;
    font-size: 20px;
}

@media all and (max-width: 736px) {
  body {
    background-color: yellow;
  }
}
```

## Bootstrap

[Bootstrap](https://getbootstrap.com/) is an open source toolkit for developing with HTML, CSS, and JS.

### Get started with Bootstrap

- [Starter Template](https://getbootstrap.com/docs/4.4/getting-started/introduction/#starter-template)

```
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

    <title>Welcome to Bootstrap</title>
  </head>
  <body>
    <h1>My First Code</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
  </body>
</html>
```

### Most Commonly used Features

- [Grid system](https://getbootstrap.com/docs/4.4/layout/grid/#how-it-works) - build layouts using containers, rows, and columns to layout and align content.
- [Bootstrap Containers](https://getbootstrap.com/docs/4.4/layout/overview/#containers) - Containers are the most basic layout element in Bootstrap and are required when using our default grid system.
- [Navbar / brand](https://getbootstrap.com/docs/4.4/components/navbar/#brand)
- [Navbar / navigation](https://getbootstrap.com/docs/4.4/components/navbar/#nav) - support for branding, navigation, and more
- [Cards](https://getbootstrap.com/docs/4.4/components/card/#content-types) - A card is a flexible and extensible content container. It includes options for headers and footers, a wide variety of content, contextual background colors, and powerful display options.
- [Jumbotron](https://getbootstrap.com/docs/4.4/components/jumbotron/) - component for showcasing hero unit style content.
- [Buttons](https://getbootstrap.com/docs/4.4/components/buttons/#examples) - custom button styles for actions in forms, dialogs, and more with support for multiple sizes, states, and more.
- [CSS Flexbox](https://getbootstrap.com/docs/4.4/utilities/flex/#enable-flex-behaviors)

### Using Terminal

- Open **Terminal**
  ![](https://hf-files-oregon.s3.amazonaws.com/hdpglitch_kb_attachments/2020/05-06/0f961dba-8003-4a74-af94-a830b5990e19/Terminal.gif)
- Change a filename
  - [Learn](https://shapeshed.com/unix-mv/) Linux and Unix mv command tutorial with examples
    ```
    mv oldfilename.html newfilename.html
    ```
- Make a **new file** using `type touch` - touch is hashed (/usr/bin/touch). Touch is a tool to create empty files and modify timestamps; We are creating empty files.

```
touch filename.html
```

- `type echo` is a shell builtin. Add **content** in the new file.

```
echo "<!DOCTYPE html>" >> filename.html
```

- Refresh page / Glitch project

```
refresh
```

## Your Project

That's this file, where you can tell people what your cool website does and how you built it.

### ← index.html

Where you'll write the content of your website.

### ← style.css

CSS files add styling rules to your content.

### ← script.js

If you're feeling fancy you can add interactivity to your site with JavaScript.

### ← assets

Drag in `assets`, like images or music, to add them to your project

## Commit Using Git

What is [Git](https://git-scm.com/)?

- GIT is not **GitHub**
  - GitHub is just a platform used to save and store your code, and track its versions in a more
    visual way.
- Git is a free and open source distributed version-control system for tracking changes in source code during software development.
- Learn how to use Git to enhance your experience using GitHub. Click [here](https://docs.github.com/en/github/using-git)
- [Git cheat sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)
- Managing remote repositories. Click [here](https://docs.github.com/en/github/using-git/managing-remote-repositories)

### Using Git in Glitch

Open **Terminal**

Terminal **Git** comments

```
git branch
git add .
git commit -m "explain what changes you made as the reasoning for commiting to Github repo"
git remote add origin https://github.com/<username>/cas.git
git push origin master
```

- Username for 'https://github.com': `<username>`
- Password for 'https://berryny@github.com': `<your password>`

### Connect from Desktop to Github

- Create a new repository on the command line

```
echo "# <repo name>" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin master
```

- Push an existing repository from the command line

```
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin master
```

### Create a README.md: Basic writing and formatting syntax

Create sophisticated formatting for your prose and code on GitHub with simple syntax.
[Learn more](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)
