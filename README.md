# SPYRUS Document Server

## Markdown content for SPYRUS Documentation Server

Markdown uses a very simple formatting syntax to accomplish the same thing that HTML or Rich Text Formatting does. The difference is that it's simpler than HTML and you don't have to worry about opening and closing tags. ... To format text, Markdown uses punctuation and characters you're already familiar with.

Documentation can be authored in markdown or can be converted from several common formats to markdown.  The markdown can be used directly on sites where the documentation will be posted (github, bitbucket, visualstudio online, etc.), or it can be converted to html generating a site for users browse.  
 * MKDocs
 * Wordpress
 * etc.

Documents created using [Helpndoc](https://www.helpndoc.com/) can also generate web content to be used directly on a website, or it can be saved as word or pdf and converted to markdown for inclusion in this site.

### Markdown Tools

This section will grow as suggestions are added to edit markdown on different platforms.  Markdown support is built into VSO and can be edited directly with a basic markdown editor directoy in the source control with preview support.

1. [MKDocs](#mkdocs) markdown to website generator (see below).
1. [Mashable Article on Markdown Tools](https://mashable.com/2013/06/24/markdown-tools/)
2. Host a website directly in Github or any web server using [MDWiki](http://dynalon.github.io/mdwiki/#!index.md)

### Markdown References

1. [Markdown Tutorial](https://www.markdowntutorial.com/)
2. [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
3. [Github Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
4. [Markdown Syntax](https://developers.google.com/web/resources/markdown-syntax#custom_attributes_and_named_anchors)


## MKDocs <a name="mkdocs"></a>
MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file.

For full documentation visit [mkdocs.org](http://mkdocs.org).

### Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

### Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


## Doxygen

Doxygen suports genrating markdown, see the doxygen manual: [Doxygen Markdown Support](https://www.stack.nl/~dimitri/doxygen/manual/markdown.html)
