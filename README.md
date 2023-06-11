# Spell-Corrector

This is used by some of our internal tool as an auto spelling corrector feature.
Similar to how "Did you mean" feature work but these are collected through out and placed into a A-Z text files for easy retrieving of the scripts.

The scripts are coded in Python, Javascript, vb6, etc and are used by some desktop apps and mobile apps.

For example, people hurrying keeps mistyping the words under and they will be auto-corrected when "spacebar in keyboard" is pressed.

```bganks **banks**
bbank	banks
bbnka	banks
banls	banks
```

There is a timer logic added to "delay" and not to interrupt the user's thoughts and typing process.
selection of cursor and taken in consideration.

User doesn't notice its being helped, the feature "just works" and applies the correction.

    .Selstart , Sellength , etc
