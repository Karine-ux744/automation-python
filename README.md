# 🤖 Automação de Sistemas e Processos com Python

Automação desenvolvida em Python para acessar dados de vendas, realizar análise e enviar relatório por e-mail de forma automatizada:
1. Acessa o Google Drive para baixar o arquivo de vendas do dia anterior
2. Analisa os dados e calcula o faturamento total e a quantidade de produtos vendidos
3. Envia automaticamente um e-mail para a diretoria com o relatório

✨ Funcionalidades
- ✅ Acesso automatizado ao Google Drive
- ✅ Download automático do arquivo de vendas
- ✅ Análise de dados com cálculo de faturamento e quantidade de produtos
- ✅ Envio automático de e-mail com relatório formatado
- ✅ Interface gráfica automatizada usando PyAutoGUI

🛠️ Tecnologias Utilizadas
- **Python**
- **PyAutoGUI**- Automação de interface gráfica
- **Pandas** - Análise e manipulação de dados
- **PyPerclip** - Manipulação da área de transferência
- **OpenPyXL** - Leitura de arquivos Excel (dependência do Pandas)

🔄 Fluxo de Execução
1. Abre o Chrome
2. Acessa o Google Drive
3. Navega até a pasta de vendas
4. Faz download do arquivo Excel
5. Lê e analisa os dados do arquivo
6. Calcula faturamento total e quantidade de produtos
7. Abre o Gmail
8. Cria um novo e-mail
9. Preenche destinatário, assunto e corpo do e-mail
10. Envia o e-mail

📧 Formato do E-mail
O e-mail enviado contém:
- Faturamento total formatado em reais (R$)
- Quantidade total de produtos vendidos
- Mensagem formatada profissionalmente
