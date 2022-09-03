# Malyala Sai Karthik
## My favorite museum to visit is The Louvre, Paris
The Louvre in Paris, France, has almost **73,000 square meters** of exhibition space, making it the **largest museum in the world**. It is regarded as one of the best and has works from **antiquity to the 19th century**, including the Mona Lisa and the famed Venus de Milo.
---
## Travel direction to The Louvre, Paris from Paris Orly Airport
There are 8 ways to get from Paris Orly Airport (ORY) to The Louvre by tram, train, bus, night bus, taxi, car, rideshare or towncar
1. It takes approximately 59 min to get from Paris Orly Airport (ORY) to The Louvre, including transfers.
2. The cheapest way to get from Paris Orly Airport (ORY) to The Louvre is to rideshare which costs $3 and takes 53 min.
3. The fastest way to get from Paris Orly Airport (ORY) to The Louvre is to taxi. Taking this option will cost $30 - $40 and takes 18 min.
4. There is an overnight bus departing from Aéroport Orly 4 and arriving at Châtelet. This bus operates every day. The journey takes approximately 1h 1m.
5. There are services departing from Orly 4 and arriving at Châtelet les Halles via Antony. The journey, including transfers, takes approximately 59 min.
## Other tourist locations around the museum
* Pyramide du Louvre
* The Tour Guy
* Auditorium du Louvre
* Fronton la Terre et l’Eau du Pavillon Colbert du Musée du Louvre
* Arc de Triomphe du Carrousel
* Seine River
* Carrousel du Louvre
* Right Bank (Rive Droite)
* Place du Carrousel
* Statue Equestre de Louis XIV

[AboutMe](https://github.com/MalyalaSaiKarthik/assignment2-malyala/blob/main/AboutMe.md)

---
## The US is home to some of the most spectacular scenery in the world and some of the most recognizable icons on the planet. 
Top attractions in the United States are bucket list destinations, drawing visitors from around the world.
|City|Location|Time spend|
|---|---|---:|
|Arizona|Grand Canyon|1h|
|New York|Niagara Falls|1h2m|
|New York|Statue of Liberty|30m|
|Orlando|Walt Disney World Resort|3h5m|

---
## Code Fencing
```
SVG use tag outputting SVG differently
<div>
    <p>Using the entire SVG code within the HTML</p>
    <svg width="24" height="25" viewBox="0 0 24 25" fill="none"   xmlns="http://www.w3.org/2000/svg">
        <path d="M5 9.00146L11.4697 15.4711C11.7626 15.764 12.2374 15.764 12.5303 15.4711L19 9.00146" stroke="#1E0564" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
    </svg>
    <svg style="display:none" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
        <symbol id="chevron" viewBox="0 0 24 24">
            <title>Chevron</title>
            <desc>Chevron icon</desc>
            <path d="M5 9.00146L11.4697 15.4711C11.7626 15.764 12.2374 15.764 12.5303 15.4711L19 9.00146" stroke="#1E0564" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </symbol>
    </svg>
    <p>Referencing SVG using &lt;use href=""&gt; tag</p>
    <svg class="useSvg">
        <use href="#chevron" />
    </svg>
</div>
```
<https://stackoverflow.com/questions/73588984/svg-use-tag-outputting-svg-differently>


This is a collection of simple SVG shapes used as patterns. This list may grow over time but the idea is less to have a comprehensive collection than it is to have the syntax handy as a starting point for creating new and exciting patterns.
```
<svg width="100%" height="100%">
    <mask maskUnits="userSpaceOnUse" id="fade">
        <linearGradient id="gradient" x1="0" y1="0" x2="0" y2="100%">
            <stop offset="0" style="stop-color: #FFFFFF"></stop>
            <stop offset="1" style="stop-color: #000000"></stop>
        </linearGradient>
        <rect fill="url(#gradient)" width="100%" height="100%"></rect>
    </mask>
    <pattern id="pattern-circles" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
        <circle mask="url(#fade)" cx="20" cy="20" r="20"></circle>
    </pattern>
    <rect x="0" y="0" width="100%" height="100%" fill="url(#pattern-circles)"></rect>
</svg>
```
Snippet from css-tricks <https://css-tricks.com/snippets/svg/svg-patterns/>