# SDRlabs

# SDRlabs - Laborator 2 Recombee

## Dataset
- **Nume:** Netflix Movies and TV Shows
- **Sursă:** Kaggle, https://www.kaggle.com/datasets/shivamb/netflix-shows
- **Fișier:** `netflix_titles.csv`
- **Număr de produse:** 8.807 (între 100 și 10.000)
- **Domeniu:** filme și seriale

## Coloane în dataset
`show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`,
`release_year`, `rating`, `duration`, `listed_in`, `description`

`show_id` este identificatorul unic și nu este înregistrat ca proprietate
(devine `itemId` în Recombee).

## Proprietăți înregistrate în Recombee
| Proprietate | Tip |
|---|---|
| type | string |
| title | string |
| director | string |
| country | string |
| release_year | int |
| rating | string |
| description | string |
