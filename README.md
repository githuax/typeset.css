# Typeset.css

A baseline set of styles for content.

### What this is

Typeset.css is a CSS file (`typeset.css`) that includes all the styles you need to ensure content on your site is styled. Styles are only applied to areas that have a parent element with the class `typeset`, so it can be limited to content-specific markup.

### And what this is *not*

This is *not* a CSS framework for styling the layout and design of your website - just blocks of content (paragraphs, lists, code snippets, and so on).

### When to use this

Any time you have stripped a browser’s default styles or haven’t specified styles for content elements, use Typeset.css. It’s great for:

* Blog posts
* Articles
* Comments
* Helper text in web apps
* and any other content blocks on a page

Never again add content to your web page just to find that you don’t have a consistent style for it&trade;.

### Why this was made

Typeset was originally created for user-generated content on UserVoice feedback forums ([here’s an example UserVoice forum](http://feedback.uservoice.com/forums/1-general-feedback)), and then expanded to work with content generated by UserVoice-powered knowledge base articles ([example article](http://feedback.uservoice.com/knowledgebase/articles/59012-advanced-css-custom-design-with-body-classes)). Because users create these articles using a WYSIWYG editor with HTML-editing capabilities, we needed to make sure we had a base set of styles for any content-related markup.

### How to use this

1. [Download](https://github.com/joshuarudd/typeset-css/zipball/master) and add the `typeset.css` file to your page.
2. Add the `typeset` class name to the parent element that wraps the content you want styled with Typeset.css.

Example:

    <div class="comment-body typeset">
      <p>Do you see any Teletubbies in here? Do you see a slender plastic tag clipped to my shirt with my name printed on it? Do you see a little Asian child with a blank expression on his face sitting outside on a mechanical helicopter that shakes when you put quarters in it? No? Well, that's what you see at a toy store. And you must think you're in a toy store, because you're here shopping for an infant named Jeb.</p>
      …
    </div>

(*Lorem ipsum* generated by http://slipsum.com.)

Also, [check out http://joshuarudd.github.com/typeset.css/](http://joshuarudd.github.com/typeset-css/) for examples of all the HTML elements styled with Typeset.css.
