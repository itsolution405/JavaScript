# Variabel

## Variable adalah tempat menyimpan data. Variable diperlukan karena data bisa berubah-ubah

membuat variabel gunakan kata kunci var, pengisian nilai pada sebuah variabel menggunakan tanda "=".

## Contoh seperti pada variabel berikut ini

```
<!DOCTYPE html>
<html>

<body>
    <script type="text/javascript">
        var nm = 0; // nm adalah variabel untuk menyimpannama
        var i = 0;
        /* i adalah index array.
                    index ibaratnya nomor gerbong kereta */
        var bil,
            bil2,
            bilMax = 0;
        bil1 = 3;
        bil2 = 4;

        // Max2 berfungsi mencari maximum dari 2 bilangan
        function max2(bil1, bil2) {
            if (bil1 > bil2) {
                return bil1;
            } else {
                return bil2;
            }
        }

        bilmax = max2(bil1, bil2);
        document.write(bilmax);
    </script>
</body>

</html>
```

Tampilan yang dihasilkan :

![button](https://github.com/itsolution405/JavaScript/blob/main/Variabel.png)

```
<!DOCTYPE html>
<html>

<body>
    <script type="text/javascript">
        var Nama = "Febriany"; // Deklarasi sekaligus pengisian
        var Perusahaan; // Deklarasi saja

        Perusahaan = "Educative Games"; // Pengisian saja
        document.write(nama);
        document.write(Perusahaan);
    </script>
</body>

</html>
```
