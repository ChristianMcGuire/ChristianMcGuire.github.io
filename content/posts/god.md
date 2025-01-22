+++
date = '2025-01-22T13:00:48+10:00'

title = 'God'
+++

{{ $asset := resources.Get "/duck.png" }}
{{ $img := $asset.Fit "600x400" }}
<figure class="image is-3by2">
  <img alt="Yellow Duck" src="{{ $img.RelPermalink }}" />
</figure>