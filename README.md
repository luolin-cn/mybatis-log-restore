# MyBatisLogRestore

## 如何使用
输入Mybatis中生成的Preparing和Parameters即可，可参考以下例子

## 比较好的例子

```sql
==>  Preparing: update table_a SET LAST_UPDATE_DATE = ?, LAST_UPDATED_BY = ?, OBJECT_VERSION_NUMBER = OBJECT_VERSION_NUMBER + 1, status = ?, amount = ?, date = ?, remark = ?, type_id = ?, flag = ?, receipt_place = ?, uuid = ?, code = ?, bank_id = ?, bank_f = ?, bank_b = ?, bank_account_name = ?, bank_account_num = ? WHERE a_id = ? AND OBJECT_VERSION_NUMBER = ?
==> Parameters: 2023-02-22 14:35:55.486(Timestamp), 977917(Long), A(String), 1.7200000000(BigDecimal), 2023-02-27 00:00:00.0(Timestamp), 77906各工厂12-1月，本次共计1元，合同账期3天。(String), 1283(Long), 0(Integer), null, null, NOT_IMPORT(String), -5(Long), 1022(String), 中国工商银行(String), 北京北(String), ~-q0kaoSB57tiN5MaSf15ycBotApMakPb5FFHuu10O5xE=1-~(String), 21(Long), 2(Long)
```
