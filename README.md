ModCloth Presentation Tool!
==============

Make simple, easy presentations using Markdown

## To create a presentation:

0. Create a file in `_posts` named `YYYY-MM-DD-some-title.html`
0. Set up the yaml block at the top of your file (see example below)
0. Write your slides in Markdown

Put this at the top of your file:

```yaml
---
title: Your Proper Title
layout: presentation
---
```

Use `---` as a slide separator.  If you want the text to appear
centered, use `class: center, middle`

Example presentation:

```
---
title: Your Proper Title
layout: presentation
---

class: center, middle

# My Presentation

---

## <big>My List</big>
0. Item 1
  - sub item 1
  - sub item 2
0. Item 2
  - etc
```

## To run/test a presentation

Install Jekyll

```bash
gem install jekyll
```

*There may be other dependencies, I forget.*

Run the server:

```bash
# NOTE: the `-w` option will reload the pages as you change them
# instead of having to stop and start the server.
> jekyll serve -w
```

Then visit [localhost:4000](http://localhost:4000/)

### Enjoy!

Powered by [Jekyll](http://jekyllrb.com/)
