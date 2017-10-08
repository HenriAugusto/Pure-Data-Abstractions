# Pure-Data-Abstractions
This a collection of Pure Data abstractions of miscellaneous uses

## PianoEye

It is a abstraction to display midi information in real time, using a 97 key keyboard. Every channel gets a separate color.

## MidiRec (WORK IN PROGRESS!)

Allows you to record and playback midi performances! You can also sequence a midi performance with it and save/load from a .txt file.

Future features:

  - Add a time scale (very easy to add. Just multiply the times sent to the [delay])

## oscformatAuto (WORK IN PROGRESS!)

Works like [oscformat] but

  - It deduces the format from the information you're sending.
  - It already does [list prepend send]->[list trim] so you can send it directly to [netsend -u -b]
