<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  {%- seo -%}
  <link rel="stylesheet" href="{{ "/assets/main.css" | relative_url }}">
  {%- feed_meta -%}
  {%- if jekyll.environment == 'production' and site.google_analytics -%}
    {%- include analytics.html -%}
  {%- endif -%}
  {%- if jekyll.environment == 'development' -%}
  <meta http-equiv="refresh" content="5">
  <style>
  .page-content > .wrapper > * {
    animation-name: none !important;
  }
  </style>
  {%- endif -%}
</head>
