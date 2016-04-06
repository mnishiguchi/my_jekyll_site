# My Jekyll site
My blog site powered by [Jekyll](https://jekyllrb.com/)

## Reference
- [Getting Started with Jekyll](https://scotch.io/tutorials/getting-started-with-jekyll-plus-a-free-bootstrap-3-starter-theme) by Scotch
- [Is Jekyll Better Than Joomla! and WordPress?](http://digitalshore.io/jekyll-better-choice-than-joomla-wordpress/)
- [Make a Static Website with Jekyll](https://www.taniarascia.com/make-a-static-website-with-jekyll/) by Tania Rascia
- [How I Created a Beautiful and Minimal Blog Using Jekyll, Github Pages, and poole](http://joshualande.com/jekyll-github-pages-poole/) by Joshua Lande
- [Codrops](http://tympanus.net/codrops/) - Ideas for UI
- [Using a custom domain with GitHub Pages](https://help.github.com/articles/using-a-custom-domain-with-github-pages/)

==

## Objectives of this project
- Creating my own portfolio website.
- Build on Jekyll.

==

## Scheduling
### Week 1 - 2 (Deadline: April 11)
- Gathering assets
- Thumbs and roughs (Wireframes)
- Processing assets (e.g., resizing, cropping etc)
- HTML

### Week 3 - 4 (Deadline: April 25)
- CSS

### Week 5
- Testing
- Deployment

==

## [Jekyll commands](https://scotch.io/tutorials/getting-started-with-jekyll-plus-a-free-bootstrap-3-starter-theme#commands)
### Starting the server
- Run `bundle exec jekyll serve`, then visit http://127.0.0.1:4000/

### Building
- Run `bundle exec jekyll build`

==

## User experience misconceptions
- [UX Myths](http://uxmyths.com/)
- [deathtobullshit.com](http://deathtobullshit.com/)

==

## Troubleshooting

### [Jekyll choking on something when running the Jekyll site locally](https://github.com/jekyll/jekyll/issues/3103)

```
gem cleanup
bundle exec jekyll serve here
```

### [Jekyll serve didnt work: It looks like you don't have pygments or one of its dependencies installed](http://stackoverflow.com/a/33440992/3837223)

```rb
# Gemfile
gem 'pygments.rb'
```

==

## [kramdown](http://kramdown.gettalong.org/)
- a free MIT-licensed Ruby library for parsing and converting a superset of Markdown.

==

## [coderay](http://coderay.rubychan.de/)
