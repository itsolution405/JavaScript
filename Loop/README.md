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

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>arrMobilWhile</title>
</head>

<body>
    <script type="text/Javascript">
        arrMobil = ["Toyota", "Suzuki", "Daihatsu", "Mazda"] var i=0; while(arrMobil[i]) { document.write(arrMobil[i] + "<br>"); i++ }
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
    <title>Break</title>
</head>

<body>
    <script type="text/javascript">
        var i = 1;
        for (i = 1; i <= 10; i++) {
            if (i == 5) {
                alert("Pembagian dengan 0");
                break;
            }
            document.write(1 / (i - 5) + "<br>");
        }
    </script>
</body>

</html>
```
Tampilan yang dihasilkan :

![button](https://github.com/itsolution405/JavaScript/blob/main/Loop/pembagian%200.png)


![button](https://github.com/itsolution405/JavaScript/blob/main/Loop/hasil.png)

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Continue</title>
</head>

<body>
    <script type="text/javascript">
        var i = 1;
        var i = 1;
        while (i <= 10) {
            if (i == 5) {
                alert("Pembagian dengan 0");
                i++;
                continue;
            }
            document.write(1 / (i - 5) + "<br>");
        }
    </script>
</body>

</html>
```

```
< script LANGUAGE = "Javascript"
src = "js/notempty.js" > < /script > < form >
Required Fleid: < input type = 'text'
id = 'req1' / >
    <
    input type = "button"
oneclick = "notEmpty (document.getElementbyId ('req'), 'Flease Enter a Value')"
value = 'check Field' / >
    </form>
```

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <a href="notempty.js"></a>
    <title>notempty</title>
</head>

<body>
    <script language="javascript" src="js/notempty.js"></script>
    <form>
        Required Field: <input type="text" id="req1" />
        <input type="button" oneclick="notEmpty (document.getelementById('req1'), 'Please enter value')" value="Check Field" />
    </form>
</body>

</html>
```
![button] (https://github.com/itsolution405/JavaScript/blob/main/Loop/Screen%20Shot%202024-05-30%20at%2017.36.02.png)
