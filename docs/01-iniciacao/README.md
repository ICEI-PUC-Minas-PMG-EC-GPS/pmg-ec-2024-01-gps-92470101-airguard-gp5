# Iniciação

 A fase de iniciação, em gerência de projetos, é o estágio que estabelece as bases para o sucesso do empreendimento. 
 Durante essa etapa, os objetivos definidos, identificando-se suas metas, escopo, partes interessadas (*stakeholders*) e restrições. 
 É o momento em que a viabilidade do projeto é avaliada, analisando-se recursos necessários, riscos potenciais e benefícios esperados.
 Nesta etapa é elaborado o Termo de Abertura do Projeto (TAP).
 Essa fase serve como um alicerce estratégico, proporcionando uma compreensão abrangente do que o projeto busca alcançar e delineando as diretrizes que orientarão as etapas subsequentes. 
 O sucesso na fase de iniciação contribui significativamente para a eficácia do gerenciamento de projetos como um todo.

# Estrutura do Documento

- [Fase de Iniciação](#iniciação)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Critérios de Sucessos](#critérios-de-sucesso)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos Preliminares](#requisitos-preliminares)
- [Partes Interessadas](#partes-interessadas)
- [Estimativa de Custo e Prazo](#estimativa-de-custo-e-prazo)
  - [Estimativa de Custo](#estimativa-de-custo)
  - [Estimativa de Prazo](#estimativa-de-prazo)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
- [Documentos](#documentos)
  - [Declaração de Escopo](#declaração-de-escopo)
  - [Registro de Partes Interessadas](#registro-de-partes-interessadas)
  - [Termo de Abertura do Projeto (TAP)](#termo-de-abertura-do-projeto-tap)

# Introdução

## Problema

A crescente degradação da qualidade do ar nas áreas urbanas constitui uma séria ameaça à saúde pública e ao meio ambiente, exacerbada pela emissão descontrolada de poluentes provenientes de veículos, indústrias e outras fontes antropogênicas. Problemas respiratórios, cardiovasculares e o aumento na incidência de doenças crônicas estão diretamente relacionados à exposição prolongada a altos níveis de poluentes atmosféricos, como partículas em suspensão (PM10 e PM2.5), dióxido de nitrogênio (NO2) e ozônio troposférico (O3). Além disso, a má qualidade do ar contribui para o aquecimento global e a acidificação de ecossistemas naturais. Diante deste cenário alarmante, a criação de um projeto de monitoramento da qualidade do ar é essencial para fornecer dados precisos e em tempo real sobre a concentração de poluentes!


## Objetivos

O principal objetivo do projeto de monitoramento da qualidade do ar é estabelecer um sistema abrangente e preciso de coleta e análise de dados atmosféricos, que permita avaliar continuamente os níveis de poluição do ar em áreas urbanas e rurais. Este projeto visa identificar as principais fontes de poluição, compreender os padrões de dispersão dos poluentes e avaliar o impacto das condições meteorológicas sobre a qualidade do ar. Além disso, o projeto pretende fornecer informações em tempo real à população e às autoridades competentes, facilitando a tomada de decisões rápidas e eficazes para mitigar os efeitos negativos da poluição. Outros objetivos incluem a promoção da conscientização pública sobre os riscos associados à poluição do ar, o apoio ao desenvolvimento de políticas ambientais mais rigorosas e a contribuição para pesquisas científicas voltadas para a melhoria da saúde pública e a proteção ambiental.

 
# Especificações do Projeto

As especificações do projeto de monitoramento da qualidade do ar incluem uma série de componentes técnicos e operacionais necessários para garantir a eficácia e a precisão do sistema. As principais especificações são:

- <b>Rede de Estações de Monitoramento:</b> Implementação de uma rede de estações fixas e móveis estrategicamente distribuídas para cobrir áreas urbanas e rurais, com sensores capazes de medir diferentes poluentes atmosféricos como PM2.5, PM10, NO2, SO2, CO, O3, entre outros.

- <b> Tecnologia de Sensores: </b> Utilização de sensores de alta precisão e sensibilidade, calibrados regularmente, para garantir a acurácia dos dados coletados. Os sensores devem ser capazes de operar em diferentes condições ambientais e fornecer dados em tempo real.
  
- <b> Plataforma de Análise de Dados: </b> Desenvolvimento de uma plataforma de software para a análise e visualização dos dados coletados. Esta plataforma deve oferecer ferramentas para a análise estatística, modelagem preditiva, mapeamento geoespacial e geração de relatórios.



## Critérios de Sucesso

Os critérios de sucesso para o projeto de monitoramento da qualidade do ar são fundamentais para avaliar a eficácia e o impacto do projeto. Alguns critérios essenciais incluem:

- <b> Precisão e Confiabilidade dos Dados:  </b> Os sensores devem fornecer dados precisos e confiáveis sobre a concentração de poluentes. A validação regular e a calibração dos sensores são cruciais para garantir a acurácia das medições.

- <b> Cobertura Geográfica Abrangente:  </b> A rede de estações de monitoramento deve cobrir todas as áreas críticas, incluindo zonas urbanas densamente povoadas e áreas rurais susceptíveis à poluição. A distribuição estratégica das estações é essencial para uma avaliação completa da qualidade do ar.

- <b> Tempo de Resposta Rápido: </b> O sistema deve ser capaz de transmitir dados em tempo real ou quase em tempo real para as plataformas de análise e para o público. Uma resposta rápida é crucial para a emissão de alertas e a implementação de medidas mitigadoras.

- <b> Integração com Políticas Públicas: </b> Os dados coletados devem ser utilizados efetivamente por autoridades e formuladores de políticas para desenvolver e implementar regulamentos ambientais que reduzam a poluição do ar e protejam a saúde pública.

## Histórias de Usuários


|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Cidadão preocupado  | Acessar os dados de qualidade do ar em tempo real    | Saber se é seguro sair de casa          |
|Cidadão preocupado      | Receber alertas de poluição alta	               | Tomar medidas preventivas para proteger minha saúde|
| Administrador municipal                    | Visualizar mapas de poluição                                    | Planejar ações para reduzir a poluição em áreas críticas         |
| Pesquisador                                | Acessar dados históricos de qualidade do ar                     | Analisar tendências e padrões de poluição                        |
| Pesquisador                                | Exportar dados em formatos compatíveis                          | Realizar análises detalhadas e publicar estudos                  |
| Responsável por políticas                  | Receber relatórios mensais de qualidade do ar                   | Avaliar a eficácia das políticas ambientais implementadas        |
| Engenheiro de sistemas                     | Manter a infraestrutura do sistema de monitoramento             | Garantir a disponibilidade e precisão dos dados coletados        |
| Educador                                   | Acessar materiais educativos sobre poluição do ar               | Informar e sensibilizar estudantes sobre a importância da qualidade do ar |
| Profissional da saúde                      | Consultar dados de poluição específicos de locais e horários    | Correlacionar dados de saúde com níveis de poluição              |
| Desenvolvedor de aplicativos               | Integrar os dados de qualidade do ar com outras aplicações      | Fornecer funcionalidades adicionais aos usuários finais          |
| Jornalista                                 | Obter dados atualizados e históricos sobre a qualidade do ar    | Publicar matérias informativas e de conscientização              |
| Morador de áreas urbanas                   | Saber a qualidade do ar no meu bairro                           | Tomar decisões sobre atividades ao ar livre                      |
| Morador de áreas rurais                    | Monitorar a qualidade do ar na minha região                     | Identificar possíveis fontes de poluição                         |
| Ativista ambiental                         | Divulgar dados de poluição para a comunidade                    | Mobilizar ações coletivas e pressionar por mudanças políticas    |
| Motorista                                  | Verificar a qualidade do ar nas rotas que utilizo               | Planejar rotas alternativas para evitar áreas poluídas           |
| Paciente com problemas respiratórios       | Acompanhar a qualidade do ar diariamente                        | Minimizar a exposição a poluentes e prevenir crises              |
| Empresa de transporte                      | Monitorar a qualidade do ar em áreas de operação                | Planejar medidas para reduzir a emissão de poluentes             |
| Operador de estação de monitoramento       | Manter e calibrar os sensores de qualidade do ar                | Assegurar a precisão e a confiabilidade dos dados                |
| Comunidade escolar                         | Consultar a qualidade do ar antes das atividades externas       | Garantir a segurança e saúde dos estudantes                      |
| Turista                                    | Verificar a qualidade do ar antes de visitar uma área           | Planejar viagens com base na segurança e conforto                |
| Responsável por obras públicas             | Monitorar o impacto das obras na qualidade do ar                | Minimizar a poluição durante grandes projetos de construção      |




## Requisitos Preliminares
Os requisitos preliminares fornecem uma visão inicial do escopo, funcionalidades-chave e as expectativas a serem atendidas.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
| RF-001 | Permitir que o usuário acesse dados de qualidade do ar em tempo real                                 | ALTA       |
| RF-002 | Enviar alertas automáticos aos usuários quando níveis de poluição ultrapassarem limites pré-definidos | ALTA       |
| RF-003 | Exibir mapas de poluição atualizados regularmente                                                     | ALTA       |
| RF-004 | Armazenar e disponibilizar dados históricos de qualidade do ar                                        | ALTA       |
| RF-005 | Permitir a exportação de dados em formatos compatíveis como CSV e Excel                                | MÉDIA      |
| RF-006 | Gerar relatórios mensais automáticos sobre a qualidade do ar                                          | ALTA       |
| RF-007 | Oferecer uma plataforma de visualização de dados com ferramentas de análise estatística              | ALTA       |

### Requisitos Não Funcionais

......  ATUALIZE OS REQUISITOS NÃO FUNCIONAIS DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                            |Prioridade |
|-------|-------------------------------------------------------------------|-----------|
| RNF-001| O sistema deve ser acessível via web e dispositivos móveis (iOS e Android)                                     | ALTA       |
| RNF-002| O sistema deve garantir a transmissão de dados em tempo real com uma latência máxima de 5 segundos            | ALTA       |
| RNF-003| O sistema deve possuir alta disponibilidade, com uptime de 99,9%                                               | ALTA       |
| RNF-004| O sistema deve assegurar a precisão dos dados coletados, com calibração regular dos sensores                   | ALTA       |
| RNF-005| O sistema deve ser escalável para suportar um aumento no número de estações de monitoramento e usuários       | ALTA       |
| RNF-006| O sistema deve garantir a segurança dos dados coletados e armazenados, com criptografia de dados em trânsito e em repouso | ALTA       |
| RNF-007| O sistema deve ter uma interface intuitiva e de fácil uso para todos os tipos de usuários                    | ALTA       |
| RNF-008| O sistema deve permitir a recuperação rápida em caso de falha, com um tempo de recuperação máximo de 1 hora   | ALTA       |
| RNF-009| O sistema deve suportar múltiplos idiomas para atender a uma base de usuários diversificada                   | ALTA       |
| RNF-010| O sistema deve ser compatível com padrões internacionais de qualidade do ar e regulamentos ambientais         | ALTA       |



### Restrições

......  ATUALIZE AS RESTRIÇÕES DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
| RE-001 | O sistema deve ser desenvolvido utilizando a linguagem Python      | ALTA       |
| RE-002 | A equipe de desenvolvimento deve seguir a metodologia ágil Scrum   | ALTA       |
| RE-003 | O orçamento total do projeto é limitado a $100.000                | ALTA       |
| RE-004 | O sistema deve estar em conformidade com as regulamentações de proteção de dados GDPR | ALTA       |
| RE-005 | O prazo de entrega do projeto é de seis meses                      | ALTA       |

# Partes Interessadas

No projeto Airguard, as partes interessadas incluem uma variedade de indivíduos e entidades que têm interesse direto ou indireto no sucesso e nos resultados do projeto. Abaixo estão algumas das partes interessadas identificadas, juntamente com seu nível de influência e possível importância para o sucesso do projeto:

1. **Governo Municipal**
   - *Expectativas:* Espera-se que o projeto contribua para o cumprimento das regulamentações ambientais e para a proteção da saúde pública.
   - *Nível de Influência:* Alto
   - *Importância:* Crucial, pois o governo municipal é responsável por políticas e ações relacionadas ao meio ambiente e à saúde pública.

2. **Moradores Locais**
   - *Expectativas:* Eles esperam que o projeto forneça informações precisas sobre a qualidade do ar em suas áreas e contribua para um ambiente mais saudável.
   - *Nível de Influência:* Médio a Alto
   - *Importância:* Significativa, pois os moradores locais serão diretamente impactados pela qualidade do ar em suas comunidades.

3. **Empresas e Indústrias Locais**
   - *Expectativas:* Podem estar interessadas em monitorar e mitigar sua própria emissão de poluentes, além de usar os dados do projeto para cumprir regulamentações ambientais.
   - *Nível de Influência:* Médio
   - *Importância:* Considerável, especialmente se forem grandes fontes de poluição na área.

4. **Pesquisadores e Acadêmicos**
   - *Expectativas:* Eles podem usar os dados do projeto para estudos e análises relacionadas à qualidade do ar e seus impactos na saúde e no meio ambiente.
   - *Nível de Influência:* Baixo a Médio
   - *Importância:* Considerável, pois sua pesquisa pode fornecer insights valiosos e contribuir para o avanço do conhecimento sobre o assunto.


# Estimativa de Custo e Prazo

## Estimativa de Custo

......  COLOQUE AQUI O SEU TEXTO ......

> A avaliação da viabilidade econômica busca determinar a sustentabilidade financeira e o retorno sobre o investimento do empreendimento. 
> Este processo envolve a análise dos custos associados ao projeto, incluindo investimentos iniciais, despesas operacionais e potenciais custos de manutenção. 
> Simultaneamente, são examinados os benefícios esperados, como receitas, economias de custos e ganhos tangíveis e intangíveis. 
> A elaboração de projeções financeiras realistas e a aplicação de métricas como o Valor Presente Líquido (VPL) e a Taxa Interna de Retorno (TIR) contribuem para uma avaliação abrangente da viabilidade econômica do projeto. 
> Este processo permite que os gestores de projeto e as partes interessadas tomem decisões informadas sobre a continuidade, ajustes ou mesmo a interrupção do projeto, garantindo uma alocação eficiente de recursos e maximizando os benefícios econômicos esperados.

......  ATUALIZE OS ITENS DE CUSTO DO SISTEMA. ADICIONE NOVOS OU SUBDIVIDA ITENS, CASO NECESSÁRIO ......

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        | Desenvolvimento de software, gerenciamento do projeto      | 1000       | $50          | $50,000     |
| Hardware                | Sensores de qualidade do ar, equipamentos de monitoramento | -          | -            | $20,000     |
| Serviços de Rede        | Configuração de rede, comunicação de dados                 | 200        | $80          | $16,000     |
| Hospedagem e Nuvem      | Servidores, armazenamento em nuvem                          | -          | -            | $15,000     |
| Software de terceiros   | Licenças de software de análise e visualização de dados    | -          | -            | $10,000     |
| Serviços e treinamento  | Consultoria especializada, treinamento de usuários         | 100        | $100         | $10,000     |
| **Total Geral**         |                                                            |            |              | **$121,000**|


## Estimativa de Prazo

......  COLOQUE AQUI O SEU TEXTO ......

> A estimativa de prazo orienta tanto o cliente quanto a equipe de desenvolvimento do projeto em termos do tempo necessário para a conclusão do projeto como um todo. 
> Esta estimativa possibilita a criação de um cronograma realista e viável, permitindo o planejamento adequado das fases do projeto, alocação de recursos de maneira eficiente e antecipação de eventuais desafios.
> Uma estimativa precisa orienta a execução do projeto, contribui para a gestão de expectativas e para o estabelecimento de metas alcançáveis.

> Indique:
> * Prazo previsto (em horas) 
> * Data de início
> * Data de término

# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, a divisão de papéis e tarefas e as ferramentas empregadas.
>
> Coloque detalhes sobre o processo utilizado e a implementação do Framework Scrum seguido pelo grupo. 
> O grupo deverá gerenciar as tarefas utilizando o GitHub Project para acompanhar o andamento do projeto, a execução das tarefas e o status de desenvolvimento da solução.
> 
> **Links Úteis**:
> - [Github Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project)
> - [O que é o GitHub Projects? | Guia de Iniciantes](https://www.youtube.com/watch?v=vxYTpsFKdiQ&ab_channel=JulioArruda)
> - [Introduction to GitHub Project Boards](https://www.youtube.com/watch?v=idZyqNIrt84&list=PLiO7XHcmTslc5hGrbnnmHIb0SeJLTpOEu&ab_channel=MickeyGousset)
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
> Indique as responsabilidades de cada membro do grupo no projeto.

## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

> Liste as ferramentas empregadas no desenvolvimento do projeto, justificando a escolha delas, sempre que possível.
> Todas as ferramentas utilizadas devem ser listadas.
> Qualquer tipo de ferramenta que for utilizada para construção de um artefato deve ser identificada, uma vez que podem ser necessárias alterações.
> A necessidade de uso de licenças e possíveis custos relacionados devem ser indicados.

| Ambiente              | Plataforma         | Link de Acesso             | Justificativa |
|-----------------------|--------------------|----------------------------|---------------|
| Quadro Kanban         | Github             | https://github.com/XXXXXXX | Centralização e organização do projeto no próprio repositório. |
| Repositório de código | GitHub             | https://github.com/XXXXXXX |               |
| Protótipo Interativo  | MavelApp ou Figma  | https://figma.com/XXXXXXX  |               |
| Documentos Textuais   | LibreOffice Writer | N/A                        |               |
| Planilhas e Gráficos  | Google Planilhas   | https://docs.google.com/   |               |
| EAP / WBS             | | | |
| Cronograma do Projeto | | | |
| Matriz RACI           | | | |

# Documentos

> Esta seção deve ser utilizada para armazenamento e listagem dos documentos e artefatos produzidos durante as aulas.
> Atualize os documentos nos respectivos links.

## Declaração de Escopo

> Você deve preencher o seguinte documento:
- [Declaração de Escopo](artefatos/declaracao-escopo.docx)

## Registro de Partes Interessadas

> Você deve preencher o seguinte documento:
- [Registro de Partes Interessadas](artefatos/registro-partes-interessadas.xlsx)

## Termo de Abertura do Projeto (TAP)

> O Termo de Abertura do Projeto (TAP) representa o ponto de partida oficial para o empreendimento. 
> Ele sintetiza de maneira clara e concisa os objetivos, escopo, partes interessadas envolvidas, entregas esperadas, cronograma preliminar e recursos necessários para a execução bem-sucedida do projeto. 
> O TAP funciona como um contrato inicial entre a equipe do projeto e as partes interessadas, estabelecendo as bases para uma compreensão compartilhada dos propósitos e limites do projeto. 
> Ao delinear esses elementos de forma detalhada, o Termo de Abertura do Projeto (TAP) fornece uma direção sólida para orientar as atividades subsequentes, facilitando a gestão eficaz do projeto desde o início até o encerramento. 
> Essa documentação garante a clareza, alinhamento e comprometimento de todos os envolvidos, contribuindo assim para o sucesso do projeto.

> Você deve preencher o seguinte documento:
> - [Termo de Abertura do Projeto](artefatos/termo-abertura-projeto.docx)
