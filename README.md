<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Cadastro</title>
</head>
<body>
  
  <div>
    <h1>Cadastro De DEVs</h1>
    <p>Complete as suas informações</p>
    <br>
  </div> 

<form>
    <fieldset>
        <div>
            <label>Nome</label>
            <input type="text" name="nome" id="nome">
        </div>

    <div>
        <label>Sobrenome</label>
        <input type="text" name="Sobrenome" id="Sobrenome">
    </div>
    </fieldset>

    <div>
        <label>Email</label>
        <input type="email" name="email" id="email">
    </div>
</form>

<div>
    <label>De Qual lado da aplicação você desenvolve</label>
    <br>
    <label>
        <input type="radio" name="devweb" value="Front-End" checked>Front-End
    </label>
</div>
<br>
    <label>
    <input type="radio" name="devweb" value="Back-End">Back-End
    </label>
<br>
<br>
<label>
    <input type="radio" name="Devweb" value="Full-stack">Full-stack
</label>
<br>
</form>
<div>
<br>
<div>
<label>Senioridade</label>
<select id="Senioridade">
    <option selected disabled value="">Escolha</option>
    <option>Junior</option>
    <option>Pleno</option>
    <option>Sênior</option>
<select>
</div>

<fieldset>
    <div>
        <label>Selecione as tecnologias que utiliza:</label><br><br>
        <input type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
        <label for="tecnologia1">HTML</label>
        <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
        <label for="tecnologia2">CSS</label>
        <input type="checkbox" id="tecnologia3" name="tecnologia3" value="Javascript">
        <label for="tecnologia3">Javascript</label>
        <input type="checkbox" id="tecnologia4" name="tecnologia4" value="PHP">
        <label for="tecnologia4">PHP</label>
        <input type="checkbox" id="tecnologia5" name="tecnologia5" value="C#">
        <label for="tecnologia5">C#</label>
        <input type="checkbox" id="tecnologia6" name="tecnologia6" value="python">
        <label for="tecnologia6">python</label>
        <input type="checkbox" id="tecnologia7" name="tecnologia7" value="Java">
        <label for="tecnologia7">Java</label>
    </div>
</fieldset>

<div>
    <br>
    <label>Conte um pouco da sua experiencia</label>
    <textarea row="6" style="width:26em" id="experiencia" name="experiencia"></textarea>
</div>

<button type="submit">Concluido Com Sucesso!</button>


<form>
</body>
</html>
