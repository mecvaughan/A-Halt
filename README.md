
# PDF and MIDI Files

See [the release page](https://github.com/mecvaughan/A-Halt/releases).

# Playing MIDI on GNU/Linux

To play a MIDI file on GNU/Linux, make sure that the `timidity` package is
installed.

Open a terminal window.  Suppose that the shell prompt is `prompt$`.  Suppose
that the MIDI file is in the directory

    ~/Music/A-Halt

and has the name `A-Halt.midi`.  In this example, one would listen to the
MIDI file by doing the following:

    prompt$ cd ~/Music/A-Halt
    prompt$ timidity A-Halt.midi


# Building New Output Files

There is a `Makefile`.  On a unix-like machine with Lilypond installed, just
open a terminal window, change to the directory containing the local clone of
the git repository, and then do

    shell-prompt$ make

This should generate both a PDF version of the score and a MIDI file.

Modify `A-Halt.ly` to change the output.  See the Lilypond documentation,
if necessary, for reference.

