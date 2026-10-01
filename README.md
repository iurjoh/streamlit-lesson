# Streamlit lesson

[Português (Brasil)](README.pt-BR.md)

## Idea and process

Supporting material for learning Streamlit commands, widgets, multipage structure and a calculator. Source reviewed on 2026-10-01. This is a fork of course material, not an original dashboard product or a reconstructed personal development diary. No dated plan, user research or wireframes were found in the reviewed files.

## Architecture and design

`1_commands_and_widgets.py` actively renders "Hello world!!!!" and a divider. Its text, data, plot, cache, widget and media examples are commented out. They are teaching examples, not all active features.

`2_app_with_multiple_pages.py`, `3_calculator.py` and the four Python files in `app_pages/` are blank or whitespace-only. A working multipage app and calculator are therefore not implemented in the reviewed files. Streamlit supplies the interface rendering; no separate design system is documented.

## Local setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
streamlit run 1_commands_and_widgets.py
```

Requirements pin Streamlit 0.85.0, NumPy 1.19.2, pandas 1.1.2 and other historical plotting dependencies. Use a compatible disposable environment; installation and runtime were not verified here. Commented examples use older APIs such as `st.cache` and `st.beta_columns`, so review compatibility before enabling them on a newer stack.

## Testing and limits

No automated test files were found in the reviewed root/app_pages listings. No application or tests were run in this update and no public deployment was verified. If extending the lesson, enable one example at a time, check rerun/widget behavior, test numeric and invalid calculator inputs and verify multipage routing only after implementing it. Do not treat blank files as completed features.

## Snapshots

No screenshot was added or verified. Future captures should show the actual enabled examples, use synthetic data and dated files under `docs/assets/`. Label a hello-world capture as hello world, not as a working dashboard or calculator. Add image links only once the files exist.

## Credits and licensing

Forked from [Code-Institute-Solutions/streamlit-lesson](https://github.com/Code-Institute-Solutions/streamlit-lesson). Original course source remains unchanged. No new license is applied to third-party material. The original short README is preserved below.

---

## Original README

# Supporting material for lessons on Tools Mechanism

* Script to teach commands and widgets at Streamlit
* Script to create a set of blank pages in Streamlit
* Small Calculator project combining python logic and Streamlit widgets
