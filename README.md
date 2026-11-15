# ReflexLab — Orbital Station

ReflexLab is a visual-response training app set inside an explorable 3D orbital station.

## Experience
- Walk around a compact station module in first person.
- Look through a panoramic observation window into space, with a planet, stars, a moon and a passing orbital craft.
- Explore the station using WASD / arrow keys or the on-screen directional pad; drag to look around.
- Approach the illuminated training console and press **E** or tap **ACCESS REFLEX TRAINING**.
- Open the logbook to review circuit history and progress.

## Daily reflex circuit
The existing six-station circuit remains part of the app:
1. Signal response — simple visual reaction
2. Go or hold — response inhibition
3. Choice mapping — colour-to-action decisions
4. Side awareness — peripheral signal detection
5. Pattern recall — short visual sequence memory
6. Moving target — visual tracking and hand-eye response

The official circuit is limited to one completion per local calendar day on that device. Progress is stored in browser local storage.

## Open the app
Enable GitHub Pages in **Settings → Pages → Build and deployment → GitHub Actions**. The Pages workflow deploys on pushes to `main`.

## Android APK
The workflow at `.github/workflows/android-apk.yml` builds a debug APK and uploads the `ReflexLab-debug-apk` artifact. Open Actions, select the latest Android build, and download its artifact after the workflow succeeds.

## Technical notes and limitations
- 3D environment uses Three.js 0.160 from jsDelivr, so the first load requires an internet connection.
- The orbital station is a real-time 3D scene, but it is a compact environment prototype rather than a full-scale space simulation.
- The reaction circuit is a screen-based practice tool, not a medical test. In-app performance does not guarantee improved real-world or sports performance.
- Use comfortable brightness and viewing distance; stop if you experience eye strain, headache or dizziness. No strobe effects are used.
