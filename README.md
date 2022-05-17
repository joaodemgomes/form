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

CSS



body {
  background: linear-gradient(
    90deg,
    rgba(255, 165, 0, 1) 0%,
    rgba(255, 255, 255, 1) 50%,
    rgba(255, 165, 0, 1) 100%
  );
}

h1 {
  text-align: center;
  font-size: 60px;
  color: orange;
  text-shadow: 1px 1px 1px black;
}

hr {
  width: 600px;
  height: 10px;
  background: orange;
}

.formulario {
  border: 5px solid orange;
  background: rgb(238, 238, 194);
  width: 600px;
  padding: 40px;
  margin: 40px auto;
}

label {
  font-size: 20px;
  font-weight: 600;
}

input,
select {
  font-size: 18px;
}

input:focus {
  background: rgb(230, 194, 128);
}

input:focus,
select:focus {
  background: rgb(230, 194, 128);
}

input[type="radio"] fieldset p {
  font-size: 20px;
  font-weight: 600;
}

#submit {
  width: 100%;
  padding: 10px;
  border-radius: 10px;
  border: none;
  background: orange;
  cursor: pointer;
  font-size: 20px;
  font-weight: 600;
  transition: 0.5s;
}

#submit:hover {
  background: black;
  color: rgb(230, 194, 128);
}

#animation {
  width: 20%;
  position: absolute;
  top: 5px;
  left: 5px;
}
