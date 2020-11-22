---
layout: post
author: nroux,jshihada
title: "Integration of latest REST/JSON API features into Unity Frontend"
---

As a continued result of our [previous standardization and implementation][api-news-post] of our [REST/JSON API of the UFrameIT server][api-spec],
we are now able to expose all new features in our [Unity plugin][unity-plugin].
These features include:

- **string interpolation**: when an assignment for a formal parameter is fixed by dragging a fact tile into a scroll, then the name/label of the parameter is replaced everywhere in the scroll. This makes it much easier to keep track of the assignments and the state of application.
- **view completion**: (todo: simplify)
- **hints** (todo: simplify)

todo: maybe add screenshots?

[api-spec]: https://github.com/UniFormal/MMT/tree/devel/src/frameit-mmt#rest-api
[unity-plugin]: https://github.com/UFrameIT/UFrameIT
[api-news-post]: {% post_url 2020-09-20-API %}
