# Research portfolio

日本語中心・英語要約の静的サイト。ビルド・依存パッケージ・JavaScript不要。

## Preview

Run `python -m http.server 8765 --bind 127.0.0.1` in this directory, then open http://127.0.0.1:8765/ .

## Preservation and release

- Original master: ae97877933b1c3c83d71f0bf990e6f023eee7688 (2018 Hugo output).
- GitHub backup branch: backup/pre-portfolio-20261031.
- Complete local history backup: ../legacy-site-20261031.bundle (not served or committed).
- Existing 2018/, post/, archives/, tags/, categories/, page/, images/, css/, js/ and feeds remain untouched.
- Original homepage copied byte-for-byte to legacy/index.html. Its original absolute URLs intentionally continue to resolve on GitHub Pages.
- Work branch: redesign/research-portfolio. Review the draft PR before merging.
- No Pages configuration or deployment workflows added or changed. Confirm current Pages source in repository Settings before merging; this redesign expects repository root publication.
- Merge only after reviewing the wording, Haptic Anatomy diagram and contact address. Current experiment progress is deliberately not asserted.
- Rollback after release: revert the merge commit via a PR. Do not force-push master or delete history.

## Content

See docs/SOURCES.md for evidence and publication boundaries. Never add private company projects, internal data, patient images, unpublished repositories or the complete source research PDF.
