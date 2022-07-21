# aula-curso-Guanabara-desafio-
Desafio que eu fiz sozinho do curso do Guanabara em JavaScript

```

<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>aula 008 curso do Guanabara</title>
</head>

<body>
  
 
    <h1>
      vamos olhar uma condição 
    </h1>
    <div id="boto">
      
    
    <input type="text" name="n1" id="n1" placeholder="Digite o seu nome">
    <input type="number" name="n2" id="n2" placeholder="Digite a sua idade">
    <input type="button" value="olha" id="but">
    </div>
      

    
    
 
  
  <script>
  var boto = window.document.getElementById("but")
  
  
  boto.addEventListener("click",condição)
  
  function condição (){
    var n1 = window.document.getElementById("n1")
    var n2 = window.document.getElementById("n2")
    var s1 = Number(n2.value)
     
     // só pode se cadastrar usuários com o Valor abaixo de 40
    if (s1 >= 40){
      
      alert("você é muito VELHO já , não pode se cadastrar ")
    }
    
   else {
     alert ("cadastrado no meu banco de dados do MySQL com integração do Phpmyadmin ")
   }
    
  }
    
    
   
  </script>

</body>

</html>
```
