Um livro de receitas culinárias, escrito em <b>JAVA FX, no ano 2019</b>.<br><br>

<img style="height:auto;" alt="" width="1000" height="560" class="avatar avatar-user width-full border color-bg-default" src="https://user-images.githubusercontent.com/9969964/153723293-e4c1f485-cfa1-416c-82b7-25dc67aaa315.png">

<img style="height:auto;" alt="" width="500" height="280" class="avatar avatar-user width-full border color-bg-default" src="https://user-images.githubusercontent.com/9969964/153723933-2a9a1987-28d3-4514-9887-b08976cb7105.png"><img style="height:auto;" alt="" width="500" height="280" class="avatar avatar-user width-full border color-bg-default" src="https://user-images.githubusercontent.com/9969964/153723598-59672263-c372-4a60-91d9-13e1093d44d4.png">



<br><b>RESUMO TÉCNICO</b><br><br>
Nesse projeto foram implementados <b>multi-threading, mvc design-pattern, observer design pattern, programação orientada a eventos, navegação entre as páginas, instalação automática de um banco de dados sql leve</b>, desde que haja permissao de escrita... Esse banco de dados persiste as receitas culinárias, informações de status,
configurações e preferências do aplicativo.<br>




<br><img style="height:auto;" alt="" width="500" height="280" class="avatar avatar-user width-full border color-bg-default" src="https://user-images.githubusercontent.com/9969964/153723838-e5a84798-e3da-4cba-830a-fc4c1f61832f.png"><img style="height:auto;" alt="" width="500" height="280" class="avatar avatar-user width-full border color-bg-default" src="https://user-images.githubusercontent.com/9969964/153724022-2a6cdc0a-7a8e-4260-bf74-a62527bc4e02.png">




<br><b>RECURSOS DO APLICATIVO</b><br><br>
<ul>
<li><b>comando</b><br>
Pode-se comandar o aplicativo tanto pelo teclado (usando um key-map que o aplicativo mostra ao usuário), quanto pelo mouse.<br><br></li>
<li><b>importação/exportação</b><br>
Ele <b>importa</b> receitas de um arquivo json.
Ele <b>exporta</b> receitas para um arquivo json.
Ele <b>imprime em pdf</b>, total ou parcialmente, as receitas.<br><br>
<br><img style="height:auto;" alt="" width="500" height="280" class="avatar avatar-user width-full border color-bg-default" src="https://user-images.githubusercontent.com/9969964/153724423-901f391d-5da3-4371-bedf-685399eb2597.png">

  
  </li><br><br>
<li><b>componente lista de receitas</b><br>
  <br><img style="height:auto;" alt="" width="500" height="280" class="avatar avatar-user width-full border color-bg-default" src="https://user-images.githubusercontent.com/9969964/153724245-88994162-2a20-4adc-95d6-3fd0e84b7897.png">                        <img style="height:auto;" alt="" width="150" height="280" class="avatar avatar-user width-full border color-bg-default" src="https://user-images.githubusercontent.com/9969964/153724560-b29a4e7a-e2c4-4684-8c29-f749bcf02260.png">             <img style="height:auto;" alt="" width="150" height="280" class="avatar avatar-user width-full border color-bg-default" src="https://user-images.githubusercontent.com/9969964/153724715-13571ff7-a473-404c-b937-25e967fa0af0.png">
 

 


Desenvolvi a lista de receitas, que é um componente do app, de maneira totalmente orientada a eventos e com recursos interessantes de multi-seleção, seleção simples, seleção alternada, inversão de seleção, pesquisa exata ou contendo a chave de busca, skin configurável.<br>
O componente lista de receitas, na verdade, é uma extensão de um componente básico : a lista vertical scrollável.<br>
O componente <b>lista vertical scrollavel</b> foi projetado pensando em reutilização de softtware. <b>Por isso, ela foi projetada com baixo acoplamento, usando a api de listeners de eventos, do java fx.</b><br>
Se algum cliente quiser escutar o que acontece na lista de receitas e tomar alguma decisão, basta se registrar nela que será notificado. A lista de receitas é um componente fortemente desacoplado.<br>
A lista de receitas, usada no aplicativo livro de receitas culinárias, é uma casquinha que envolve o <b>componente core lista vertical scrollavel</b>, extendendo, ampliando o componente core com algumas particularidades, usadas apenas no livro de receitas culinarias.
Caso se queira usar a <b>lista vertical scrollavel</b> em outro aplicativo, por exemplo, uma agenda telefônica, basta fazer pequenas extensões e settings de textos no core e na extensão, que temos rapidamente uma lista de nomes e números telefônicos.
<b>Reutiliza-se facilmente esse componente de software.</b><br><br></li></ul>
