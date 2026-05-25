---
{"dg-publish":true,"permalink":"/10-projects/11-tiep-can-benh-nhan/","noteIcon":"","created":"2026-05-25T14:50:28.226+07:00","dg-note-properties":{}}
---

**Sơ đồ lập luận lâm sàng:** [[40_MOCS/sơ đồ lập luận lâm sàng.canvas\|sơ đồ lập luận lâm sàng.canvas]]
![image.png](https://pub-0f3d5db202bd49b5be3e8ab177fb5e6b.r2.dev/20260525183254978.png)

---
### Biện luận các triệu chứng


```base
views:
  - type: table
    name: Bảng
    filters:
      and:
        - file.name.startsWith("11_")
        - '!file.path.contains("10_PROJECTS")'
    order:
      - file.name
      - file.mtime
      - dg-publish
    sort:
      - property: file.ctime
        direction: ASC

```


---
### Khác liên quan
