
# Tonsystem

```mermaid
graph TD;
    TonPhysik --> HarmonischeAnalyse
    TonPhysik --> Tonhöhe
    HarmonischeAnalyse--> Teiltonreihe
    Teiltonreihe --> Tonsystem
    Teiltonreihe -->Klangfarbe--> Obertonreihe
    Teiltonreihe -->KlingelteTöne --> Naturtonreihe
    
    HarmonischeAnalyse --> Unharmonische
    HarmonischeAnalyse -->Harmonische

    Tonsystem -->Stimmung
    Tonsystem-->NotationSystem
    Tonsystem --> Skale

    Skale-->DiatonischeScale
    DiatonischeScale-->Stammtonreihe
    NotationSystem -->Stammtonreihe
    Stammtonreihe-->Klaviatur
    Stammtonreihe-->NotenschriftWest
    Stammtonreihe-->MIDI
    MIDI-->SchriftlicheTon
    NotenschriftWest-->SchriftlicheTon
    Klaviatur-->SchriftlicheTon

    Skale --> Tonmaterial
    Skale-->Stuffentheory
    Tonmaterial-->Tonalität
    DiatonischeScale-->Tonalität
    Tonalität-->Harmonie

    Harmonie-->Dissonanz
    Harmonie-->Konsonanz
    Harmonie-->Akkord
    Harmonie-->Intervall

    Dissonanz--> KlingelteTon
    Konsonanz-->KlingelteTon
    Akkord-->KlingelteTon
    Intervall-->KlingelteTon

    Skale --> KlingelteTon
    Stimmung-->KlingelteTon


````
