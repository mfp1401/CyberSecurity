# Estudo de Caso: Ataque Cibernético à Change Healthcare (2025)

## 1. Contexto

Em **janeiro de 2025**, foi confirmado um grande ataque cibernético envolvendo a empresa **Change Healthcare**, uma das principais empresas de tecnologia do setor de saúde nos Estados Unidos. A empresa pertence ao grupo **UnitedHealth Group** e é responsável por processar pagamentos, dados médicos e informações de seguros entre hospitais, clínicas, farmácias e seguradoras.

O ataque foi realizado por um grupo de ransomware conhecido como **ALPHV/BlackCat**, que já é conhecido por atacar grandes empresas e instituições.

Após as investigações, foi divulgado que aproximadamente **192 milhões de pessoas tiveram seus dados de saúde expostos**, tornando esse incidente o **maior vazamento de dados de saúde da história dos Estados Unidos**.

Além do vazamento de dados, diversos sistemas utilizados por hospitais e farmácias ficaram temporariamente indisponíveis, causando atrasos em pagamentos, prescrições médicas e outros serviços importantes do sistema de saúde.



## 2. Ambiente afetado

O ataque afetou principalmente a infraestrutura digital da **Change Healthcare**, que funciona como uma plataforma intermediária entre diversas organizações do sistema de saúde.

Entre os sistemas afetados estavam:

- servidores de processamento de dados médicos  
- sistemas de faturamento e pagamento de seguros  
- sistemas de autorização de procedimentos médicos  
- redes internas da empresa  
- plataformas utilizadas por hospitais e farmácias para comunicação com seguradoras  

Como milhares de instituições médicas dependem desses sistemas, a interrupção afetou uma grande parte da infraestrutura de saúde dos Estados Unidos.



## 3. Vetor de ataque

A investigação mostrou que o acesso inicial dos invasores ocorreu por meio de um **portal de acesso remoto da empresa que não possuía autenticação multifator (MFA)**.

Os criminosos conseguiram acessar o sistema utilizando **credenciais válidas de usuário e senha**. Como não havia uma segunda camada de verificação, os atacantes conseguiram entrar na rede da empresa com mais facilidade.

Essa falha de segurança permitiu que os invasores obtivessem acesso inicial à infraestrutura da organização.



## 4. Cadeia do ataque

Depois de obter acesso à rede, os invasores começaram a explorar os sistemas internos da empresa.

Primeiro, eles analisaram a estrutura da rede para identificar servidores importantes e contas com privilégios administrativos. Em seguida, realizaram **movimentação lateral**, acessando outros sistemas dentro da rede.

Durante essa etapa, os atacantes coletaram informações e copiaram grandes quantidades de dados sensíveis.

Após comprometer os sistemas principais, os criminosos executaram o **ransomware**, que criptografou servidores e sistemas da empresa. Antes disso, os dados foram extraídos, permitindo que os atacantes utilizassem essas informações para extorsão.

Esse tipo de estratégia é comum em ataques modernos de ransomware.



## 5. Impacto

O ataque teve um impacto muito grande tanto do ponto de vista técnico quanto operacional.

Entre as principais consequências estão:

- interrupção de sistemas de faturamento médico  
- atraso em pagamentos para hospitais e clínicas  
- dificuldades em farmácias para processar prescrições médicas  
- exposição de dados pessoais e médicos de milhões de pacientes  

Informações como nomes, datas de nascimento, endereços, registros médicos e dados de seguro de saúde foram comprometidas.

Além disso, o incidente causou prejuízos financeiros significativos e afetou o funcionamento do sistema de saúde em várias regiões dos Estados Unidos.



## 6. Resposta e recuperação

Após identificar o ataque, a empresa iniciou diversas ações para conter o incidente.

Entre as medidas adotadas estavam:

- desligamento de sistemas comprometidos  
- isolamento da rede para impedir a propagação do ataque  
- realização de investigação forense para entender como ocorreu a invasão  
- cooperação com autoridades e especialistas em cibersegurança  

A empresa também trabalhou na restauração gradual dos sistemas afetados e na reconstrução da infraestrutura comprometida.

Durante o processo de recuperação, novas medidas de segurança foram implementadas para reduzir o risco de novos incidentes.



## 7. Lições aprendidas

O incidente mostrou várias lições importantes para a área de cibersegurança.

Uma das principais foi a importância da **autenticação multifator (MFA)** em sistemas de acesso remoto. A ausência desse mecanismo facilitou o acesso inicial dos invasores.

Outra lição importante é a necessidade de monitoramento constante da rede para identificar atividades suspeitas rapidamente.

Também ficou evidente a importância de proteger melhor sistemas críticos e separar redes internas para evitar que um invasor tenha acesso a toda a infraestrutura.

Além disso, o caso demonstrou como ataques de ransomware podem causar impactos graves não apenas em sistemas digitais, mas também em serviços essenciais, como o sistema de saúde.