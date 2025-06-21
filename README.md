
## Step-by-Step: Deploy Jekyll to GitHub Pages
1. ✅ Create a GitHub Repository
Go to github.com/new

Name it something like: blog

Choose Public

Don't initialize with README (you’ll push your local files)

2. ✅ Prepare Your Local Jekyll Site
Inside your myblog folder:

git init
# Add all files
git add .
# Commit changes
git commit -m "Initial Jekyll blog"
# Add remote (replace with your actual repo URL)
git remote add origin https://github.com/dadinjaenudin/blog.git
# Push to GitHub
git push -u origin master


### Enable GitHub Pages
Go to your repo:
👉 https://github.com/dadinjaenudin/blog

Then:
Go to Settings tab
Scroll down to Pages (left sidebar or bottom area)
Under Source, select:

Branch: main

Folder: / (root)

Click Save
You should now see a green confirmation banner like:

Your site is published at https://dadinjaenudin.github.io/blog/





Freshman21
==========

Freshman21 is a Jekyll blog theme, base on theme [Freshman](http://github.com/yulijia/freshman). 

A tribute to WordPress Theme Twenty-Twelve and Twenty-eleven.

Enjoy.


![Screen](http://i.imgur.com/oSp7kacl.png)

### Version 2.1 update 2016.06.06

- master branch: the simplest template, original version with
	* Open Graph META Tags
	* Microdata(schema.org)

- gh-pages branch: master branch with 

	* [google analytics js template](https://github.com/yulijia/freshman21/blob/gh-pages/_includes/google_analytics.js)
        * [BackToTop js script](https://github.com/yulijia/freshman21/tree/gh-pages/js)
        * <q>readmore</q> module
        * [keyboard shortcuts for pagination](http://yulijia.net/freshman21/news/2016/05/24/new-features.html)
	* font awesome icon
	* [Google search](https://github.com/yulijia/freshman21/blob/gh-pages/_includes/google_search.js)

Clone master branch: 

` git clone https://github.com/yulijia/freshman21.git -b master --single-branch`

Clone gh-pages branch: 

`git clone https://github.com/yulijia/freshman21.git -b gh-pages --single-branch`


### A Summary of Features

- Provide single column and two columns layout
- Powerful configure file
- Comments by Disqus
- Support LaTeX (by MathJax)
- Syntax highlighting
- Multiple Languages support 
    * English
    * Chinese
    * Japanese (Contributed by [kokeiro001](https://github.com/kokeiro001))
    * Polish (Contributed by [Derson5](https://github.com/Derson5))
    * Korean (Contributed by [Clifford Choi](https://github.com/ulgoon))
    * Russian (Contributed by [Anton Alekseev](https://github.com/alexeyev))
    * Turkish (Contributed by [Muhammet Kara](https://github.com/mrkara))
    * Indonesian (Contributed by [Samsul Ma'arif](https://github.com/samsulmaarif))

### How to install this theme?

```
# please make sure you have already installed git tools and ruby tools(gem)
$ gem install sass
$ gem install jekyll
$ git clone https://github.com/yulijia/freshman21.git
$ mv freshman21/ yourblogname.github.io/

```

### Demo

Single column, please see [my own blog](http://yulijia.net/en/)

Two columns, please see the [theme website](http://yulijia.net/freshman21/)


