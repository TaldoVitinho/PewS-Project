# PEWS - Pediatric Early Warning System

O **PEWS** é um sistema de alerta precoce para monitoramento de pacientes pediátricos, projetado para auxiliar profissionais de saúde na identificação de sinais de deterioração clínica. Este projeto inclui funcionalidades como treinamento, suporte, notificações personalizadas, gestão de medicamentos e gráficos de comorbidades.

## Funcionalidades Principais

1. **Treinamento e Simulação de Uso da PEWS**
   - Módulos interativos para treinamento de profissionais de saúde.
   - Simulações de cenários clínicos para prática do uso do sistema.

2. **Suporte (Feedback e Suporte)**
   - Canal integrado para feedback dos usuários.
   - Suporte técnico para resolução de problemas.

3. **Notificações Personalizadas**
   - Alertas customizáveis com base no estado clínico do paciente.
   - Notificações em tempo real para a equipe médica.

4. **Gestão de Medicamentos**
   - Controle de prescrições e administração de medicamentos.
   - Alertas para interações medicamentosas e doses incorretas.

5. **Gráfico de Comorbidade do Paciente**
   - Visualização gráfica das comorbidades e histórico clínico.
   - Análise de tendências para auxiliar na tomada de decisões.


## Padrão de Projeto


   Neste projetos estamos utilizando o padrão de prjeto Model-View-Controller (MVC), o padrão de projeto MVC é um padrão de arquitetura de software amplamente utilizado para desenvolvimento de softwares, especialmente aqueles com interfaces gráficas. Ele separa a aplicação em três componentes principais, cada um com uma responsabilidade distinta: 
   
   * Model (Modelo):
      - Representa a lógica de negócios e os dados da aplicação;
      - Gerencia as regras, a lógica e os dados do sistema;
      - É independente da interface do usuário, o que significa que ele não sabe como os dados serão exibidos ou manipulados.

   * View (Visão):
      - Representa a interface do usuário (UI);
      - Exibe os dados do Model para o usuário e envia as interações do usuário (como cliques ou entradas de formulário) para o Controller;
      - Pode ser atualizada automaticamente quando o Model muda, geralmente através de um mecanismo de observação.

   * Controller (Controlador):
      - Atua como intermediário entre o Model e a View.
      - Recebe as entradas do usuário da View, processa essas entradas (possivelmente atualizando o Model) e retorna a View apropriada.
      - Contém a lógica para manipular as interações do usuário e atualizar o Model e a View conforme necessário.

   Algumas das vantagens que fazem o MVC ser comumente utilizado em interfaces gráficas nas aplicações, é que a View pode ser alterada sem afetar diretamento o Model,  permitindo a reutilização do código; a separação clara entre os componentes, permite testar cada parte de forma isolada facilitando a parte de teste; o MVC também serapara a responsabilidade de cada componente de forma clara, facilitando a manutenção e a escalabilidade.

   O MVC foi utilizada na nossa tela de LOGIN.


## Como Abrir a Página WEB

   1° Devemos instalar a pasta Projeto_PEWS.rar;
   
   2° Descompactar o arquivo RAR Projeto_PEWS.rar gerando a pasta Projeto_PEWS;
   
   3° Abrir a pasta Projeto_PEWS, e abrir o arquivo Index.html ou arrastar o arquivo Index.html até a página do navegador. O arquivo Index.html é a página incial da Página WEB.
