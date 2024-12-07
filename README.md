# Formulário
Criação de um formulário simples utilizando html e css..
# Código HTML
    <!DOCTYPE html>
    <html lang="pt-br">
     <head>
	 <meta charset="utf-8">
	  <meta name="viewport" content="width=device-width, initial-scale=1">
	   <title>Login</title>
	  <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>
	 <div class="login-container">
		<h2>Login</h2>
		 <form id="loginForm">
			<div class="input-group">
				<label for="username">Usuario:</label>
				 <input type="text" id="username" placeholder="Digite o usuario">
			 </div>
			 <div class="input-group">
				<label for="password">Senha:</label>
				<input type="password" id="password" placeholder="Digite a senha">
			 </div>
			 <form>
				 <div class="input-group">
     <label for="dia">Data de Nascimento:</label>
     <input type="date" id="dia" name="dia" />
    </div>
    </form>
    <form>
  
    
    <div class="input-sex">
    	<label for="sexo">Sexo:</label>
      <input type="radio" id="sexo" name="sexo" value="feminino"/>
      <label for="sexo">Feminino</label>

      <input type="radio" id="sexo" name="sexo" value="masculino"/>
      <label for="sexo">Masculino</label>

			
		</form>
		
	</div>
	
	<div class="input-group">
    <label for="dia">Email:</label>
	<input type="email" placeholder="exemplo@example.com" />
    </div>
    <form>
     <fieldset>
    <h3>Quais seus interesses?</h3>
    <div class="input-check">
      <label>
        <input type="checkbox" id="coding" name="interest" value="coding" />
        Programação
      </label>
    </div>
    <div>
      <label>
        <input type="checkbox" id="music" name="interest" value="music" />
        Tecnologia
      </label>
    </div>
    <div>
      <label>
        <input type="checkbox" id="art" name="interest" value="art" />
        Artes
      </label>
    </div>
    <div>
      <label>
        <input type="checkbox" id="sports" name="interest" value="sports" />
        Música
      </label>
    </div>
    <div>
      <label>
        <input type="checkbox" id="cooking" name="interest" value="cooking" />
        Cozinhar
      </label>
    </div>
    <div>
      <label>
        <input type="checkbox" id="other" name="interest" value="other" />
        Outros
      </label>
      <input
        type="text"
        id="otherValue"
        name="other"
        aria-label="Other interest" />
                 </div>
                   <div>
      
                 </div>
            </fieldset>
                </form>

               <button type="submit">Entrar</button>
               </body>
               </html>


# Código CSS
    body{
	font-family: Arial,sans-serif;
	background-color:blueviolet;
	display: flex;
	justify-content: center;
	align-items: center;
	height: 100vh;
	margin: 0;



       }

     .login-container{
	background-color: aliceblue;
	padding: 20px;
	border-radius: 20px;
	box-shadow: 0 0 10px rgba(0,0 ,0, 0.5);
	width: 300px;


     }

    h2{

	text-align: center;
	margin-bottom: 20px;
    }

    .input-group{
	margin-bottom: 15px;
    }

    .input-group label{
	display: block;
	font-weight: bold;
	margin-bottom: 5px;
    }

    .input-group input{
	font-family: Arial,sans-serif;
	width: 85%;
	padding: 10px;
	border: 1px solid #ccc;
	border-radius: 5px;
    }

    button{
	width: 99%;
	padding: 10px;
	background-color: whitesmoke;
	color: black;
	border: none;
	border-radius: 5px;
	cursor: pointer;
	font-size: 16px;
    }

    button:hover{
	background-color: skyblue;
    }

    .input-sex{
	margin-bottom: 15px;
	font-family: Arial,sans-serif;
	font-size: 16px;
	
	


    }
    .input-sex label {
	font-weight: bold;
	

    }

    
              
