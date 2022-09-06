# Veri Yapilari & Algoritmalar

[Patika.dev](www.patika.dev)

## ***Merge Sort Projesi***

*[16,21,11,8,12,22] -> Merge Sort*

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

### **Soru ve Cevabi**

*Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.*

[16,21,11,8,12,22]

[16,21,11] --- [8,12,22]  
[16] --- [21,11] &nbsp; &nbsp; --- &nbsp; &nbsp; [8] --- [12,22]  
[16] --- [11,21] &nbsp; &nbsp; --- &nbsp; &nbsp; [8] --- [12,22]  
[11,16,21] &nbsp; &nbsp; --- &nbsp; &nbsp; [8,12,22]  
[8,11,12,16,21,22]

*Big-O gösterimini yazınız.*

`Big-O Gosterimi: O(nlogn)`