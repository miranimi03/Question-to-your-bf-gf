<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Question</title>
</head>
<body>
  <h1 id="resultText"></h1>
  <script>
    
    let response = prompt("Do you love me? Type Yes or No");
    let outputText = "";
    
    if (response=="Yes"){
      outputText = " BJ ka saakin (BUKO JUICE) ";
    }else if(response=="No"){
      outputText = " edi wag ";
    }else{
      outputText = "please type Yes or No!!";
    }
    
    document.getElementById("resultText").innerHTML = outputText;
  </script>
</body>
</html>
