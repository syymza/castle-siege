# Before the Siege

[Explore the castle](https://syymza.github.io/castle-siege/)

A human-scale castle preparing for a siege. Walk through the gatehouse and courtyard, climb to the battlements, operate the defences and begin a short watch-and-alarm scene.

## Controls

Desktop: W A S D to walk; drag or use arrow keys to look. Phone: the left thumb pad walks; drag elsewhere to look. Tap a nearby gate for its action, or use Defences. Begin watch starts the event and enables optional horn audio; Replay watch restarts it. Gates remain manual.

## Static release

Serve this complete directory over HTTP(S). The small loading page fetches the bundled script and two compressed models sequentially. There is no backend, account, analytics or runtime third-party asset service. A current browser with WebGL2 and DecompressionStream is required. GitHub Pages serves main at the repository root. A separate single-file offline export is maintained in the development project; this hosted HTML requires its accompanying files.

This release includes the reviewed scene polish from source revision 25a5246be3eda9642f068379e3ab48166b8c409d: courtyard materials and lighting, a corrected distant landscape, and fourteen authored guard turns with interrupted alarm replay support. The bounded-memory startup fix and sequential loading remain in place. Phone rendering uses conservative resolution and shadow settings. Loading and graphics errors offer a manual reload action. The public repository contains only static release files and credits, excluding development history and internal reports.

## Limits

This is a stylized historical composite, not a surveyed reconstruction or battle simulation. Hall and tower interiors are closed; distant terrain is scenery. There is no combat. Browser testing uses Chromium/WebKit desktop and phone emulation on a Mac. This scene-polish release has not been tested on a physical iPhone; device performance and audio support vary. See CREDITS.md and THIRD-PARTY-LICENSES.txt.
