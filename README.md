<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        label {
            display: block;
            margin-top: 10px;
           
            
        }
        fieldset{
            display: inline;
            margin-top: 10px;
            display: block;
            background-color: var(--botao-azul);
            border-radius: 5px;
            padding: 1em;
            color: var(--branco-principal);
            display: block;
            text-decoration: burlywood;
            margin-bottom: none;
            margin-left: none;
            width: 225px;
            

        }
        button{
            margin-top: 10px;
            display: inline;
            background-color: var(--botao-azul);
            border-radius: 5px;
            padding: 1em;
            color: var(--branco-principal);
            display: block;
            text-decoration: burlywood;
            margin-bottom: none;
             margin-left: none;
            width: 225px;
            color:brown
        }select{
            margin-top: 10px;
            display: inline;
            display: block;
            margin-top: 10px;
            margin-top: 10px;
            display: inline;
            background-color: var(--botao-azul);
            border-radius: 5px;
            padding: 1em;
            color: var(--branco-principal);
            display: block;
            text-decoration: burlywood;
            margin-bottom: none;
            margin-left: none;
            width: 225px;
            
        }input{
            margin-top: 10px;
            display: inline;
            display: block;
            margin-top: 10px;
            margin-top: 10px;
            display: inline;
            background-color: var(--botao-azul);
            border-radius: 5px;
            padding: 1em;
            color: var(--branco-principal);
            display: block;
            text-decoration: burlywood;
            margin-bottom: none;
            margin-left: none;
            width: 225px;
            
        }legend{
            margin-top: 10px;
            display: inline;
             display: block;
            margin-top: 10px;
            margin-top: 10px;
            display: inline;
            background-color: var(--botao-azul);
            border-radius: 5px;
            padding: 1em;
            color: var(--branco-principal);
            display: block;
            text-decoration: burlywood;
            margin-bottom: none;
            margin-left: none;
            width: 225px;

            
        }
    </style>
</head>
<body>
    <h2>Trikas Computers</h2>
    <h3>Cadastro de Usuário</h3>

    <form action="" id="user-form" name="user-form">

        <div>
            <label for="nome">Nome</label>
            <input type="text" name=""id="nome"
                placeholder="Digite seu Nome"
                maxlength="50">
        </div> 
        <div>
            <label for="Email">Email</label>
            <input type="Email@exemplo.com" id="email"
            maxlength="30" required
            placeholder="dígite seu Email">
        </div>
        <div>
            <label for="Celular">Telefone</label>
            <input type="(00)0000-0000" id="Celular"
            maxlength="14" required
            placeholder="dígite seu Telefone">
        </div>
        <div>
            <label for="Senha">Senha</label>
            <input type="password" id="senha"
            minlength="8" maxlength="20" required
            placeholder="dígite sua Senha">
        </div>
        <div>
            <label for="CorfimarSenha">ConfirmarSenha</label>
            <input type="password" id="ConfirmarSenha"
            minlength="8" maxlength="20" required
            placeholder="dígite sua Senha">
        </div>
       
            <fieldset>
  <legend>Quais linguagens você programa: </legend>

  <div>
    <input type="checkbox" id="Html" name="Html" checked label for="Html">Html</label>
  </div>

  <div>
    <input type="checkbox" id="CSS" name="CSS" label for="Notebook">CSS</label>
  </div>
  <div>
    <input type="checkbox" id="JS" name="JS" label for="JS">JS</label >
  </div>
  <div>
    <input type="checkbox" id="Phyton" name="Phyton" label for="Phyton">Phyton</label >
  </div>
  <div>
    <input type="checkbox" id="Php" name="Php" label for="Php">Php</label >
  </div>
</fieldset>
        </div>
        <div>
            <div>
                <div>Qual estado você vive: </div>
                
            <select name="select">
                <option value="valor1" selected >Acre</option>
                <option value="valor2">Alagoas</option>
                <option value="valor3">Amapá</option>
                <option value="valor4">Amazonas</option>
                <option value="valor5">Bahia</option>
                <option value="valor6">Ceará</option>
                <option value="valor7">Distrito Federal</option>
                <option value="valor8">Espírito Santo</option>
                <option value="valor9">Goiás</option>
                <option value="valor10">Maranhão</option>
                <option value="valor11">Mato Grosso</option>
                <option value="valor12">Mato Grosso do Sul</option>
                <option value="valor13">Minas Gerais</option>
                <option value="valor14">Pará</option>
                <option value="valor15">Paraíba</option>
                <option value="valor16">Paraná</option>
                <option value="valor17">Pernambuco</option>
                <option value="valor18">Piauí</option>
                <option value="valor19">Rio de Janeiro</option>
                <option value="valor20">Rio Grande do Norte</option>
                <option value="valor21">Rio Grande do Sul</option>
                <option value="valor22">Rondônia</option>
                <option value="valor23">Roraima</option>
                <option value="valor24">Santa Catarina</option>
                <option value="valor25">São Paulo</option>
                <option value="valor26">Sergipe </option>
                <option value="valor27">Tocantins</option>
              </select>
            </div>
        </div>
        <div>
        <label for="tentacles">Quantos anos de experiencia você possui na programação:</label>

<input type="number" id="tentacles" name="tentacles" min="1" max="100" />

        </div>
        <div>
            <div>
                Data de nascimento:
            </div>
        <div>
            
            <input id="date" type="date" value="2017-06-01" />
        </div>
        <button name="botao-enviar"type="button"
        onclick="enviarform()">
        enviar</button>
    
<div>
</div>

        <script>
            function enviarform(){
                let nome = document.getElementById('nome').value;
                let senha = document.getElementById('senha').value;
                let ConfirmarSenha = document.getElementById('ConfirmarSenha').value;
            if(senha)
                if(senha == ConfirmarSenha){
                    alert('Seu formulario foi enviado')
                }else{
                    alert('As senhas estão diferentes por gentilesa corrija o erro para proseguir')
                }
            }
        </script>

    </form>
