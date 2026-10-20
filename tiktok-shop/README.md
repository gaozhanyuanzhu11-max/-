# TikTok Shop approved product images

Only final product images that have passed product-identity, structure, quantity,
color, copy, anatomy, scene-logic and functional-proof checks belong here.

Layout: tiktok-shop/<sanitized-SKU-with-hash>/<new-image-version>/01.jpg (or .png).
Every image must be 3:4, JPG/PNG, and strictly smaller than 5,000,000 bytes.
Never overwrite a different image at an existing version path. Never use Git LFS.
Original source material, rejected drafts, secrets and credentials are excluded.

Consumers use anonymous raw.githubusercontent.com URLs. Each image is validated
after upload for HTTP 200, image MIME type, real decoded image bytes, aspect ratio,
file size and SHA256 equality before its URL is recorded in Feishu.
