---
title: Использование атрибута aria-label
slug: orphaned/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-label_attribute
---

Атрибут [`aria-label`](https://www.w3.org/TR/wai-aria/#aria-label) создаёт текстовую метку текущего элемента в случае отсутствия видимого текста описания элемента. Если есть видимый текст, обозначающий элемент, используйте вместо этого [aria-labelledby](/ru/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-labelledby_attribute "Using the aria-labelledby attribute").

Этот атрибут может быть использован для любого стандартного HTML-элемента; не ограничивается элементами с ARIA `role`.

### Значение

строка

### Возможные эффекты на клиентские приложения и вспомогательные технологии

> **Примечание:** Мнения могут отличаться от того, как вспомогательные технологии должны справляться с этой техникой. Информация, представленная выше, является одним из таких мнений и поэтому не является нормативной.

## Примеры

#### Пример 1: Множественные лейблы

В примере ниже, кнопка стилизована под типичную кнопку "закрыть" с X посередине. Поскольку нет ничего обозначающего значение того, что кнопка закрывает диалог, то `aria-label` атрибут используется чтобы обеспечить метку для любой вспомогающей технологии.

```
<button aria-label="Close" onclick="myDialog.close()">X</button>
```

#### Рабочие примеры:

### Примечания

- Чаще всего API доступности для лейбла привязывается к свойству _accessible name_.
- Атрибуты, включая **aria-label,** игнорируются большинством автоматических сервисов перевода**.**

### Использование ARIA ролями

Все элементы базовой разметки

### Связанные ARIA техники

- [Использование атрибута aria-labelledby](/ru/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-labelledby_attribute "en/ARIA/ARIA_Techniques/Using_the_aria-labelledby_attribute")

### Совместимость

Будет определено позднее: Добавить информацию о поддержке для общих комбинаций продуктов UA и AT

### Дополнительные ресурсы

- [WAI-ARIA спецификация для aria-label](https://www.w3.org/TR/wai-aria/#aria-label)
