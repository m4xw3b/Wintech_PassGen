# Wintech Password Generator (PassGen) 🚀

O **Wintech Password Generator** é uma ferramenta web moderna, responsiva e de alta performance desenhada para a criação de chaves/passwords criptograficamente seguras. Ideal para a proteção de contas de e-mail e credenciais críticas, o utilitário corre inteiramente no lado do cliente (*client-side*), garantindo privacidade absoluta uma vez que nenhum dado é enviado para servidores externos.

---

## 🛠️ Funcionalidades Principais

*   **Segurança Criptográfica:** Utilização da API nativa `window.crypto.getRandomValues` em vez de geradores pseudo-aleatórios comuns (`Math.random`), mitigando riscos de previsibilidade.
*   **Algoritmo de Validação Estrita:** O motor garante obrigatoriamente a inclusão de pelo menos um caracter de cada categoria selecionada (Maiúsculas, Minúsculas, Números ou Símbolos), aplicando um baralhamento (*shuffle*) seguro no final.
*   **Interface Responsiva Adaptativa:** Layout otimizado nativamente para qualquer dispositivo. Apresentação panorâmica em 3 colunas para Computador/Desktop e reestruturação vertical automática para Tablets e Smartphones.
*   **Histórico de Sessão Inteligente:** Guarda as últimas 3 passwords geradas na sessão atual para evitar perdas acidentais por cliques duplos.
*   **Modo Escuro (Dark Mode):** Alternância fluida de ambiente visual para maior conforto em utilizações noturnas.
*   **Notificações Flutuantes (Toasts):** Apresentação dinâmica de boas práticas e princípios fundamentais de cibersegurança (como diretiva NIS2, proteção de redes, higiene de credenciais e alertas de phishing/smishing) a cada geração.
*   **Cópia Rápida Dinâmica:** Botão de cópia dedicado com feedback visual em tempo real.

---

## 💻 Tecnologias Utilizadas

*   **HTML5** – Estruturação semântica e acessível.
*   **Tailwind CSS** – Framework utilitário para estilização fluida, transições animadas e Dark Mode nativo.
*   **JavaScript (Vanilla ES6+)** – Lógica de computação e criptografia nativa no ecossistema do navegador.

---

## 🚀 Como Executar o Projeto

Por ser uma aplicação puramente *client-side*, não necessita de qualquer instalação ou dependências de backend.

1. Faça o clone ou download deste repositório.
2. Abra o ficheiro `index.html` diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).

A aplicação está também disponível online via **GitHub Pages**:
🔗 `https://<o-teu-utilizador>.github.io/<nome-do-repositorio>/`

---

## ⏳ Histórico de Versões (Changelog)

*   **v3.1.0** — Integração de padrão geométrico de fundo (`bg-pattern`), efeito fosco (*backdrop blur*) e migração das dicas de segurança para Popups dinâmicos flutuantes.
*   **v3.0.1** — Otimização da simetria visual e fixação de limites verticais na barra lateral (máximo de 3 chaves gravadas).
*   **v3.0.0** — Reestruturação da aplicação em arquitetura de Separadores (Tabs), centralizando o Gerador, Tutorial Técnico, Changelog e Perfil do Autor.
*   **v2.0.0** — Implementação do layout horizontal responsivo em colunas e botão unificado de cópia.
*   **v1.0.0** — Conceção do algoritmo core inicial baseado no módulo `secrets` em ambiente CLI.

---

## 👤 Autor

Desenvolvido por **João Fernandes** — Especialista em Desenvolvimento de Software e Gestão de Redes/Sistemas Computacionais.

*   **LinkedIn:** [O teu link do LinkedIn](https://linkedin.com)
*   **GitHub:** [O teu link do GitHub](https://github.com)

---
*Desenvolvido sob o selo de qualidade e utilidade do ecossistema Wintech.*
