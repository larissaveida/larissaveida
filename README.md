<! doctype html>
<html lang="pt-br">
    <head>
        <meta charset="utf-8">
        <title> Validação de Dados</title>>
        </head>
        <body>
            <h1 align="center"> Validação de Dados </h1>
            <hr> 
            <br> 
            <center> 
                <form name="formulario"> 
                    <input type="text" placeholder="Digite sua idade" name="idade">
                    <input type="button" value="Entrar" onclick="validade()">

                </form>
            
            </center> 

            <script> 
            function validade (){
                var recidade = document.formulario.idade.value
                if (recidade >= 18) { 
                    window.alert("Você é maior de idade! \nPode navegar")
                window.location="https://www.megamaniadasorte.com.br/"
                }
                else{ window.alert("Você é menor de idade! \nSai Fora rapaz!")
            window.location="https://www.galinhapintadinha.com.br/"
                }
            }
            </script>
            
            

         </body>
  </html>
