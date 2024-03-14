Refleksion over implementer et Figma design

Jeg havde overset, at vi skulle kode fire udvalgte sider, så jeg startede med den første side og nåede ikke længere end den. Jeg kodede mobilversionen først, og det brugte jeg meget lang tid på, så jeg nåede ikke at arbejde særlig meget med responsivitet, og det lykkedes mig ikke at få container queries til at virke, så jeg endte med at bruge media queries. Jeg skal blive bedre til at gå i gang med nye ting, når jeg sidder fast. Jeg føler, at jeg har brugt alt for meget tid på enkelte detaljer.

Som det første kiggede jeg på designet og forsøgte at lave custom properties for styles, jeg tænkte skulle genbruges. Undervejs dukkede der nye styles op, som jeg så prøvede at tilføje til mit eksisterende system. Jeg kan godt se, at custom properties er smarte for genbrugelighed, men det blev hurtigt lidt rodet, og jeg havde svært ved at finde ud af, hvilke kategorier jeg skulle placere dem i.

Det har været godt at bruge Astro igen og få det genopfrisket. I fremtiden vil jeg forsøge at lægge en plan over, hvilke komponenter jeg skal bruge, så jeg kan have bedre overblik over dem og organisere og navngive dem bedre.

Jeg kan ikke få container queries til at virke. Jeg tænkte, at det var fordi mine containere ikke blev større, fordi de var låst fast i et gridlayout. Jeg prøvede at lave en container, som udvidede sig sammen med skærmen, når skærmen blev bredere, men her kunne jeg heller ikke få det til at virke. Jeg prøvede i forskellige browsere, men det hjalp ikke.

Jeg forsøgte at bruge container queries ved at tilføje:

container: navn / inline-size;

til den container, jeg gerne ville bruge, og prøvede at vælge containeren ved at skrive:

@container navn (width < 50ch) {}

Men kunne ikke få hul igennem. Jeg prøvede også andre måder, som jeg fandt ved at google, men intet virkede. Det må jeg lære i fremtiden.

Jeg er tilfreds med mobilversionen af mit projekt, men i større formater fungerer det ikke så godt. Jeg var i tidsnød, så jeg endte med kun at tilføje en media query ved 1200px, da mit design fungerede bedst i denne størrelse.

At arbejde med denne opgave har gjort mig mere tilpas med mange af de ting, som vi er blevet introduceret for på dette tema, som brugerdefinerede variabler og centrerede grid layouts.