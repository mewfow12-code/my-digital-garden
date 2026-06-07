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

##### Nhiễm Khuẩn đường tiết niệu
**UTIs tái phát** thường được định nghĩa là có từ 3 đợt nhiễm trùng trở lên trong khoảng thời gian 12 tháng, hoặc từ 2 đợt nhiễm trùng trở lên trong khoảng thời gian 6 tháng. 

**UTI không phức tạp** là tình trạng xảy ra ở một phụ nữ khỏe mạnh, không mang thai, có đường tiết niệu sinh dục bình thường và không có tiền sử can thiệp thiết bị gần đây, bao gồm cả đặt ống thông bàng quang. 

Cấy nước tiểu là xét nghiệm chẩn đoán tiêu chuẩn vàng cho tất cả các UTIs


#### **Bệnh học**

![[Sơ đồ bệnh học tiết niệu.canvas\|Sơ đồ bệnh học tiết niệu.canvas]]


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
    columnSize:
      note.dg-publish: 109

```



### Nhiễm khuẩn đường tiết niệu
