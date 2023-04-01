# Verilen dizi [16,21,11,8,12,22] iki eşit parçaya ayrılır: [16,21,11] ve [8,12,22].
** Her parça ayrı ayrı Merge Sort algoritmasına sokulur. **
## İki parça, birleştirme (merge) adımında, sıralı hale getirilir: [11,16,21] ve [8,12,22].
##Son olarak, iki sıralı parça birleştirilir ve tamamı sıralanmış diziye dönüştürülür: [8, 11, 12, 16, 21, 22].
Aşamaların görsel bir şekilde gösterimi:

[16,21,11,8,12,22]
/
[16,21,11] [8,12,22]
/ \ /
[16,21] [11] [8,12] [22]
/ \ / \ /
[16] [21] [11] [8] [12] [22]
\ / \ / \ /
[16,21] [11] [8,12] [22]
\ / \ /
[11,16,21] [8,12,22]
\ /
[8,11,12,16,21,22]

# Bu aşamaların Big-O gösterimi O(n log n)’dir.# mergePatikadev
