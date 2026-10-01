# Streamlit lesson

[English](README.md)

## Ideia e processo

Material de apoio para aprender comandos, widgets, estrutura multipágina e calculadora em Streamlit. Código revisado em 01/10/2026. Fork de material de curso, não dashboard original ou diário pessoal reconstruído. Não foram encontrados plano datado, pesquisa de usuários ou wireframes nos arquivos revisados.

## Arquitetura e design

`1_commands_and_widgets.py` renderiza ativamente "Hello world!!!!" e um divisor. Exemplos de texto, dados, gráficos, cache, widgets e mídia estão comentados: são exemplos de ensino, não funcionalidades todas ativas.

`2_app_with_multiple_pages.py`, `3_calculator.py` e os quatro arquivos Python em `app_pages/` estão vazios ou só têm espaços. Aplicação multipágina e calculadora funcional não estão implementadas nos arquivos revisados. Streamlit renderiza a interface; não há design system separado documentado.

## Execução local

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
streamlit run 1_commands_and_widgets.py
```

Requirements fixa Streamlit 0.85.0, NumPy 1.19.2, pandas 1.1.2 e outras dependências históricas de gráficos. Use ambiente compatível e descartável; instalação e execução não foram verificadas aqui. Exemplos comentados usam APIs antigas como `st.cache` e `st.beta_columns`; revise compatibilidade antes de ativá-los em stack atual.

## Testes e limites

Não foram encontrados testes automatizados nas listagens revisadas da raiz/app_pages. Aplicação e testes não foram executados; nenhum deploy público foi confirmado. Ao expandir, ative um exemplo por vez, verifique rerun/widgets, teste entradas numéricas/inválidas e navegação multipágina só depois de implementá-la. Arquivos vazios não são funcionalidades completas.

## Capturas

Nenhuma captura adicionada ou verificada. Capturas futuras devem mostrar exemplos realmente habilitados, dados fictícios e arquivos datados sob `docs/assets/`. Identifique hello world como hello world, não como dashboard ou calculadora funcional. Só adicione links depois que os arquivos existirem.

## Créditos e licença

Fork de [Code-Institute-Solutions/streamlit-lesson](https://github.com/Code-Institute-Solutions/streamlit-lesson). Código original do curso mantido. Nenhuma licença nova aplicada a material de terceiros. README original preservado no [apêndice em inglês](README.md#original-readme).
