# Fokus

Fokus é um aplicativo fictício de gerenciamento de tarefas com foco em produtividade. Ele ajuda os usuários a otimizar seu tempo, alternando entre períodos de foco e descanso. Desenvolvido por Alura como um projeto educacional, este aplicativo inclui funcionalidades como um timer, música de foco, gerenciamento de tarefas e modos de descanso.

## Funcionalidades

- **Timer com Modos de Foco e Descanso**: Três modos de contagem regressiva - foco (30 segundos), descanso curto (5 segundos) e descanso longo (15 segundos).
- **Música de Fundo**: Opção de ativar ou desativar música durante o período de foco.
- **Gerenciamento de Tarefas**: Adição, edição, conclusão e remoção de tarefas.
- **Persistência de Dados**: As tarefas são armazenadas no localStorage, permitindo que os dados sejam mantidos após a atualização da página.
- **Notificações Sonoras**: Alertas sonoros para início, pausa e término do período de foco.

## Estrutura do Projeto

### Arquivos Principais

1. **index.html**: Estrutura HTML do aplicativo.
2. **styles.css**: Estilos CSS para o layout e aparência do aplicativo.
3. **script.js**: Contém a lógica principal do timer e da interface do usuário.
4. **script-crud.js**: Gerencia o CRUD (Create, Read, Update, Delete) das tarefas.

### Bibliotecas Externas

- **Meyer Reset CSS**: Utilizado para redefinir os estilos padrão do navegador.
- **Google Fonts**: Fontes Montserrat, Prata e Unbounded.

## Estrutura HTML

O HTML é composto por várias seções principais:

- **Header**: Contém o logotipo do aplicativo.
- **Banner**: Inclui o título e uma imagem de destaque.
- **Card**: Área onde estão os botões de modo (foco, descanso curto, descanso longo), o timer e a opção de música.
- **Lista de Tarefas**: Seção para gerenciamento das tarefas com opções para adicionar, editar e remover tarefas.
- **Footer**: Informação sobre o projeto e créditos.

## Scripts JavaScript

### script.js

Este script gerencia:

- Alternância entre os modos de foco e descanso.
- Início e pausa do timer.
- Execução de músicas e sons de notificação.
- Mudança de contexto visual (imagens e textos).

### script-crud.js

Este script gerencia:

- Adição, edição e remoção de tarefas.
- Armazenamento das tarefas no localStorage.
- Atualização da interface de acordo com as ações do usuário.
- Eventos personalizados, como a conclusão do período de foco.

## Como Executar o Projeto

1. Clone o repositório ou faça o download dos arquivos.
2. Abra o arquivo `index.html` em um navegador web.

## Desenvolvimento

Este projeto foi desenvolvido como parte de um curso da Alura e é inteiramente educacional. Todas as imagens foram geradas por IA no Adobe Firefly.

### Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.

## Créditos

Projeto para estudo da linguagem.
