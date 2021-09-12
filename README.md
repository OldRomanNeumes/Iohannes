# Old Roman Neumes
### Typesetting for Old Roman and Beneventan notation.

## Project
 We started working in Spring 2020 on translating medieval plainchant into square notation, 
 and it became apparent that we had to develop a convenient typesetting system for the Old 
 Roman and Beneventan notation, currently not implemented in available sofware. 
 The long-term aim of this project is to build a network of researchers, who study 
 manuscripts containing rare or unique symbols, and are interested in transcriptions for 
 academic publication.
## Fonts
 The first goal is to design and develop a new font set representing Old
 Roman and Beneventan notation. At the current stage, we currently have
 30 new glyphs, drawn using [FontForge](https://fontforge.org/en-US/) and designed to
 seamlessly integrate with the existing _greciliae_ and _Joseph_Pothier_ fonts. The
 attached [document](Examples.pdf) showcases them, and we plan to make all fonts available,
 bundled in a new version of Gregorio.
## Gregorio
 The second goal is to integrate the new glyphs into an usable piece of software. The
 natural choice is of course integrate them in
 [Gregorio](http://gregorio-project.github.io/).  We developed a fork, which is currently
 in **Alpha** stage. The main issue at the moment is to let the build and install phase
 automatically deal with the new font.
 
 We aim at having our fork pulled into the main Gregorio branch, if this is feasible.
## Licensing
The accompaning documentation and new font is Copyright (C) 2020-2021 Old Roman Neumes,
and is released under a custom [license](LICENSE.txt), which is inspired by the 
[SIL Open Font License]{https://scripts.sil.org/OFL}. The only addition to the SIL OFL 
license is the requirement to acknowledge the authors in other derivative works using 
the new font.
