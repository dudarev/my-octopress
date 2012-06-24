## About

This is a fork from [original Octopress repo](https://github.com/imathis/octopress).

My posts are stored in a [separate repository](https://github.com/dudarev/blog) and should be linked to `source/_posts`.

To make a post:

```
rake preview
rake rsync
```

## Updating

```bash
git pull octopress master     # Get the latest Octopress
bundle install                # Keep gems updated
rake update_source            # update the template's source
rake update_style             # update the template's style
```

Read more about [updating](http://octopress.org/docs/updating/) and what `update_*` commands do.
