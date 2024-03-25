<script src="https://maps.googleapis.com/maps/api/js?key={{ .Site.Params.map.APIkey }}&libraries=geometry"></script>



            {{ $sitemap := .Site.Menus.sitemap }}
            {{ range $sitemap }}
            <li class="mb-2"><a class="text-light" href="{{ .URL | absURL }}">{{ .Name }}</a></li>
            {{ end }}



            <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-195T973V33"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-195T973V33');
</script>