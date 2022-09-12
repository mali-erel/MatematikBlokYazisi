# MatematikBlokYazisi
Patika.dev Temel Matematik dersi için  3x3 Matrix Determinant belirlemeye dair blok yazısı.

# Matrix determinant nasıl hesaplanır?

Örnek Matrix : 

M = (1 5 3)
    (2 4 7)
    (4 6 2)  

## 1. Aşama:
İlk satırı 1. referans noktası kabul edelim: 1 5 3.

## 2. Aşama:
1. referansın ilk değerine ait stunu seçin: 1 2 4

## 3. Aşama:
Seçtiğimiz 1. stun ve 1. satırın üzerini çizdiğimizde arada kalan 4 değeri çaprazlayarak çarpın ve birbirinden çıkartın. (4 7) 
                                (6 2) --> 4x2 - 7x6 = -34
## 4. Aşama:
Bulduğumuz değeri seçtiğimiz satırın ve stunun kesiştiği yerde bulunan değerle çarpın.
-34*1 = -34

## 5. Aşama:
Aynı işlemleri 1. satırın her stunu için uygulayıp toplayın.
2. 2x2-7x4 = -22 --> -22x(-5) = 120
3. 2x6-4x4 = -4 --> -4x(3) = -12

## 6. Aşama:
Elde ettiğimiz 3 değeri toplayınca bu 3x3 matrixin determinantını bulmuş oluyoruz.
-34 + 120 + (-12) = 74
