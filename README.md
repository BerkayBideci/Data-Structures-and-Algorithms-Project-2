# Veri Yapıları ve Algoritmalar | Merge Sort Projesi
- [www.patika.dev](www.patika.dev) eğitimleri kapsamında tasarlanmıştır.

---

Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.  
Big-O gösterimini yazınız.

---

1. [16,21,11,8,12,22] merge sort ile birlikte mümkün mertebe iki eşit parçaya bölünür.  
Sonuç: [16,21,11]---[8,12,22]
2. Aynı şekilde [16,21,11]---[8,12,22] bölünen elementler mümkün mertebe iki eşit parçaya bölünür.  
Sonuç: [16]---[21,11]---[8,12]---[22]
3. Bu işlem her kısımda tek bir element kalıncaya dek devam eder.  
Sonuç: [16]---[21]---[11]---[8]---[12]---[22]
4. Daha sonrasında elementler tekrar birleştirilir ve kendi aralarında sıralanır.  
Sonuç: [16]---[11,21]---[8,12]---[22]
5. İşlem aynı şekilde devam eder.  
Sonuç: [11,16,21]---[8,12,22]
6. İşlem aynı şekilde devam eder ve merge sort tamamlanır.  
Sonuç: [8,11,12,16,21,22]

- Big-O Notation = O(nLogn)