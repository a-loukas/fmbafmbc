---
layout: default
#layout: splash
author_profile: false
---

<!--{% include_relative _pages/shed.md %}-->

{% capture schedule %}{% include _pages/shed.md %}{% endcapture %}
{{ my_include | schedule }}
