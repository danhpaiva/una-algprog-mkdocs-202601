# Una - Algoritmos e Programacao Template

Template padrão para documentação de Unidades Curriculares (UC) utilizando **MkDocs Material**.

## 🚀 Como usar este template
1. Clique no botão **"Use this template"** no topo deste repositório.
2. Clone o seu novo repositório.
3. Instale as dependências:
   ```bash
   python -m venv venv
   .\venv\Scripts\Activate  # Windows
   pip install -r requirements.txt

4. Inicie o servidor local: mkdocs serve.

### 🛠️ Tecnologias inclusas
MkDocs Material

Plugin de Busca (Search)

Plugin de Data de Revisão (Git Revision Date)

#### 2. Subindo as alterações
No seu terminal:

```powershell
# Adicionar o requirements.txt e as mudanças no yml
git add .
git commit -m "docs: finalize template with requirements and guide"
git push origin develop

# (Opcional) Levar para a main
git checkout main
git merge develop
git push origin main