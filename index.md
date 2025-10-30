---
layout: null
---

<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>DevOps Pages Lab</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 40px; }
    pre { background: #f4f4f4; padding: 15px; border-radius: 8px; }
  </style>
</head>
<body>
  <h1>My GitHub Pages Site</h1>
  <p>Owner: Tanuki</p>
  <p>Course: 軟體開發維運</p>
  <p>Deployed via GitHub Pages.</p>

  <hr>

  <h2>最近活動（自動更新）</h2>
  <pre>
{% raw %}
{{ site.data.readme | markdownify }}
{% endraw %}
  </pre>
</body>
</html>
