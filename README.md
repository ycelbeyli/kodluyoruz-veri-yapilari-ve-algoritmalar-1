# Kodluyoruz - Veri Yapıları ve Algoritmalar "Insertion Sort Projesi"

### Soru 1: [22,27,16,2,18,6] -> Insertion Sort
### Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

#### Cevap 1:
#### 1. Aşama: [22,27,16,2,18,6] --> 2 ile 22 Yer değiştirir = [2,27,16,22,18,6]
#### 2. Aşama: [2,27,16,22,18,6] --> 6 ile 27 Yer değiştirir = [2,6,16,22,18,27]
#### 3. Aşama: [2,6,16,22,18,27] --> 22 ile 18 Yer değiştirir = [2,6,16,18,22,27]
#### Bu dizinin sonucu: [2,6,16,18,22,27]

### Soru 2: Big O gösterimini yazınız.

#### Cevap 2: O(n²) = O(6²) = O(36)

### Soru 3: Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

#### Not: Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

#### Cevap 3: Aradığımız sayı 18 olduğu için, Average Case kapsamına girer.

### Soru 4: [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

#### Cevap 4:

#### 1. Aşama: [7,3,5,8,2,9,4,15,6] --> 7 ile 2 Yer Değiştirir. = [2,3,5,8,7,9,4,15,6]
#### 2. Aşama: [2,3,5,8,7,9,4,15,6] --> 5 ile 4 Yer Değiştirir. = [2,3,4,8,7,9,5,15,6]
#### 3. Aşama:  [2,3,4,8,7,9,5,15,6] --> 8 ile 5 Yer Değiştirir. = [2,3,4,5,7,9,8,15,6]
#### 4. Aşama:  [2,3,4,5,7,9,8,15,6] --> 7 ile 6 Yer Değiştirir. = [2,3,4,5,6,9,8,15,7]
#### Bu dizinin sonucu: [2,3,4,5,6,9,8,15,7]


