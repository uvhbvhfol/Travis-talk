# Travis Talk

An offline, single-file communication aid for a person who can reliably nod YES and shake NO. A caregiver reads or shows each question and clicks the response.

## Predictive spelling

The app shows one likely next letter at a time. **YES** confirms it; **NO** moves to the next likely letter. Predictions use common English word-frequency patterns and the prefix already spelled. The app also learns confirmed common words on this device (browser local storage). Every A–Z letter remains available even when predictions are wrong. Word suggestions can be confirmed through the same YES/NO buttons.

## Controls

- **Spell a message:** predictive letters, with caregiver-driven YES/NO buttons
- **Quick needs:** yes/no choice groups of common requests
- **Tap letters:** caregiver manually adds confirmed letters
- **Space / Delete / Undo response / Restart choice / Clear**
- **Speak message:** uses the device's built-in browser voice where available

## Use

Open `index.html` in a modern browser. No account, server, API key, Claude, or internet connection required. To host it, upload `index.html` to a GitHub repository and enable GitHub Pages.

## Privacy and safety

Messages stay in the current browser session and learned word counts stay in local storage on the device. Nothing is sent over the network by this app. Do not enter identifying medical information if publishing screenshots or code. This is an experimental communication aid, not an emergency alert, and does not replace clinical evaluation by a speech-language pathologist/AAC specialist.

## Customize Quick Needs

Choose **Quick needs**. Add a phrase using the text box and **+ Add need** button. Remove any phrase using its **Remove** button. Changes save to this browser's local storage and persist between visits on the same device, unless site data is cleared. **Restore default needs** replaces the customized list with the original options. Changes do not automatically synchronize across devices.
