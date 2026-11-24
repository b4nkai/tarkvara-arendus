<h1>M-TVA4-26 HARJUTUSED</h1>

>harjutamine git käsklused

1. git init
2. git add
3. git commit
4. git switch
5. git merge
6. git branch
7. git switch
8. git log
9. git status
10. git push
11. git checkout

>Uue repositooriumi loomine

`git init`

>Repositoriumi 

echo > failinimi.txt

>faili lisamine *stage*'i (lavastamine)

`git add failinimi.txt`
`git add .` - lisa koik muudatused

>koodi kinnituse loomine (*commit*)

`git commit -m "add fail in repo`
`git commit -a -m "add feature"`

- -a lisab koik muudatused, saab kasutada ilma lavastamata
- -m lubad kohe kinnitus sonumi lisada

> koodiharu loomine ja kasutamine

`git switch haru-nimi` - vahetada branchi
`git switch -c uue-haru-nimi` - looma uued branchi ja kohe vahetada

> koodiharude sidumine (*merge*)

`git merge mestitav-haru`

>mestimisel konflikti lahendamine

```
<<<<<<<<<< HEAD
minu tehtud muudatused
=========
mestitaval harul tehtud muudatused
>>>>>>>>> mestitav-haru
```

    1. Tuleb eemaldada read:
    ```
        <<<<<<<<<< HEAD
        =========
        >>>>>>>>> mestitav-haru
    ```

    ülejäänud sisu võib oma äranägemist järgi ümber kirjutada

    teha koodi kinnitus, mis sisaldab konflikti lahenduse käigus muudetud faile




>versiooniajaloo kuvamine




