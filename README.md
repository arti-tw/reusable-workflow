# Reusable Workflow
提供本組織慣用的 GitHub Action Workflow 供其他專案 reuse

## Usage
- 在 `.github/workflows` 目錄下新增檔案
- 透過 `uses` 指定本組織的 workflow:
- 範例: 
    - `uses: arti-tw/reusable-workflow/.github/workflows/coding-style-python.yml`，即可使用 coding-style-python.yml 的 workflow

## Reference
- https://stackoverflow.com/a/72708636
