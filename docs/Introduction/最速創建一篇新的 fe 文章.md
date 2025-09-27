# 最速創建一篇新的 fe 文章

## 複製粘貼原始md文件
  - 進入您的 fe 項目目錄
  - 複製原始 Markdown 文件到 `docs/Introduction/` 目錄
  - 重命名文件，例如 `最速創建一篇新的 fe 文章.md`

![GitHub全自動部署-20.png](https://cloudflare-imgbed-7oz.pages.dev/file/1758996239126_GitHub全自動部署-20.png)

## 添加文章索引
  - 進入您的 fe 項目目錄
  - 打開 `docs/.vitepress/sibeBar/FrontEndSideBar.js` 文件
  - 搜索 `export default function FrontEndSideBar` 函數
  - 在該函數裏的 `items` 數組中，依葫蘆畫瓢填入一下内容
```typescript
                {
                    text: '最速創建一篇新的 fe 文章',
                    link: '/Introduction/最速創建一篇新的 fe 文章/',
                },
```