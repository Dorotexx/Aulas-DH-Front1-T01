GLOSSÁRIO DA AULA 5

< ol type = "1"> ... </ ol>
        o atributo "type" permite alterar o tipo de Marcação da lista.
        o valor "1" altera o número do item da lista e pode ser usado:
            "1" para números
            "A" ou "a" para alfabeto
            "I" para números romanos

< ol start = "20"> ... </ ol>
        o atributo "start" permite definir de onde iniciar a contagem.
        o valor pode ser altera para número positivos e negativos.

< ul type =
        o atributo "type" permite alterar o tipo de Marcação da lista.
        o valor "disc" altera o número do item da lista e pode ser usado:
            "disc" circulo preenchido
            "circle" círculo vazado
            "square" quadrado
            "none" nenhum (fica em branco)

Para o uso de listas (< ol> / < ul> não é permitido usar uma tag dentro de outra, mas é permitido que se use uma
delas dentro da tag < li> 


Hiperlinks

< a href = "https://www.google.com"> Vamos acessar o google < /a> (Link externo)

        O atributo href é usado para indicar o destino para o qual o link aponta
        A rota "https://..." é usado para especificar um caminho absoluto ou relativo
        O Texto é onde é escrito o texto que ficará visivel para o usuário.

< a href = "inicio.html">Início< /a> (link local)


Âncoras
        Fragmento ou elemento dentro de uma página, como uma seção ou um título.
        Ele começa com uma # ou com a propriedade id.


< a href = "# biografia"> Biografia < /a>
< a href = "https:// www.site.com/#contato"> Contato< /a>
< a href = "https:// nos.html#nossa-equipe"> Nossa Equipe< /a>

Correspondência

< a href = "mailto:user@server.com">Enviar mensagem< /a>
< a href = "tel:1145678899"> Inicio< /a>

Imagens

< img src="img/fotoPerfil.jpg alt="imagem de perfil> 
        atributo src indica o destino onde a imagem está hospedada
        rota "img/..." especifica a imagem contida dentro da pasta "img"
        alt= contém uma descrição da imagem (auto descrição). Suporta 125 caracteres.

< img width="320" "img/fotoPerfil.jpg"> especifica a largura da imagem
< img height="560" "img/fotoPerfil.jpg"> especifica a altura da imagem