# school-task
Šis ir repo kuru jūs visi izmantosiet sava uzdevuma izpildei

# Uzdevumu nosacījumi

Visi uzdevumi būs saistīti ar kādu no git komandām. 
Visu uzdevumu izvadītais teksts no konsoles ir jāsaglabā pēc šadiem nosacījumiem : 

  * Katrs uzdevumuma teksts ir savā commitā.
  * Uzvevumi ir jaatdala ar tukšu līniju starpā 

# Uzdevumi 

## 0.Sagatavošanās

Visu jāsāk ar git lejuplādi [šeit](https://www.git-scm.com/download), un [github](https://github.com/join?source=header-home) profila izveidi.

Pēc git iegūšanas un github profila izveides, git ir jakonfigurē izmantošanai.
To darama ar kommandām 

```
$ git config --global user.email tavs@epasts.com
$ git config --global user.name "Tavs vārds"
```

## 1.Git clone

Šo mēs būsim izdarījuši jau stundas laikā, bet ja nebiji stundā ir jaizdara 3 lietas
  1. Jauztaisa šī repo forks
  2. Jauztaisa savs repo lokālais klons, lai var izmantot
  3. Japievieno šis repo kā upstream, lai var turēt līdzi izmaiņām

## 2.Git add 

Jaizveido fails kurā visa informācija tiks glabāta. Nosaukumam ir jābūt ```VARDS_UZVARDS```. Ja tas nebūs izpildīts, uzdevumu nevarēs tālāk pildīt un es nemaz nemēģināšu labot.

Šajā failā ir jāpievieno kommandas ```git remote -v``` izvads.
Pēc tam šis fails ir jāpievieno jaunā commita un japusho uz github.com.

## 3.Git branch

Jaizveido jauns git branch ar commandu ```git checkout -b <branch-name>``` vai ```git branch <branch-name> && git checkout <branch-name>```. ```<branch-name>``` var būt jebkāds sakarīgs topic nosaukums jaunajam branch uz kura visa turpmākā darbība tiks balstīta.

