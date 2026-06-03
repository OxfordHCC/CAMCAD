# CAMCAD
Website for the Child-Centred AI-Mediated Collaborative Agency by Design workshop at CHI 2026

Set up locally with 
```bash
bundle install
bundle exec jekyll serve
```

The project requires ruby v3.
```
Because jekyll-nagymaros >= 3.2.0 depends on github-pages ~> 232
  and github-pages >= 232 depends on jekyll-commonmark-ghpages = 0.5.1,
  jekyll-nagymaros >= 3.2.0 requires jekyll-commonmark-ghpages = 0.5.1.
And because jekyll-commonmark-ghpages >= 0.2.0 depends on jekyll-commonmark ~>
1.4.0,
  jekyll-nagymaros >= 3.2.0 requires jekyll-commonmark ~> 1.4.0.
And because jekyll-commonmark >= 1.4.0 depends on commonmarker ~> 0.22
  and commonmarker >= 0.22.0, < 1.0.0.pre depends on Ruby >= 2.6, < 4.0,
  jekyll-nagymaros >= 3.2.0 requires Ruby >= 2.6, < 4.0.
So, because Gemfile depends on jekyll-nagymaros >= 3.3.1, < 4.A
  and current Ruby version is = 4.0.4,
  version solving has failed.
```