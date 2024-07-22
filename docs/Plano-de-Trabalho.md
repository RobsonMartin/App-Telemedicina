# PLANO DE TRABALHO
___

| Nome do Projeto:|  MediPortal App   |
|-----------------|-------------------|
| Versão:         | 2.2               |
| Status:         |Em andamento       |
|Coordenador do Projeto:| Andrey Rodrigues|


## HISTÓRICO DE VERSÕES

|Versão| Descrição | Autor | Data |
|------|-----------|-------|------|
|1.0   |Elaboração do Plano de Trabalho| Gabriel, Kaic, Luanny, Fran, Rebeca  | 26/05 |
|1.1   |Introdução| Gabriel e Luanny | 26/05 |
|1.2   |Informações Gerais| Luanny, Rebeca e Kaic | 27/05 |
|1.3   |Escopo Geral| Fran Robson | 30/05 |
|1.4   |Escopo Específico e Escopo Negativo| Rebeca e Kaic | 01/06 |
|1.5   |Ambiente de Desenvolvimento| Fran Robson e Gabriel | 04/06 |
|1.6   |Características Inovadoras| Gabriel, Kaic, Luanny, Fran e Rebeca | 04/06 |
|1.7   |Implementação de GitHub| Fran Robson | 09/06 |
|1.8   |Revisão Geral| Gabriel, Luanny, Fran, Kaic e Rebeca | 10/06 |
|1.9   |Criamento de personas e user story|Gabriel, Luanny, Fran, Kaic e Rebeca| 17/06|
|2.0   |Inspeção dos requisitos| Gabriel, Luanny, Fran, Kaic e Rebeca | 03/07|
|2.1   |Elaboração dos diagramas e modelo C4| Gabriel, Luanny, Fran, Kaic e Rebeca| 16/07|
|2.2   |Criação das issues no GitHub|Luanny, Fran| 16/07|
___

## ÍNDICE

___

## 1. INTRODUÇÃO

 No contexto atual de transformação digital, a área da saúde enfrenta desafios significativos
 que demandam soluções inovadoras para melhorar a eficiência e a qualidade do
 atendimento médico. Com o avanço da tecnologia, a telemedicina surge como uma
 resposta promissora para essas necessidades. Este projeto tem como objetivo desenvolver
 um aplicativo de telemedicina que permite aos pacientes marcar consultas médicas online,
 enviar exames, acessar seus prontuários e acompanhar a fila de atendimento.
 Simultaneamente, o aplicativo fornecerá aos médicos ferramentas avançadas para
 gerenciar seus horários e o histórico de consultas dos pacientes.
 
 ### 1.1. Objetivo
   
 Desenvolver um aplicativo para telemedicina que permite aos pacientes marcar consultas
 médicas online, enviar exames, ver seus prontuários, e acompanhar a fila de atendimento,
 enquanto oferece aos médicos ferramentas para gerenciar seus horários e histórico de
 consultas dos pacientes, é uma solução abrangente e inovadora no campo da saúde digital.
 Esse tipo de aplicativo pode revolucionar a maneira como os serviços de saúde são
 prestados e geridos, proporcionando conveniência e eficiência tanto para pacientes quanto
 para médicos.
 
 ### 1.2. Motivação, Justificativa e Oportunidade
 
 A motivação por trás deste projeto é a crescente demanda por soluções de saúde mais
 acessíveis e eficientes, especialmente em um contexto onde a tecnologia digital
 desempenha um papel cada vez mais importante. A justificativa para o desenvolvimento
 deste aplicativo reside na necessidade de proporcionar uma experiência mais conveniente e
 ágil para os pacientes, ao mesmo tempo em que otimiza a gestão de consultas para os
 profissionais de saúde. A oportunidade apresentada pela telemedicina é significativa,
 oferecendo a possibilidade de melhorar a eficiência dos serviços de saúde ao permitir
 consultas médicas remotas e acessíveis a um número maior de pessoas.
 
 ### 1.3. Caracterização do Projeto:
 
#### 1.3.1. Classe

 |  Classe  |  Detalhamento  |
 |----------|----------------|
 | Aplicativo Móvel | Aplicativo desenvolvido para plataformas iOS e Android, com funcionalidades de marcação de consultas, envio de exames, visualização de prontuários e acompanhamento da fila de atendimento.|
 
 #### 1.3.2. Enquadrabilidade
 
 | Enquadrabilidade | Detalhamento |
 |------------------|--------------|
 |Aplicativo de Telemedicina| O aplicativo será desenvolvido em conformidade com as regulamentações do Conselho Federal de Medicina(CFM), a Lei Geral de Proteção de Dados(LGPD), normas internacionais de segurançada informação (ISO27001), padrões técnicos de saúde (HL7eDICOM), e diretrizes de acessibilidade digital (WCAG), garantindo práticas médicas legítimas, segurança e privacidade dos dados,interoperabilidade e acessibilidade para todos os usuários.|

 #### 1.3.3. Tipo
 
 | Tipo |     | Detalhamento |
 |------|-----|--------------|
 |Desenvolvimento|Software| Criação de um aplicativo com backend em nuvem, interface de usuário responsiva e intuitiva,integração com sistemas de saúde(HL7,DICOM), suporte a video chamadas para teleconsultas, e funcionalidades para envio seguro de exames e acesso a prontuários.
 ___
 ## 2.INFORMAÇÕES GERAIS
 
 ### 2.1. Objetivo
 
 O objetivo principal deste projeto é desenvolver um aplicativo de telemedicina que ofereça
 aos pacientes a conveniência de marcar consultas médicas online, enviar exames, acessar
 prontuários médicos, visualizar a fila de atendimento, enquanto também permite aos
 médicos gerenciar seus horários e o histórico de consultas dos pacientes.
 
 ### 2.2. Escopo Geral
 
 O escopo geral deste projeto abrange a criação de um aplicativo de telemedicina que
 possibilitará consultas médicas remotas, o envio de exames, o acesso a prontuários
 médicos e a gestão de horários para pacientes e médicos, proporcionando uma solução
 abrangente e integrada para as necessidades de saúde.
 
 #### 2.2.1. Escopo Específico
 
 - Marcação de consultas médicas online;
 - Envio de exames para análise;
 - Acesso a prontuários médicos;
 - Gestão de filas de atendimento;
 - Gerenciamento de horários para médicos.
 
 #### 2.2.2. Escopo Negativo
 
 - Não inclui diagnóstico médico automático;
 - O aplicativo não substituirá a avaliação médica presencial, apenas facilitará o acesso aos serviços de saúde;
 - Não oferece suporte para casos de emergência médica;
 - Os pacientes poderão apenas marcar consultas, enquanto o pagamento será realizado de acordo com as políticas de cobrança do consultório médico;
 - Não será fornecido suporte para dispositivos móveis ou navegadores web desatualizados;
 - Não abrange tratamento médico via aplicativo, apenas consultas e
acompanhamento.

### 2.3. Ambiente de Desenvolvimento

|                             | Ferramentas e Tecnologias      |
|-----------------------------|--------------------------------|
| Tipo                        | Modelo e Especificações        |
| GitHub (repositório remoto) | Modelo: Plataforma de hospedagem de código-fonte baseada em Git. Especificações: Oferece controle de versão, rastreamento de problemas e colaboração para projetos de software. |                               
| Canva (logo) |Modelo: Ferramenta online de design gráfico. Especificações: Facilita a criação de logotipos e outros materiais visuais, oferecendo modelos e elementos gráficos variados. |
| Figma (prototipagem) |Modelo: Ferramenta de design de interface do usuário baseada na nuvem. Especificações: Permite criar protótipos interativos e designs responsivos, com recursos de colaboração em tempo real e integração com outras ferramentas de design e desenvolvimento. |



### 2.4. Características Inovadoras do Projeto:

- Monitoramento Remoto em Tempo Real: Ferramentas para acompanhamento contínuo de sinais vitais dos pacientes, com alertas automáticos para os médicos;
- Interface de Usuário Intuitiva e Responsiva: Design focado na experiência do usuário, adaptável a diversos dispositivos (smartphones, tablets e desktops);
- Segurança Avançada de Dados: Implementação de criptografia ponta a ponta e autenticação multifatorial para proteger informações médicas sensíveis;
- Interoperabilidade com Diversos Sistemas de Saúde: Compatibilidade com padrões como HL7 e DICOM para facilitar a troca de informações médicas entre diferentes plataformas e dispositivos;
- Fila de Atendimento Dinâmica e Transparente: Visualização em tempo real do
status na fila de atendimento, permitindo aos pacientes acompanhar a previsão de tempo de
espera.

### 2.5. Resultados Esperados

Os resultados esperados deste projeto incluem a redução do tempo de espera para consultas
médicas, o aumento da eficiência na gestão de horários dos médicos e a melhoria geral na
acessibilidade aos serviços de saúde, proporcionando uma experiência mais conveniente e
eficaz para todos os envolvidos.
___
## 3. METODOLOGIA DE PROJETO

### 3.1. Estrutura do Projeto

- Gerente de Projeto;
- Equipe de Desenvolvimento;
- Equipe de Design;
- Equipe de Testes.

### 3.2 Equipe de Projeto: Papéis e Responsabilidades dos Integrantes

| Responsabilidade | Profissional |
|------------------|--------------|
| **Gerente de Projeto**: Responsável pela coordenação geral, assegurando a conclusão das fases no prazo e dentro do orçamento, além de mediar a comunicação entre as equipes. |  Gabriel Batista  |
| **Equipe de Desenvolvimento**: **Desenvolvedores de Backend**: Construção e manutenção do servidor, banco de dados e APIs em nuvem. **Desenvolvedores de Frontend**: Criação da interface de usuário responsiva e intuitiva. **Especialistas em Integração**: Garantem a compatibilidade do sistema com padrões de saúde como HL7 e DICOM. | Luanny Victoria, Fran Robson, Kaic Tavares |
| **Equipe de Design**: Designers de UX/UI: Criam interfaces que priorizam a experiência do usuário. Especialistas em Acessibilidade: Asseguram que o aplicativo atenda às diretrizes de acessibilidade digital (WCAG). | Rebeca Isabelly, Kaic Tavares |
| **Equipe de Testes**: Testadores de Qualidade: Realizam testes de funcionalidade, segurança e desempenho para identificar e corrigir problemas. | Gabriel Batista, Luanny Victoria, Fran Robson |


### 3.3 Fases, Atividades e Cronograma

-	Fase I: Especificação:
    - Planejamento Inicial: Estabelecer cronograma, recursos necessários e alocação da equipe para as diferentes tarefas.

    - Criação das Personas: Identificação dos principais usuários do aplicativo, focando no ambiente hospitalar, como Médicos e Pacientes, considerando suas necessidades e expectativas no uso do aplicativo de telemedicina.
  
    - Definição dos Requisitos: Realização de reuniões com a equipe para levantar as funcionalidades essenciais, detalhamento das funcionalidades principais como agendamento de consultas, envio de exames, acesso a prontuários, fila de atendimento, e gerenciamento de horários.
    - Priorização dos requisitos com base no objetivo principal: facilitar a consulta e exames como necessidades fundamentais dos pacientes.

    - Resultado Esperado: Documento de Especificação de Requisitos detalhado, contendo as personas e uma lista priorizada das funcionalidades.
  
- Fase II: Inspeção:
    - Revisão dos artefatos: Avaliar e validar requisitos e planejamento inicial.
      
-	Fase III: Projeto e Arquitetura:
    - Design da arquitetura do sistema: Definir estrutura do sistema e integração.
    - Criação de wireframes: Elaborar wireframes para as principais telas do aplicativo.

- Fase IV: Prototipagem e Refinamento:
   - Desenvolvimento do protótipo inicial: Criar protótipo funcional com as principais funcionalidades.
   - Feedback e ajustes: Coletar feedback de usuários e ajustar o protótipo.
     
-	Fase V: Prototipagem e Refinamento:
    - Testes de usabilidade: Realizar testes com usuários para identificar melhorias
    - Implantação nos servidores de produção e distribuição nas lojas de aplicativos.
     
-	Fase VI: Encerramento:
    - Implementação final: Finalizar ajustes e lançar a versão completa do aplicativo.

### 3.4. Entregas de cada Fase

|  Fase  |  Mês  |  Entregável  |
|--------|-------|--------------|
| I.	Especificação | Junho  | Especificação de Requisitos  |
| II.	Inspeção     | Julho  | Avaliar e validar requisitos |
| III.	Projeto e Arquitetura |    Julho  | Elaborar os diagramas |
| IV.	Prototipagem e Refinamento |   Julho     | Crição do protótipo e testes de usabilidade|
| V.	Encerramento  |  Junho      |              |


4. REFERÊNCIAS
   
Conselho Federal de Medicina (CFM)BRASIL. Conselho Federal de Medicina. Portal do CFM. Disponível: [aqui](<https://portal.cfm.org.br/>) . Acesso em: 03 jun. 2024.

Lei Geral de Proteção de Dados (LGPD)BRASIL. Lei nº 13.709, de 14 de agosto de 2018. Lei Geral de Proteção de Dados Pessoais. Disponível: [aqui](<https://www.gov.br/lgpd.>) Acesso em: 03 jun. 2024.

ISO 27001INTERNATIONAL ORGANIZATION FOR STANDARDIZATION. ISO/IEC 27001:2013 - Information technology - Security techniques - Information security management systems - Requirements. Disponível: [aqui](<https://www.iso.org/isoiec-27001-information-security.html.>)  Acesso em: 03 jun. 2024.

Health Level Seven International (HL7)HL7 INTERNATIONAL. Health Level Seven International. Disponível: [aqui](<https://www.hl7.org/.>) Acesso em: 03 jun. 2024.

Digital Imaging and Communications in Medicine (DICOM)DICOM STANDARDS COMMITTEE. DICOM Standard. Disponível: [aqui](<https://www.dicomstandard.org/.>) Acesso em: 03 jun. 2024.

Web Content Accessibility Guidelines (WCAG)WORLD WIDE WEB CONSORTIUM (W3C). Web Content Accessibility Guidelines (WCAG) Overview. Disponível: [aqui](<https://www.w3.org/WAI/standards-guidelines/wcag/.>)  Acesso em: 03 jun. 2024.

GitHubGITHUB. GitHub. Disponível: [aqui](<https://github.com/.>) Acesso em: 05 jun. 2024.

VS CodeMICROSOFT. Visual Studio Code. Disponível: [aqui](<https://code.visualstudio.com/.>)  Acesso em: 05 jun. 2024.

Android StudioANDROID DEVELOPERS. Android Studio. Disponível: [aqui](<https://developer.android.com/studio.>) Acesso em: 05 jun. 2024.

CanvaCANVA. Canva. Disponível: [aqui](<https://www.canva.com/.>)  Acesso em: 05 jun. 2024.

FigmaFIGMA. Figma. Disponível em: [aqui](<https://www.figma.com/.>)  Acesso em: 05 jun. 2024.
