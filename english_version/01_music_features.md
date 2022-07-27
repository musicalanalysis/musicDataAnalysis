
## Musical Features

Music analysis has differnet musically meaningfull labels - **Musical Features**. We need to specify and select the **Features** to use them in Music Data Analysis. Commonly used the **EDA-Approuch**(exploratory data analysis) with Visualitation. 

The hierarchy of **Musical Features** and their connection:

```mermaid
graph TD;
    Musicanalysis-->Ton
    
    Ton-->Timbre
    Timbre-->Instrumenten
    Ton-->Dinamic
    Ton-->Tonduration
    Tonduration-->Rhytmus
    Tonduration-->Tempo
    Ton-->Pitsh
    Pitsh-->pitshSpace
    pitshSpace-->Tuning
    pitshSpace-->Scale
    
    Scale-->diatonicScale
    diatonicScale-->Staffnotation
    diatonicScale-->keyboard
    diatonicScale-->MIDI
    Scale --> Tonmaterial
    diatonicScale --> Tonality

    Musicanalysis-->Interval
    Interval-->melodicIntervall
    melodicIntervall-->Scale
    Interval-->harmonicInterval
    harmonicInterval-->Chord
    
    Chord-->RomanNumericAnalysis
    Tonmaterial --> RomanNumericAnalysis


    Chord-->FunctionalTheory
    FunctionalTheory --> Harmony
    Tonality --> Harmony

    melodicIntervall-->Melody
    Melody-->Texture
    Rhytmus-->Texture
    Harmony-->Texture

    Texture-->Monophony
    Texture-->Polyphony
    Texture-->Homophony

    Musicanalysis-->Style
    Style-->musicClassification
    Musicanalysis-->Form
    Form-->structureAnalysis
```
