# 🐾 VittaPet

> Gestão inteligente de saúde preventiva e adoção responsável de pets.

## 👥 Integrantes

- **Gabrielly Lorentz — RM 565806**
- **Giovanna Praieiro — RM 565681**
- **Heitor Fernandes — RM 563078**
- **Júlia Aparicio — RM 563623**
- **Maria Eduarda de Oliveira — RM 565386**
- **Nicolle Calasans — RM 564381**

## 🎯 Proposta de Valor

Facilitar o cuidado preventivo de cães e gatos por meio da centralização de informações de saúde, lembretes de cuidados e vacinação, além de promover a adoção responsável.

O VittaPet busca transformar o cuidado com os animais em uma experiência mais simples, preventiva e organizada, contribuindo para uma vida longa e saudável dos pets.

## 🚀 Funcionalidades (MVP)

- **Gestão de Perfis de Pets:** cadastro detalhado do animal, incluindo nome, espécie, raça, idade e informações de nascimento.
- **Painel Inteligente de Lembretes:** organização de cuidados preventivos, como vacinas, vermífugos e antipulgas.
- **Carteirinha Digital de Vacinação:** apresentação das informações de vacinação e cuidados do pet.
- **Agenda de Cuidados:** visualização dos eventos programados para vacinas e medicamentos.
- **Notificações:** apresentação dos próximos cuidados e lembretes importantes.
- **Espaço de Adoção Responsável:** divulgação de animais disponíveis para adoção e visualização de informações dos pets.
- **Cadastro de novos pets:** possibilidade de adicionar novos animais pelo perfil, com persistência dos dados no Cloud Firestore.

## 🎯 Público-Alvo

- Tutores de cães e gatos com rotinas atarefadas.
- Tutores de primeira viagem.
- ONGs e protetores independentes.

## 🏷️ Marca

### Naming

O nome **VittaPet** combina a ideia de *vita*, associada à vida, vitalidade e longevidade, com o termo *pet*, utilizado para representar animais de estimação. A combinação transmite o propósito da aplicação de contribuir para o cuidado, a saúde e o bem-estar dos animais ao longo de suas vidas.

### Tom de Voz

- **Acolhedor e empático:** estabelece uma relação de proximidade com os tutores e reconhece o vínculo afetivo com os animais.
- **Preventivo e confiável:** apresenta informações e lembretes de saúde de forma clara e responsável.
- **Claro e direto:** utiliza uma comunicação simples e objetiva, facilitando a compreensão das informações e ações necessárias.

## 🎨 Identidade Visual

### Logotipo

![Logo VittaPet](./assets/vittapet-logo.png)

O logotipo representa a união entre cuidado, afeto e bem-estar animal. A composição com cão e gato, o coração central e a combinação das cores reforçam a proposta acolhedora e preventiva do VittaPet.

### Paleta de Cores

| Elemento | Código HEX | Aplicação |
|---|---|---|
| Primary Blue | `#3B82F6` | Botões principais, navegação, cabeçalhos e elementos de destaque |
| Secondary Green | `#10B981` | Indicadores positivos, medicamentos e confirmações |
| Accent Orange | `#F59E0B` | Carteirinha e elementos de destaque |
| Background Grey | `#F9FAFB` | Fundo da aplicação e áreas de conteúdo |

### Tipografia

A identidade visual do VittaPet utiliza a família tipográfica **Nunito**.

- **Nunito Bold:** títulos e elementos de maior destaque.
- **Nunito SemiBold:** subtítulos, botões e informações importantes.
- **Nunito Regular:** textos, descrições e informações gerais.

A Nunito foi escolhida por sua boa legibilidade e pelas formas arredondadas, que reforçam a proposta acolhedora, amigável e confiável do VittaPet.

## 💡 Proposta de Venda

### Pitch

> O VittaPet é a plataforma integrada que transforma o cuidado pet em uma experiência simples, preventiva e sem esquecimentos. Conectamos o acompanhamento médico completo do animal a um ecossistema consciente de adoção responsável, garantindo que todo pet tenha uma vida longa, saudável e cercada de carinho desde o primeiro dia.

### Diferencial Competitivo

- **Abordagem Preventiva Integrada:** foco no ciclo de imunização e na saúde preventiva contínua.
- **Ponte com o Ecossistema de Adoção:** conexão entre adoção responsável e acompanhamento dos cuidados do animal.
- **Praticidade Mobile First:** proposta de interface simplificada, com cards claros e navegação fluida.

### Modelo de Negócio

**Modelo Freemium:** acesso gratuito às ferramentas essenciais de perfil, lembretes e adoção, com possibilidade de recursos premium para gestão ilimitada de múltiplos pets, backup em nuvem e exportação de relatórios.

**Parcerias com Clínicas e Pet Centers:** possibilidade de parcerias com clínicas veterinárias, pet centers e marcas relacionadas à saúde e ao bem-estar animal.

## 🛠️ Tecnologias

- **Framework:** Flutter (Dart)
- **Interface:** Material 3
- **Tipografia:** Google Fonts / Nunito
- **Banco de dados:** Firebase Cloud Firestore
- **Configuração Firebase:** FlutterFire CLI
- **Controle de versão:** Git e GitHub
- **Ambiente de desenvolvimento:** Visual Studio Code
- **Ambiente de testes:** Android Studio / Emulador Android

## 📱 Estrutura do Aplicativo

O aplicativo possui quatro áreas principais acessíveis pela navegação inferior:

- **Início**
- **Agenda**
- **Adoção**
- **Perfil**

### 🏠 Início

A tela inicial apresenta as informações e próximos cuidados do pet selecionado.

Entre os recursos estão:

- Seleção entre pets.
- Próximo cuidado.
- Vacinas.
- Medicamentos.
- Carteirinha.
- Próximos cuidados.
- Notificações.

Os dados apresentados para a demonstração incluem os pets **Thor** e **Luna**.

### 📅 Agenda

A Agenda apresenta os cuidados programados dos pets em um calendário.

São apresentados:

- Vacinas.
- Medicamentos.
- Datas e horários.
- Eventos marcados no calendário.
- Resumo dos cuidados.

Os dados utilizados na demonstração têm como referência **05/10/2026**.

### 🐶 Adoção

A área de adoção apresenta pets disponíveis para adoção.

É possível filtrar os animais por:

- Todos
- Cães
- Gatos

Pets utilizados na demonstração:

- **Amora** — Shih-tzu — 4 meses
- **Max** — Spitz Alemão — 2 anos
- **Mia** — Persa — 4 anos
- **Bolt** — Border Collie — 8 meses

Também é possível favoritar animais e visualizar seus detalhes.

### 👤 Perfil

A tela de perfil apresenta:

- Informações da tutora.
- Pets cadastrados.
- Edição de perfil.
- Cadastro de novos pets.
- Notificações.
- Privacidade e segurança.
- Ajuda e suporte.
- Informações sobre o aplicativo.

O cadastro de novos pets possui:

- Nome.
- Tipo.
- Raça.
- Data de nascimento.

A idade do pet é calculada utilizando como referência a data-base definida para a apresentação do projeto.

## 🔥 Firebase e Cloud Firestore

No Checkpoint 5, o VittaPet passou a contar com integração com o **Firebase Cloud Firestore**.

O Firebase é inicializado na aplicação por meio do arquivo:

```text
lib/firebase_options.dart
```

O banco utilizado é o:

**Cloud Firestore**

### Persistência de pets

O cadastro de novos pets realizado pelo aplicativo é armazenado na coleção:

```text
pets
```

Cada novo pet recebe um documento com ID automático.

A estrutura utilizada é semelhante a:

```text
pets
└── [ID automático]
    ├── nome
    ├── tipo
    ├── raca
    ├── nascimento
    └── responsavel
```

Dessa forma, quando um novo pet é cadastrado pelo aplicativo, seus dados são enviados para o Cloud Firestore.

### Teste de conexão

Durante a integração do Firebase também foi realizado um teste de comunicação entre o aplicativo e o banco de dados.

Foi criada a coleção:

```text
testes
└── conexao
```

O teste confirmou a comunicação entre:

```text
Aplicativo Flutter
        ↓
Firebase
        ↓
Cloud Firestore
```

Além do teste de conexão, foi realizado um cadastro real de pet pelo aplicativo, confirmando que os dados foram persistidos no Firestore.

## 🧪 Dados Mockados

O protótipo utiliza dados simulados para representar informações que, em uma versão completa do aplicativo, poderiam ser obtidas diretamente de uma base de dados.

Entre os dados simulados estão:

- Informações de Thor.
- Informações de Luna.
- Agenda de vacinas.
- Agenda de medicamentos.
- Notificações.
- Pets disponíveis para adoção.

A utilização de dados mockados permite demonstrar o fluxo principal do aplicativo mesmo sem depender de uma estrutura completa de backend para todas as funcionalidades.

Ao mesmo tempo, o cadastro de novos pets já possui persistência real utilizando o Cloud Firestore.

## 🔄 Navegação

A aplicação possui uma navegação inferior persistente com quatro áreas principais:

```text
Início
  │
  ├── Agenda
  │
  ├── Adoção
  │
  └── Perfil
```

A navegação é realizada utilizando `NavigationBar` e `IndexedStack`.

## ⚙️ Configuração do Firebase

Para configurar o projeto Firebase em um novo ambiente, é necessário possuir Flutter, Dart, Node.js e Firebase CLI instalados.

### Firebase CLI

Verifique a instalação:

```bash
firebase --version
```

Faça login:

```bash
firebase login
```

### FlutterFire CLI

Instale o FlutterFire CLI:

```bash
dart pub global activate flutterfire_cli
```

Depois configure o projeto:

```bash
flutterfire configure
```

Durante a configuração, deve ser selecionado o projeto Firebase utilizado pelo VittaPet.

O processo gera o arquivo:

```text
lib/firebase_options.dart
```

## 📦 Instalação das Dependências

Na pasta raiz do projeto, execute:

```bash
flutter pub get
```

As principais dependências utilizadas na integração com o Firebase são:

```bash
flutter pub add firebase_core
flutter pub add cloud_firestore
```

## ▶️ Como Executar o Projeto

### Pré-requisitos

É necessário possuir:

- Flutter instalado e configurado.
- Dart.
- Node.js.
- Firebase CLI.
- FlutterFire CLI.
- Android Studio ou outro ambiente com dispositivo/emulador Flutter configurado.

### Passo a passo

Clone o repositório:

```bash
git clone [URL_DO_NOVO_REPOSITORIO]
```

Entre na pasta do projeto:

```bash
cd VittaPetApp
```

Instale as dependências:

```bash
flutter pub get
```

Verifique possíveis problemas:

```bash
flutter analyze
```

Execute no emulador Android:

```bash
flutter run -d emulator-5554
```

Para verificar os dispositivos disponíveis:

```bash
flutter devices
```

## 🧪 Ambiente de Testes

O projeto foi desenvolvido e testado utilizando:

- Windows
- Visual Studio Code
- Flutter SDK
- Android Studio
- Emulador Android
- Dispositivo virtual Pixel 8

A aplicação foi executada com sucesso no emulador Android.

Também foi utilizado:

```bash
flutter analyze
```

para verificar a existência de erros no código.

O projeto foi testado com sucesso no ambiente de desenvolvimento, incluindo a execução das telas e a integração com o Cloud Firestore.

## 📌 Checkpoint 5 — Protótipo Funcional

O Checkpoint 5 corresponde à etapa de **Protótipo Funcional**, com o objetivo de tirar o projeto do papel e apresentar telas navegáveis, dados simulados e execução em ambiente de teste.

### Requisitos desenvolvidos

- [x] Protótipo funcional com dados mockados.
- [x] Navegação entre as principais telas.
- [x] Fluxo principal do aplicativo navegável.
- [x] Integração com Firebase Cloud Firestore.
- [x] Cadastro de pets com persistência no banco de dados.
- [x] Ambiente de teste configurado.
- [x] Execução em emulador Android.
- [x] Interface baseada na identidade visual definida anteriormente.
- [x] Documentação atualizada.

### Fluxo principal

```text
Início
   ↓
Seleção do pet
   ↓
Cuidados e lembretes
   ↓
Agenda
   ↓
Adoção
   ↓
Perfil
   ↓
Cadastro de novo pet
   ↓
Cloud Firestore
```

## 📋 Decisões Técnicas

### Flutter

Foi escolhido Flutter para permitir o desenvolvimento de uma aplicação mobile utilizando uma única base de código.

### Material 3

O projeto utiliza Material 3 para componentes de interface e navegação.

### Google Fonts

A família Nunito foi utilizada para manter a identidade visual definida para o aplicativo.

### Cloud Firestore

O Cloud Firestore foi escolhido para permitir a persistência dos dados dos pets e demonstrar a integração do aplicativo com um banco de dados em nuvem.

### Dados Mockados

Os dados simulados foram mantidos nas funcionalidades que não dependem diretamente do banco de dados, permitindo uma demonstração completa do protótipo durante a apresentação.

## ✅ Funcionalidades Implementadas

- [x] Identidade visual do VittaPet
- [x] Tela inicial
- [x] Seleção entre pets
- [x] Próximos cuidados
- [x] Vacinas
- [x] Medicamentos
- [x] Carteirinha
- [x] Notificações
- [x] Agenda
- [x] Calendário de cuidados
- [x] Área de adoção
- [x] Filtros de adoção
- [x] Favoritos
- [x] Detalhes dos pets para adoção
- [x] Perfil da tutora
- [x] Edição de perfil
- [x] Cadastro de novos pets
- [x] Cálculo da idade dos pets
- [x] Configurações
- [x] Firebase configurado
- [x] Cloud Firestore configurado
- [x] Persistência de novos pets no Firestore
- [x] Ambiente Android configurado e testado
- [x] Navegação entre as telas

## 👨‍💻 Responsabilidades dos Integrantes

- **Gabrielly Lorentz:** pesquisa e documentação do problema e público-alvo, contribuindo para a estruturação da documentação inicial do projeto.
- **Giovanna Praieiro:** organização e revisão da documentação, definição e detalhamento das funcionalidades do MVP e apoio no desenvolvimento inicial da aplicação em Flutter.
- **Heitor Fernandes:** criação e configuração inicial do projeto Flutter, estruturação do projeto, desenvolvimento da tela inicial e organização do repositório GitHub.
- **Júlia Aparicio:** estruturação da proposta de valor, diferencial competitivo, pitch e informações relacionadas ao modelo de negócio.
- **Maria Eduarda de Oliveira:** desenvolvimento da identidade visual, definição da aplicação da paleta de cores e tipografia e apoio na organização visual da interface inicial.
- **Nicolle Calasans:** revisão e validação da documentação, conferência da coerência entre proposta, público-alvo e funcionalidades e apoio na validação final dos requisitos do projeto.

## 📌 Checkpoint 4

O Checkpoint 4 corresponde à etapa de **Idealização do App**, contemplando a definição do problema, público-alvo, funcionalidades do MVP, desenvolvimento da marca, identidade visual, proposta de venda, diferencial competitivo e modelo de negócio.

O projeto foi posteriormente evoluído para o Checkpoint 5, passando da etapa de idealização para um **protótipo funcional e navegável**, executado em ambiente de testes e integrado ao Firebase Cloud Firestore.

## 🚀 Próximos Passos

Como evolução futura do projeto, podem ser implementados:

- Sistema completo de login e cadastro.
- Associação dos pets ao usuário autenticado.
- Recuperação dos pets diretamente do Firestore ao iniciar o aplicativo.
- Persistência de vacinas e medicamentos.
- Notificações push.
- Edição e exclusão de pets.
- Integração com serviços reais de adoção.
- Regras de segurança mais específicas para o Firestore.
- Expansão dos recursos de saúde preventiva.

---

**VittaPet — Cuidar ficou mais simples.** 🐾