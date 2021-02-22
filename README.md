# Praktikum-Alpro-2
LAB-3-STRUKTUR KONTROL dan MODULAR PROGRAMING
#NAMA : TRI HADIONO
#NIM : 71200536
#GROUP : D
#UNIVERSITAS KRISTEN DUTA WACANA
#REFERENSI : MODUL

nama= input("Nama Siswa: ")
nilai= int(input("Nilai: "))

if nilai>80:
    print("Note: LULUS, Harus dipertahankan.")
elif nilai >=70:
    print("Note: LULUS, Harus ditingkatkan lagi.")
else:
    print("REMIDI, Mengulang lagi minggu depan.")

