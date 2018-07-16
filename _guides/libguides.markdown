---
breadcrumbs: true
title: LibGuides Widgets Embeds
layout: article
published: true
---

# Hours Calendar

{% raw %}
```handlebars
<div class="
  hours-widget hours-widget--{{ page.libcal_id }}
  {% if page.libcal_truncated %} is-truncated{% endif %}"
  data-id="{{ page.libcal_id  }}">
</div>
```

{% endraw %}

## Example

<div
  class="hours-widget hours-widget--991 is-truncated"
  data-id="991">
</div>

```html
<div
  class="hours-widget hours-widget--991 is-truncated"
  data-id="991">
</div>
```

# Call Numbers Map

[Live example](https://library.nyu.edu/about/collections/search-collections/call-numbers/)

```html
<script defer type="text/javascript" src="//lgapi-us.libapps.com/web/jquery/js/jquery-ui.min.js?2695"></script>
<script defer type="text/javascript" src="//lgapi-us.libapps.com/web/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script defer type="text/javascript" src="//lgapi-us.libapps.com/web/js1.24.3/springshare.public.min.js"></script>
<script defer type="text/javascript" src="//lgapi-us.libapps.com/web/js1.24.3/springshare.common.min.js"></script>
<script defer type="text/javascript" src="//lgapi-us.libapps.com/web/js1.24.3/common/springspace_sui_helptip.js"></script>

<script defer src="//lgapi-us.libapps.com/sa.php?site_id=873" onload="jQuery(window).on('load', function() {springSpace.springTrack.init({_st_site_id: '873'});});"></script>

<script>
  window.addEventListener('DOMContentLoaded', function() {
    $(function() {
      springSpace.Common = springSpace.Common || { };
      springSpace.Common.constant = { PROCESSING: { ACTION_DISPLAY_POLL: 159}};
      springSpace.Common.baseURL = "//lgapi-us.libapps.com/";
      springSpace.Common.apiLoad = true;
    })
  })
</script>

<script>springshare_widget_config_1528131547517 = { path: 'boxes/8876096' };</script>

<div id="s-lg-widget-1528131547517"></div>

<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://lgapi-us.libapps.com/widgets.php?site_id=873&widget_type=8&output_format=1&widget_title=Call+Number+Chart&widget_height=250&widget_width=100%25&widget_embed_type=1&guide_id=423573&box_id=8876096&map_id=10466619&content_only=0&config_id=1528131547517";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","s-lg-widget-script-1528131547517");</script>
```

# Frontmatter plugins

## LibAnswers

```yaml
libanswers:
  topic_ids: 29303
  link: http://library.answers.nyu.edu/
---
```

## Libcal RSS (classes)

```yaml
classes:
  title: 'Library Classes '
  rss: http://nyu.libcal.com/rss.php?m=fortnight&iid=1287&cid=1564
  link: http://nyu.libcal.com/calendar/classes
  sort_order: asc
---
```

## NYU Blog (WordPress)

```yaml
blog:
  title: Library News & Updates
  rss: https://wp.nyu.edu/library-news/category/news/feed/
  link: https://wp.nyu.edu/library-news/category/news/
---
```
