# Signed catalog v2

Schema 2 adds three signed entry fields: `description` (1–320 characters), `category` (an allow-listed identifier) and `tags` (at most 16 unique text tokens, 1–32 characters). Pack format, URLs, image format, trust key and signature domain are unchanged. No script or HTML is accepted.

`catalog.json` and `catalog-v1.json` remain schema 1, with exactly the fields accepted by Tube Studio 2.5 and 2.5.1. `catalog-v2.json` serves 2.6. Both list the same 20 static clock packs in this first collection publication. The three additional portrait collections are not part of this publication.

The v2 sequence is one greater than the v1 sequence. This permits upgrade after an old client has already refreshed the new v1 response: the existing monotonic sequence/digest protection is retained, without accepting two different payloads under the same sequence.

Each signed preview is an inline, palette PNG, 810×240 pixels, at most 32768 bytes. Full 135×240 RGB565 glyphs and full-color PNG previews are in the independently SHA-256 checked ZIP. There are 14 clock glyphs: digits 0–9, colon, blank, AM and PM.

Limits remain 262144 bytes for the canonical signed payload, 400000 bytes for its JSON envelope, and 50 catalog entries. No limit or signature verification was disabled. Existing five immutable pack versions, URLs and SHA-256 hashes are retained.

All artwork is static. Glass/glow, mechanical pointers/gears and terminal screens do not add animation or firmware functionality. Preview, phone download, draft selection and explicit installation are separate operations. Installation remains guarded by supported model/firmware, layout capability, inventory/name collision and measured free storage, with archive and glyph readback. No physical clock installation is part of catalog publication.
