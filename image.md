```mermaid
graph TD
    A[Connexion<br>connexion.html] -->|Connexion réussie| B[Index<br>index.html]
    B -->|Menu déroulant| C[État des frais<br>etat-frais.html]
    B -->|Menu déroulant| D[Fiche frais forfait<br>fiche-frais-for-frait.html]
    B -->|Menu déroulant| E[Fiche frais<br>fiche-frais.html]
    B -->|Menu déroulant| F[Fiche note de frais<br>fiche-note-frais.html]
    B -->|Menu déroulant| G[Frais forfait<br>frais-forfait.html]
    B -->|Menu déroulant| H[Déconnexion<br>deconnexion.html]
    C -->|Menu déroulant| B
    C -->|Menu déroulant| D
    C -->|Menu déroulant| E
    C -->|Menu déroulant| F
    C -->|Menu déroulant| G
    C -->|Menu déroulant| H
    D -->|Menu déroulant| B
    D -->|Menu déroulant| C
    D -->|Menu déroulant| E
    D -->|Menu déroulant| F
    D -->|Menu déroulant| G
    D -->|Menu déroulant| H
    E -->|Menu déroulant| B
    E -->|Menu déroulant| C
    E -->|Menu déroulant| D
    E -->|Menu déroulant| F
    E -->|Menu déroulant| G
    E -->|Menu déroulant| H
    F -->|Menu déroulant| B
    F -->|Menu déroulant| C
    F -->|Menu déroulant| D
    F -->|Menu déroulant| E
    F -->|Menu déroulant| G
    F -->|Menu déroulant| H
    G -->|Menu déroulant| B
    G -->|Menu déroulant| C
    G -->|Menu déroulant| D
    G -->|Menu déroulant| E
    G -->|Menu déroulant| F
    G -->|Menu déroulant| H
    H -->|Déconnexion| A
    B -->|Non connecté| A
    C -->|Non connecté| A
    D -->|Non connecté| A
    E -->|Non connecté| A
    F -->|Non connecté| A
    G -->|Non connecté| A
