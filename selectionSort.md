# Veri Yapıları ve Algoritmalar - Ödev #1

[patika.dev profil linkim](https://app.patika.dev/hbgursoy)

## Selection (Insertion) (Insertion) 

---

1. [22, 27, 16, 2, 18, 6] verilen dizinin;
    
* *Selection (Insertion) Sort* türüne göre aşamalarını yazınız

    ```
    [22 27 16 2 18 6] \\ (n)
    [2 27 16 22 18 6] \\ (n-1)
    [2 6 16 22 18 27] \\ (n-2)
    [2 6 16 18 22 27] \\ (1)
    ```

* 'Big-O' gösterimini yazınız

    O($n^2$)

* Dizi sıralandıktan sonra 18 sayısı aşağıdaki caselerden hangisinin kapsamına girer?

    - Average case
    - Worst case
    - Best case

    Insertion sort türüne göre dizi sıralaması aşağıdaki gibidir.

    ```
    [2 6 16 18 22 27]
    ```
    18 sayısı dizinin orta bölgesinde bulunduğu için ***Average case*** kapsamında girer.

---

2. [7, 3, 5, 8, 2, 9, 4, 15, 6] verilen dizinin *Selection (Insertion) Sort* türüne göre ilk 4 adımını yazınız.

    ```
    [7 3 5 8 2 9 4 15 6] \\ (n)
    [2 3 5 8 7 9 4 15 6] \\ (n-1) --> 1. adım
    [2 3 4 8 7 9 5 15 6] \\ (n-2) --> 2. adım
    [2 3 4 5 7 9 8 15 6] \\ (n-3) --> 3. adım
    [2 3 4 5 6 9 8 15 7] \\ (n-4) --> 4. adım
    ```