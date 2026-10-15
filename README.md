# 📦 Event Merch Flow Pro - Gestão de Inventário & Fechamento Financeiro

Aplicação web *Single Page Application* (SPA) desenvolvida em **HTML5, CSS3 e JavaScript (Vanilla)** para controlo de inventário em tempo real, registo ágil de vendas por múltiplos meios de pagamento (PIX, Cartão e Cortesias) e apuração financeira automática com taxas e comissões de consignado.

---

## 🚀 Funcionalidades Principais

* **Operação em Tempo Real (PDV Ágil):** Interface otimizada para terminais móveis e ecrãs táteis, permitindo o registo rápido de saídas de peças com um clique e opção de estorno imediato (`undo`).
* **Auditoria de Inventário Físico:** Rastreio contínuo de peças recebidas, vendidas, cortesias/brindes e saldo devolvido ao fornecedor.
* **Cálculo Financeiro Automatizado:**
  * Dedução dinâmica de taxas de processamento de maquininha de cartão.
  * Cálculo proporcional da margem de comissão da agência / organização.
  * Apuração exata do montante líquido para repasse ao artista ou titular dos produtos consignados.
* **Privacidade Operacional:** Mecanismo integrado de alternância rápida de visibilidade de valores monetários na interface para proteção de dados financeiros em ambientes com circulação de público.
* **Persistência Local (Offline-First):** Armazenamento de estado automático via `localStorage`, prevenindo a perda de dados em caso de falha de conexão ou fecho acidental do navegador.
* **Exportação Analítica em PDF:** Geração client-side de relatório analítico de fecho de evento compatível com o padrão A4 via biblioteca `html2pdf.js`.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico & CSS3 Responsivo** (Design adaptativo com suporte a *Mobile-First* e tema escuro de alto contraste)
* **JavaScript Vanilla (ES6+)** (Sem frameworks externos, garantindo carregamento instantâneo)
* **html2pdf.js & jsPDF** (Renderização e conversão vetorial de relatórios em PDF)
* **Local Storage API** (Gestão de persistência e metadados no cliente)

---

## 📋 Como Testar e Executar

### 1. Acesso Online (GitHub Pages):
Aceda à demonstração interativa em tempo real através do link do projeto no GitHub Pages:
> `https://<seu-utilizador>.github.io/<nome-do-repositorio>/`

### 2. Execução Local:
1. Clone o repositório ou descarregue o ficheiro `index.html`:
   ```bash
   git clone [https://github.com/](https://github.com/)<seu-utilizador>/event-merch-tracker.git
