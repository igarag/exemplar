# Exemplar - A Jekyll Template

This is my Jekyll site template version forked from [Tybenz](http://tybenz.github.io/exemplar/) and updated for Jekyll 3.8. Used for blog and project pages.

## Requirements.

First of all, if you don't have Ruby installed you can follow [this guide](https://www.ruby-lang.org/es/documentation/installation/#apt). After that, make sure you have the `jekyll` and `sass` *gems* installed. In your terminal run:

```
gem install jekyll
gem install sass
```

You can optionally install the *bourbon* gem in order to update the Bourbon folder:

```
gem install bourbon
cd _sass
bourbon install
```

Bourbon allows you to simplify CSS actions with a few commands. Bourbon works with another library called Neat. You can see its documentation in [this link](https://neat.bourbon.io). In order to update the Bourbon folder:

```
cd _sass/
bourbon update
```

## Serving up the site.

Start running Jekyll (defaults to port 4000) with the following command:

```bash
bundle exec jekyll serve
```



