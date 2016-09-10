# Nye Java-Projekter

Filerne i dette repository, er de standardfiler, som skal være i alle nye java-repositories. Den indeholder en gitignore-fil som ignorerer alle unødige filer genereret af både Eclipse og IntelliJ. Dvs. at det vil være lettere for os at arbejde sammen, selvom vi arbejder i forskellige programmer.

Desuden ligger der også "travis"-filer, som gør det muligt for [Travis-CI](https://travis-ci.org/hold11) at lave automatisk build.

Husk dog for hvert projekt, at lave sin egen README.md-fil (så ikke denne her fil).

# Oprettelse af nye projekter

Hvis du skal lave et nyt projekt, så lav som <u>det første</u> et git-repository. Dernæst, så sørg for at projektet er klonet til din computer, og læg derefter disse filer ind i projektet, og commit. *Først* derefter kan du rette i filer (fx README.md) og oprette et nyt projekt i fx Eclipse eller IntelliJ.

Gå ind under releases på dette repository og hent den nyeste version af disse filer.

# Rettelser i filer

I nogle projekter, kan det være et krav, at der laves rettelser til build.xml-filen og .trvis.yml-filen, så vær opmærksom på det.

# Travis-CI - Automatisk build

Hvis travis-ci skal benyttes (automatisk test og build) til projektet, skal man ind og aktivere det på [Travis-CI](https://travis-ci.org/hold11)'s hjemmeside.
