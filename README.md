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
          ['IE6 ',   5],
          ['IE7 ',  20],
          ['IE8 ',  75]
          ]);
        var options = {
        title: ' Datos Pie Chart:'
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
 

<script>
       
      <div id="piechart" style="width: 900px; height: 500px;"></div> 
      <input type="button" value="Cambiar" onclick ="click">

        var cambiarValores = function ()
           {
        var data = google.visualization.arrayToDataTable([
          ['Task', 'Hours per Day'],
          ['IE6 ',     50],
          ['IE7 ',      40],
          ['IE8 ',  10]
          ]);
          var click=new google.visualization.PieChart(document.get.ElementById(cambiarValores).value);   
      }
 
</script>
</body>

</html>
