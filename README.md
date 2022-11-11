# hdri-panorama

## `hdri-panorama.html`
This view hdri panorama 360.
|Key|Description|Possible Values|
| --- | --- | --- |
| `environment_tonemapping` | Tonemapping style to use. | `linear` (recommended for an analytical look) or `filmic` (for a "prettier" look with tonemapping.) |
| `environment_exposure` | Exposure offset in EVs. | Any integer or decimal number. Negative values darken the image, positive brighten it. |
|`environment_url`| Link to one or multiple equirectangular HDR panoramas in `hdr` or `exr` file format.|Semicolon-separated list of URLs ending in `.hdr` or `.exr`. |
|`environment_name`| List of names for the environments. Required if more than one environment is used. |Semicolon-separated list of Strings.|
