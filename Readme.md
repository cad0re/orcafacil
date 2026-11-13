# 📱 OrcaFácil

> O **OrcaFácil** é uma aplicação web mobile-first desenvolvida para auxiliar freelancers, prestadores de serviços autônomos e pequenos profissionais a calcularem com precisão o valor da sua hora técnica, comporem o preço de serviços e gerarem orçamentos profissionais em PDF prontos para envio via WhatsApp.

---

## 🚀 Funcionalidades

1. **Módulo 1: Minha Hora**
   - Cálculo automático do valor da hora técnica e diária com base nos custos fixos mensais, horas/dias trabalhados e margem de lucro desejada.
2. **Módulo 2: Composição de Serviços**
   - Soma inteligente de materiais, tempo de execução (horas ou dias), valor da hora, taxa de deslocamento e margem de imprevistos/riscos.
3. **Módulo 3: Geração de Orçamentos & PDF**
   - Criação de um orçamento detalhado com layout profissional em formato A4, pronto para exportação em PDF via `html2pdf.js` e disparo direto para o WhatsApp do cliente com mensagem formatada.
4. **Armazenamento Local (LocalStorage)**
   - Os dados inseridos pelo usuário ficam salvos no navegador, evitando perda de informações ao recarregar a página.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído para ser leve, rápido e de fácil manutenção, sem necessidade de servidores complexos ou ferramentas de *build*:
- **HTML5 & CSS3**
- **Tailwind CSS** (via CDN para estilização moderna e responsiva)
- **JavaScript (Vanilla)** para toda a lógica de cálculo e manipulação do DOM
- **html2pdf.js** para exportação de documentos PDF no padrão A4

---

## 📦 Como Executar o Projeto Localmente

Como a aplicação é estática, você não precisa instalar dependências via Node.js ou rodar servidores locais complexos:

1. Clone o repositório ou baixe os arquivos:
   ```bash
   git clone [https://github.com/SEU-USUARIO/orcafacil.git](https://github.com/SEU-USUARIO/orcafacil.git)