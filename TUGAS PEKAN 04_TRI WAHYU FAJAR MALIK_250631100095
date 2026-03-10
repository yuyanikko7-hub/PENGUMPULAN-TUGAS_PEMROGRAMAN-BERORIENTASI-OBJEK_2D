// Class utama
public class Mahasiswa {

    // Atribut dengan modifier private
    private String nama;
    private int umur;
    private String jurusan;

    // Constructor tanpa parameter
    public Mahasiswa() {
        this.nama = "Tidak diketahui";
        this.umur = 0;
        this.jurusan = "Belum ada";
    }

    // Constructor dengan parameter
    public Mahasiswa(String nama, int umur, String jurusan) {
        this.nama = nama;       // penggunaan keyword this
        this.umur = umur;
        this.jurusan = jurusan;
    }

    // Method dengan modifier public
    public void tampilkanData() {
        System.out.println("Nama    : " + nama);
        System.out.println("Umur    : " + umur);
        System.out.println("Jurusan : " + jurusan);
        System.out.println();
    }

    // Main class untuk menjalankan program
    public static void main(String[] args) {

        // Objek menggunakan constructor tanpa parameter
        Mahasiswa mhs1 = new Mahasiswa();

        // Objek menggunakan constructor dengan parameter
        Mahasiswa mhs2 = new Mahasiswa("Tri wahyu", 26, "Informatika");

        // Menampilkan data
        mhs1.tampilkanData();
        mhs2.tampilkanData();
    }
}
