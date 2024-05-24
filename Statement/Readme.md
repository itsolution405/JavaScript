# Statement

```
<!DOCTYPE html>
<html>
<body>
    <script type="text/javascript">
        KODE JAVASCRIPT DISINI
    </script>
</body>
</html>
```

## Sebuah statement/perintah Javascript biasanya diakhiri dengan semicolon/titik koma

### Contoh: bukalah notepad++ kemudian tuliskan kode-kode berikut

```
<!DOCTYPE html>
<html>

<body>
    <script type="text/javascript">
        document.write("Hello World");
    </script>
</body>

</html>
```

### Simpan dengan nama hello.html

Tampilan yang dihasilkan :

![button](https://github.com/itsolution405/JavaScript/blob/main/Statement/Statement.png)

### Untuk string yang terlalu panjang Anda bisa memisahka nya menjadi baris menggunakan backlash seperti (pemimpin.html)

```
<!DOCTYPE html>
<html>

<body>
    <script type="text/javascript">
        document.write("Pemimpin yang baik adalah pelayan \ masyarakat");
    </script>
</body>

</html>
```

### tetapi Anda tidak bisa memisaahkan kode dengan cara seperti ini

```
<!DOCTYPE html>
<html>

<body>
    <script type="text/javascript">
        document.write \ ("Pemimpin yang baik adalah pelayan masyarakat");
    </script>
</body>

</html>
```

```
<script type="text/javascript">
    var visitor = "user";
    if (visitor == "admin") {
        document.write("Selamat datang Admin");
    } else if (visitor == "user") {
        document.write("selamat datang user");
    } else {
        document.write("Anda di larang mengakses halaman ini");
    }
</script>
```
