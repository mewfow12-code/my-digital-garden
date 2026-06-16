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
      - dg-publish
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
      - dg-publish
      - tags
      - file.mtime
      - BC
      - State
    sort:
      - property: dg-home
        direction: ASC
    columnSize:
      file.name: 131
      note.tags: 144
      file.mtime: 93

```



### Hệ Tiết niệu
#### **Khái niệm chung**

##### **Nhiễm Khuẩn đường tiết niệu (UTIs)**
- **UTIs tái phát** thường được định nghĩa là có từ 3 đợt nhiễm trùng trở lên trong khoảng thời gian 12 tháng, hoặc từ 2 đợt nhiễm trùng trở lên trong khoảng thời gian 6 tháng. 
- **UTI khu khú (localized UTIs)** được định nghĩa là UTIs tại bàng quang không có bất kỳ triệu chứng của UTI toàn thân nào. 
- **UTI toàn thân (systematic UTIs)** được định nghĩa là UTI có các triệu chứng toàn thân hay không có triệu chứng UTI khu trú.

```sheet
| Triệu chứng Khu trú (Localised UTI) | Triệu chứng Toàn thân (Systemic UTI) |
| ----------------------------------- | ------------------------------------ |
| Tiểu buốt (đau, rát, châm chích)    | Sốt (> 38 độ ) hoặc hạ thân nhiệt    |
| Tiểu gấp                            | Rét run, ớn lạnh                     |
| Tiểu lắt nhắt / tiểu nhiều lần      | Lú lẫn                               |
| Xón tiểu                            | Tụt huyết áp                         |
| Chảy mủ niệu đạo                    | Nhịp tim nhanh                       |
| Căng tức hoặc đau quặn bụng dưới    | Ấn đau góc sườn thắt lưng            |
```

> [!NOTE] Tài liệu tham khảo: 
> EAU Guidelines on Urological Infections (2025). https://drive.google.com/file/d/1t0-PGVUH_Bhoc9MJkLc7LLTmA4fcbjSY/view?usp=sharing
##### **Biến chứng của UTIs**
- [[Nhiễm trùng huyết\|Nhiễm trùng huyết]] (Sepsis) và sốc nhiễm trùng

#### **Bệnh học**

![[40_MOCS/Sơ đồ bệnh học tiết niệu.canvas\|Sơ đồ bệnh học tiết niệu.canvas]]


```base
views:
  - type: table
    name: Bảng
    filters:
      and:
        - file.tags.contains("BH_tiết_niệu")
    order:
      - file.name
      - dg-publish
      - file.tags
      - State
      - Ghi chú
    columnSize:
      note.dg-publish: 109
      file.tags: 171

```


### Nhiễm khuẩn đường tiết niệu





