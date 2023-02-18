---
layout: grid

title: Travel
slug: travel

description: >
  Travel posts during my free times. 🌍

# (Optional) You can disable grouping posts by date.
no_groups: true

# Exclude this example category from the sitemap.
# DON'T USE THIS SETTING IN YOUR CATEGORIES!
sitemap: false
permalink: /travel/
---



I would like to add here a map to star where I visit.

<sricpt>
{% leaflet_map %}
    {% leaflet_marker { "latitude" : 41.881832,
                       "longitude" : -87.623177,
                       "popupContent" : "Hello World from Chicago!"} %}
{% endleaflet_map %}
</script>

## Highlights