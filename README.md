# -klid-Hesalamas-
# Mesafe Hesaplaması için belirlenecek noktaları kartezyen sistemine uygun olarak Kullanıcıdan alma 
x1 = float(input("1. noktanın X koordinatını girin: ")) 
y1 = float(input("1. noktanın Y koordinatını girin: ")) 
x2 = float(input("2. noktanın X koordinatını girin: ")) 
y2 = float(input("2. noktanın Y koordinatını girin: ")) 
# Noktaları liste olarak tanımlama 
points = [(x1, y1), (x2, y2)] 
# İki nokta arasındaki mesafeyi hesaplama 
distance = ((x2 - x1) ** 2 + (y2 - y1) ** 2) ** 0.5 
# Sonucu yazdırma 
print("\n1. nokta:", points[0]) 
print("2. nokta:", points[1])
print("İki nokta arasındaki mesafe:", distance)
