## Circular A-130: Managing Information as a Strategic Resource

The [Office of Management and Budget (OMB)](https://www.whitehouse.gov/omb/) is proposing to revise [Circular No. A-130, Managing Information as a Strategic Resource] (https://a130.cio.gov), to incorporate new statutory requirements and enhanced technological capabilities, as well as address current and evolving technical and personal security threats. 

The proposed guidance is now open for public comment on this page. The public feedback period will be 30 days, closing on November 20, 2015. Following the public feedback period, OMB will analyze all submitted feedback and revise the policy as necessary. 

### Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.

### Developing on the site locally

This site uses [Jekyll](http://jekyllrb.com), [Sass](http://sass-lang.com), [Bourbon](http://bourbon.io), [Neat](http://neat.bourbon.io), and requires **Ruby 2.x**.

Install dependencies with Bundler:

```
bundle install
```

Start up a Sass watcher to keep assets auto-compiled:

```
make watch
```

And run the site with Jekyll:

```
bundle exec jekyll serve --watch
```

If all goes well, visit the site at `http://localhost:4000`.
