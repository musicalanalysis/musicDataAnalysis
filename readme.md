
## "Musical Tone and his Feautures"   

### *computational music analysis/music data analysis*

Plan and Referenzen to Jupiter Notebooks (englich):

[Music tone](musical_tone_englisch.md)

---

## "Ton und sein Charakteristik"

### *computergestützte Musikanalyse/musikalische Daten Analyse* 

Plan und Referenzen zu Jupiter Notebooks(deutsch):

 [Musikalische Klang](musikalische_klang_deutsch.md)

---
## Ton in Musikanalyse

> Musikanalyse hat verschiedene Aspekten(Dimensionen)-  **Music Features**. Für Algoritm wird oft *EDA/Exploration Data Analysis* Method mit *Visualitation* benutzt. Die *Feature Extraction* zu bestimmen baruchen wir **Music Features**! Hier in Diagramm sehen wir die Hierarchy und Zusammenhang von denen. 

```mermaid
graph TD;
    Musikanalyse-->Ton
    
    Ton-->Timbre
    Timbre-->Instrumenten
    Ton-->Dinamik
    Ton-->Tondauer
    Tondauer-->Rhytmus
    Tondauer-->Tempo
    Ton-->Tonhöhe
    Tonhöhe-->Tonsystem
    Tonsystem-->Stimmung
    Tonsystem-->Skale
    
    Skale-->diatonischeScale
    diatonischeScale-->Stammtonreihe
    Stammtonreihe-->Notenschrift
    Stammtonreihe-->Klaviatur
    Stammtonreihe-->MIDI
    Skale --> Tonmaterial
    diatonischeScale --> Tonalität

    Musikanalyse-->Intervall
    Intervall-->harmonischeIntervall
    Intervall-->melodischeIntervall
    harmonischeIntervall-->Akkord
    
    Akkord-->Stuffentheorie
    Tonmaterial --> Stuffentheorie


    Akkord-->Funktionstheorie
    Funktionstheorie --> Harmonie
    Tonalität --> Harmonie

    melodicInterval-->Melody
    Melody-->Tonsatz
    Rhytmus-->Tonsatz
    Harmonie-->Tonsatz

    Musikanalyse-->Style
    Style-->musikClassification
    Musikanalyse-->Form
    Form-->strukturAnalyse
```

---

> Music analysis has differnet musically meaningfull label - Music Features. They specify the  Feature Extraction in Algorithm.

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
    Interval-->harmonicInterval
    Interval-->MelodicIntervall
    harmonicInterval-->Chord
    
    Chord-->RomanNumericAnalysis
    Tonmaterial --> RomanNumericAnalysis


    Chord-->FunctionalTheory
    FunctionalTheory --> Harmony
    Tonality --> Harmony

    MelodicIntervall-->Melody
    Melody-->Texture
    Rhytmus-->Texture
    Harmony-->Texture

    Musicanalysis-->Style
    Style-->musicClassification
    Musicanalysis-->Form
    Form-->structureAnalysis
```

---


[Musikalische Begriffe in Deutsch und Enlisch](begriffe.md
)

**Quellen:**

*Wikipedia:*

[Tonsystem](https://de.wikipedia.org/wiki/Tonsystem)

[Harmonic](https://en.wikipedia.org/wiki/Harmonic)




