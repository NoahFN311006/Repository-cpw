<h1>Construção de Página Web(CPW)</h1>

<p> Relatório dos códigos da Cadeira CPW da graduação em Sistemas Para internet. Graduação no Instituto Federal do RS, lecionada pelo professor: Evantro Miletto </p>


<p>Como me encontra</p>
<ul>
  <li>Github:https://github.com/NoahFN311006</li>
</ul>




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

</head>
<body>
    <form action="">
        <input type="text" id="Inome">
        <input type="submit" value="mOSTRAR">
        <input type="number" name="invalor" id="">
     </form>
     <h3></h3>
  <script>
   const frm = document.querySelector("form")
   const resp = document.querySelector("h1")
   frm.addEventListener("submit"), (e) => {
    const nome = frm.inNome.value 
    resp.innerText = 'Olá $(nome) '
    e.preventDefault()
   }
  </script>
</body>
</html>
