## Basic Formal Ontology Hierarchy
```mermaid
graph LR
    A(Entity):::BFO --> B(Continuant)
    B(Continuant):::BFO --> D(Specifically Dependent<br> Continuant)
    B(Continuant) --> E(Generically Dependent<br> Continuant):::BFO
    B(Continuant) --> F(Independent<br> Continuant)
    F(Independent<br> Continuant):::BFO --> G(Material Entity)
    F(Independent<br> Continuant) --> H(Immaterial<br> Entity)
    D(Specifically Dependent<br> Continuant):::BFO --> I(Quality)
    D(Specifically Dependent<br> Continuant) --> J(Realizable<br> Entity):::BFO
    I(Quality):::BFO --> K(Relational<br> Quality):::BFO
    J(Realizable<br> Entity):::BFO --> L(Role):::BFO
    J(Realizable<br> Entity) --> M(Disposition):::BFO
    M(Disposition) --> N(Function):::BFO
    H(Immaterial<br> Entity):::BFO --> O(Site):::BFO
    H(Immaterial<br> Entity) --> P(Spatial<br> Region):::BFO
    H(Immaterial<br> Entity) --> Q(Continuant Fiat<br> Boundary):::BFO
    Q(Continuant Fiat<br> Boundary):::BFO --> R(Fiat<br> Point):::BFO
    Q(Continuant Fiat<br> Boundary) --> S(Fiat<br> Surface):::BFO
    Q(Continuant Fiat<br> Boundary) --> T(Fiat<br> Line):::BFO
    P(Spatial<br> Region):::BFO --> VD(Zero-Dimensional<br> Spatial Region):::BFO
    P(Spatial<br> Region):::BFO --> U(One-Dimensional<br> Spatial Region):::BFO
    P(Spatial<br> Region):::BFO --> V(Two-Dimensional<br> Spatial Region):::BFO
    P(Spatial<br> Region):::BFO --> W(Three-Dimensional<br> Spatial Region):::BFO
    G(Material<br> Entity):::BFO --> X(Fiat Object Part):::BFO
    G(Material<br> Entity):::BFO --> Y(Object<br> Aggregate):::BFO
    G(Material<br> Entity):::BFO --> Z(Object):::BFO
    A(Entity):::BFO --> C(Occurrent):::BFO
    C(Occurrent):::BFO --> AA(Process):::BFO
    C(Occurrent) --> AB(Process<br> Boundary):::BFO
    C(Occurrent) --> AC(Temporal<br> Region):::BFO
    C(Occurrent) --> AD(Spatiotemporal<br> Region):::BFO
    AA(Process):::BFO --> AE(History):::BFO
    AC(Temporal<br> Region):::BFO --> AF(Zero-Dimensional<br> Temporal Region):::BFO
    AC(Temporal<br> Region) --> AI(One-Dimensional<br> Temporal Region):::BFO
    AF(Zero-Dimensional<br> Temporal Region):::BFO --> AG(Temporal<br> Instant):::BFO
    AI(One-Dimensional<br> Temporal Region):::BFO --> AH(Temporal<br> Interval):::BFO

    classDef BFO fill:#F5AD27,color:#060606

  ```
  
