
Um livro de receitas culinárias, escrito em <b>JAVA FX, no ano 2019</b>.<br><br>

<b>RESUMO TÉCNICO</b><br><br>
Nesse projeto foram implementados <b>multi-threading, mvc design-pattern, observer design pattern, programação orientada a eventos, navegação entre as páginas, instalação automática de um banco de dados sql leve</b>, desde que haja permissao de escrita... Esse banco de dados persiste as receitas culinárias, informações de status,
configurações e preferências do aplicativo.

<br><b>RECURSOS DO APLICATIVO</b><br><br>
<ul>
<li><b>comando</b><br>
Pode-se comandar o aplicativo tanto pelo teclado (usando um key-map que o aplicativo mostra ao usuário), quanto pelo mouse.<br><br></li>
<li><b>importação/exportação</b><br>
Ele importa receitas de um arquivo json.
Ele exporta receitas para um arquivo json.
Ele imprime em pdf, total ou parcialmente, as receitas.<br><br></li>
<li><b>componente lista de receitas</b><br>
Desenvolvi a lista de receitas, que é um componente do app, de maneira totalmente orientada a eventos e com recursos interessantes de multi-seleção, seleção simples, seleção alternada, inversão de seleção, pesquisa exata ou contendo a chave de busca, skin configurável.<br>
O componente lista de receitas, na verdade, é uma extensão de um componente básico : a lista vertical scrollável.<br>
O componente <b>lista vertical scrollavel</b> foi projetado pensando em reutilização de softtware. <b>Por isso, ela foi projetada com baixo acoplamento, usando a api de listeners de eventos, do java fx.</b><br>
Se algum cliente quiser escutar o que acontece na lista de receitas e tomar alguma decisão, basta se registrar nela que será notificado. A lista de receitas é um componente fortemente desacoplado.<br>
A lista de receitas, usada no aplicativo livro de receitas culinárias, é uma casquinha que envolve o <b>componente core lista vertical scrollavel</b>, extendendo, ampliando o componente core com algumas particularidades, usadas apenas no livro de receitas culinarias.
Caso se queira usar a <b>lista vertical scrollavel</b> em outro aplicativo, por exemplo, uma agenda telefônica, basta fazer pequenas extensões e settings de textos no core e na extensão, que temos rapidamente uma lista de nomes e números telefônicos.
<b>Reutiliza-se facilmente esse componente de software.</b><br><br></li></ul>
