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

## 1.git clone

Šo mēs būsim izdarījuši jau stundas laikā, bet ja nebiji stundā ir jaizdara 3 lietas
  1. Jauztaisa šī repo forks
  2. Jauztaisa savs repo lokālais klons, lai var izmantot
  3. Japievieno šis repo kā upstream, lai var turēt līdzi izmaiņām

## 2.git add 

Jaizveido fails kurā visa informācija tiks glabāta. Nosaukumam ir jābūt ```VARDS_UZVARDS```. Ja tas nebūs izpildīts, uzdevumu nevarēs tālāk pildīt un es nemaz nemēģināšu labot.

Šajā failā ir jāpievieno kommandas ```git remote -v``` izvads.
Pēc tam šis fails ir jāpievieno jaunā commita ar ziņu ```Otrais uzdevums``` un japusho uz github.com.

Visu komandu izvade ir jāiekopē failā ```VARDS_UZVARDS``` un jaizveido jaunā comitā .

## 3.git branch

Jaizveido jauns git branch ar commandu ```git checkout -b <branch-name>``` vai ```git branch <branch-name> && git checkout <branch-name>```. ```<branch-name>``` var būt jebkāds sakarīgs topic nosaukums jaunajam branch uz kura visa turpmākā darbība tiks balstīta.

Visu komandu izvade ir jāiekopē failā ```VARDS_UZVARDS``` un jaizveido jaunā comitā ar ziņu ```Trešais uzdevums``` un japusho uz github.com.

## 4.git log

Izmantojot ```git log``` komandu ir jātrod, kad šis uzdevums tika pievienots, kuram branch tas piederēja un kāds bija aprakst šim commitam, un commita checksumas, garā un īsā.
Visa inforācija par šo komandu atrodama [šeit](https://git-scm.com/docs/git-log).
To visu informāciju ir jāpievieno jaunā failā ar nosaukumu ```Git-log-found.txt``` un jāpievieno visa prasītā informācija sekojošā formāta :
```
Datums : <dd-mm-yyyy>
Branch : <branch-nosaukums>
Commit description: <Commit apraksts>
Long checksum : <checksum>
Short checksum : <checksum>
```

## 5.git blame

```
NEVER MENTION THAT SHIT AGAIN!!!!
```
Uzdevums ir atrast, kļūdu šajā uzdevuma tekstā un to izlabot izmantojot git blame komandu. 

> Tiem kas nesaprot. Javascript nav kuul. Tā rindiņa ir jaizmaina, bet git blame komanda tāpat ir jaizmanto, jo jums vajag comit hash.

Comitā ir jānorāda, hash comitam, kurā bija izveidota šī ķļūda.
Visu komandu izvade ir jāiekopē failā ```VARDS_UZVARDS``` un jaizveido jaunā comitā ar ziņu ```piektais uzdevums``` un japusho uz github.com.

## 6.git show

Jaizvada informācija par kādu commit izmantojot ``git show --pretty=format``` komandu ar pašizveidotu preaty formātu.
Info par to [šeit](https://git-scm.com/docs/git-show)

Visu komandu izvade ir jāiekopē failā ```VARDS_UZVARDS``` un jaizveido jaunā comitā ar ziņu ```sestais uzdevums``` un japusho uz github.com.

## 7.git diff

Ar kommandu ```git diff``` var apskatīt izmaiņas starp commitiem, kas ir laba informācija, bet var arī veidot patch failus. Tas ir arī uzdevums izveidot jaunu failu, tajā veikt izmaiņas ar ```git diff HEAD > save.patch```  izveidot jaunu patch failu un šo failu comitot, bet ne failu ko izveidoja.

Visu komandu izvade ir jāiekopē failā ```VARDS_UZVARDS``` un jaizveido jaunā comitā ar ziņu ```septītais uzdevums``` un japusho uz github.com.

