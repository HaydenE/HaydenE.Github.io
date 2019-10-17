<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Weather Analysis</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

  <link rel="stylesheet" href="style.css">
</head>

<div body style="background-color:lightgrey;">
    <div>
        <div class= "jumbotron">
            <h1>
                Climate Analysis
            </h1>
            <p>
                Climate change is a problem of the 21st Century that will affect humans around the globe. This project is one among a great many that documents correlations between temperature and other factors to give some insight into global climate variations. Please click the links below to find out more!
            </p>
            <div class="btn-group-vertical" role="group" aria-label="Visualization Buttons">
                <button type="button" onclick= "window.location.href='visualization_1.html'" class="btn btn-info">Latitude Versus Max Temperature</button>
                <button type="button" onclick= "window.location.href='visualization_2.html'" class="btn btn-info">Latitude Versus Humidity</button>
                <button type="button" onclick= "window.location.href='visualization_3.html'" class="btn btn-info">Latitude Versus Cloudiness</button>
                <button type="button" onclick= "window.location.href='visualization_4.html'" class="btn btn-info">Latitude Versus Wind Speed</button>
            </div>
        </div>

    </div>
</div>