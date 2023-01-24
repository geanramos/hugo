## Sobre - picpay.com
Emerald é um tema minimalista criado para Jekyll. O principal objetivo do Emerald é fornecer um tema claro para quem quer um blog pronto para usar, focado no conteúdo e mobile-first.

![Esmeralda](/img/Emerald01.png "Esmeralda")

## Configuração e uso
O Emerald pode ser instalado simplesmente baixando a pasta .zip do [repositório no Github](https://github.com/KingFelix/emerald/archive/master.zip).

Depois de extrair o conteúdo da pasta para o diretório selecionado, você pode digitar ``jekyll serve`` no terminal, abrir seu navegador em ``0.0.0.0:4000/emerald/`` e você o encontrará lá.

Além disso, é possível bifurcar o repositório e usar o Github Pages como hospedagem. Seguindo este caminho será suficiente alterar o valor ``baseurl`` para o arquivo ``_config.yml``, com o nome do diretório do seu projeto (por exemplo /blog) ou simplesmente com um "/" (barra ) se você quiser instalar o Emerald na raiz.

### Opções
A partir da versão 1.1.0, você pode personalizar o Emerald graças a algumas opções. Agora é possível definir uma tag de cabeçalho personalizada definindo a opção relacionada no arquivo ``_config.yml`` como "true". Em seguida, insira seu código personalizado no arquivo ``header-custom.html``.
Da mesma forma, você pode personalizar o rodapé do menu de navegação, definindo como "true" a opção relacionada e colocando seu código no arquivo ``nav-footer-custom.html``.
Além disso, agora é possível selecionar uma opção reversa que permite mover o menu de navegação para o lado esquerdo, definindo-o como "verdadeiro".

### Cores
As cores básicas são definidas no arquivo ``base.scss``:
- $main-color: usado para o menu, título, link e rodapé
- $background-color: usado para fundo e links no menu de navegação
- $text-color: usado para texto e título em postagens e páginas

Para personalizar as cores, basta definir os valores em HEX, RGB (ou RGBa) ou qualquer outro formato aceito pelo CSS.

### Menu de navegação
A partir da versão 1.1.0, os links dentro do menu de navegação são gerados automaticamente a partir de páginas com layout definido como ``page``.
Você pode definir links personalizados, colocando a tag ``<a>`` no arquivo ``link.html``.

### Filial
Esmeralda tem dois ramos:
- ``master``: é para desenvolver propósitos.
- ``gh-pages``: é apenas para site de demonstração.  

### Baseurl
O Emerald foi pensado para ser usado principalmente com o Github, em particular no [site do projeto](https://pages.github.com/). Por esta razão, várias tags foram incluídas ``{{ site.baseurl }}`` para se referir ao diretório "/emerald/".
Você pode alterar o valor "baseurl" no arquivo ``config.yml``, para corresponder ao seu diretório (por exemplo "/blog/") ou à raiz do seu projeto. Nesse caso, você deve definir o valor "baseurl" como "/".

### Tipografia
Para manter o ritmo vertical, foi aplicada uma **escala tipográfica** como uma escala modular, com uma linha de base definida para 24px. Para manter este ritmo é necessário inserir elementos como imagem, vídeo ou outros conteúdos com uma altura de 24px (ou múltiplos) conforme referido.

Por último, mas não menos importante: a [documentação do Jekyll](http://jekyllrb.com) é o melhor ponto de partida!

## Autor

### Jacopo Rabolini

- Site: [www.jacoporabolini.com](http://www.jacoporabolini.com)
- Linkedin: [linkedin.com/in/jacopo-rabolini/](https://www.linkedin.com/in/jacopo-rabolini/)

## Licença
O Emerald é lançado sob [Licença MIT](license.md).
