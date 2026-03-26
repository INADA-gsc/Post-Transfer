# 転送後プロセス

## ファイル移動UIサンプル

```mermaid
graph TD
    subgraph SP_Page [SharePoint ページ]
        direction TB
        Title[📂 ファイル移動センター]
        Guide[操作：左から右へドラッグ＆ドロップ]

        subgraph ActionArea [作業エリア]
            direction LR
            Source[📥 SP受け取りBOX] -->|D&D| Dest[📤 Fileforceフォルダ]
        end
    end

    style SP_Page fill:#f9f9f9,stroke:#333
    style ActionArea fill:#fff
