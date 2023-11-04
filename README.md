# NO 1
1. Inisialisasi variable "name" dengan string "Ricardo Gellael"

       String name = "Ricardo Gellael";
2. Mencetak nama dengan menggunakan System.out.println

        System.out.println("Nama : " + name);
4. Mencetak "=====" sebagai garis pemisah antara nama dan angka yang akan di cetak selanjutnya

         System.out.println("=================");

5. Melakukan perulangan for dari 0 sampai 100

         for (int i = 0 ; i<=100 ; i++){
7. Jika nilai variabel "i" lebih besar atau sama dengan 10, maka akan mencetak nama. Jika tidak, akan melanjutkan ke langkah selanjutnya

         if (i>= 10 ){
                System.out.println(name);

8. Jika nilai variabel "i" kurang dari 10, maka akan mencetak nilai variabel "i" sebagai angka yang akan di cetak.

          else{
                System.out.println(i);
            }
# NO 2
1. Buat variabel bernama count dengan tipe data int dan isikan dengan angka 1

          int count = 1;

2. Gunakan perulangan while untuk melakukan operasi sampai nilai count mencapai angka 10
 
        while (count <= 10) {
3. Dalam operasi yang akan diulang, cek apakah nilai count bernilai genap atau ganjil menggunakan operator modulo (%)

         if (count % 2 == 0) {
4. Jika count bernilai genap, cetak pesan " even " dan hitungan angka

         System.out.println(count + " is an even number.");

5. Jika count bernilai ganjil, cetak pesan " odd " dan hitungan angka

          System.out.println(count + " is an odd number.");

# NO 3
1. Import class yang diperlukan. Dalam kasus ini, kita perlu import Scanner untuk membaca input pengguna.
 
       import java.util.Scanner;
2. Buat kelas ProgramZodiak dengan method main yang didefinisikan dalam class tersebut.

       public class ProgramZodiak {
3. Buat object Scanner dan minta input pengguna untuk tanggal lahir dalam format "dd-mm-yyyy".

        System.out.println("Masukkan tanggal lahir Anda (dd-mm-yyyy): ");
4. Extrak bagian tanggal, bulan, dan tahun dari input yang diberikan oleh pengguna.

         String[] dateParts = scanner.nextLine().split("-");
        int day = Integer.parseInt(dateParts[0]);
        int month = Integer.parseInt(dateParts[1]);

5. Gunakan beberapa blok kondisi if-else untuk menentukan zodiak yang sesuai berdasarkan tanggal lahir yang diberikan oleh pengguna.

        if ((month == 1 && day >= 20) || (month == 2 && day <= 18)) {
            zodiacSign = "Aquarius";
        } else if ((month == 2 && day >= 19) || (month == 3 && day <= 20)) {
            zodiacSign = "Pisces";
        } else if ((month == 3 && day >= 21) || (month == 4 && day <= 19)) {
            zodiacSign = "Aries";
        } else if ((month == 4 && day >= 20) || (month == 5 && day <= 20)) {
            zodiacSign = "Taurus";
        } else if ((month == 5 && day >= 21) || (month == 6 && day <= 20)) {
            zodiacSign = "Gemini";
        } else if ((month == 6 && day >= 21) || (month == 7 && day <= 22)) {
            zodiacSign = "Cancer";
        } else if ((month == 7 && day >= 23) || (month == 8 && day <= 22)) {
            zodiacSign = "Leo";
        } else if ((month == 8 && day >= 23) || (month == 9 && day <= 22)) {
            zodiacSign = "Virgo";
        } else if ((month == 9 && day >= 23) || (month == 10 && day <= 22)) {
            zodiacSign = "Libra";
        } else if ((month == 10 && day >= 23) || (month == 11 && day <= 21)) {
            zodiacSign = "Scorpio";
        } else if ((month == 11 && day >= 22) || (month == 12 && day <= 21)) {
            zodiacSign = "Sagittarius";
        } else {
            zodiacSign = "Capricorn";
        }
6. Jalankan program dan periksa hasilnya. Seharusnya melihat zodiak yang sesuai berdasarkan tanggal lahir yang diberikan. Jika tanggal lahir yang diberikan tidak sesuai dengan aturan zodiak, program akan 
   menampilkan "Unknown" sebagai hasilnya. Untuk menghilangkan bug ini, pastikan untuk memasukkan tanggal lahir dalam format yang benar (dd-mm-yyyy) dan pastikan untuk memasukkan tanggal yang valid. Selain itu, 
   jangan lupa untuk menggunakan beberapa blok kondisi if-else untuk menentukan zodiak yang sesuai berdasarkan tanggal lahir yang diberikan oleh pengguna.
   
# NO 4
1. Membuat sebuah variabel dengan tipe data array. Variabel ini akan menampung semua nilai yang ada dalam array. Dalam contoh ini, variabel tersebut adalah "array" dengan tipe data int. Nilai-nilai yang dimasukkan dalam array ini adalah 1, 2, 3, 4, dan 5.

         int[] array = {1, 2, 3, 4, 5};
2. Menggunakan perulangan for untuk menampilkan semua nilai dalam variabel array. Dalam bahasa pemrograman Java, perulangan for digunakan untuk mengeksekusi blok kode secara berulang dengan melakukan pengecekan kondisi. Pada contoh ini, perulangan for akan mengeksekusi blok kode selama variabel "i" lebih kecil dari jumlah nilai yang ada dalam array (array.length). Dalam setiap iterasi perulangan, variabel "i" akan bertambah nilainya sebanyak 1.

        for (int i = 0; i < array.length; i++) {
4. Dalam blok kode perulangan for, sistem akan menampilkan nilai yang ada pada indeks "i" dari array "array".

         System.out.println(array[i]);
5. Dengan demikian, aplikasi akan menampilkan nilai-nilai yang ada dalam array. Jika dijalankan, aplikasi akan menampilkan output berikut:


       1
       2
       3
       4
       5


   
