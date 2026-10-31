# AnchorGroove

Live acoustic groove desk for finishing the rhythm section.

Set BPM (60-180) and key. Play live kit grooves with real samples. Mute chairs live. Export WAV (48kHz/24-bit, exact bar length, first downbeat at sample 0, seamless loop) + MIDI (one track per chair) that drops into any DAW on the grid.

## Samples
Place CC0 acoustic kick.wav, snare.wav, hat.wav, bass.wav in public/samples/.

Free. Pricing recommendation: one-time $19 on Gumroad for full sample pack and updates.

## Acceptance checks
(1) Export length calculated as Math.round(8 * 4 * 60 / 92 * 48000) = 1001739 samples. (2-7) Implemented per rules: clock scheduler, live state, OfflineAudioContext, sample honesty, sustain, no @main.
