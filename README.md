Proposta Base do Projeto
O projeto desenvolvido é uma aplicação web interativa que utiliza a API do Google Gemini para resumir textos fornecidos pelos usuários. Além disso, agora inclui funcionalidades adicionais como a criação de nuvem de palavras e a exibição das top 20 palavras mais frequentes (exceto stopwords). A aplicação foi implementada em Python usando Streamlit e está disponível online para uso público.

Plano do Projeto
Descrição do Projeto: O projeto consiste em criar uma ferramenta de resumo de texto que facilita a condensação de grandes volumes de informação textual de forma rápida e eficiente. Utilizando o modelo Gemini 1.5 Pro da API do Google Gemini, a aplicação permite que os usuários insiram textos longos, façam upload de documentos (PDF e Word) ou forneçam URLs de páginas web para análise. Após o envio, a aplicação exibe um resumo do texto, uma nuvem de palavras e as top 20 palavras mais frequentes (exceto stopwords).

Objetivos Esperados:

Desenvolver uma aplicação web intuitiva e fácil de usar para resumir textos, criar nuvem de palavras e exibir estatísticas de frequência de palavras.
Integrar a API do Google Gemini para realizar as funcionalidades de resumo e análise textual.
Disponibilizar a aplicação na web através do Streamlit Cloud para acesso público.
Proteger informações sensíveis, como a chave da API, utilizando variáveis de ambiente.
Fontes de Dados Utilizadas:

A aplicação utiliza textos fornecidos diretamente pelos usuários através da interface web, upload de documentos ou URLs de páginas web.
A API do Google Gemini é utilizada para processar e resumir os textos, além de extrair as informações necessárias para a nuvem de palavras e a análise de frequência de palavras.
Observação: O projeto inicial se tratava de um classificador de texto. Porém, não foi possível colocá-lo em produção, pois ele demorava muito para realizar a classificação e a base de teste, validação e o modelo eram muito grandes para colocar no GitHub.

Disponibilização dos Arquivos
Os arquivos do projeto, incluindo o código fonte atualizado com as novas funcionalidades, estão disponíveis no repositório GitHub: https://github.com/dalles-oliveira/ResumirTexto

Link de Acesso à Aplicação
A aplicação web pode ser acessada através do seguinte link: https://resumotextofrequencia.streamlit.app/
