importance: 5

---

# طباعة قائمة متصلة فردية

هذه هي القائمة المتصلة كما ذكرناها في هذا الفصل <info:recursion>: 


```js
let list = {
  value: 1,
  next: {
    value: 2,
    next: {
      value: 3,
      next: {
        value: 4,
        next: null
      }
    }
  }
};
```
إكتب دالة `printList(list)` التي تقوم بطباعة القائمة واحداً تلو الأخر.

قم بحلها بطريقتين: 
1. مرة بإستخدام الحلقة:
2. مرة بإستخدام التكرار:

ماهو الأفضل: بالتكرار أم بدون التكرار؟
