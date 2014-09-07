---
layout: themes
meta_title: Theme helper reference - Ghost Docs
meta_description: Ghost theme helper API, helper reference documentation
chapter: themes
section: helpers
permalink: /themes/helpers/pagination/
---

{% raw %}

# pagination

*   Helper type: output, template-driven
*   Options: none (coming soon)

`{{pagination}}` is a template driven helper which outputs HTML for 'newer posts' and 'older posts' links if they are available and also says which page you are on.

You can override the HTML output by the pagination helper by placing a file called <code class="path">pagination.hbs</code> inside of <code class="path">content/themes/your-theme/partials</code>.

{% endraw %}