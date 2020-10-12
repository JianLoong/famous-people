{{ define "main" }}

<h1>{{ .Title }}</h1>
<p>Date Published: {{ .Date }}</p>

<h3>Short Description</h3>

<p>{{ .Description }}</p>

<h3>Description</h3>
{{ .Content }}

{{ end }}