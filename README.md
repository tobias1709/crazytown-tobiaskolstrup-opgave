# Crazytown Tobias Kolstrup Opgave

## Opgavebeskrivelse
***

### Fase 1
Lav to knapper som der kan bruges til at kører frem og tilbage imellem 1-4.

Hvis du kommer over 4 skal den gå tilbage til 1 og på samme måde skal den gå op til 4 hvis den kommer under 1.

***

### Fase 2
(https://dog.ceo/api/breeds/image/random)

Fetch via API som kalder et random billedet hver gang du trykker på frem knappen.

Lav en local mappe hvor du downloader 4 billeder fra din fetch som du nu skal bruge i stedet for at fetch et nyt billedet hver gang.

Knapperne skal nu kunne kører igennem disse 4 billeder på samme måde som den kunne køre igennem tallene 1-4.

***

### Fase 3
Vi skal nu bruge billederne som thumbnails under vores main image. Layout skal være ligesom vi ser nedenfor.
```
Linje 29: Main image.
Linje 30: Thumbnails.
Linje 31: Buttons.

   []
[][][][]
- -  - -
```

Gør så man kan trykke på thumbnails for at komme til det valgte billedet.

***

### Fase 4
Lav 2 nye knapper.

Den første knap skal skifte til det næste billedet efter 3 sekunder.

Den anden knap skal kører konstant igennem billederne hver fjerde sekund ligesom et slideshow. (Hint: setInterval).

Gør så når man trykker på billedet stopper den slideshowet.

***

### Ekstra
Lav en CSS Loader som giver siden 3 sekunder før hjememsiden bliver vist.

Gør så det valgte thumbnail bliver markeret med en border og alle de andre thumbs bliver greyed out.

***
