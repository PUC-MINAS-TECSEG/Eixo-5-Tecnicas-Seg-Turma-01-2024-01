# Etapa 3 - Arcabouço para a Computação Forense e Perícia Digital

No contexto da segurança da informação, a perícia forense computacional busca investigar e analisar evidências digitais em casos de crimes cibernéticos, incidentes de segurança e fraudes eletrônicas. Em tempos de soluções digitais integradas ao cotidiano, onde a tecnologia é protagonista em várias esferas da sociedade, a necessidade de profissionais especializados em investigar e interpretar dados de sistemas computacionais torna-se imprescindível.

Nesta mesma direção, a atividade explora os fundamentos da perícia forense computacional aplicada a um cenário totalmente hipotético envolvendo um computador utilizado por um funcionário de uma empresa fictícia chamada TechGuard Solutions. Há suspeitas de que o funcionário estaria utilizando o computador e a internet da empresa para a mineração de criptomoeda, uma atividade proibida pelo regimento interno da empresa. Dessa forma, a direção da TechGuard Solutions solicitou uma análise detalhada do referido computador, com o objetivo de validar ou refutar essas suspeitas.

A análise forense do computador, obtido como evidência, pode revelar informações cruciais sobre como o usuário utilizava o dispositivo. Para amparar o desenvolvimento da prática de perícia, deverão ser exploradas técnicas e ferramentas para a extração de informações relevantes do disco rígido, rastreando possíveis documentos, imagens ocultas e sites suspeitos.


🚩 **ATENÇÃO:** É importante observar que a tecnologia de virtualização esteja habilitada no computador de trabalho (conforme instruções do fabricante).

## Para orientar a execução adequada das tarefas dessa etapa, são propostos os seguintes passos:

### Passo 1: Preparação

- Realize o download e a instalação da ferramenta de virtualização [Oracle VM VirtualBox](https://www.virtualbox.org/wiki/Downloads).
- Realize o download da VM disponibilizada para investigação.
    - [Evidência](https://drive.google.com/drive/folders/1Nl8wcKEji2c7UJMIjEpZlLWdsxZHiCqu?usp=sharing)

### Passo 2: Execução

- Acesse a VM carregando ou importando a imagem no [VirtualBox](https://www.virtualbox.org/).
- Inicie a VM e aguarde o carregamento do SO.
- Login na máquina virtual: Usuario/pucminas

#### Passo 2.1: Objetivos da tarefa:

>Utilizando de ferramentas que possam auxiliar na análise forense, em especial o Autopsy, os objetivos da tarefa são:

1. **Encontrar Indícios de Envolvimento com Criptomoeda**
   - Identificar qualquer evidência que sugira que o funcionário estava envolvido em atividades relacionadas à mineração de criptomoedas.

2. **Encontrar o Código em C**
   - Localizar o programa em C que, conforme alertado, pode estar sendo utilizado para a mineração de criptomoedas.

3. **Utilizar os Passos para Perícia Digital**
   - **Clonar a Imagem do Disco:**
     - Realizar a clonagem do disco rígido do computador suspeito para garantir a integridade das evidências.
   - **Análise da Imagem Clonada:**
     - Examinar a imagem clonada do disco rígido em busca de evidências de atividades de mineração e do código em C.
   - **Documentação das Evidências:**
     - Documentar todas as etapas do processo de investigação, incluindo a coleta, análise e interpretação das evidências.
   - **Relatório Final:**
     - Preparar um relatório detalhado apresentando as conclusões da investigação, incluindo a presença ou ausência de atividades de mineração de criptomoedas e a utilização do programa em C para essa finalidade.




### Passo 3: Relatório de Arquivos

- Documentando suas intervenções, analise as pastas, subpastas e o que achar mais necessário na VM.
- Produza o primeiro relatório apresentando os procedimentos e registros observados na analise dos arquivos.

### Passo 4: Relatório de Perícia do Artefato

- Documentando suas intervenções, elabore o relatório pericial, que é o artefato de interesse dessa avaliação.
- Tomando como referência o documento modelo de perícia disponibilizado (no material complementar), produza o segundo relatório apresentando os procedimentos, considerações e conclusões sobre o referido artefato.

### Passo 5: Vídeo

- Preferencialmente como screencast, elabore um vídeo (em formato MP4) para apresentar o desenvolvimento das atividades investigativas, com propósito de comentar a abordagem e identificar os principais procedimentos desenvolvidos nos Passos 3 e 4.

Ao final desta etapa, espera-se que os participantes tenham adquirido e consolidado conhecimentos sobre a prática de perícia forense computacional e a aplicação desse domínio de competências em um contexto específico e em ambiente incomum. Além disso, espera-se que desenvolvam habilidades analíticas e interpretativas que possam ser aplicadas em futuras investigações digitais, contribuindo para a proteção e segurança da era da informação.

Texto original elaborado pelo saudoso Prof. Cláudio Correa e adaptado pelo Prof. Diego Roberto.