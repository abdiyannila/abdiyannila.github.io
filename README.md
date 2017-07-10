# Start Jekyll
* [Demo](http://abdiyannila.github.io)

A getting started exercise with Jekyll. Jekyll with a simple and blog-aware static site generator built in Ruby.
- Learn about static site generators
- Create a custom website running on Jekyll and Sass

### Layouts

Refers to files within the `_layouts` directory, that define the markup for your theme.

  - `default.html` &mdash; The base layout that lays the foundation for subsequent layouts. 
  - `page.html` &mdash; The layout for your documents that contain FrontMatter, but are not posts.
  - `post.html` &mdash; The layout for your posts.

 ### Includes

Refers to snippets of code within the `_includes` directory that can be inserted in multiple layouts (and another include-file as well) within the same theme-gem.

  - `footer.html` &mdash; Defines the site's footer section.
  - `head.html` &mdash; Code-block that defines the `<head></head>` in *default* layout.
  - `header.html` &mdash; Defines the site's main header section.

### Sass

Refers to `.scss` files within the `_sass` directory that define the theme's styles.

  - `_base.scss` &mdash; Resets and defines base styles for various HTML elements.
  - `_layout.scss` &mdash; Defines the visual style for various layouts.
  - `_syntax-highlighting.scss` &mdash; Defines the styles for syntax-highlighting.

### CSS to import all file from Sass
### Blog to display  '_posts' 

This is just a starter theme!
## Getting Started
	To start coding away, first clone this repository  (http://abdiyannila.github.io)

	```
	git clone https://......
	```

	Then run Jekyll [if you don't have Jekyll installed, see the tutorial or docs](https://jekyllrb.com):

	```
	jekyll clean
	jekyll serve
	```

	Open browser and change `url` to:
	```
	http://127.0.0.1:4000
	```

For Start Coding.
## Docs
	Read the tutorial!  
	[docs](https://jekyllrb.com/docs/home).

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).






