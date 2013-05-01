# README #

Octopress plugin to generate tag pages. Based upon the jekyll category page generator plugin by Dave Perrett.

Version: 0.4


## Getting Started #

Put `tag_generator.rb` in the `/plugins` folder. Then add the `tag_index.html` file to `/source/_layouts`. Some additional files are provided in `/source/_layouts` and `/source/_includes` to demonstrate basic usage. This plugin can be paired with an [octopress tag cloud plugin](https://github.com/robbyedwards/octopress-tag-cloud) to create tag clouds.


## Usage #

Included filters :

- `tag_links`:           Outputs the list of tags as comma-separated `<a>` links.
- `date_to_html_string`: Outputs the `post.date` as formatted html, with hooks for CSS styling.

Available _config.yml settings :

- `tag_dir`:          The subfolder to build tag pages in (default is `tags`).
- `tag_title_prefix`: The string used before the tag name in the page title (default is `Tag: `).


## License #

Copyright (c) 2012 Robby Edwards, http://robbyedwards.com/
Licensed under the MIT license (http://www.opensource.org/licenses/mit-license.php)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
