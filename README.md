# SZE-FordProg-2021-Calculator
Az alapműveleteket tudjuk elvégezni, azonban nem csak a számok használatával, hanem, mint egy programozási nyelvben deklarálni tudunk változókat, melyek értékeivel tudunk számolni.
A változónak nem csak direkt utasítással adhatunk értéket, hanem elágazással is.

# Segítség
A `help` szó beírásával a kimeneten láthatjuk a szintaxist.  
```  
>  help  
DECLARE:
   int|integer 'variable'
   int|integer 'variable' = 'value'
SET VARIABLE VALUE:
   'variable' = 'value'
CHECK VARIABLE VALUE:
   'variable'
CALCULATE:
   calc 'expression'
BRANCH:
   if ('comparison') {'variable' = 'value'} else {'variable' = 'value'}
DELETE VARIABLE:
   free 'variable'
EXIT:
   exit 
```

# Változó
Deklarálni az `int` vagy `integer` szavakkal tudunk új változót, ahol egyből értéket is adhatunk neki.
```
> int a = 10
'a' = 10
```
Ha a változó már deklarálva lett:
```
> int a
'a' already declared!
```
Értékadás a már deklarált változónak:
```
> a = 2
'a' = 2
```
## Törlés
```
> free a
Variable 'a' deleted!
```

# Számolás
Ha számolni szeretnénk valamit, akkor szükséges a `calc` szó használata:
```
> calc a + 10
'a' = 2
Result: 12
```
## Elágazás
Ha elágazással szeretnénk értéket adni a változónak:
```
> if (a=2) {b=10}
> b
'b' = 10
```
# Kilépés
Kilépni az `exit` használatával tudunk.
