# FM Style Instruments
Instruments that exhibit Frequency Modulation effects. https://glicol.org/tour#fm

## Instruments

siren-crash
```sh
hi: saw ~fm >> sawsynth 0.01 0.3
~fm: sin 0.2 >> mul 450.0 >> add 500.0
```
