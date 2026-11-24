# Sabreza View promotional film

[Watch in your browser](https://beyzakararti.github.io/sabreza-view-international/watch/).

Revision 2: 36 seconds, 1920 × 1080, 30 fps, H.264/AAC MP4 with fast-start playback. English on-screen copy and application interface, music without narration. Optional English, Turkish and German WebVTT subtitles.

The lifestyle footage is AI-generated fiction. The tablet/home-PC comparison uses the real, unmodified application frontend with an isolated sample desktop. Actual browser pointer events were sent through the frontend as `screen.input` messages; a fixture changed the sample preview and check status. No physical tablet, distant computer or real project was controlled during capture, and the edit does not measure network latency. The sample project's “8 checks passed” is illustrative, not a result from the software's test suite. See `promo-provenance.json` for event receipts and source revisions.

Feature panels use real application captures with synthetic data. The scenario depicts separately configured authorized personal use; current operator-managed downloads have their own explicit consent conditions. No offline remote-control claim is made.

The new soundtrack is an original local composition using plucked-string synthesis, bass and soft percussion. The existing lifestyle footage was reused; no additional image, video or audio generation service was called for revision 2.

The watch page is in `../watch/index.html` and uses a native HTML video player. Playback starts only after a click, supports inline mobile playback and subtitles, and has a separate download link. No analytics, external scripts or paid hosting are required. GitHub Pages publishes the existing public repository's `docs` directory.

For a future website:

```html
<video controls playsinline preload="metadata" poster="/media/promo-poster.jpg">
  <source src="/media/sabreza-view-promo-en.mp4" type="video/mp4">
  <track kind="subtitles" src="/media/promo.en.vtt" srclang="en" label="English">
  <track kind="subtitles" src="/media/promo.tr.vtt" srclang="tr" label="Türkçe">
  <track kind="subtitles" src="/media/promo.de.vtt" srclang="de" label="Deutsch">
</video>
```
