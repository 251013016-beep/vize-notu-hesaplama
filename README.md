# vize-notu-hesaplama
vize = int(input("Vize notunu giriniz: "))
final = int(input("Final notunu giriniz: "))

ortalama = (vize * 0.4) + (final * 0.6)

print("Ders ortalamanız:", ortalama)

if ortalama >= 50:
    print("Dersten geçtiniz")
else:
    print("Dersten kaldınız")
