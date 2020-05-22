# How to contribute?

Content: 
-   Get Started
-   Using Jekyll (Basic Usage)
    -   Add a page
    -   Add a post
    -   Change theme’s design
    -   Liquid
    -   Configuration
    -   Build locally
    -   Git Push

This guide explains how to contribute to our documentation!

## Get Started

First, install jekyll:

[Installation Guide](https://jekyllrb.com/docs/installation/)

Clone the repository and then check out the branch:

```
cd your_repo_root/repo_name
git fetch origin
git checkout gh-pages

```

  

## Using Jekyll (Basic Usage)

### Add a page

Create a markdown file in the root of the project.

### Add a post

Create a markdown file in the  __posts_  folder. Jekyll requires post files to be named according to the following format:

> YEAR-MONTH-DAY-title.MARKUP

### Change theme’s design

You can change the design by modifying the css files in  __sass_  or  _css_  folder. You can also add your css file inside  __sass_  folder and include a reference to it on  __includes/head.html_.

### Liquid

Jekyll uses the standard Liquid templating language package.  [Jekyll Variables](https://jekyllrb.com/docs/variables/)

### Configuration

Using  __config.yml_. Site’s title, description, baseurl, twitter and github username as many other configurations are included here.

[Link](https://jekyllrb.com/docs/configuration/)

### Build locally

If you want to display the changes locally before pushing, use this command:

```
jekyll build --increment

```

This command builds a static website according the contents of the project. The output is under the  __site_  folder.

### Git Push

```
git add
git commit
git push origin gh-pages
```
