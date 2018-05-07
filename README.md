# data-analysis-Lyceum-UEA
Classroom Project

Tarefas
--
* (Adham) ~~Unir os conjuntos de dados em um só~~
* Remover atributos irrelevantes (i.e., unidade física e porcentagem de presença)
* Renomear todas os atributos com nomes mais organizados e descritivos (i.e., Data de nascimento ao invés de DT_NASC)
* Organizar atributos *aluno*, *série* e *ano de ingresso*
    * Procurar inconsistências (i.e., discrepância do que se espera nos dados, como um aluno ingressando no ano "bola", um aluno com id negativo, uma série maior que 10, etc)
    * Caso existam inconsistências, reportar ao grupo para decidirmos o que fazer
    * Converter o tipo de dados desses atributos para `str` (isso não pode ser feito antes das últimas etapas)
* Converter o tipo de dados do atributo *data de nascimento* 
* Transformar as strings vazias em np.nan, no atributo *nota final*
* Verificar quantos alunos "unificados" existem (um aluno só pode ter um município de nascimento e uma data de nascimento, então se um aluno não atende a esses requisitos, precisaremos tratar esses casos)
* Procurar e corrigir erros de digitação nos atributos nominais (i.e., nome da disciplina, nome do curso, etc)


Bônus: procurar outros problemas no conjunto de dados e adicionar nesta lista!
