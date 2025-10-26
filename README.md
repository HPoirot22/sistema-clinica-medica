# 🏥 Gestão de Consultas Médicas

Este é um projeto de uma aplicação web simples para agendamento e gestão de consultas médicas. A interface permite que o usuário selecione um paciente, um médico e uma data para agendar uma nova consulta, que é então exibida em uma lista.

## ✨ Funcionalidades

- **Carregamento Dinâmico de Dados**: Carrega listas de médicos e pacientes a partir de arquivos JSON locais.
- **Agendamento de Consultas**: Permite selecionar um paciente, um médico e uma data para criar um novo agendamento.
- **Validação**: Impede o agendamento se algum dos campos não for preenchido.
- **Prevenção de Duplicatas**: Verifica se uma consulta idêntica já foi agendada e alerta o usuário.
- **Listagem de Consultas**: Exibe as consultas agendadas em uma lista clara e organizada.
- **Cancelamento de Consultas**: Cada consulta na lista possui um botão "Cancelar" para removê-la.
- **Design Responsivo**: Interface limpa e adaptável a diferentes tamanhos de tela.

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica da página.
- **CSS3**: Estilização moderna com o uso de variáveis CSS para um tema consistente.
- **JavaScript (ES6+)**:
  - **Módulos (ESM)**: Para organização e modularização do código.
  - **Async/Await com Fetch API**: Para carregar os dados dos arquivos JSON de forma assíncrona.
  - **Manipulação do DOM**: Para criar e atualizar a interface de forma dinâmica.
  - **Programação Orientada a Objetos (POO)**: Utilização de classes para representar `Paciente` e `Medico`.

## 📂 Estrutura do Projeto

```
ClinicaMedica/
├── assets/
│   ├── clinicaMedica.webp
│   └── cuidados-de-saude.png
├── css/
│   └── style.css
├── data/
│   ├── medicos.json
│   └── pacientes.json
├── js/
│   ├── DomHandler.js     # Módulo para manipular o DOM
│   ├── Medico.js         # Classe Medico (não fornecida no contexto)
│   ├── Paciente.js       # Classe Paciente (não fornecida no contexto)
│   └── main.js           # Lógica principal da aplicação
└── index.html            # Arquivo principal da página
```

- **`index.html`**: A página principal que contém a estrutura do formulário de agendamento e a lista de consultas.
- **`css/style.css`**: Contém todos os estilos da aplicação, incluindo o tema de cores e o layout.
- **`js/main.js`**: Orquestra a aplicação. É responsável por carregar os dados, popular os seletores e registrar o evento de clique para agendar consultas.
- **`js/DomHandler.js`**: Uma classe estática com métodos dedicados a interagir com o DOM, como atualizar as listas de seleção e exibir as consultas agendadas.
- **`data/*.json`**: Arquivos que simulam um banco de dados, contendo as informações dos médicos e pacientes.

## 🚀 Como Executar

Apenas acessar o link: https://hpoirot22.github.io/sistema-clinica-medica/
