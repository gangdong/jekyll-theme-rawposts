# jekyll-theme-rawposts
rawposts is a free jekyll portfolio-style theme, which is designed to be as a starting point for any Jekyll website.

`[Theme Author]`: David Dong  
`[License]`: MIT License  

![screenshot]({{site.baseurl}}/assets/screenshot.png)

### [Theme Demonstration](https://gangdong.github.io/daviddong.github.io/blog/index.html)  

### Features
------
+ Fully responsive
+ Optimized for tablets & mobiles
+ Pagination
+ Archive posts
+ Category posts
+ Gittalk
+ Disqus
+ Google analytics
+ busuanzi analytics
+ rss
+ jemoji for emoji
+ dark mode selectable

### Plugins
------
+ jekyll-seo-tag
+ jemoji
+ kramdown
+ jekyll-archives
+ jekyll-paginate

### Installation
------
1. fork the theme at [here]().
2. clone the repository to your local machine.
3. Run the command `bundle install` in the root of project to install the theme and its dependencies.
4. Run `bundle exec jekyll server` to build and serve your site.
5. Done! Next you can customize your own website through the _config.yml

### Customization & Configuration
------
you can use the _config.yml file to configuration the features and contents on this theme. 

#### `Site personal settings`
You'll need to change the description, title and url to match with the project. You'll also need to replace the logo, default social and default offline images in the /assets/ directory with your own graphics.The email needs to be changed to the email you want to receive contact form enquirers with. 
The default of this theme are my settings and just replace with yours.
#### `show_excerpts`
set to true to show excerpts on the homepage
#### `paginate`
set the number of posts of each pages.
#### `paginate_path`
set the path of pages in your site.
#### `sitemap`
set to true to generate sitemap.xml content
#### `dark_mode`
set to true to add dark mode toggle
#### `reading_time`
set to true to add reading time statistics
#### `archives`
set to true to generate archives page 
#### `categories`
set to true to generate categories page
#### `gittalk`
set to true to add gittalk 
#### `show_statistics`
set to true to show statistics of site visitors number
#### `rss`
set to true to add rss 
#### `source_code` 
set to true to add link to source code

### Include Files
------
There are some necessary `.html` files for the site's features and they are in the different folders.

#### `index.html`
index.html is the entry of homepage and is in the `/blog` folder.

#### `archives.html`
archives.html is for the archives function and is in the `/archives` folder.

#### `categories.html`
categories.html is used for category of the posts and is in the `/category` folder.

#### `about.html`
for about content display and is in the `/about` folder.

#### `pagination.html`
for paginate the pages and is in the `_includes` folder.

#### `reading_time.html`
reading_time.html is used for statistic the reading time of posts and display. it is in `_includes` folder.

#### `title.html`
used for setting the menu bar of the homepage, is in the `_includes` folder.

### Development
------
To set up your environment to develop this theme:

1. Clone this repo
2. cd into /example and run `bundle install`.

To test the theme the locally as you make changes to it:

1. cd into the root folder of the repo (e.g. jekyll-theme-rawposts).
2. Run `jekyll server` to preview and open your browser to http://localhost:4000/.

This starts a Jekyll server using the theme's files and contents of the / directory. As modifications are made, refresh your browser to see any changes.

### Pull Requests
------
When submitting a pull request:

1. Clone the repo.
2. Create a branch off of master and give it a meaningful name (e.g. my-awesome-new-feature) and describe the feature or fix.
3. Open a pull request on GitHub.

Welcome to submitting pull requests to me, for any submitting, I will review as soon as possible and merge any good good submits.

### Version
------
1.0.0

### Q & A
------
to be continued...

### Contact
------
Welcome raise issues if you have any questions about this theme, for usage, bug fix, new features requirements...