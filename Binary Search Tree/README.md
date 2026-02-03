# Binary Search Tree Projesi (Böyle düzenli olması için yapay zekadan yardım aldım.)

## Proje 3
**Dizi:** `[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]`

**Binary Search Tree Aşamaları:**
Verilen dizinin elemanları sırayla ağaca eklenir. Kural: Her düğümün solunda kendinden küçük, sağında kendinden büyük değerler yer alır.

1. **Root (Kök): 7** olarak belirlenir.
2. **5**, 7'den küçük olduğu için **soluna** eklenir.
3. **1**, 7 ve 5'ten küçük olduğu için 5'in **soluna** eklenir.
4. **8**, 7'den büyük olduğu için **sağına** eklenir.
5. **3**, 5'ten küçük ama 1'den büyük olduğu için 1'in **sağına** eklenir.
6. **6**, 7'den küçük ama 5'ten büyük olduğu için 5'in **sağına** eklenir.
7. **0**, hepsinden küçük olduğu için 1'in **soluna** eklenir.
8. **9**, 7 ve 8'den büyük olduğu için 8'in **sağına** eklenir.
9. **4**, 3'ten büyük olduğu için 3'ün **sağına** eklenir.
10. **2**, 3'ten küçük olduğu için 3'ün **soluna** eklenir.

## Ağaç Yapısı (Görsel)

```text
        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
     / \
    2   4
