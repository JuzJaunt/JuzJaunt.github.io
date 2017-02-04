<!DOCTYPE html>
<html lang="en">

<head>

  <title>{{site.title}}</title>
  
  <meta charset="utf-8">
  <meta name="description" content="{{site.description}}">
  <meta name="author" content="{{site.author.name}}">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <link rel="icon" 
        type="image/png" 
        href="/images/logo.png">
        
  <!-- jQuery library -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
  
  <!-- fonts -->
  <link href="https://fonts.googleapis.com/css?family=Oswald|Audiowide" rel="stylesheet">
  
  <!-- material design -->
  <link rel="stylesheet" href="https://code.getmdl.io/1.3.0/material.deep_orange-light_green.min.css" />
  <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
  <link rel="stylesheet" href="https://code.getmdl.io/1.3.0/material.indigo-pink.min.css">
  <script defer src="https://code.getmdl.io/1.3.0/material.min.js"></script>
  
  <!-- bootstrapcdn -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  
</head>

<body>
  <div style="position: fixed;
              height: 100%;
              width: 100%;
              max-width: none;
              background: url({{page.bgurl}}) center center no-repeat #666666;
              background-size: cover;">
  
  {{content}}
  </div>
</body>

</html>