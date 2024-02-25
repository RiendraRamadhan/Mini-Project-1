class Kanvas:
    def __init__(self, nama, jumlah, warna, ukuran, harga):
        self.nama = nama
        self.jumlah = jumlah
        self.warna = warna
        self.ukuran = ukuran
        self.harga = harga

    def __str__(self):
        return f"Nama: {self.nama}, Jumlah: {self.jumlah}, Warna: {self.warna}, Ukuran: {self.ukuran}, Harga: {self.harga}"


class Cat:
    def __init__(self, nama, jumlah, warna, jenis, harga):
        self.nama = nama
        self.jumlah = jumlah
        self.warna = warna
        self.jenis = jenis
        self.harga = harga

    def __str__(self):
        return f"Nama: {self.nama}, Jumlah: {self.jumlah}, Warna: {self.warna}, Jenis: {self.jenis}, Harga: {self.harga}"


class Kuas:
    def __init__(self, nama, jumlah, jenis, ukuran, harga):
        self.nama = nama
        self.jumlah = jumlah
        self.jenis = jenis
        self.ukuran = ukuran
        self.harga = harga

    def __str__(self):
        return f"Nama: {self.nama}, Jumlah: {self.jumlah}, Jenis: {self.jenis}, Ukuran: {self.ukuran}, Harga: {self.harga}"

class Dudukan_Kanvas:
    def __init__(self, nama, jumlah, bahan, ukuran, harga):
        self.nama = nama
        self.jumlah = jumlah
        self.bahan = bahan
        self.ukuran = ukuran
        self.harga = harga

    def __str__(self):
        return f"Nama: {self.nama}, Jumlah: {self.jumlah}, Bahan: {self.bahan}, Ukuran: {self.ukuran}, Harga: {self.harga}"

class Palet:
    def __init__(self, nama, jumlah, warna, bahan, ukuran, harga):
        self.nama = nama
        self.jumlah = jumlah
        self.warna = warna
        self.bahan = bahan
        self.ukuran = ukuran
        self.harga = harga

    def __str__(self):
        return f"Nama: {self.nama}, Jumlah: {self.jumlah}, Warna: {self.warna}, Bahan: {self.bahan}, Ukuran: {self.ukuran}, Harga: {self.harga}"

class Koper:
    def __init__(self, nama, jumlah, warna, bahan, ukuran, harga):
        self.nama = nama
        self.jumlah = jumlah
        self.warna = warna
        self.bahan = bahan
        self.ukuran = ukuran
        self.harga = harga

    def __str__(self):
        return f"Nama: {self.nama}, Jumlah: {self.jumlah}, Warna: {self.warna}, Bahan: {self.bahan}, Ukuran: {self.ukuran}, Harga: {self.harga}"

class ManajemenInventaris:
    def __init__(self):
        self.inventaris = []

    def tambah_item(self, item):
        self.inventaris.append(item)
        print("Item berhasil ditambahkan.")

    def tampilkan_inventaris(self):
        if self.inventaris:
            print("Inventaris Saat Ini:")
            for item in self.inventaris:
                print(item)
        else:
            print("Inventaris kosong.")

    def perbarui_item(self, nama_item, jumlah_baru):
        for item in self.inventaris:
            if item.nama == nama_item:
                item.jumlah = jumlah_baru
                print("Item berhasil diperbarui.")
                return
        print("Item tidak ditemukan dalam inventaris.")

    def hapus_item(self, nama_item):
        for item in self.inventaris:
            if item.nama == nama_item:
                self.inventaris.remove(item)
                print("Item berhasil dihapus.")
                return
        print("Item tidak ditemukan dalam inventaris.")


def main():
    manajemen_inventaris = ManajemenInventaris()

    while True:
        print("\nSistem Manajemen Inventaris")
        print("1. Tambah Kanvas")
        print("2. Tambah Cat")
        print("3. Tambah Kuas")
        print("4. Tambah Dudukan Kanvas")
        print("5. Tambah Palet")
        print("6. Tambah Koper")
        print("7. Tampilkan Inventaris")
        print("8. Perbarui Jumlah Item")
        print("9. Hapus Item")
        print("0. Keluar")

        pilihan = input("Masukkan pilihan Anda: ")

        if pilihan == '1':
            nama = input("Masukkan nama kanvas: ")
            jumlah = int(input("Masukkan jumlah kanvas: "))
            warna = input("Masukkan warna kanvas: ")
            ukuran = input("Masukkan ukuran kanvas: ")
            harga = float(input("Masukkan harga kanvas: "))
            item = Kanvas(nama, jumlah, warna, ukuran, harga)
            manajemen_inventaris.tambah_item(item)
        elif pilihan == '2':
            nama = input("Masukkan nama cat: ")
            jumlah = int(input("Masukkan jumlah cat: "))
            warna = input("Masukkan warna cat: ")
            jenis = input("Masukkan jenis cat: ")
            harga = float(input("Masukkan harga cat: "))
            item = Cat(nama, jumlah, warna, jenis, harga)
            manajemen_inventaris.tambah_item(item)
        elif pilihan == '3':
            nama = input("Masukkan nama kuas: ")
            jumlah = int(input("Masukkan jumlah kuas: "))
            warna = input("Masukkan jenis kuas: ")
            ukuran = input("Masukkan ukuran kuas: ")
            harga = float(input("Masukkan harga kuas: "))
            item = Kuas(nama, jumlah, jenis, ukuran, harga)
            manajemen_inventaris.tambah_item(item)
        elif pilihan == '4':
            nama = input("Masukkan nama Dudukan Kanvas: ")
            jumlah = int(input("Masukkan jumlah Dudukan Kanvas: "))
            bahan = input("Masukkan bahan Dudukan Kanvas: ")
            ukuran = input("Masukkan ukuran Dudukan Kanvas: ")
            harga = float(input("Masukkan harga Dudukan Kanvas: "))
            item = Dudukan_Kanvas(nama, jumlah, bahan, ukuran, harga)
            manajemen_inventaris.tambah_item(item)
        elif pilihan == '5':
            nama = input("Masukkan nama Palet: ")
            jumlah = int(input("Masukkan jumlah Palet: "))
            warna = input("Masukkan warna Palet: ")
            bahan = input("Masukkan bahan Palet: ")
            ukuran = input("Masukkan ukuran Palet: ")
            harga = float(input("Masukkan harga Palet: "))
            item = Palet(nama, jumlah, warna, bahan, ukuran, harga)
            manajemen_inventaris.tambah_item(item)
        elif pilihan == '6':
            nama = input("Masukkan nama Koper: ")
            jumlah = int(input("Masukkan jumlah Koper: "))
            warna = input("Masukkan warna Koper: ")
            bahan = input("Masukkan bahan Koper: ")
            ukuran = input("Masukkan ukuran Koper: ")
            harga = float(input("Masukkan harga Koper: "))
            item = Koper(nama, jumlah, warna, bahan, ukuran, harga)
            manajemen_inventaris.tambah_item(item)
        elif pilihan == '7':
            manajemen_inventaris.tampilkan_inventaris()
        elif pilihan == '8':
            nama = input("Masukkan nama item untuk memperbarui jumlah: ")
            jumlah = int(input("Masukkan jumlah baru: "))
            manajemen_inventaris.perbarui_item(nama, jumlah)
        elif pilihan == '9':
            nama = input("Masukkan nama item untuk dihapus: ")
            manajemen_inventaris.hapus_item(nama)
        elif pilihan == '0':
            print("Keluar dari program.")
            break
        else:
            print("Pilihan tidak valid. Silakan masukkan opsi yang benar.")


if __name__ == "__main__":
    main()
