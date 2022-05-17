# form
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="css/estilos.css">
  <title>Document</title>
</head>

<body>

  <h1>Cadastro de Alunos</h1>
  <hr>
  <img src="imagem/social-distance-at-school-animate.svg" alt="" id="animation">

  <form action="https://formsubmit.co/joaopaulo.heitorgo@gmail.com" method="post" class="formulario">
    <label for="nome">Nome:</label>
    <input type="text" name="nome" id="nome" required>
    <br>
    <br>

    <Label for="email">E-mail:</Label>
    <input type="email" name="email" id="email" required>
    <br>
    <br>

    <label for="estado">Estado:</label>

    <select name="estado" id="estado" required>


      <option value="">Escolha Seu Estado</option>
      <option value="ap">Amapá</option>
      <option value="ba">Bahia</option>
      <option value="pe">Pernambuco</option>
      <option value="rj">Rio de Janeiro</option>

    </select>
    <br>
    <br>

    <fieldset>


      <p> Gênero:</p>
      <input type="radio" name="genero" id="" value="m">
      <label for="">M</label>
      <input type="radio" name="genero" id="" value="f">
      <label for="">F</label>
      <input type="radio" name="genero" id="" value="outros">
      <label for="">Outros</label>

    </fieldset>
    <br>
    <br>

    <label for="cidade">Cidade:</label>
    <input type="text" name="cidade" id="cidade" required>
    <br>
    <br>

    <label for="Telefone">Telefone:</label>
    <input type="tel" name="tel" id="telefone" required>
    <br>
    <br>

    <label for="datanasc">Data de Nascimento:</label>
    <input type="date" name="data nasc" id="datanasc" required>
    <br>
    <br>
    <br>

    <input type="submit" value="Enviar" id="submit" name="submit">
    <input type="hidden" name="_captcha" value="false">
    <input type="hidden" name="_next" value="http://127.0.0.1:5500/obrigado.html">
    <input type="hidden" name="_template" value="table">
    <br>
    <br>















  </form>






</body>

</html>
