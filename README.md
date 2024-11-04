# Projeto Banco de Dados 1 - Modelo Relacional - Clínica Equilibrium
Criamos um banco de dados unificado para uma cliníca fictícia de reabilitação e apoio emocional. A tarefa principal era unir 3 sistemas: Clínica, Restaurante, Evento,então criamos a Equilibrium. A clínica se baseia em realizar eventos para os pacientes como aulas de yoga, meditação e até culinária. 
# Nosso manifesto
"Através de um banco de dados unificado, administramos consultas médicas, atendimentos personalizados e eventos, criando uma rede fluida que facilita o cuidado contínuo dos pacientes. Nosso foco é especial para pacientes psiquiátricos, que podem se beneficiar de um ambiente hospitalar mais acolhedor e interativo. Através de atividades educativas, refeições personalizadas no restaurante e eventos terapêuticos, incentivamos a recuperação emocional e social.

Os pacientes com condições psiquiátricas muitas vezes precisam de estímulos que vão além do tratamento médico tradicional. Por isso, nossa plataforma oferece eventos como sessões de meditação, palestras sobre técnicas de manejo de estresse e oficinas de culinária saudável. Tudo isso para garantir um ambiente de suporte completo ao bem-estar mental e emocional, em um espaço seguro dentro do hospital."

# Modelo MER
![WhatsApp Image 2024-11-03 at 16 34 33-2](https://github.com/user-attachments/assets/23a26584-4679-4b82-a7d0-687257cb1cf3)

# Modelo MR
![WhatsApp Image 2024-11-03 at 16 34 33](https://github.com/user-attachments/assets/178d1e11-d7df-455b-814f-5ff5b6ffabf2)

# 10 perguntas que agreguem valor ao negócio
O projeto requeriu que fizéssemos 10 perguntas que agreguem valor à equipe baseadas no banco de dados, e respondidas com consultas. Foram elas: 

1. Qual o percentual de inscritos que realmente foram aos últimos eventos?
Este dado mostra a assiduidade dos inscritos, ajudando a entender o engajamento e a real adesão dos participantes. Isso é fundamental para avaliar o sucesso dos eventos e planejar melhorias para aumentar a frequência.

2. Qual o percentual de pacientes satisfeitos com os eventos da clínica?
A satisfação dos pacientes com os eventos é diretamente ligada à qualidade dos serviços oferecidos. Este dado é complementar à assiduidade (pergunta 1) e pode indicar se o conteúdo dos eventos está atendendo às expectativas dos participantes.

3. Qual o percentual de médicos muito satisfeitos com o local de trabalho?
Justificativa: Uma clínica que é considerada um bom local de trabalho atrai e retém profissionais de qualidade. Medir a satisfação dos médicos pode indicar o nível de comprometimento e ajudar a promover um ambiente de trabalho saudável.

4. Qual é o período do ano com maior número de inscrições nos eventos?
Conhecer a sazonalidade nas inscrições ajuda a equipe a planejar eventos e campanhas para momentos de maior engajamento. Essa informação pode ser usada para aumentar o impacto de eventos nos períodos de maior procura.

5. Qual o gasto médio no restaurante por pedido?
Justificativa: O ticket médio dos pedidos no restaurante fornece insights sobre o comportamento de consumo dos clientes. Esse dado pode orientar promoções e ajustes de cardápio para aumentar o gasto médio por pedido.

6. Quais tipos de casos são mais comuns entre os pacientes?
Conhecer os tipos de casos mais frequentes permite criar eventos e serviços personalizados, atendendo melhor às necessidades dos pacientes e melhorando a experiência de atendimento.

7. Quais especialidades médicas têm a maior demanda de consultas?
Identificar as especialidades mais procuradas permite à clínica adequar sua estrutura e equipe médica para melhor atender à demanda. Além disso, pode ajudar na criação de pacotes de serviços direcionados às especialidades de maior interesse.

8. Os eventos influenciam no aumento de pedidos?
Comparar as vendas (pedidos) realizadas antes, durante e depois dos eventos ajuda a identificar picos de vendas associados aos eventos. Isso pode guiar a criação de estratégias promocionais para aproveitar esses picos.

9. Qual foi o valor médio dos pedidos com delivery?
Entender o valor médio dos pedidos com entrega ajuda a analisar a viabilidade e lucratividade do serviço de delivery. Esse dado pode orientar campanhas promocionais e ajustes logísticos.

10. Qual foi o valor médio dos pedidos sem delivery?
Comparar o valor médio dos pedidos com e sem entrega permite identificar se clientes que optam por retirada tendem a gastar mais ou menos. Essas informações podem ser valiosas para definir promoções voltadas a cada modalidade de compra. Ela é complementar à pergunta 9.

# Atributos adicionados 
• **satisfacao_Medico** -  O atributo satisfacao_Medico foi atribuído à entidade Medico ele serve para armazenar a pesquisa de satisfação com uma nota média de 1 a 5 mostrando se os médicos gostam de trabalhar no local.

• **Frequencia** - O atributo Frequencia foi adicionado à entidade associativa Inscricao, que relaciona Participante e Evento ele guarda um valor booleano para indicar se o inscrito esteve presente ou não no evento através do escaneamento do ingresso.

• **satisfacao_Participante** - o atributo satisfacao_Participante também foi incluído na entidade associativa Inscricao ele registra se o participante gostou do evento com uma nota de 1 a 5 com uma pesquisa de satisfação assim como no atributo satisfacao_Medico.
# Toque final
Montamos nosso logotipo, com tons pastéis brancos e azuis para referir a paz e tranquilidade.
![_e2e66f5f-f6de-401e-bf07-c87a8e32f614](https://github.com/user-attachments/assets/4088c15f-67e9-46db-8ab1-65d6590bfcd9)  
Esse trabalho foi feito por: Adele Brovelli, Bruna Lopes, Maria Eduarda Carvalho e Sérgio Melo
 
# Divisão de tarefas entre o grupo 
Adele Brovelli: ddl, dml e dql dos codigos.

Bruna Lopes: preparação do github e slides.

Maria Eduarda Carvalho: escolha das perguntas agregadoras.

Sérgio Melo: escolha do diferencial. 
