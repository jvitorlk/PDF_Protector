# Protetor de PDF -  um aplicativo Web para modificar PDF com Flask

Este é um aplicativo web simples que permite aos usuários fazer upload de um arquivo PDF e aplicar uma modificação nele. O aplicativo utiliza o framework Flask para criar uma interface web para a modificação de PDFs.

Você pode visualizar meu aplicativo [clicando aqui](https://pdf-protector-40nn.onrender.com/)

## Requisitos

Antes de executar este aplicativo, você precisa ter as seguintes bibliotecas Python instaladas:
- flask
- flask-wtf
- wtforms
- PyPDF2
- reportlab

Você pode instalar as bibliotecas usando o pip:
```bash
pip install flask flask-wtf wtforms PyPDF2 reportlab
```

## Como Executar
Para executar o aplicativo, siga estas etapas:

1. Clone este repositório:

```bash
git clone https://github.com/jvitorlk/PDF_Protector.git
cd PDF_Protector
```

2. Execute o aplicativo:
```bash
flask --app app run --debug
```

3. Acesse o aplicativo no seu navegador em [http://127.0.0.1:5000](http://127.0.0.1:5000).

## Uso
O aplicativo permite que os usuários façam o upload de um arquivo PDF e especifiquem um CPF, posição e cor para a modificação. Quando o formulário é enviado, o aplicativo modifica o PDF de acordo com as opções escolhidas e disponibiliza o arquivo modificado para download.

## Estrutura do Código
- `app.py`: O arquivo principal que define o aplicativo Flask e suas rotas.
- `pdf_modifier.py`: Presume-se que seja um módulo personalizado que contém a lógica de modificação de PDF.
- `templates/index.html`: Um modelo HTML para a página da web.
- `uploads/`: Uma pasta onde os arquivos PDF enviados pelos usuários são armazenados.

## Contribuição

Sinta-se à vontade para contribuir para este projeto abrindo problemas ou enviando solicitações pull. Se você tiver alguma melhoria ou correção a ser feita, teremos prazer em considerá-la.
