def faktoriyel(sayı):             # Burada faktoriyel hesaplamak için bir fonksiyon tanımlıyoruz.
    faktoriyel = 1
    if (sayı == 0 or sayı ==1):  
        return 1
    else:
        while (sayı >=1):
            faktoriyel *= sayı
            sayı -= 1
        return faktoriyel

# Fonksiyonu tanımladıktan sonra, kullancııdan sayı isteyip fonksiyonu çalıştırabilirim.

sayıgir = int(input("Faktöriyelini hesaplamak istediğiniz sayıyı giriniz:"))
print(faktoriyel(sayıgir))
