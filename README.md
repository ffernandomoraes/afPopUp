# afPopUp

afPopUp é um simples Pop-Up em javascript utilizando cookies.

## Features

- Fácil configuração
- Possibilidade de incluir links
- NO JQUERY!
- Apenas um arquivo e um svg para o botão de close que pode ser trocado
- Cookie para limitar a visualização por um certo tempo configurado pelo usuário
 
## Installation

1. Inicie uma div com a classe ou id desejado
2. Inicie o afPopUp com a mínima configuração abaixo:

```
  afPopUp.init({
        // Selecione a sua div
	    element: '.teste',
	    // Url da Imagem
		image: 'src/images/imagem.jpg',
		// Tempo em minutos para não exibir o Pop-Up
		expirateCacheTime: 30
	});
```

## Options

##### element: '#elemento'
Seleciona o elemento onde será aplicado o Pop-Up.

##### image: 'image.jpg'
Url de onde está armazenada a imagem.
Formatos suportados: jpg, jpeg, png, gif.
O tamanho padrão do Pop-Up é de 550px de largura, recomendamos que a imagem selecionado seja quadrada.

##### expirateCacheTime: 60
Define em minutos quanto tempo o usuário ficará sem visualizar o Pop-Up.

##### haveLink: true or false
Define se irá existir no Pop-Up um link ou não.

##### link: 'url de destino ao clicar na imagem'
Caso haveLink seja definido como true, definir o destino ao clicar no Pop-Up.

#### target: '_blank'
Define o target, caso seja definido '_blank' irá para outra aba senão ele irá para a mesma aba, qualquer outro valor irá ser definido o padrão '_self'.

## Authors


[<img src="http://i.imgur.com/rOUPyUs.jpg">](http://github.com/ffernandomoraes)
[<img src="http://i.imgur.com/3ShxeeX.jpg">](http://github.com/angelorodriigors)
