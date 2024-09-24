# Tempo Otimizado
# Como deixar o tempo mais otimizado
## Equipe
- Dalton Henrique
- Lucas do Amaral Rodrigues
- Vitor de Freitas Rios

---

## Contexto do Projeto

Muitas pessoas enfrentam dificuldades para otimizar o tempo devido à sobrecarga de tarefas, falta de planejamento e distrações. Isso pode causar atrasos na rotina e uma sensação de improdutividade. O objetivo do nosso grupo é criar uma plataforma online que ajude os usuários a otimizar seu tempo, conectando-os a ferramentas e estratégias eficazes para melhorar a produtividade.

---

## Problema

- *Dificuldade em gerenciar o tempo*: Pessoas enfrentam desafios para organizar tarefas e prioridades, resultando em perda de produtividade e acúmulo de responsabilidades.
- *Impacto na qualidade de vida*: A falta de estratégias eficazes para otimizar o tempo pode resultar em estresse, esgotamento e sobrecarga.
- *Dificuldade de acesso a ferramentas*: Os usuários têm dificuldade em encontrar métodos e recursos confiáveis para melhorar sua gestão do tempo de forma prática.
- *Sobrecarga de responsabilidades*: O excesso de tarefas e a falta de organização resultam em longas listas, aumentando o tempo para concluir atividades importantes.

---

## Especificação do Projeto (Entrevistas dos Usuários)

*André Albuquerque*  
Desenvolvedor de software, 19 anos, tenta equilibrar trabalho, estudos e jogos eletrônicos. Quer organizar melhor seu tempo para se dedicar aos jogos sem comprometer a carreira.

*Aline Maia*  
Coordenadora, 43 anos, sobrecarregada com responsabilidades profissionais, resultando em estresse e queda de produtividade. Deseja equilibrar tarefas profissionais com tempo para relaxar e hobbies.

*Carlos Mendonça*  
Professor, 30 anos, tem dificuldades para encontrar tempo para seu hobby de restaurar carros clássicos, devido ao aumento das responsabilidades no trabalho. Busca gerenciar sua agenda para poder se dedicar mais ao hobby sem prejudicar a carreira.

---

## Objetivo do Projeto

- *Facilitar a otimização do tempo*: Criar uma plataforma online que ajude os usuários a organizar e gerenciar melhor seu tempo, conectando-os a ferramentas eficazes de produtividade.
- *Reduzir as dificuldades na gestão do tempo*: Oferecer uma maneira prática e acessível para os usuários planejarem suas atividades e alcançarem um equilíbrio entre trabalho e vida pessoal.

---

## Justificativa

- *Impacto positivo na produtividade*: Facilitar o acesso a ferramentas de gestão de tempo pode aumentar a eficiência, reduzir o estresse e melhorar a qualidade de vida dos usuários.
- *Redução da procrastinação*: A plataforma ajudará a superar barreiras que impedem uma gestão eficaz do tempo, fornecendo planejamento e priorização de tarefas.

---

## Público-Alvo

- *Fundamentais*: Profissionais que enfrentam dificuldades na gestão do tempo. Estudantes que precisam organizar suas rotinas de estudo.
- *Importantes*: Indivíduos que buscam melhorar sua produtividade e equilíbrio entre trabalho e vida pessoal.
- *Influenciadores*: Empresas que promovem o bem-estar de seus funcionários. Educadores que apoiam estudantes no gerenciamento do tempo.

---


### Requisitos Funcionais e Não Funcionais

| *Tela*                               | *Requisitos Funcionais (RF)*                                                                                                                                           | *Requisitos Não Funcionais (RNF)*                                                                                                                                                                              |
|----------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| *1. Tela de Abertura*                | - Exibir o logotipo com animação.<br>- Exibir botão para avançar à tela de cadastro/login ou redirecionar automaticamente após a animação.                                | - Animação com tempo de 2-3 segundos.<br>- Design responsivo.<br>- Transições suaves entre telas.                                                                                                                 |
| *2. Tela de Cadastro/Login*          | - Login com e-mail e senha.<br>- Opção de cadastro para novos usuários.<br>- Links para recuperação de senha e alternar entre cadastro/login.<br>- Login com Google.      | - Segurança dos dados (senhas criptografadas).<br>- Resposta do sistema em < 2 segundos.<br>- Design acessível e legível.                                                                                         |
| *3. Tela de Onboarding*              | - Exibir slides sobre o aplicativo.<br>- Navegar entre slides com botões.<br>- Opção de pular o onboarding.<br>- Registrar se o usuário completou o onboarding.           | - Processo de onboarding em 2-3 minutos.<br>- Textos e gráficos simples e claros.<br>- Compatível com dispositivos móveis e desktops.                                                                             |
| *4. Tela de Dashboard*               | - Exibir tarefas do dia/semana.<br>- Destaque para tarefas urgentes.<br>- Atalhos para “Criar Tarefa”, “Estatísticas” e “Desempenho”.<br>- Atualização em tempo real.      | - Carregamento rápido das tarefas.<br>- Design responsivo.<br>- Suportar grande quantidade de tarefas sem perda de desempenho.                                                                                     |
| *5. Tela de Criação de Tarefas*      | - Formulário para criar/editar tarefas.<br>- Campos obrigatórios: nome, data/hora, prioridade, categoria e notificação.<br>- Salvar tarefa e adicionar ao cronograma.      | - Validação dos campos em tempo real.<br>- Design intuitivo e responsivo.<br>- Salvamento em < 1 segundo.                                                                                                         |
| *6. Tela de Cronograma Diário/Semanal*| - Exibir tarefas organizadas no cronograma.<br>- Permitir arrastar e reorganizar tarefas.<br>- Botão para adicionar nova tarefa.                                           | - Transição rápida e sem travamentos.<br>- Layout responsivo.<br>- Reorganização de tarefas salva imediatamente.                                                                                                   |
| *7. Popup de Sugestões de Otimização*| - Exibir sugestões para otimizar o tempo.<br>- Dicas sobre horários vagos, descanso, estudo.<br>- Permitir aceitar ou ignorar sugestões.                                  | - Popup discreto e não intrusivo.<br>- Design simples e de fácil compreensão.<br>- Sugestões baseadas em análise automática precisa.                                                                               |
| *8. Tela de Análise de Progresso*    | - Exibir gráficos e relatórios sobre tarefas concluídas e tempo por categoria.<br>- Estatísticas diárias, semanais e mensais.                                             | - Gráficos rápidos e interativos.<br>- Layout responsivo.<br>- Informações claras e visualmente atrativas.                                                                                                        |
| *9. Tela de Suporte/Feedback*        | - Formulário para feedback e suporte.<br>- Campos obrigatórios: descrição e categoria.<br>- Envio do formulário e confirmação de recebimento.                              | - Resposta para envio do formulário em < 2 segundos.<br>- Design simples e acessível.<br>- Feedback registrado de forma segura e confidencial.                                                                    |
| *10. Tela de Perfil do Usuário*      | - Exibir informações de perfil.<br>- Permitir edição de informações.<br>- Opções para ajustes de notificação e tema (claro/escuro).                                        | - Alterações salvas em tempo real.<br>- Design responsivo.<br>- Garantia de proteção de dados pessoais com autenticação para mudanças sensíveis.                                                                  |
| *11. Tela de Sugestão*               | - Exibir quatro tipos de sugestões:<br>  1. Ajuda com horários.<br>  2. Dicas para estudo.<br>  3. Descansar/dormir.<br>  4. Dicas para bom desempenho.                   | - Sugestões claras e interativas.<br>- Análise rápida e baseada em dados reais.<br>- Layout compatível com dispositivos móveis e desktops, oferecendo uma experiência fluida.                                       |

### Ações do Usuário

| *Tela*                               | *Ações do Usuário*                                                                                                                                                   |
|----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| *1. Tela de Abertura*                | - Observar a animação do logotipo.<br>- Clicar no botão para prosseguir, caso não redirecionado automaticamente.                                                      |
| *2. Tela de Cadastro/Login*          | - Inserir e-mail e senha para login.<br>- Clicar na opção de cadastro.<br>- Alternar entre login e cadastro.<br>- Utilizar a opção de login com Google.                |
| *3. Tela de Onboarding*              | - Navegar entre os slides.<br>- Pular o onboarding, se desejado.<br>- Receber informações sobre o aplicativo.                                                         |
| *4. Tela de Dashboard*               | - Visualizar as tarefas do dia/semana.<br>- Interagir com tarefas urgentes.<br>- Usar atalhos para criar tarefas, acessar estatísticas e desempenho.                  |
| *5. Tela de Criação de Tarefas*      | - Completar o formulário (nome, data/hora, prioridade, etc.).<br>- Salvar e adicionar a tarefa ao cronograma.                                                         |
| *6. Tela de Cronograma Diário/Semanal*| - Visualizar tarefas no cronograma.<br>- Reorganizar tarefas arrastando-as.<br>- Adicionar novas tarefas diretamente no cronograma.                                   |
| *7. Popup de Sugestões de Otimização*| - Ler as sugestões.<br>- Aceitar ou ignorar as sugestões.                                                                                                             |
| *8. Tela de Análise de Progresso*    | - Visualizar gráficos e relatórios sobre o progresso.<br>- Navegar entre estatísticas diárias, semanais e mensais.                                                    |
| *9. Tela de Suporte/Feedback*        | - Preencher e enviar o formulário de feedback/suporte.<br>- Aguardar a confirmação de recebimento.                                                                   |
| *10. Tela de Perfil do Usuário*      | - Visualizar informações de perfil.<br>- Editar informações do perfil.<br>- Ajustar preferências de notificação e alternar tema claro/escuro.                         |
| *11. Tela de Sugestão*               | - Visualizar as quatro categorias de sugestões.<br>- Interagir e aplicar as dicas fornecidas.                                                                         |

## Projeto de Interface

Desenvolvemos wireframes para o layout da plataforma, chamada *“Tempo Otimizado”*, durante reuniões do grupo, com foco em gestão eficiente de tarefas e otimização do cronograma.

---

## Protótipo Interativo

O protótipo da interface foi criado utilizando o Figma e pode ser acessado no link abaixo.

---

## Metodologia

O desenvolvimento do projeto seguiu a metodologia SCRUM. Realizamos encontros semanais e utilizamos um grupo no WhatsApp para comunicação. Reuniões online foram realizadas para revisar o progresso e definir novas tarefas. A divisão de tarefas foi organizada utilizando a metodologia Kanban.

---

## Links

- *Miro*: [Miro Board](https://miro.com/app/board/uXjVKn9kuFg=/)
- *Figma*: [Protótipo no Figma](https://www.figma.com/design/IEsgUebiFZGQOkeAWqdyTZ/Tempo-otimizado?node-id=0-1&node-type=canvas&t=I7xRj2ulRa4trN3M-0)
- *Canva*: [Apresentação no Canva](https://www.canva.com/design/DAGQcupPwlQ/dfEuhXloz-nZyA6wFmDoVQ/edit)
- *Documentação do Projeto*: [Documentação no DOCS](https://docs.google.com/document/d/1Q8gyPVwmVyhmgnTF2TCXz3vqIcY56G-rgm00SgYForM/edit).
