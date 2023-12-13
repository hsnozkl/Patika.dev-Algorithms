# Kodluyoruz Veri Yapilari ve Algoritmalar
    Kodluyoruz Veri yapilari ve algoritmalar eğitimi projeleri için açtığım repo.
# Selection Sort Projesi

- **Proje 1**
--------------------------------------------------------------------
    [22,27,16,2,18,6] -> Insertion Sort

    Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

        Cevap :

        [2,27,16,22,18,6]

        [2,6,16,22,18,27]

        [2,6,16,22,18,27]

        [2,6,16,18,22,27]

        [2,6,16,18,22,27]
    
    Big-O gösterimini yazınız.

        Cevap : n+(n-5)+(n-4)+(n-3)+(n-2)+(n-1)+1=[n(n+1)]/2=(n^2+n)/2 → O(n^2)

    1. Average case: Aradığımız sayının ortada olması
    2. Worst case: Aradığımız sayının sonda olması
    3. Best case: Aradığımız sayının dizinin en başında olması.
    Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

        Cevap : Average case
--------------------------------------------------------------------
    [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

        Cevap :

        [2,3,5,8,7,9,4,15,6]

        [2,3,5,8,7,9,4,15,6]

        [2,3,4,8,7,9,5,15,6]

        [2,3,4,5,7,9,8,15,6]
--------------------------------------------------------------------


- **Proje 2**

--------------------------------------------------------------------
    [16,21,11,8,12,22] -> Merge Sort

    Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

    Cevap :
                                    [16,21,11,8,12,22]
                                        /        \
                               [16,21,11]        [8,12,22]
                                 /    \            /   \
                           [16,21]    [11]    [8,12]   [22]
                             /  \       |      /  \      |
                          [16]  [21]  [11]   [8]  [12] [22]
                            \    /      \    /      \   /
                            [16,21]     [8,11]     [12,22]
                                \         /            |
                                [8,11,16,21]        [12,22]
                                     \                /
                                    [8,11,12,16,21,22]

        Big-O gosterimi : O(nlogn) olacaktir.

--------------------------------------------------------------------

- **Proje 3**

--------------------------------------------------------------------
    [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

    Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

    Cevap:
                    
                    Root = 5 
                    
                      5                        
                   /     \
                  1       7
                /  \     /  \
               0    3   6    8
                  /  \        \
                 2    4        9
--------------------------------------------------------------------