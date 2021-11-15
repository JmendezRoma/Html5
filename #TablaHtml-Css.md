<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Ejercicio12</title>
    <link href="capas.Css.css" rel="stylesheet" type="text/css"/>
</head>
<body>
    <div class="fondo">
    <table border=1>
        <tr id="color1">
            <td >9</td>
            <td>*</td>
            <td>1</td>
            <td>=</td>
            <td>9</td>
        </tr>
        <tr id="color2">
            <td>9</td>
            <td>*</td>
            <td>2</td>
            <td>=</td>
            <td>18</td>
        </tr>
        <tr id="color1">
            <td>9</td>
            <td>*</td>
            <td>3</td>
            <td>=</td>
            <td>21</td>
        </tr>
        <tr id="color2">
            <td>9</td>
            <td>*</td>
            <td>4</td>
            <td>=</td>
            <td>36</td>
        </tr>
        <tr id="color1">
            <td>9</td>
            <td>*</td>
            <td>5</td>
            <td>=</td>
            <td>45</td>
        </tr>
        <tr id="color2">
            <td>9</td>
            <td>*</td>
            <td>6</td>
            <td>=</td>
            <td>54</td>
        </tr>
        <tr id="color1">
            <td>9</td>
            <td>*</td>
            <td>7</td>
            <td>=</td>
            <td>63</td>
        </tr>
        <tr id="color2">
            <td>9</td>
            <td>*</td>
            <td>8</td>
            <td>=</td>
            <td>72</td>
        </tr>
        <tr id="color1">
            <td>9</td>
            <td>*</td>
            <td>9</td>
            <td>=</td>
            <td>81</td>
        </tr>
        <tr id="color2">
            <td>9</td>
            <td>*</td>
            <td>10</td>
            <td>=</td>
            <td>90</td>
        </tr>
    </table>
</div>
    
</body>
</html>

CSS//

@charset "UTF-8";

*{margin:10px;padding:3px;border:;box-sizing:border-box;}

#color1{
    background-color: lightsalmon;
    color:blue;
}

#color2{
    background-color: rgb(71, 217, 253);
    color:red;
}

table{
    border-collapse: collapse;
    border: solid 1px black ;
    width: 50%; <br>
    text-align:center ;<br>
    margin: 300px;<br>
    padding:150px;<br>
}

tr td:hover{<br>
    background-color:maroon; <br>
    border: solid 2px black; <br>
}
body {<br>
    background-color:black; <br>
}
.fondo{ <br>
    background-image: url("fondo.jpg");<br>
    width: 1000px;<br>
    height: 1000px;<br>
    background-repeat: no-repeat; <br>
    background-size: cover;<br>
    background-position: 100px;<br>
    background-attachment: scroll;<br>
}
