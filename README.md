# pattern-synthesis-pd

## What is this?

This is a pd patch to try and implement Pattern Synthesis. The main source of information is from Mark Fell's PhD Thesis
[Works in sound and pattern synthesis folio of works](https://openresearch.surrey.ac.uk/esploro/outputs/doctoral/Works-in-Sound-and-Pattern-Synthesis/99516858802346#file-0)

### Considerations
There is a plain synth engine as a way to hear results.  
~~No note duration or velocity are being used at the moment, as well as no midi note generation.~~  
Midi is now implemented.

## Implementation considerations

This was implemented with [Purr-data](https://agraef.github.io/purr-data/) and no guarantees exist if it will work on vanilla-pd (there are plans to test and make it compatible)

## How-to use this

The documentation and object labels should be enough
