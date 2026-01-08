# Athens_Metro

## Stations 

Modern Athens revolves around 3 central Stations: 
#### [[Monastiraki]]-Station  

#### [[Syntagma]]-Station 

#### [[Omonoia_Station]]  



## Lines 

### [[Green_Metro_1,Athens]]

### [[Blue_Metro_3,Athens]] 

### [[Red_Metro_2,Athens]] 


## Metro Network 

```mermaid
graph TD;


    %% Class Definitions %%
    classDef greenText fill:#6ECF68,stroke:#2E7D32,stroke-width:2px,color:#FFFFFF;
    classDef redText fill:#E57373,stroke:#C62828,stroke-width:2px,color:#FFFFFF;
    classDef blueText fill:#64B5F6,stroke:#1565C0,stroke-width:2px,color:#FFFFFF;

    %% Line definitions %%
    subgraph Line1_Green["Green Line (1)"]
      Kifisia --> KAT --> Marousi --> Neratziotissa --> Irini --> Iraklio --> Nea_Ionia --> Pefkakia --> Perissos --> Ano_Patisia --> Aghios_Eleftherios --> Kato_Patisia --> Aghios_Nikolaos --> Attiki-G --> Victoria --> Omonia-G --> Monastiraki-G --> Thiseio --> Petralona --> Tavros --> Moschato --> Faliro --> Piraeus 
    end
    
    subgraph Line2_Red["Red Line (2)"]
      Anthoupoli --> Sepolia --> Attiki-R --> Larissa --> Metaxourghio --> Omonia-R --> Panepistimio --> Syntagma-R --> Akropoli --> NeosKosmos --> Aghios_Ioannis --> Dafni --> Aghios_Dimitrios --> Ilioupoli --> Alimos --> Argyroupoli --> Elliniko 
    end
    
    subgraph Line3_Blue["Blue Line (3)"]
      Airport --> Koropi --> Palania_Kantza --> Pallini --> Doukissis_Plakentias --> Halandri --> Agia_Paraskevi --> Nomismatokopio --> Holargos --> Ethniki_Amyna --> Katehaki --> Panormou --> Ampelokipi --> Megaro_Moussikis --> Evangelismos --> Syntagma-B --> Monastiraki-B --> Kerameikos --> Eleonas --> Egaleo --> Aghia_Marina
    end
    
    %% Intersection Points %%
    Monastiraki-G--Transfer-->Monastiraki-B
    Omonia-G--Transfer-->Omonia-R
    Attiki-G --Transfer --> Attiki-R
    Syntagma-R -- Transfer --> Syntagma-B 


    %% Custom styles for each Station %%
    class Kifisia,KAT,Marousi,Neratziotissa,Irini,Iraklio,Nea_Ionia,Pefkakia,Perissos,Ano_Patisia,Aghios_Eleftherios,Kato_Patisia,Aghios_Nikolaos,Attiki-G,Victoria,Omonia-G,Monastiraki-G,Thiseio,Petralona,Tavros,Moschato,Faliro,Piraeus greenText;
    class Anthoupoli,Sepolia,Attiki-R,Larissa,Metaxourghio,Omonia-R,Panepistimio,Syntagma-R,Akropoli,NeosKosmos,Aghios_Ioannis,Dafni,Aghios_Dimitrios,Ilioupoli,Alimos,Argyroupoli,Elliniko redText;
    class Airport,Koropi,Palania_Kantza,Pallini,Doukissis_Plakentias,Halandri,Agia_Paraskevi,Nomismatokopio,Holargos,Ethniki_Amyna,Katehaki,Panormou,Ampelokipi,Megaro_Moussikis,Evangelismos,Syntagma-B,Monastiraki-B,Kerameikos,Eleonas,Egaleo,Aghia_Marina blueText;

```


## Confidential Links & Embeds: 

### #is_/same_as :: [[/_Standards/Earth/Continent/Europe/Europe~South/Greece/Regions-Greek/Attica/cities~Attica/Athens/Athens_Metro|Athens_Metro]] 

### #is_/same_as :: [[/_public/Earth/Continent/Europe/Europe~South/Greece/Regions-Greek/Attica/cities~Attica/Athens/Athens_Metro.public|Athens_Metro.public]] 

### #is_/same_as :: [[/_internal/Earth/Continent/Europe/Europe~South/Greece/Regions-Greek/Attica/cities~Attica/Athens/Athens_Metro.internal|Athens_Metro.internal]] 

### #is_/same_as :: [[/_protect/Earth/Continent/Europe/Europe~South/Greece/Regions-Greek/Attica/cities~Attica/Athens/Athens_Metro.protect|Athens_Metro.protect]] 

### #is_/same_as :: [[/_private/Earth/Continent/Europe/Europe~South/Greece/Regions-Greek/Attica/cities~Attica/Athens/Athens_Metro.private|Athens_Metro.private]] 

### #is_/same_as :: [[/_personal/Earth/Continent/Europe/Europe~South/Greece/Regions-Greek/Attica/cities~Attica/Athens/Athens_Metro.personal|Athens_Metro.personal]] 

### #is_/same_as :: [[/_secret/Earth/Continent/Europe/Europe~South/Greece/Regions-Greek/Attica/cities~Attica/Athens/Athens_Metro.secret|Athens_Metro.secret]] 

