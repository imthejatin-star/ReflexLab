# ReflexLab

An offline-first daily visual-response training app with a guided six-station circuit.

## Daily circuit

The main session takes about 6–8 minutes:
1. Signal response — simple visual reaction
2. Go or hold — response inhibition
3. Choice mapping — colour-to-action decisions
4. Side awareness — peripheral signal detection
5. Pattern recall — short visual sequence memory
6. Moving target — visual tracking and hand-eye response

Each station runs for 60 seconds. The app records response times and accuracy, keeps a local performance history, and adjusts the next circuit's level based on accuracy. The official circuit is limited to one completion per local calendar day on that device.

## Open the app

- Open `index.html` in a modern browser, or
- Enable GitHub Pages in repository Settings → Pages and deploy from the GitHub Actions workflow.

## Android APK

The workflow at `.github/workflows/android-apk.yml` builds a debug APK and uploads it as the `ReflexLab-debug-apk` artifact. Open the Actions tab, select the latest Android build, and download its artifact after the workflow succeeds.

## Data and limitations

Progress is stored in browser local storage on the device. Clearing browser/app data can erase the history. This is a training game, not a clinical assessment. Faster scores on these exercises do not prove transfer to everyday or sports performance. Use comfortable screen brightness and stop if you experience eye strain, headache or dizziness. No strobe or flashing-light training is used.

## Evidence-informed design

The circuit combines visual detection, response selection, inhibition, peripheral awareness, short sequence recall and visual-motor tracking. Research suggests visual and integrated perceptual-motor training can improve some reaction-time and sport-specific outcomes, but effects vary and task practice can inflate scores. The app therefore tracks both speed and accuracy and changes task demands instead of relying on one repeated tap test.
