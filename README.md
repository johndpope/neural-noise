# Neural Noise
Generate music snippets using Recurrent Neural Networks and display them on the web.

## Introduction

Neural Noise is a series of Python scripts that interact with external programs
in order to:

1. Generate a training set of music represented as character data, using
[ABC notation](http://abcnotation.com) or some variation thereof;
1. Train a Recurrent Neural Network (RNN) with the data, using the excellent
[char-rnn](https://github.com/karpathy/char-rnn) package;
1. Generate new music snippets using checkpoints output by char-rnn;
   1. Create companion MIDI files and sheet music PNGs for each of these
   snippets using [abcmidi](https://github.com/audiodude/abcmidi) and
   [abcm2ps](https://github.com/audiodude/abcm2ps);
   1. Store the snippets, MIDI files and metadata in a MongoDB instance; and
1. Finally, allow the user to randomly browse the new snippets using a [web interface](http://nn.0-z-0.com).

This is a complicated mish-mash (hack) of software, and getting it running is
not for the faint of heart. Still, in this README we will attempt to document
the complete set of steps that were used in installing char-rnn, massaging the
training data, running the training, generating the snippets, and finally
getting the web interface up and running.

## Instructions

(coming soon)