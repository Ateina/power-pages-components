# Power Pages: Dashboard Stat Card

A reusable web template component for Power Pages that displays analytical dashboard tiles with FetchXML data from Dataverse.

## Files

- **dashboard-stat.html** — Web template with Liquid, FetchXML, HTML, and manifest
- **home-page.html** — Example page that includes multiple stat cards
- **style.css** — CSS styles for the cards

## Usage

1. Create a new Web Template in Power Pages Management
2. Paste the contents of `dashboard-stat.html` as the source
3. Add the CSS from `style.css` to your site styles
4. Include the component on any page:

```liquid
{% include "Dashboard Stat" status: '455810000' title: "Read" secondary_title: "Finished books" card_color: "#b6d7a8" card_icon: "✅" %}
```

## Blog Post

Full walkthrough: [Power Pages Web Templates: Working with Liquid and FetchXML](BLOG_POST_URL)