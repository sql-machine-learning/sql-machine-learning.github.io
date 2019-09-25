---
layout: default
---

<script>
    document.getElementsByClassName('site-title')[0].innerHTML = "<img src='/assets/sqlflow-logo.svg' style='height: 30px' />"
</script>

<style>
a {color: #1BA2FF}
</style>

{% assign href_prefix = 'href="' | append: page.prefix %}

{{content | replace: "README.md", "" | replace: ".md", "" | replace: 'href="/', href_prefix }}

