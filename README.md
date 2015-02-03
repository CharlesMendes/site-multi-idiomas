# site-multi-idiomas
Exemplo de como criar um site com 2 ou mais idiomas, essa dica tambem vale para aplicativos web para android e ios por exemplo

## Estrutura de diretorios
Abaixo a descriçao dos arquivos do projeto, pode ser adaptado da melhor forma possivel.
       _ index.html         = Pagina de exemplo usando o conteudo de languages.xml
      |_ js
          |_ languages.js   = Esse arquivo contem a logica que efetua a troca do idioma
      |_ xml
          |_ languages.xml  = Nesse arquivo fica todos labels/campos e mensagens do app que sera usado nas paginas .html

* Uma boa pratica seria separar mensagens de negocio e labels em dois arquivos .xml, nesse exemplo usamos o languages.xml, poderia existir por exemplo um labels.xml e outro mensagens.xml.... 
* Na pagina index.html deve deve utilizar a classe correspondente ao campo do label no arquivo .xml, exemplo:
      <span class="label-hello"></span>

### Pronto, criamos um exemplo de site/webapp multi idiomas

Duvidas podem enviar email para contato@charlesmendes.com

##License
MIT, see LICENSE.
