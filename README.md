# A javascript (S)low (S)can (T)ele(V)ision converter

see: https://www.sigidwiki.com/wiki/Slow-Scan_Television_(SSTV)

## PLEASE NOTE: This is a placeholder/work in progress.

The planned implementation is:

``` javascript
import SSTV from 'sstv';

const waveformStream = sstv.toWaveform('path/to/image.png', 'sstv-protocol'); // where mode can be one of the implemented protocols
const imageStream = sstv.toImage('path/to/sound.mp3', 'sstv-protocol'); // where mode can be one of the implemented protocols - default is "auto"
``` 


## Planned protocols for implementation:
``` 
Robot 8 B/W
Robot 12 B/W
Robot 24
Robot 36
Robot 72
Martin 1
Martin 2
Scottie 1
Scottie 2
ScottieDX
``` 
