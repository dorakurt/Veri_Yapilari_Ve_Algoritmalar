# Veri Yapıları ve Algoritmalar

## Insertion Sort

[22,27,16,2,18,6] -> Insertion Sort

* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```
[22,27,16,2,18,6]   (n)
[2,27,16,22,18,6]   (n-1)
[2,6,16,22,18,27]   (n-2)
[2,6,16,18,22,27]   (1)
```

---

* Big-O gösterimini yazınız.

```
Big-O : (n²)
```

---

* Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

-Average case: Aradığımız sayının ortada olması
-Worst case: Aradığımız sayının sonda olması
-Best case: Aradığımız sayının dizinin en başında olması.

```

Average Case: [..,..,..,18,..,..,]
Worst Case: [..,..,..,..,..,18]
Best Case: [18,..,..,..,..,..]

-[2,6,16,18,22,27] dizi sıralandığında ortada kalan 18 average case'imizdir.
-
```

---

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

```
[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
```