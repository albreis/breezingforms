# breezingforms

O Breezing Forms tem alguns bugs conhecidos que não permitem que sejam adicionados
mais de um formulário na mesma página pois geram alguns conflitos.

Resolvi trabalhar em uma solução para isso.

O bug acontece por conta do Javascript que é gerado em duplicidade. Tive que modificar 3 arquivos .php 
para que os codigos fossem gerados sem duplicar os nomes de algumas funções de variáveis.

Modifiquei também o arquivo que importa os "scripts" nativos do Breezinf Forms para o banco de dados,
esse script são usados para gerar códigos dinâmicos de validação e também continham erros.

Caso precise de auxílio na instalação do Breezing Forms entre em contato comigo pelo whatsapp:
https://wa.me/5551981108038