# Prueba-Sumset
<html>

<head>
 <script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
    <script type="text/javascript">
      google.charts.load('current', {'packages':['corechart']});
      google.charts.setOnLoadCallback(drawChart);

      function drawChart() {

        var data = google.visualization.arrayToDataTable([
          ['Task', 'Hours per Day'],
          ['Work',     11],
          ['Eat',      2],
          ['Commute',  2],
          ['Watch TV', 2],
          ['Sleep',    7]
        ]);

        var options = {
          title: 'My Daily Activities'
        };

        var chart = new google.visualization.PieChart(document.getElementById('piechart'));

        chart.draw(data, options);
      }
    </script>

</head>

<body>
<h6> JAZNEIDY VARGAS SILVA</h6>
<h6> HOBBIES</h6>
<p> Hola, los hobbies que tengo es mirar series, me gusta mucho ver series y peliculas (GAME OF THRONES,DC COMICS Y MARVEL)
 me gusta hacer ejercicio, por lo que voy al GYM y hacer recetas de cocina </p>
 
 <div id="piechart" style="width: 900px; height: 500px;"></div>


</body>

</html>
