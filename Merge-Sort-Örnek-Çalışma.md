# Merge Sort Proje

### [ 16, 21, 11, 8, 12, 22 ]

 ***Yukarıda verilen dizinin Merge Sort'a göre aşamalarını yazınız.***

* Diziyi ikiye bölüyoruz

[ 16, 21, 11 ] | [ 8, 12, 22 ]

* Oluşan dizileride ikiye bölüyoruz

[ 16, 21 ] | [ 11 ]  | [ 8 ] | [ 12, 22 ]

* Oluşan dizileri tekrar ikiye bölüyoruz

[ 16 ] | [ 21 ] | [ 11 ] | [ 8 ] | [ 12 ] | [ 22 ]

* İkilileri sıralayarak birleştiriyoruz

[ 16, 21 ] | [ 11 ] | [ 8 ] | [ 12, 22 ]

* İkilileri sıralayarak birleştiriyoruz

[ 11, 16, 21 ] | [ 8, 12, 22 ]

* Dizi son haline geliyor

[ 8, 11, 12, 16, 21, 22 ]

***Yukarıda verilen dizinin Big-O gösterimini yazınız.***

Her aşamada sorguladığımız eleman sayısı yarı yarıya düşmektedir ve bu durum ***n*** adım boyunca tekrarlanmaktadır. Buradan yola çıkarak 2^x = logn tek bir adımın karmaşıklığı olarak hesaplanabilir. Elimizde ***n*** tane adım olduğu için Big-O gösterimi O(nlogn) şeklinde hesaplanır.

