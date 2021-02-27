# Alterando a cor do cursor de entrada 

A barra vertical que sinaliza a entrada de um texto em uma box é chamda de cursaor de entrada, esse cursor por padrão tem a cor preta como você pode observar na imagem.

![Cursor Padrão](https://github.com/Evaldo-comp/CSS-Tutoriais/blob/main/Input%20cursor/cursor_padrao.gif)

Podemos alterar a cor deste cursor para dar um destaque maior na  inserção de texto dentro da text-box. Para isso utilizamos a propriedade `caret-color`

```html
<body>
    <!--trecho de estilização -->
    <style>
        input {
            caret-color: red;
            
        }
    </style>


    <h3>Alterando a cor do cursor de entrada</h3>
    <input type="text">
    
</body>
```

Observe que a diferença é sutil, mas para determinados casos pode ser significante.

![Cursor Alterado](https://github.com/Evaldo-comp/CSS-Tutoriais/blob/main/Input%20cursor/red-cursor.gif)

:house: [Home](https://github.com/Evaldo-comp/CSS-Tutoriais/blob/main/README.md)  
