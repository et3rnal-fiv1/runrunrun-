import math

def gizli_hesaplama():
    # Gizlenmiş koordinatları türetmek için matematiksel işlemler kullanıyoruz
    x = math.sqrt(1379.806049)  # 37.159613 türetiliyor
    y = (310.33532 / 8.0) + 0.791915  # 38.791915 türetiliyor
    return round(x, 6), round(y, 6)

def main():
    lat, lon = gizli_hesaplama()
    print(f"Konum Bilgisi: {lat}, {lon}")

if __name__ == "__main__":
    main()
