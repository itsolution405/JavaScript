# For Loop

```
<html>

<head>
    <script type="text/Javascript">
        var arrkota = new Array ("JKT", "BDG", "SBY", "MDN");
        document.write(arrkota[0] + "<br>");
        document.write(arrkota[1] + "<br>");
        document.write(arrkota[2] + "<br>");
        document.write(arrkota[3] + "<br>");
    </script>
</head>

</html>
```
Tampilan yang dihasilkan :

![button](https://github.com/itsolution405/JavaScript/blob/main/Loop/Screen%20Shot%202024-05-25%20at%2014.32.23.png)

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>arrKotaFor</title>
</head>

<body>
    <script type="text/javascript">
        var arrkota = new Array("JKT", "BDG", "SBY", "MDN");
        for (var i = 0; i <= 3; i++) {
            document.write(arrkota[i] + "<br>");
        }
    </script>
</body>

</html>
```
Tampilan yang dihasilkan :

![button](https://github.com/itsolution405/JavaScript/blob/main/Loop/Screen%20Shot%202024-05-25%20at%2014.32.23.png)

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>arrMobilFor</title>
</head>

<body>
    <script type="text/javascript">
        arrMobil = ["Toyota", "Suzuki", "Daihatsu", "Mazda"];
        var i = 0;
        for (; arrMobil[i];) {
            document.write(arrMobil[i] + "<br>");
        }
    </script>
</body>

</html>
```

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>objMobilforln</title>
</head>

<body>
    <script type="text/javascript">
        var objMobil = {
            nama: "Suzuki Escudo",
            warna: "hijau"
        };
        for (var i in objMobil) {
            document.write(objMobil(i));
        }
    </script>
</body>

</html>
```

```
<html>

<head>
    <script type="text/Javascript">
        var i = 1; while (i
        <1000 ) { document.write(i + ".Saya tidak akan telat lagi <br>"); i++; } </script>
</head>

</html>
```

Tampilan yang dihasilkan :

![button](https://github.com/itsolution405/JavaScript/blob/main/Loop/Saya%20tidak%20akan%20telat.png)
