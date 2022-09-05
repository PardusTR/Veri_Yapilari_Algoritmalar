# Veri Yapilari & Algoritmalar

[Patika](www.patika.dev)

## ***Insertion Sort Projesi***

### **1.Soru ve Cevabi**

*[22,27,16,2,18,6] -> Insertion Sort  
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.*

[**2**,27,16,22,18,6]  
[**2**,**6**,16,22,18,27]  
[**2**,**6**,**16**,22,18,27]  
[**2**,**6**,**16**,**18**,22,27]  
[**2**,**6**,**16**,**18**,**22**,27]  

### **2.Soru ve Cevabi**

*Big-O gösterimini yazınız.*  

**O(n<sup>2</sup>)**  

### **3.Soru ve Cevabi**

*Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.*  

*Average case:* Aradigimiz sayinin dizinin ortasinda olmasi. `Or. 16, 18` ve O(n<sup>2</sup>)'e esittir.  
*Worst case:* Aradigimiz sayinin dizinin en sonunda olmasi. `Or. 27`  ve O(n<sup>2</sup>)'e esittir.  
*Best case:* Aradigimiz sayinin dizinin en basinda olmasi. `Or. 2`  ve O(n)'e esittir.  

### **4.Soru ve Cevabi**

*Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.*

Siralama tamamlandiktan sonra 18 sayisi dizinin ortalarinda oldugu icin `Average Case` kapsamina girecektir.

### **Son Soru ve Cevabi**

*[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.*

`1.Adim` [**2**,3,5,8,7,9,4,15,6]  
`Bos Adim Sirali Olarak Geldigi Icin` [**2**,**3**,5,8,7,9,4,15,6]  
`2.Adim` [**2**,**3**,**4**,8,7,9,5,15,6]  
`3.Adim` [**2**,**3**,**4**,**5**,7,9,8,15,6]  
`4.Adim` [**2**,**3**,**4**,**5**,**6**,9,8,15,7]