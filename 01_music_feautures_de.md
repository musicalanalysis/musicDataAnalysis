
## Musikalische Dimensionen (*Musical Features*)

Musikanalyse hat verschiedene Aspekten(Dimensionen) -  **Musical Features**. Für Algoritm wird oft *EDA/Exploration Data Analysis* Method mit *Visualitation* benutzt. Um *Feature Extraction* zu bestimmen brauchen wir *Musical Features*.

Hier in Diagramm sehen wir die Hierarchie und Zusammenhang von denen:

```mermaid
graph TD;

    Musikanalyse -->  Energie
    Energie -->Interpretation 
    Energie --> InnereDynamikTon
    Interpretation-->Intonation
    Interpretation --> Atmung
    Interpretation -->Gewichtung
    InnereDynamikTon -->Bewegung
    InnereDynamikTon --> Schwerkraft
  


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
    Tonsystem --> Notationsystem
    Notationsystem -->Stammtonreihe
    Tonsystem-->Skale
    
    Skale-->diatonischeScale
    diatonischeScale-->Stammtonreihe
    Stammtonreihe-->NotenschriftWest
    Stammtonreihe-->Klaviatur
    Stammtonreihe-->MIDI
    Skale --> Tonmaterial
    Tonmaterial-->Tonalität
    diatonischeScale --> Tonalität

    Musikanalyse-->Intervall
    Intervall-->melodischeIntervall
    melodischeIntervall-->Skale
    Intervall-->harmonischeIntervall
    harmonischeIntervall-->Akkord
    
    Akkord-->Stuffentheorie
    Skale --> Stuffentheorie


    Akkord-->Funktionstheorie
    Funktionstheorie --> Harmonie
    Tonalität --> Harmonie

    melodischeIntervall-->Melody
    Melody-->Tonsatz
    Rhytmus-->Tonsatz
    Harmonie-->Tonsatz

    Tonsatz-->Monophonie
    Tonsatz-->Polyphonie
    Tonsatz-->Homophonie

    Musikanalyse-->Style
    Style-->musikClassification

    Musikanalyse-->Form
    Form-->strukturAnalyse


```

Die wissenschaftliche Gebiete für Implementation von Algorithmen :

1. Mathematik (Harmonische analyse, Funktionsanalyse, Linearalgebra, Komplexeebene, Calculus)

2. Physik (Akustik, Schall)

3. Psychologie( Tonpsychologie,Musikpsychologie,Wahrnehmungspsychologie)

4. Musiktheorie

5. 