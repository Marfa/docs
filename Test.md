---
title: "Тестовая заметка"
description: "Description of your new file."
---

**Поиск диагнозов к задаче**

```Plain
select doc_task_id, code from f_doc_diagnosis_processing
left join d_mkb10 d on f_doc_diagnosis_processing.mkb10_id = d.id
where doc_task_id = 109
```

**Обновить c\_mo\_task\_filter\_priority**

```Plain
insert into c_mo_task_filter_priority (mo_id, priority) values (204, 100);
insert into c_mo_task_filter_priority (mo_id, priority) values (10000454, 100);
insert into c_mo_task_filter_priority (mo_id, priority) values (10000290, 100);
insert into c_mo_task_filter_priority (mo_id, priority) values (141, 100);
insert into c_mo_task_filter_priority (mo_id, priority) values (10000394, 100);
insert into c_mo_task_filter_priority (mo_id, priority) values (10000287, 100);
insert into c_mo_task_filter_priority (mo_id, priority) values (10000363, 100);
insert into c_mo_task_filter_priority (mo_id, priority) values (10000377, 100);
insert into c_mo_task_filter_priority (mo_id, priority) values (10000268, 100);
insert into c_mo_task_filter_priority (mo_id, priority) values (10011503, 100);
```