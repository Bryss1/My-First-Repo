

Git:
Existem Varios comandos que podem ser utilizados


A estrutura do código se geralmente define como a seguinte:

Branchs (Ramificações):

Master:
O versionamento principal do código.
seguindo por exemplo:

\\Linha de branch\\---- (v0.1)----------> (v0.2)----------> (v1.0 "Versão Atual")-----

Develop:
Particionamento da versão em que o dev trabalha:
\\Linha de branch\\----(v0.1)--->("Dev".elop)--->(Dev)--->(Dev)---> (v0.2)-----------> (v1.0 "Versão Atual") -----

Feature:
Uma parte ja fracionada do código a ser trabalhada separadamente, e que pode eventualmente, se juntar ao codigo principal se assim houver a necessidade de se fundirem aprimorando até a versão mais atual:

\\Linha de branch Master\\---- (v0.1)-----------------------------> (v0.2)----------------------------> (v1.0 "Versão Atual")-----
\\Linha de branch Develop\\--- (v0.1)--->("Dev".elop)--->(Dev)--->(Dev)---> (v0.2)--------------------> (v1.0 "Versão Atual")-----
\\Linha de branch Feature\\(v0.1) -------(Dev)--->("Feat".ure)--->(Feat)--->(Feat)--->(Feat)----------> (v1.0 "Versão Atual")-----