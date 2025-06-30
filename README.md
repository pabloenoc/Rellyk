# Rellyk

Rellyk is a Rakefile-based blog management system for Jekyll websites. This is the Rakefile I use on my personal website [ENOCC.com](https://enocc.com) for managing blog posts from the terminal.

## Features

- Start development server
- Build site for production
- Create new posts with populated front matter 
- Organize markdown files `_posts/` directory by year and month
- Manage all posts
- Manage recent posts
- Colorized terminal output

## Getting Started

Simply copy or download the Rakefile to the root directory of your Jekyll site and you'll have access to all Rake tasks.

### Start Development Server

``` bash
$ rake serve
```

Since the `serve` command is the default task, simply running `$ rake` will also start the local server.

### New Blog Post

``` bash
$ rake posts:new
```

### See All Blog Posts

``` bash
$ rake posts:all
```
