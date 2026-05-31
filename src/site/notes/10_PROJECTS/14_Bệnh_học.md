---
{"dg-publish":true,"permalink":"/10-projects/14-benh-hoc/","created":"2026-05-27T19:26:13.294+07:00","dg-note-properties":{}}
---

## Hệ tiêu hóa

#### **Bệnh học**

```base
views:
  - type: table
    name: Bảng
    filters:
      and:
        - file.tags.contains("BH_tiêu_hóa")
    order:
      - file.name
      - dg-home
      - tags
      - file.mtime
      - BC
      - State
    columnSize:
      file.name: 132
      file.mtime: 123
      note.BC: 165

```



#### **Vi sinh** 

```base
views:
  - type: table
    name: Bảng
    filters:
      and:
        - file.tags.contains("VS_tiêu_hóa")
    order:
      - file.name
      - dg-home
      - tags
      - file.mtime
      - BC
      - State
    columnSize:
      file.name: 131
      note.tags: 144
      file.mtime: 93

```



### Hệ Tiết niệu
#### **Bệnh học**

```base
views:
  - type: table
    name: Bảng
    filters:
      and:
        - file.tags.contains("BH_tiết_niệu")

```



