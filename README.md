# 🏠 Dona Neuza

**Cuidado, segurança e autonomia dentro de casa.**

A Dona Neuza é um ecossistema integrado de software e hardware (aplicativos, sensores, câmeras e relógios inteligentes) para monitorar e proteger pessoas que precisam de cuidados especiais em suas residências. O sistema dá independência a quem é cuidado, com zero atrito tecnológico, e tranquilidade a familiares e cuidadores.

🔗 **Site:** [lii0004.github.io/donaneuza](https://lii0004.github.io/donaneuza/)

---

## 📌 Sobre o projeto

Este repositório contém o site institucional da Dona Neuza, voltado aos clientes. Ele apresenta o serviço, os recursos, os planos de assinatura e os canais de contato.

O projeto foi desenvolvido no **Projeto Integrador I** do curso de Desenvolvimento de Software Multiplataforma (DSM), integrando as disciplinas de Engenharia de Software I, Design Digital e Desenvolvimento Web I.

## 🧩 Como o sistema funciona

O produto é dividido em duas frentes:

| Frente | Público | Descrição |
|---|---|---|
| **Central do Cuidador** (mobile) | Familiares e enfermeiros | Câmeras, alertas de saúde, liberação de portões e gestão da rotina |
| **Interface do Assistido** (wearable e smart home) | Pessoa cuidada | Smartwatch com botão SOS e comandos de voz pela casa, sem telas complexas |

## ✨ Funcionalidades

**Saúde e biometria**
- Batimentos cardíacos, oxigenação do sangue e localização por GPS em tempo real
- Detecção de anomalias, como picos de batimentos e quedas de saturação

**Segurança e automação residencial**
- Monitoramento por câmeras com modo de privacidade
- Sensores de presença e detecção de quedas bruscas
- Controle remoto de portões e portas

**Comunicação e acessibilidade**
- Pedido de ajuda por voz (ex.: "Socorro", "Ligar para meu filho")
- Botão físico de pânico (SOS) no relógio
- Intercomunicador: o cuidador fala pelo celular e a voz sai nas caixas de som da casa

## 💳 Planos

O modelo de negócios é SaaS, com assinatura mensal paga pelos familiares. Os planos variam conforme o armazenamento das gravações das câmeras.

| Plano | O que inclui |
|---|---|
| **Básico** | Câmeras em tempo real, alertas vitais do relógio e botão SOS |
| **Standard** | Tudo do Básico, 7 dias de gravação na nuvem, histórico de saúde e abertura remota de portas |
| **Premium** | Tudo do Standard, 30 dias de gravação, relatórios avançados de saúde e acionamento automático de portaria e SAMU |

> Os valores exibidos no site são ilustrativos.

## 🛠️ Tecnologias do site

- **HTML5** semântico
- **CSS3** com variáveis, Grid e Flexbox
- **JavaScript** puro, sem bibliotecas
- Fontes [Sora](https://fonts.google.com/specimen/Sora) e [Nunito Sans](https://fonts.google.com/specimen/Nunito+Sans) (Google Fonts)
- Hospedagem no **GitHub Pages**

## 📁 Estrutura do repositório

```
donaneuza/
├── index.html   # Estrutura e comportamento da página
├── style.css    # Estilos, paleta de cores e responsividade
└── README.md    # Documentação do projeto
```

## ▶️ Como executar localmente

1. Baixe ou clone o repositório:
   ```bash
   git clone https://github.com/lii0004/donaneuza.git
   ```
2. Abra a pasta `donaneuza`.
3. Dê um duplo clique no `index.html` para abri-lo no navegador. Não é preciso instalar nada.

## 🎨 Identidade visual

| Cor | Código | Uso |
|---|---|---|
| Azul primário | `#2A5CAA` | Identidade, títulos e fundo de destaque |
| Coral | `#FF6F5E` | Ações, alertas e botão SOS |
| Cinza azulado | `#4A4E69` | Textos e contraste |
| Verde menta | `#9DE0CC` | Status normal e feedback positivo |

As cores ficam no início do `style.css`, como variáveis (`:root`).

## 👥 Equipe

- Lidia Nascimento
- Marcos Franco
- Vitor Barbosa
- Alejandro Quispe

**Orientação:** Prof. Esp. Vickybert Freire

## 📄 Observações

Este é um projeto acadêmico. Os formulários do site não enviam dados a nenhum servidor, e a demonstração do aplicativo usa dados fictícios.
