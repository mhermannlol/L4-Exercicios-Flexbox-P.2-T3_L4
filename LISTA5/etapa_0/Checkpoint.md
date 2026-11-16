1. Em qual aba das ferramentas do desenvolvedor a mensagem apareceu?
R: A mensagem aparece na aba Console.


2. O atributo defer faz o navegador esperar o HTML ser lido antes de executar o script.
Por que isso será importante mais adiante, quando o script precisar mexer em elementos
da página?
R:O defer faz o script rodar só depois que o HTML foi lido por completo. Quando o script for buscar elementos como o <p id="mensagem">, eles já existirão na página.


3. Se você escrevesse <script src="codigo.js" defer> no HTML, mas o arquivo se
chamasse script.js, o que aconteceria?
R: O navegador não encontra o arquivo codigo.js, retorna erro 404 e o script não roda. Nada aparece no console, e a mensagem de erro de carregamento aparece na aba Console ou Rede.