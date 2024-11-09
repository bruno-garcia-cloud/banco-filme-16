# banco-filme-corra
# descrição
Armazena as informações do filme

# Estrutura do banco de dados
## Tabela:
Usuario,
Relação,
Contexto_sociocultural,
Tratamento,
familia e 
membrofamilia_tem
## descricao
Armazenar as informações do usuario
## Colunas:
- 'Id_personagem' identificador unico do personagem
- 'Fk_tratamento_id_tratamento' Identificador de outra tabela chamada 'Tratamento'
- 'Nome_personagem' nome do personagem
- 'Idade' idade do personagem 
- 'Etnia_personagem' Diz o tom da melatonina do personagem
- 'Personalidade' descreve a personalidade do personagem
- 'profissão' diz qual o trabalho do personagem
- 'conflito' descreve um conflito do personagem 
- 'genero' fala qual é o genero do personagem

Tabela: Relacao
- 'id_relacao' Identificador unico da relacao
- 'tipo_de_relacao' Descreve qual o tipo de relacao

Tabela: Familia
- 'id_familia' Identificador unico da familia
- 'nome-familia' Nome da familia
- 'descricao_familia' Descreve a familia

Tabela: Contexto_sociocultural
- 'id_contexto_sociocultural' Identificador unico do contexto_sociocultural
- 'fk_familia_id_familia' Chave estrangeira
- 'lugar' Diz o local onde a familia/personagem moram
- 'classe_social' Diz a condição da familia/personagem
- 'etnia_contexto_sociocultural' Diz o tom de melatonina da familia/personagem
- 'cultura' Diz a cultura da familia/personagem
  
Tabela: Tratamento
- 'id_tratamento' Identificador unico do tratamento
- 'descricao' Descreve o tratamento
- 'nome_tratmento' Diz o nome do tratamento

Tabela: Membrofamilia_tem
- 'fk_familia_id_familia' Chave estrangeira da familia
- 'fk_personagem_id_personagem' Chave estrangeira do personagem
- 'parentesco' Descreve o parentesco
- 'funcao' Diz a funcao da familia


#Diagrama ER:
<img width="490" alt="Captura de tela 2024-11-08 215325" src="https://github.com/user-attachments/assets/868b09f5-4ed6-437a-9320-f7fac0dda425">
