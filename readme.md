# Another grid system

Another grid system is a fully customizable grid system and mobile first utilities

## Roadmap
Próximas entregas:

- [ ] Remover o compass do projeto sass
- [ ] Substituir a estrutura atual de breakpoints [por essa](https://css-tricks.com/media-queries-sass-3-2-and-codekit/)
- [ ] Dividir o sass em vários arquivos
- [ ] Baseado nos arquivos divididos criar templates [handlebars](http://handlebarsjs.com) para cada arquivo
- [ ] Criar um index.html simples sem css com as opções descritas abaixo
- [ ] Iniciar projeto angular
- [ ] Permitir que os arquivos gerados sejam baixados via [JSZip](https://stuk.github.io/jszip/)
- [ ] Incluir um modal pra antes da pessoa baixar ela responder 'Você gostaria que esse projeto incluí-se mais recursos como fontes e paleta de cores?' - Resultado vai para uma planilha
- [ ] Criar um layout css de uma página só para o index.html
- [ ] Colocar seção de exemplos no index.html
- [ ] Criar um arquivo de CONTRIBUTING.md 
- [ ] Divulgar!
- [ ] Adicionar suporte a novos pre-processadores
- [ ] Pensar em adicionar suporte a novos recursos como fonte e cores


## O que é customizável?
* Quantidade de breakpoints. 
* Nome e largura máxima de cada breakpoint.
* Quantidade de colunas.
* Quantidade de espaçamentos.
* Valores dos espaçamentos.
* Se o projeto possui ou não classes utilitárias. default: true;
* Se o projeto possui ou não espaçamentos padronizados. default: true.
* Pre-processador css usado, ordem de prioridade: sass, scss, css puro, stylus, postcss, less. default: scss.
