# Merge Sort Projesi

## 1. Aşamalar
Verilen dizi: `[16, 21, 11, 8, 12, 22]`

Dizi, elemanlar tek kalana kadar parçalanır, sonra sıralanarak birleştirilir:

1. **Parçalanma:**
   - `[16, 21, 11]` ve `[8, 12, 22]`
   - `[16]`, `[21, 11]` ve `[8]`, `[12, 22]`
   - `[16]`, `[21]`, `[11]`, `[8]`, `[12]`, `[22]` (Hepsi tek kaldı)

2. **Birleşme (Sıralı):**
   - `[11, 21]` ve `[12, 22]` (İkili gruplar sıralanır)
   - `[11, 16, 21]` ve `[8, 12, 22]` (Üçlü gruplar oluşur)
   - **[8, 11, 12, 16, 21, 22]** (Son birleşme)

## 2. Big-O Gösterimi
Merge Sort her durumda (Best, Average, Worst) aynı performansı gösterir:
**Time Complexity:** $O(n \log n)$
