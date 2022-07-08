[16,21,11,8,12,22] -> Merge Sort <br>

1-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. <br>
2-Big-O gösterimini yazınız. <br>

<hr>

1. [16,21,11,8,12,22] -- İki eşit parçaya ayrılır. <br>

    [16,21,11] ve [8,12,22] -- Bu iki listede kendi içlerinde ikiye bölünür. <br>

    [16,21] ve [11] -- [8,12] ve [22] -- Tüm listeler birer eleman kalacak şekilde düzenlenir. <br>

    [16] - [21] - [11] -- [8] - [12] - [22] -- Listeler sıralanarak bir araya getirilir. <br>

    [16,21] - [11] -- [8,12] - [22] -- Listeler sıralanarak bir araya getirilir. <br>

    [11,16,21] -- [8,12,22] -- Listeler sıralanarak bir araya getirilir. <br>

    [8,11,12,16,21,22] -- Sıralanmadan sonraki son durum bu aşamada görüldüğü gibidir. <br>

2. Big-O Notasyonu <br><br>
    O(nlogn)
