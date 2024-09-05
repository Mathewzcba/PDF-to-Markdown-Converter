# PDF to Markdown Converter 📄➡️📑

Bem-vindo ao repositório do **PDF to Markdown Converter**! Este projeto é uma ferramenta simples e eficiente desenvolvida em Python, que permite converter arquivos PDF em arquivos Markdown (.md). Ideal para quem deseja transformar documentos PDF em texto de fácil edição e leitura.

## 🚀 Descrição

O **PDF to Markdown Converter** utiliza as bibliotecas `PyMuPDF` e `markdownify` para extrair o conteúdo de arquivos PDF e convertê-los em Markdown, um formato amplamente utilizado em documentações, blogs e projetos de código aberto.

### Funcionalidades

- 📝 **Conversão automática de PDFs para Markdown**: Transforme seus arquivos PDF em arquivos `.md` com apenas alguns comandos.
- 📚 **Markdown legível e estruturado**: Cada página do PDF é organizada com cabeçalhos e o conteúdo formatado adequadamente.
- 🛠️ **Bibliotecas usadas**: `PyMuPDF` para leitura de PDFs e `markdownify` para converter HTML em Markdown.

## 🔧 Instalação

Siga os passos abaixo para instalar e rodar o script no seu ambiente local:

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seuusuario/pdf-to-markdown-converter.git
   cd pdf-to-markdown-converter

2. **Instale as dependências necessárias:**

Certifique-se de ter o Python instalado e, em seguida, execute o comando:
   
    pip install pymupdf markdownify

## 🛠️ Uso
***Depois de instalar as dependências, você pode converter seus PDFs em Markdown com o comando abaixo:***
   
    python convert_pdf_to_md.py caminho/para/seu/arquivo.pdf caminho/para/seu/arquivo.md

## Exemplo:
Coloque o arquivo PDF no diretório do projeto ou insira o caminho completo do arquivo.
Execute o comando acima substituindo caminho/para/seu/arquivo.pdf pelo nome ou caminho do seu arquivo PDF e caminho/para/seu/arquivo.md pelo nome ou caminho desejado para o arquivo .md.

***Exemplo de execução:***
   python convert_pdf_to_md.py ArquiteturaLimpa.pdf ArquiteturaLimpa.md
   
Isso vai gerar um arquivo Markdown formatado com base no conteúdo do PDF.

## 📁 Estrutura do Projeto
pdf-to-markdown-converter/
│
├── convert_pdf_to_md.py       # Script principal de conversão
├── README.md                  # Este arquivo!
└── requirements.txt           # Dependências do projeto

## 🤝 Contribuindo 
Contribuições são sempre bem-vindas! Se você quiser sugerir melhorias, detectar problemas ou adicionar novos recursos, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Fork o projeto
Crie sua branch de feature (git checkout -b minha-feature)
Commit suas mudanças (git commit -m 'Adicionei uma nova feature')
Faça o push para a branch (git push origin minha-feature)
Abra um pull request

Feito com ❤️ por Matheus Gonçalves. Se tiver alguma dúvida ou sugestão, entre em contato através do e-mail ou Rede Social.
