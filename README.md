# projeto_leitor_nota_fiscal

O projeto tem como objetivo a criação de um script que faça leitura de notas fiscais em pdf, anotações de informações e armazenamento de notas que não foram identificadas

Funções criadas:

- Ler_pdf(caminho_arquivo): Lê o conteúdo do PDF especificado e retorna o texto.

- Extrair_informacoes(texto_pdf): Extrai informações relevantes (como número da nota fiscal, data, valor total) do texto PDF e retorna um       dicionário.

- Gerar_planilha(dados_notas, nome_arquivo): Cria uma planilha Excel com as informações extraídas e a salva com o nome especificado.

- Registrar_erro(caminho_arquivo): Anota o caminho do arquivo PDF que não pôde ser lido em um arquivo de texto.

