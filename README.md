# framework-intangiveis-fintechs

Aplicativo Streamlit para exploração do framework de intangíveis em fintechs.

## Executar localmente

```bash
python -m pip install -r requirements.txt
streamlit run app.py
```

A matriz integrada é opcional para abrir a interface. Para carregar os dados da
matriz, coloque um arquivo `.xlsx` com nome `03_MATRIZ_INTEGRACAO.xlsx`,
`04_BASE_CONSOLIDADA.xlsx`, `06_MATRIZ_EVIDENCIAS.xlsx` ou contendo `MATRIZ`
no nome, na pasta do aplicativo.

## Publicar no Streamlit Community Cloud

1. Entre em [share.streamlit.io](https://share.streamlit.io/) com a conta GitHub que tem acesso ao repositório.
2. Crie um app selecionando o repositório `framework-intangiveis-fintechs`, a branch `main` e o arquivo `app.py`.
3. Selecione **Deploy**. O Streamlit instalará as dependências de `requirements.txt`.

Se a matriz for necessária na versão publicada, inclua o arquivo `.xlsx` no
repositório antes do deploy. Verifique se ele pode ser compartilhado
publicamente antes de adicioná-lo.