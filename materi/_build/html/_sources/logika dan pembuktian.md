---
title: logika dan pembuktian

---

# Logika Matematika

## Negasi
 Dalam matematika diskrit, negasi dapat dijelaskan sebagai proses menentukan kebalikan dari pernyataan matematika yang diberikan. Misalkan pernyataan yang diberikan adalah ''Saya tidak suka kucing'' maka negasi dari pernyataan ini adalah ''Saya suka kucing''.
 
|p     | ¬p   |
|----- | -----|
|T     |  F   |
|F     |  T   |

https://www.javatpoint.com/negation-in-discrete-mathematics

## Konjungsi
 Konjungsi adalah suatu pernyataan p dan q dapat digabungkan dengan menggunakan kata hubung 'dan' sehingga membentuk pernyataan majemuk 'p dan q' yang disebut konjungsi yang dilambangkan dengan "p∧q".
 
|p |q | p ∧ q|
|--|--|------|
|T |T |T     |
|T |F |F     |
|F |T |F     |
|F |F |F     |

## Disjungsi
 Disjungsi adalah suatu pernyataan p dan q dapat digabungkan dengan menggunakan kata hubung 'atau' sehingga membentuk pernyataan majemuk 'p atau q' yang disebut disjungsi yang dilambangkan dengan "p∨q". 
 
|p | q|p∨q  |
|--|--|-----|
|T | T|T    |
|T | F|T    |
|F | T|T    |
|F | F|F    |

## Implikasi
 Implikasi adalah hubungan antara dua pernyataan dimana pernyataan kedua merupakan konsekuensi logis dari pernyataan pertama. Implikasi ditandai dengan notasi ''. Misalkan p,q adalah pernyataan, implikasi berikut:
 
 ' p → q'
 
 dibaca 'jika p maka q'. 
 
|p |q | p → q|
|--|--|------|
|T |T | T    | 
|T |F | F    |
|F |T | T    |
|F |F | T    | 

dari tabel diatas dapat disimpulkan dalam konsep implikasi bernilai salah jika dan hanya jika sebab bernilai benar namunnakibat bernilai salah.

contoh pernyataan 'jika budi sembuh maka budi akan sekolah'
 
 

## Biimplikasi
 Biimplikasi adalah suatu pernyataan p dan q dapat digabungkan dengan menggunakan kata hubung 'jika dan hanya jika' sehingga membentuk pernyataan majemuk 'p jika dan hanya jika p' yang disebut biimplikasi yang dilambangkan dengan "p ↔ q".
 
|p |q | p ↔ q|
|--|--|------|
|T |T | T    |
|T |F | F    |
|F |T | F    |
|F |F | T    |

dari tabel diatas dapat disimpulkan konsep biimplikasi akan bernilai benar jika sebab dan akibatnya (pernyataan p dan q) bernilai sama.

contoh pernyataan 'Ayah mendapatkan gaji jika dan hanya jika ayah bekerja'.

https://www.zenius.net/blog/memahami-logika-matematika-dengan-mudah



Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{-}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{-}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{-}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{-}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{-}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{-}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{-}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{-}&\text{T}&\text{T}&\text{}\end{array}$$