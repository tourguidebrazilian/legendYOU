# Coletor de Evidências Audiovisuais v0.4.3
**TCC & Pesquisa Acadêmica**

Ferramenta web desenvolvida em HTML5, JavaScript e Tailwind CSS para auxiliar pesquisadores, estudantes e acadêmicos na validação de fontes, gestão de metadados e estruturação de transcrições de vídeos do YouTube para fundamentação empírica em Trabalhos de Conclusão de Curso (TCC) e pesquisas científicas.

---

## 🚀 Principais Funcionalidades (Versão 0.4.3)

* **Ficha de Auditoria e Metadados da Fonte:** Permite registrar e preencher campos essenciais como URL, título do vídeo, nome do canal, data de publicação, duração total e descrição da postagem.
* **Atalho Interativo do YouTube:** Botão integrado com o ícone oficial do YouTube que permite abrir o vídeo de origem instantaneamente em uma nova guia do navegador.
* **Referência ABNT Automatizada:** Gera a citação bibliográfica pronta conforme as normas vigentes, dispondo de um botão de cópia rápida para a área de transferência.
* **Estruturação de Transcrições por Janelas Temporais:**
  * Configuração de agrupamento temporal em blocos customizáveis ($30$ segundos, $1$ minuto, $2$ minutos, $3$ minutos ou $5$ minutos).
  * Conversão e parsing de timestamps flexíveis vindos do YouTube.
  * Alinhamento justificado do texto para rigor com as normas de formatação acadêmica.
* **Exportação Inteligente de Relatórios:**
  * **Word (.doc/.docx):** Exporta um documento formatado contendo os metadados, descrição, citação ABNT e a transcrição estruturada, utilizando dinamicamente o título do vídeo para nomear o arquivo.
  * **Texto Plano (.txt):** Exportação alternativa em formato de texto para auditoria e portabilidade.
* **Segurança e Privacidade:** Processamento $100\%$ local e seguro diretamente no navegador do usuário, sem dependência de servidores externos para o armazenamento das transcrições.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 & Vanilla JavaScript:** Lógica de interface, manipulação de texto/transcrições e rotinas de exportação de arquivos.
* **Tailwind CSS (via CDN):** Framework utilitário para estilização de uma interface moderna, limpa e responsiva.

---

## 📖 Como Utilizar

1. Abra o arquivo HTML da aplicação (`AcademicTCCv0.4.3.html`) em qualquer navegador web moderno (Google Chrome, Firefox, Microsoft Edge, etc.).
2. Insira a **URL do vídeo do YouTube** e clique em **"Obter"** para preencher os metadados de forma automatizada (ou preencha os campos manualmente se preferir).
3. Cole o texto bruto copiado da transcrição do YouTube na seção **"2. Entrada de Transcrição"**.
4. Selecione a janela de bloco desejada (ex: blocos de $1$ minuto) e clique no botão **"Estruturar Transcrição em Blocos"**.
5. Revise o resultado gerado no painel direito (Ficha de Metadados, Citação ABNT e Blocos Temporais).
6. Clique em **"Exportar Relatório em Word (.doc/.docx)"** ou **"Exportar Arquivo em Texto (.txt)"** para baixar o documento final pronto para uso em seu TCC.

---

## 📄 Licença

Este projeto é de uso livre e aberto para fins acadêmicos, de investigação e educacionais.