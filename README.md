# Merge-Sort-Projesi
www.patika.dev
# [16,21,11,8,12,22]
- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
# Sort Adımları
- İlk Adım         >         16   21   11   8   12   22
- İkinci Adım      >         16 ,21,11  -------    8,12,22   
- Üçüncü Adım      >         16 -- 21,11 -------    8,12 -- 22
- Dördüncü Adım    >         16 -- 11 -- 21 -------   8 -- 12 -- 22
- Beşinci Adım     >         16 -- 11,21 -------   8,12 -- 22
- Altıncı Adım     >         11,16,21 -------      8,12,22
- Son Adım         >         8,11,12,16,21,22
# BigO Gösterimi
- O(nlog(n))' dir.
