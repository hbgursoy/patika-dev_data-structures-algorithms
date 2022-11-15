# Veri Yapıları ve Algoritmalar - Ödev #2

[patika.dev profil linkim](https://app.patika.dev/hbgursoy)

## Merge Sort 

---

1. [16, 21, 11, 8, 12, 22] verilen dizinin;
    
* *Merge Sort* türüne göre aşamalarını yazınız

    ```
                [16 21 11 8 12 22]

        [16 21 11]               [8 12 22]

      [16 21] [11]             [8] [12 22]

    [16] [21] [11]           [8] [12] [22]

      [16 21] [11]             [8] [12 22]

        [11 16 21]               [8 12 22]

                [8 11 12 16 21 22]

* 'Big-O' gösterimini yazınız

    O(n $log{n}$)