# Recomendação de Álbuns de Música

Este é um projeto simples de um site desenvolvido em HTML e CSS para recomendação de álbuns de música. O objetivo deste site é fornecer aos usuários sugestões de álbuns de diferentes gêneros musicais, acompanhados de informações relevantes sobre os artistas e as faixas.

## Conteúdo

- [Demonstração](#demonstração)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)

## Demonstração

Você pode verificar a demonstração deste projeto [aqui](https://cenourissimo-site.vercel.app/).

## Tecnologias Utilizadas

- HTML5
- CSS3

## Lista e Explicação de Tags HTML

!DOCTYPE html:

Esta declaração define o tipo de documento HTML sendo usado, que é HTML5 neste caso. Ela deve estar no início de cada documento HTML para especificar a versão do HTML que está sendo usada.

html:

Esta é a tag raiz que envolve todo o conteúdo HTML da página. Ela indica o início de um documento HTML.

head:

A seção "head" contém metadados sobre o documento HTML, como o conjunto de caracteres, o título da página e links para folhas de estilo externas.

meta:

As tags "meta" fornecem informações adicionais sobre o documento HTML. No seu caso, você usou duas tags "meta" para definir o conjunto de caracteres (UTF-8) e a configuração da viewport.

title:

A tag "title" define o título da página que é exibido na barra de título do navegador. É uma parte importante para a otimização de mecanismos de busca (SEO) e também para ajudar os usuários a identificar a página.

link:

A tag "link" é usada para vincular recursos externos ao documento HTML. No seu caso, você a usou para vincular uma folha de estilo externa (styles.css) ao seu documento.

body:

A tag "body" contém o conteúdo visível da página, como texto, imagens e elementos HTML. Tudo o que você deseja que os usuários vejam na página deve estar dentro desta tag.

header:

A tag "header" é usada para definir a seção do cabeçalho do seu site, que geralmente contém elementos como logotipos, menus de navegação e informações de contato.

nav:

A tag "nav" define uma seção de navegação em seu site. Normalmente, ela contém menus ou links de navegação que ajudam os usuários a se locomover pelo site.

ul e li:


"ul" (unordered list) e "li" (list item) são usadas para criar listas não ordenadas. No seu caso, você usou essas tags para criar uma lista não ordenada de itens de menu de navegação.
  
h1, h2:

As tags "h1", "h2", etc., são usadas para criar cabeçalhos ou títulos em uma página. Elas indicam a importância e a hierarquia do texto na página, sendo "h1" o título mais importante.

"img":

A tag "img" é usada para inserir imagens na página. Você especifica o caminho da imagem no atributo src e pode adicionar um texto alternativo no atributo alt para acessibilidade.

"p":

A tag "p" é usada para criar parágrafos de texto na página. Ela é usada para separar e formatar o texto em blocos legíveis.

"a":

A tag "a" cria hiperlinks ou âncoras para outras páginas ou recursos da web. O atributo href especifica o URL de destino para onde o link leva.

## Lista e Explicação de Seletores CSS 

"*" (seletor universal):

O seletor universal "*" seleciona todos os elementos HTML na página. Nesse caso, é usado para aplicar um reset básico de margens e preenchimentos, garantindo que não haja margens ou preenchimentos padrão em nenhum elemento.

".classe" (seletor de classe):

Os seletores de classe são precedidos por um ponto (.) e são usados para aplicar estilos a elementos com uma determinada classe.

header (seletor de tipo):

O seletor de tipo seleciona elementos HTML com um nome específico. Por exemplo, header seleciona todos os elementos <header> na página. Você pode aplicar estilos diretamente a esses elementos.

nav ul (seletor de tipo e seletor descendente):

Este seletor seleciona elementos "ul" que estão dentro de elementos "nav". É um exemplo de um seletor de tipo combinado com um seletor descendente.

".link:hover" (seletor de classe com pseudo-classe):

Este é um seletor de classe combinado com uma pseudo-classe (:hover). Ele seleciona elementos com a classe .link quando o cursor do mouse está sobre eles. 

".guts", ".moments", ".grace", ... (seletores de classe individuais):

Cada uma dessas classes, como ".guts", ".moments", etc., é um seletor de classe que é usado para aplicar estilos específicos a elementos com essas classes.
