## Making new theme example

This folder on an orphan branch is intended to be used to produce consistent theme examples.

1. Be sure your new theme is on the master branch.
1. Get this branch locally and checkout to it.
1. Be sure that the `ExerciseHandler.bash` file is up-to-date. You can try to [update it](https://stackoverflow.com/a/45622874) via `git checkout master -- ExerciseHandler.bash` and then doing `git status`. Add, commit and push in case.
1. Change directory to `MakeThemeExamples`.
1. Run an `Exercise Handler` setup choosing the desired theme.
1. Produce an exercise sheet using the `Fermat.tex` and the `Solitary.tex` exercises.
1. Convert the `PDF` file to a `png` e.g. [here](https://pdf2png.com/).
1. Push your png on the orphan branch and update the `README` file on the master branch.
