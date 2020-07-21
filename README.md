# hexo-nofollow-only
Adds nofollow attribute to all external links in your hexo blog posts automatically.


## Features
* Add rel="external nofollow" ONLY (not noreferrer, noopeener) to all external links, SEO friendly.

## Install

``` bash
$ npm install hexo-nofollow-only --save
```

## Options
You can configure this plugin in  _config.yml.
```
nofollow:
	enable: true
	exclude:
    - exclude1.com
    - exclude2.com
```

- **enable** - Enable the plugin. Defaults to **false**.
- **exclude** - Exclude hostname
