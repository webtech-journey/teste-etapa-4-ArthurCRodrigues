# 🧪 Relatório de Avaliação – Autograder HTML - ArthurCRodrigues

**Data:** 11/04/2025 17:31

**Nota Final:** `6.67/100`
**Status:** ❌ Reprovado

---
## ✅ Requisitos Obrigatórios (80%)
- Foram encontrados `8` problemas nos requisitos obrigatórios. Veja abaixo os testes que falharam:
  - ⚠️ **Falhou no teste**: `test_base.py::test_bootstrap_css_included`
    - **Melhoria sugerida**: O CSS do Bootstrap está ausente. Certifique-se de incluir o link do CSS do Bootstrap na seção <head>.
  - ⚠️ **Falhou no teste**: `test_base.py::test_bootstrap_js_included`
    - **Melhoria sugerida**: O JS do Bootstrap está ausente. Certifique-se de incluir o arquivo JS do Bootstrap para garantir que os componentes interativos funcionem.
  - ⚠️ **Falhou no teste**: `test_base.py::test_profile_card_class`
    - **Melhoria sugerida**: A card de perfil com a classe 'card' está ausente. Certifique-se de implementar a card de perfil usando o componente de card do Bootstrap.
  - ⚠️ **Falhou no teste**: `test_base.py::test_profile_image_class`
    - **Melhoria sugerida**: A imagem de perfil está sem a classe 'rounded-circle'. Certifique-se de adicionar a classe 'rounded-circle' à imagem para o estilo correto.
  - ⚠️ **Falhou no teste**: `test_base.py::test_user_name_title`
    - **Melhoria sugerida**: O nome do usuário está ausente ou colocado incorretamente. Certifique-se de que o nome do usuário esteja em uma tag de título como h1, h2 ou h3.
  - ⚠️ **Falhou no teste**: `test_base.py::test_profile_description`
    - **Melhoria sugerida**: A descrição do perfil está ausente. Certifique-se de incluir uma breve descrição do perfil dentro de uma tag <p>.
  - ⚠️ **Falhou no teste**: `test_base.py::test_button_class`
    - **Melhoria sugerida**: O botão está sem a classe 'btn' ou não é interativo. Certifique-se de que o botão tenha a classe 'btn' e seja interativo usando JavaScript ou um link.
  - ⚠️ **Falhou no teste**: `test_base.py::test_d_flex_class_usage`
    - **Melhoria sugerida**: A classe 'd-flex' está ausente. Por favor, use a classe 'd-flex' para implementar o layout flexível quando necessário.

## ⭐ Itens de Destaque (20%)
- Nenhum item bônus foi identificado. Tente adicionar mais estilo e complexidade ao seu código nas próximas tentativas!

## ❌ Problemas Detectados (Descontos de até -30%)
- Foram encontrados `2` problemas que acarretam descontos. Veja abaixo os testes penalizados:
  - ⚠️ **Falhou no teste de penalidade**: `test_penalty.py::test_missing_or_incorrect_alt_text`
    - **Correção sugerida**: A imagem de perfil está ausente ou com o texto 'alt' incorreto. Por favor, adicione um texto 'alt' apropriado para acessibilidade.
  - ⚠️ **Falhou no teste de penalidade**: `test_penalty.py::test_unnecessary_custom_javascript`
    - **Correção sugerida**: Foi encontrado JavaScript personalizado desnecessário. Evite usar JavaScript personalizado quando a funcionalidade interna do Bootstrap for suficiente.

---
Continue praticando e caprichando no código. Cada detalhe conta! 💪
