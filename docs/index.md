doctype html
html
    head
        title Learn to code HTML, CSS and JavaScript
        meta(name="description", content="This is an HTML replica of w3schools.com")
        style
            include style.scss
    body 
        header
            style
            a.current(href="/") Home
            a(href="/html") HTML
            a(href="/css") CSS
            a(href="/javascript") JavaScript

        article
            h1 This is a replica of w3schools.com
            p This HTML tutorial contains hundreds of HTML examples. With our online HTML editor, you can edit the HTML, and click on a button to view the result. 
            h2 HTML
            p The language for building webpages. #[a(href="/html") Check it out!]
            h2 CSS
            p The language for styling webpages! #[a(href="/css") See awesomeness happening!]
            h2 JavaScript
            p The language for programming webpages! #[a(href="/javascript") Discover the way up!]

        nav
            h3 HTML and CSS
            a(href="/html") Learn HTML
            a(href="/css") Learn CSS
            a(href="/javascript") Learn JavaScript

        footer &copy; 2017 My name is Gabriel.
