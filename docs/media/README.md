# Sabreza View promotional film

35 seconds, 1920 × 1080, H.264/AAC MP4 with fast-start playback. English on-screen copy and application interface; Turkish, English and German WebVTT files are provided for an HTML video player.

The lifestyle scenes are AI-generated fiction, not a customer testimonial. Interface shots come from the actual application with synthetic demonstration data. The remote-screen capture uses an example feed, not a live connection. The scenario depicts separately configured authorized personal use; current operator-managed downloads require their own explicit consent. No claim of offline control, guaranteed notification delivery, precise location or universal hardware support is made.

The music was composed and synthesized locally for this film; no commercial song or third-party music recording was sampled. The existing application icon is preserved. See `promo-provenance.json` for the source revision, generation identifier, timeline and checksum.

For a future website, copy these files to its own media directory and adjust the paths:

```html
<video controls playsinline preload="metadata" poster="/media/promo-poster.png">
  <source src="/media/sabreza-view-promo-en.mp4" type="video/mp4">
  <track kind="subtitles" src="/media/promo.tr.vtt" srclang="tr" label="Türkçe">
  <track kind="subtitles" src="/media/promo.en.vtt" srclang="en" label="English">
  <track kind="subtitles" src="/media/promo.de.vtt" srclang="de" label="Deutsch">
</video>
```

Do not auto-play audio. The README uses a linked poster because Markdown video playback varies by client. The MP4 can also be downloaded for playback.
