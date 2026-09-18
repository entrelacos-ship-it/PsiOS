# dados/ — drop zone

Solte aqui qualquer arquivo que você quer que o PsiOS leia uma vez: CSV
de exportação do Google Ads, planilha de vendas, PDF de contrato,
transcrição de reunião, print de relatório.

Skills como `/analisar-dados` e `/relatorio-ads` leem direto dessa pasta.
Você arrasta o arquivo, chama o comando, recebe o resumo.

Não é arquivo final — é entrada. O que importa do que tá aqui vira
artefato em `_memoria/`, `marketing/` ou `saidas/`.

Quando você tiver MCPs de armazenamento conectados (Google Drive,
Notion), pode pedir pro Claude buscar os arquivos direto da fonte — sem
precisar baixar nada pra cá.

**Nunca solte aqui:** prontuário, transcrição de sessão, dado clínico ou
qualquer coisa que identifique paciente. Essa pasta é só pra dados
administrativos e de marketing (planilha de vendas, export de ads,
relatório de tráfego).
