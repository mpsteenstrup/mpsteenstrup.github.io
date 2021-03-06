# Webteknologier

## Indholdsfortegnelse
* [Præsentationer](##Præsentationer)
* [Læringsmål for undervisningen](laeringsmaal.md)
* [index.html, et eksempel på basal html kodning som opfylder læringsmålene](https://mpsteenstrup.github.io/index.html)
* [Eksempler til introduktion til html, side1.htlm...](/introduktion)
* [Opbygning af website](#-opbygning-af-website)
* [Layout](#css-og-webside-layout)
* [Farver](farver.md)
* [Gestaltlovene](gestaltlovene.md)
* [Interaktionsdesign](interaktionsdesign.md)
* [Github til hosting af websider](#github-til-hosting-af-websider)
* [AstroPi](https://github.com/mpsteenstrup/AstroPi2020/tree/master/informatik2020)

## Præsentationer
* [Webteknologier 1, hvad er internettet](/filer/Webteknologier1.pdf)
* [Webteknologier 2, projekt og HTML introduktion](/filer/Webteknologier2.pdf)
* [Webteknologier 3, CSS](/filer/Webteknologier3.pdf)
* [Webteknologier 4, design](/filer/Webteknologier4.pdf)

# Github til hosting af websider

Github er et online sted hvor udviklere lægger programmer,data og meget mere. Det er et versionsstyringsværktøj lavet til at arbejde på forskellige versione af samme software. Vi kommer ikke til at bruge denne feature men kun bruge
det til at have vores websider liggenden.
Det anbefales generelt ikke at bruge specialtegn og æøå i filnavne.


I kan bruge Github til at hoste jeres webside. Startsiden hedder ```index.html``` og skal placeres i roden af jeres github repository. I kan linke til undersider ved relative referencer, eks ```<a href="side2.html"> Link til side 2 </a>```.

For at aktivere jeres side skal I på Github gå in i:
```index.html -> Settings -> options -> Github pages.```

Denne siden kan ses på
[https://mpsteenstrup.github.io/index.html](https://mpsteenstrup.github.io/index.html)

Indsæt selv brugernavn og repository
```https://username.github.io/repository/index.html```


Det kan godt kræve lidt tålmodighed at arbejde direkte i editoren på Github, da siden ikke altid opdatere så hurtigt. Man kan evt prøve ```shift command R``` for hard reload af den side I vil se.


### Layout med topbar
Her er en template til et layout med en menu i toppen, [layoutTopbar.html](/introduktion/layoutTopbar.html)


## ```div``` og ```class```
```div``` står for **Content Division element** og er en ramme for indhold. Vi bruger den til at specificere forskelligt design og layout. ```class```giver elementer forskellige attributter, ud fra vores designvalg.

I eksemplet [class_capitals](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_classes_capitals) fra w3schools.com, definere vi designet i ```<style>``` med ```.city { }``` og kalder designet med ```<div class="city">```.

## CSS og webside layout
W3schools har faktisk skrevet ret godt, så her er linket.
[https://www.w3schools.com/css/css_website_layout.asp](https://www.w3schools.com/css/css_website_layout.asp)

Filen [responsiveWebdesign](/introduktion/responsivWebdesign.html) er en kommenteret version som skalerer fint med forskellige skærmstørrelser. Den er ret fin.
