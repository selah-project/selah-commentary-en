# Rashi HE↔EN alignment notes (diagnosed 2026-07-09, pre-loader)

Census: 14 mismatched verse-slots Torah-wide (13 HE>EN, 1 EN>HE).

1. The EN (Rosenbaum & Silbermann 1929-34) SYSTEMATICALLY OMITS
   Rashi's sexually explicit comments: Gen 9:22, 18:11, 19:5,
   19:36, 24:16, 26:8, 34:2, 38:9, 49:25(partial), Exod 33:8
   (partial). Period bowdlerization, not digitization noise.
   Likely plain gaps: Gen 15:19, 17:25, 48:1(partial).
2. Exod 20:6 EN-extra = Decalogue versification split, not content.

LOADER RULES:
- Match EN renderings to HE things BY LEMMA (EN embeds the Hebrew
  dibbur hamatchil at comment head), never by index.
- Censored comments get NO R&S rendering — they stand Hebrew-only
  (visible absence, edition-attributed), until a selah-en rendering
  fills them (first rails-translation candidates for Rashi).
- Decalogue verses: lemma-match across a ±1 verse window.
