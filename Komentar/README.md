# Komentar

## Komentar adalah catatan kita teradap sebuah bagian kode. maka anda bisa menggunakan bahasa apa pun di dalam komentar mulai dari Bahasa Inggris, Indonesia, Daerah, bahasa yang bisa di mengerti oleh pembacanya

Komentar ini penting agar kita bisa mengetahui fungsi dari sebuah bagian kode tanpa membaca kodenya. Komentar biasdanya diselipkan di dekat kode yang ingin kiya beri tanda //. Jika komentar berlebih dari satu baris maka komentar harus di awali tanda /* dan di akhiri dengan tanda */

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
