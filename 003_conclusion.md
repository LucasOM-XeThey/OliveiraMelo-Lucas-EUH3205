---
layout: default
title: Conclusion
number: 3
---

# Conclusion

What is the significance of the historical subject you analyzed? What is the broader meaning of it to nineteenth-century and modern European history? (250-350 words)

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'How-is-this-for-high'" %}
{% include media.html pages=media %}
