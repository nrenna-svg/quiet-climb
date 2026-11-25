# Quiet Climb

A classroom whiteboard game: the quieter the class works, the higher their climber goes.
Noise makes the climber slip back to the last checkpoint. Classes race to climb highest each week
and collect treasures found on the ledges.

Play: https://nrenna-svg.github.io/quiet-climb/

- Open in Chrome on the classroom computer and allow the microphone.
- Settings: teacher name, classes, microphone choice, calibration, volume goal, climb speed.
- Practice mode works without a microphone (hold Space to make noise).

## Smart listening

The game recognizes sounds with Google's YAMNet sound model (Apache-2.0, see `models/yamnet/LICENSE`),
run in the browser with TensorFlow.js (Apache-2.0). Only voices count as noise; phones, alarms,
classroom bumps and (optionally) music are ignored. Audio never leaves the computer.
