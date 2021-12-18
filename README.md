# Opdracht-Data-Mining
# **Onderzoek naar Ondezoek verband pubs en ongevallen in Engeland**

In dit onderzoek zal worden getracht om een verband te zoeken tussen de locaties van pubs en de locaties van accidenten in het Verenigd Koninkrijk.

# Data sets
De gebruikte accidenten en casualties data komen allebei van Kaggle: https://www.kaggle.com/benoit72/uk-accidents-10-years-history-with-many-variables . Deze bestanden zijn te groot voor github maar zitten nrml in een map "./Kaggle_datasets/" om het goed te runnen.  

De dataset van de pubs komt ook van Kaggle. Verder wordt er, tijdens het onderzoek, ook gebruik gemaakt van datasets over bijvoorbeeld alcohol-blaastesten die werden genomen na een accident. Deze datasets zijn terug te vinden op https://www.gov.uk/government/statistical-data-sets/reported-drinking-and-driving-ras51 . Door een probleem met een onderliggende spark libary konden we de excel bestanden niet inlezen in xlsx formaat en hebben ze omgevorm in csv formaat. Deze kunnen worden terug gevonden via https://apbe-my.sharepoint.com/:f:/g/personal/s112617_ap_be/En5CVwuqbYRLm6N2sqzkeYQB9l67uctFv7vw9QOhY-lDbg?e=xt96dd en zitten gewoonlijk in de map "./Drink_and_drive_datacsv/..."

Voor enkele van de maps hebben we ook GeJson data gebruikt, Deze is eveneens terug te vinden op de drive https://apbe-my.sharepoint.com/:f:/g/personal/s112617_ap_be/En5CVwuqbYRLm6N2sqzkeYQB9l67uctFv7vw9QOhY-lDbg?e=xt96dd en zitten in de map "./GeoJson/..."

