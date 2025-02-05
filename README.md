# Insertion-Sort-Projesi
Bu projeyi, Algoritma öğrenmek ve veri yapıları konusundaki bilgimi pekiştirmek amacıyla patika.dev için hazırladım.

# Proje 1: Insertion Sort
[22,27,16,2,18,6] -> Insertion Sort

# **Soru 1** - Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Insertion Sort Aşamaları;
[22, 27, 16, 2, 18, 6] **(n)**
[22, 27, 16, 2, 18, 6] **(n-1)**
[16, 22, 27, 2, 18, 6] **(n-2)**
[2, 16, 22, 27, 18, 6] **(n-3)**
[2, 16, 18, 22, 27, 6] **(n-5)**
[2, 6, 16, 18, 22, 27] **(n-6)**

# **Soru 2** - Big-O gösterimini yazınız. 
Best Case (En İyi Durum):**O(n)** — Dizi zaten sıralıysa, sadece her eleman bir kez kontrol edilir.
Average Case (Ortalama Durum):**O(n²)** — Ortalama durumda her eleman için sıralı kısmı gezmemiz gerekir.
Worst Case (En Kötü Durum):**O(n²)** — Dizi tersten sıralıysa, her eleman için sıralı kısmın tamamını kontrol etmek gerekir.

# **Soru 3** - Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
Dizi sıralandıktan sonra, 18 sayısının yerleştirildiği aşama ortalama durumda olduğu için Average Case (O(n²)) kapsamına girer.
Çünkü her adımda, elemanları uygun pozisyonlarına yerleştirirken daha önce sıralanmış kısmı gezmek gerekecektir.

# **Soru 4** [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
Selection Sort, her adımda en küçük elemanı bulur ve bu elemanı dizinin başına yerleştirir. 
**1.Adım**
 - En küçük eleman **2** (bu dizideki en küçük sayı)
   **[2, 3, 5, 8, 7, 9, 4, 15, 6]** (2, 7 ile yer değiştirdi)
**2.Adım**
 - En küçük eleman **3** (bu dizideki en küçük sayı)
   **[2, 3, 5, 8, 7, 9, 4, 15, 6]** (Değişiklik yok, zaten 3 zaten 2'nin sağında)
**3.Adım**
  -  En küçük eleman **4**
   **[2, 3, 4, 8, 7, 9, 5, 15, 6]** (4, 5 ile yer değiştirildi)
**4.Adım**
  -En küçük eleman **5** (5 zaten doğru konumda)
   **[2, 3, 4, 5, 7, 9, 8, 15, 6]** (Değişiklik yok, zaten 5 doğru pozisyonda)
**SONUÇ**:
   **[2, 3, 4, 5, 7, 9, 8, 15, 6]**




                                                                                                                                                                                   **SEFA EMİR KALKAN**






 
