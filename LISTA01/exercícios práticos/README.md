1. b
display:block ocupa toda largura do elemento disponível e força quebra de linha.

2. c
a tag spam é um elemento inline enquanto outros são elementos em bloco.

3. c
elementos inline não respeitam propriedades de dimensão.

4. b
display:none remove completamente o elemento enquanto visibility:hidden oculta o elemento.

5. b
inline-block permite alinhar elementos lado a lado na mesma linha sem quebrar a página.

6. c 
odos os elementos no HTML possuem position: static.

7. c 
elemento com position:relative se desloca utilizando a posição original no fluxo como ponto de referência.

8. b
o posicionamento absoluto busca o primeiro elemento pai que possua um posicionamento definido.

9. c
position:fixed fixa o elemento com relação à janela de visualização do navegador.

10. b
a propriedade z-index não se aplica a elementos com posicionamento padrão.

11. b
position:sticky alterna entre relative e fixed assim que a rolagem atinge o ponto especificado.

12. b
elementos com absolute ou fixed são removidos do fluxo normal.

13. 
inline faz o elemento ficar lado a lado com outros, mas ignora larguras/alturas e margens verticais. o inline-block mantém o comportamento de ficar lado a lado, mas aceita a definição explicita de largura, altura e margens.

inline: formatar uma palavra específica dentro de um parágrafo
inline-block: criar botões lado a lado ou itens de um menu horizontal

14.
o elemento .filho será alinhado no canto inferior direito do container .pai

o elemento .pai possui position:relative, e vira o container de referência. o .filho possui position:absolute com bottom:0 e right:0, encostando na base e na borda direita do pai.

15. 
o .filho não usará mais o .pai como referência. ele procurará o próximo ancestral posicionado ou se alinhará no canto inferior direito da página.

sem position: relative no .pai, o container passa a ser static.

16.
a - 
fixed: sempre a viewport.
sticky: o fluxo normal até atingir o limite estipulado

b- 
fixed: ele fica estático independentemente de quanto se rola.
sticky: rola com a página até o ponto de fixação e depois desgruda quando o elemento pai some da tela.

c-
fixed: botão para voltar ao topo ou chat flutuante.
sticky: cabeçalho de tabelas longas ou menus de navegação.

17.
O navegador interpreta quebras de linha e espaços em branco dentro das tags <.li> como espaço de texto.

remover os espaços entre os <.li> no HTML.

18.
display:none oculta o elemento e recolhe o espaço no layout. visibility:hidden oculta a visualização, mas espaço em branco continua reservado na página.

display:none: menus dropdown ou abas que apenas ocupam espaço na tela.

visibility:hidden: reservar um espaço fixo para mensagens de erro em formulários.






