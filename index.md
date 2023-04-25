---
title: CHF Decoder
layout: home
---

This is a *bare-minimum* page to test the asn.1 to json decoder of 3gpp CHF cdrs, which is still in early stages of it's development.

The related 3GPP spec is [TS 32.298], and the asn.1 spec files can be downloaded from this [FTP] site. Only an old version (15.10.1) of chargingFunctionRecord is supported.

Check the [Test] site, or use:
```html
POST http://129.151.202.193/decode
Content-Type: application/octet-stream
content-length: __your_data_length__

__your_asn.1_chf_cdr_binary_data_here__

```
*The data is processed in memory only and not saved.*

The embedded one is here for preview.
<div class="html-container">
  <iframe src="http://129.151.202.193/upload.html" width="100%" height="480" frameborder="0"></iframe>
</div>
----

[TS 32.298]: https://portal.3gpp.org/desktopmodules/Specifications/SpecificationDetails.aspx?specificationId=1915
[FTP]: https://www.3gpp.org/ftp/Specs/archive/32_series/32.298
[Test]: http://129.151.202.193/upload.html
[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
