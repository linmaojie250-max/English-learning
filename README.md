# English Learning

这是一个用于长期积累、复习和导出个人英语学习资料的仓库。内容按类型存放，并以总库与每周增量相结合的方式维护。

## 目录结构

```text
English-learning/
├─ vocabulary/
│  ├─ README.md
│  └─ weekly/
│     └─ README.md
├─ phrases/
│  └─ README.md
├─ sentences/
│  └─ README.md
├─ grammar-notes/
│  ├─ README.md
│  └─ weekly/
│     └─ README.md
├─ reading-notes/
│  └─ README.md
├─ review/
│  └─ README.md
├─ exports/
│  └─ README.md
└─ templates/
   └─ README.md
```

## 推荐工作流

1. 遇到新单词时，先记录到 `vocabulary/weekly/YYYYWww.xlsx`。
2. 固定搭配和短语放入 `phrases/`，值得模仿的完整句子放入 `sentences/`。
3. 对查询句子的结构、时态、搭配和仿写说明放入 `grammar-notes/weekly/`。
4. 阅读文章、书籍或视频字幕后的笔记放入 `reading-notes/`。
5. 每周从新增内容生成复习清单，存入 `review/`。
6. 需要打印、分享或导入其他应用的文件放入 `exports/`，不要把导出文件当作唯一数据源。
7. 新建表格或笔记时优先复用 `templates/` 中的模板。

## 命名约定

- 周度目录或文件使用 ISO 周编号：`YYYYWww`，例如 `2026W37`。
- 文件名使用小写英文和连字符，避免空格。
- 日期使用 `YYYY-MM-DD`。
- 不覆盖历史周文件；新一周创建新文件。

## 建议的生词字段

`word`、`phonetic`、`part_of_speech`、`definition_en`、`meaning_zh`、`usage_notes`、`collocations`、`example_sentence`、`synonyms`、`source`、`date_added`、`mastery_level`、`last_reviewed`、`next_review`。

熟练度建议使用 1–5：1 表示刚收录，5 表示能够熟练理解和使用。
