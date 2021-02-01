
# Inserindo Highlight com CSS
È muito comum que alguns trechos de conteúdo textual de um site precise de um destaque maior, podemos fazer isso utilizando as tags ```<strong``` ou ```<em>```, mas existe uma maneira mais sofisticada de destacar seu texto, tipo como se você utilizasse uma marcador. O que iremos fazer é adicionar um background a um determinado trecho do texto, e sinalizar o recurso desse background diretamente do site [SVGBox](https://svgbox.net/). Iremos copiar o link do brush que queremos aplicar como destaque e tcharan! A mágica está feita:
## Vamos ver como faz
```
<html>
<style>
        .highlight {
            background: url("https://s2.svgbox.net/pen-brushes.svg?ic=brush-5&color=ffff43 " );
            
        }
        
    </style>
    
    <div>
        <h1>Esse é um <span class="highlight">
            trecho destacado
        </span> do texto</h1>
    </div>
  </html>
 ```
 ---
  ## Como fica :
  ![](https://github.com/Evaldo-comp/CSS-Tutoriais/blob/main/Highlight/print-css.png)
  
  Para deixar a coisa mais interessante podemos brincar com as possibilidades, como por exemplo adicionar um :hover para que o destaque mude toda vez que o mouse passe pelo trecho.
  
  ```
  .highlight:hover{
            background: url("https://s2.svgbox.net/pen-brushes.svg?ic=brush-7&color=f33343 " );
    }
   ```
   ## Como fica:
   ![](https://github.com/Evaldo-comp/CSS-Tutoriais/blob/main/Highlight/hover.gif)
   
   ---
   
   Explore, pois com os recursos do SVGBox, é possível fazer muito mais. 
   
   Esse tutorial foi adaptado do artigo publicado no site dev.to escrito por [Shubham Jain](https://github.com/shubhamjain)
   
  :house: [Home](https://github.com/Evaldo-comp/CSS-Tutoriais/blob/main/README.md)  
    
