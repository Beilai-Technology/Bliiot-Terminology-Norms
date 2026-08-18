# Beilai Terminology Library

A lightweight single-page terminology repository for Beilai.

## Open

- Local preview: double-click `index.html`
- GitHub Pages: push to GitHub and open the Pages URL

## Structure

- `index.html`: single-page terminology site
- `terms.js`: terminology data source
- `assets/style.css`: page styles
- `assets/logo.png`: brand logo

## How to add terms

Only edit `terms.js`.

Add one object in this format:

```js
{
  cn: "中文术语",
  en: "English Term",
  note: "备注说明"
}
```

Example:

```js
{
  cn: "串口服务器",
  en: "Serial Device Server",
  note: "用于产品分类或功能描述。"
}
```

## Notes

- No Chinese/English language switch
- All content is shown on one page
- Includes a client-side search box for quick filtering
- The table is rendered automatically from `terms.js`
