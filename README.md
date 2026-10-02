# mtb-avatar-assets

Public asset bucket for the `avatar-ads` pipeline. Image generators and video models
(Replicate / Kling / Veo) need a publicly fetchable, durable URL for an avatar's locked
reference image - the working repo is private, so the images live here.

Serve via jsDelivr, not `raw.githubusercontent`:

```
https://cdn.jsdelivr.net/gh/leofriend1048/mtb-avatar-assets@main/<file>
```

| File | Avatar |
| --- | --- |
| `creator-woman-50s-scene-v4-2k.jpg` | `creator-woman-50s` - Creator Woman 50s (at-home UGC) |

Filenames are versioned. jsDelivr caches a branch ref for up to 12h, so a changed
image ships under a NEW filename rather than overwriting an old one.

Images only. No code, no customer data, no credentials.
