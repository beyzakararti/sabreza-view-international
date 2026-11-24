# Screenshot provenance

These images are rendered from the actual application HTML, CSS and JavaScript in Chromium. An isolated local preview supplies synthetic API responses; it does not run the application backend or connect to a real computer. No real enrollment, consent submission, remote command, notification delivery or file transfer took place during capture.

## Feature showcase captured on 24 November 2026

The current feature images use source revision `38e5e8ca3c098c42128798b8cc8af02b7beb09e2`. They illustrate the configured, authorized personal/manual interface available in the source. They are not evidence that the currently published managed installer exposes the same configuration or contains these unreleased source changes.

Each scene is available with `tr`, `en` and `de` language prefixes:

| Filename suffix | Actual interface shown | Demonstration data and limitations |
| --- | --- | --- |
| `system.png` | CPU, memory, temperatures, GPU, disks, network, battery and process cards | All readings and graph histories are synthetic. `Demo-PC` and `Demo server` are fictional names. Sensor availability depends on the real machine. |
| `notifications.png` | Private notifications, remote-input switch, sound/read-aloud/vibration choices, limit alerts and push controls | Selected toggles illustrate available settings, not defaults. No real notification or sound was sent. No account usage was queried. |
| `files.png` | File browser, directory creation and upload controls | Every displayed directory, filename and size is synthetic. No files were read, uploaded or downloaded from a real device. |
| `remote-controls.png` | Display and quality selectors, remote-input controls, shortcuts and the PC keyboard | The screen area contains a cropped screenshot of this same real System interface with synthetic readings. It is a static demonstration image, not a live desktop feed. |
| `external-input.png` | Expanded external keyboard/mouse guidance and the Stop PC control action | No physical Bluetooth/USB device was paired or tested. The actual UI explains that operating-system settings manage pairing; the app only observes input received by the browser. |

The pages and controls were rendered without redesigning their HTML, CSS or application JavaScript. Only initial browser preferences and local API/WebSocket responses were supplied by the capture fixture. Existing UI labels are preserved, including the Turkish `Boşluk` label on the space key in the English and German virtual-keyboard views.

These are resized desktop Chromium viewports, not native application or physical-phone screenshots. The System capture is 1050 × 1440, notifications 1050 × 1190, files 1050 × 720, remote controls 1050 × 1200, and external input 760 × 850. The source revision, fixture scope and per-image dimensions are recorded in [feature-capture-info.json](feature-capture-info.json).

## Earlier v0.3.12 preview images

The earlier screenshots remain for historical reference. In particular, their agreement design predates the revised compact terms and should not be presented as the current source design.

- `consent`: initial consent page.
- `consent-mobile`: the A4-style consent page in a mobile browser viewport.
- `consent-ready`: consent text scrolled to the end, with a simulated user checkbox selection. This is not the default state.
- `connected`: example connected status and disconnect control.
- `wizard`: connection-method step of the separate personal/manual setup wizard.
- `desktop`: sample conversation in a desktop browser viewport.
- `pin`: PIN screen in a mobile browser viewport.
- `phone`: the sample conversation in a mobile browser viewport.

Pages taller than the viewport are captured at full page height. The agreement itself remains scrollable.

The `en`, `de` and `tr` prefixes identify the selected interface language. Existing untranslated UI strings are preserved as rendered. Mobile images emulate a 390 × 844 viewport; they are not physical-device or native Android screenshots. These are application pages, not operating-system installer screenshots.

All conversations, project paths and test results are illustrative. No private conversations, credentials or actual device identifiers are included. The operator name is the configured public product identity.

See [capture-info.json](capture-info.json) for the earlier source revision and capture dimensions.
