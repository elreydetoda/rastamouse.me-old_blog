Standing up a mirror of Rasta Mouse's old blog, to preserve the old blog posts.

All content was originally authored by [Rasta Mouse](https://github.com/rasta-mouse)

Checkout his new blog here: https://rastamouse.me/

command used:

```shell
find . -iname "*.html" -exec sed -i -e 's,href="/,href="/rastamouse.me-old_blog/,g' -e 's,src="/,src="/rastamouse.me-old_blog/,g' -e 's,https://rastamouse.me/,/rastamouse.me-old_blog/,g' {} \;
```
