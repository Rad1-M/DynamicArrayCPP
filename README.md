# DynamicArrayCPP
كلاس C++ لإدارة مصفوفة ديناميكية مع كل العمليات الأساسية (إضافة، حذف، تعديل، عكس، تغيير حجم)
تمام، هذه نسخة **README.md** جاهزة لمشروعك، مكتوبة بأسلوب واضح ومبسّط:

````markdown
# Dynamic Array Class in C++

هذا المشروع عبارة عن **كلاس Dynamic Array** باستخدام **Template** في C++، يتيح لك التعامل مع أي نوع بيانات وإدارة مصفوفة ديناميكية بسهولة.

---

## الميزات

- إنشاء مصفوفة بأي حجم وحذفها بأمان.
- إضافة عناصر في البداية، النهاية، أو أي موقع تحدده.
- حذف عناصر بالموضع أو بالقيمة مباشرة.
- الوصول لأي عنصر وتغيير قيمته بسهولة.
- تغيير حجم المصفوفة، قلب ترتيب العناصر، أو مسحها بالكامل.
- طباعة المصفوفة للاختبار والمتابعة.

---

## Features (English)

- Create an array of any size and delete it safely.
- Add elements at the beginning, end, or any position.
- Delete elements by index or by value directly.
- Access any element and modify its value easily.
- Resize the array, reverse its order, or clear it completely.
- Print the array for testing and tracking.

---

## كيفية الاستخدام

1. قم بإنشاء كائن من الكلاس:

```cpp
clsDynamicArray<int> myArray(5); // مصفوفة من 5 عناصر
````

2. إضافة عناصر:

```cpp
myArray.InsertAtEnd(10);
myArray.InsertAtBeginning(5);
```

3. حذف عناصر:

```cpp
myArray.DeleteFirstItem();
myArray.DeleteItem(10);
```

4. الوصول وتعديل العناصر:

```cpp
int val = myArray.GetItem(0);
myArray.SetItem(1, 20);
```

5. تغيير الحجم أو قلب المصفوفة:

```cpp
myArray.Resize(10);
myArray.Reverse();
```

---

## Notes

* يستخدم الكلاس **new** و **delete[]** لإدارة الذاكرة.
* المثال يوضح التعامل مع **dynamic memory** في C++ بشكل عملي.
* الكلاس عام **Template**، لذلك يمكن استخدامه مع أي نوع بيانات (int, float, string…).


