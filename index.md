---
layout: home
#layout: splash
author_profile: false
---

{% capture schedule %}{% include shed.md %}{% endcapture %}
{{ my_include | schedule }}
