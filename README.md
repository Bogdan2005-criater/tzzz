**Техническое задание: Учебный сайт "Семантика и контейнеры"**  

---

### **Цель проекта**  
Создать одностраничный сайт для отработки навыков работы с семантическими тегами HTML и контейнерами.  

---

### **Структура сайта**  
1. **Шапка (header)**  
   - Заголовок: "Мой учебный проект".  
   - Навигационное меню (nav) с якорными ссылками: "О себе", "Расписание", "Предметы", "Цитаты".  

2. **Основной контент (main)**  
   - Секции (section) с контентом:  
     - **"О себе"**: Краткая информация об ученике (имя, возраст, увлечения).  
     - **"Моё расписание"**: Таблица с расписанием уроков на неделю.  
     - **"Любимые предметы"**: Список предметов с кратким описанием для каждого (article).  
     - **"Вдохновляющие цитаты"**: 2-3 цитаты с указанием автора (blockquote + cite).  

3. **Боковая панель (aside)**  
   - Дополнительная информация: например, список полезных ресурсов для учёбы.  

4. **Подвал (footer)**  
   - Контакты: email или соцсети (использовать тег `address` для контактной информации).  

---

### **Требования к верстке**  
- Обязательные семантические теги: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `blockquote`, `address`.  
- Контейнеры `div` разрешены только для стилизации (например, группировка элементов внутри секции).  
- HTML-документ должен проходить валидацию через [W3C Validator](https://validator.w3.org/).  

---

### **Дизайн**  
- Минималистичный стиль.  
- Обязательные элементы:  
  - Четкое разделение секций (границы или отступы).  
  - Удобочитаемые шрифты (например, Arial или sans-serif).  
  - Фон секций — светлый, текст — тёмный.  

---

### **Инструкция для ученика**  
1. Создать базовую структуру HTML-документа с семантическими тегами.  
2. Наполнить каждую секцию контентом, соблюдая правила:  
   - Для текста использовать параграфы (`p`), списки (`ul/ol`), заголовки (`h2-h3`).  
   - В разделе "Расписание" добавить таблицу (`table`, `tr`, `td`).  
3. Группировать элементы внутри секций с помощью `div` (например, обертка для карточки предмета).  
4. Проверить код через валидатор.  

---

### **Критерии проверки**  
1. Правильное использование семантических тегов.  
2. Логичная структура документа (без лишних `div`).  
3. Наличие всех требуемых секций и контента.  
4. Валидный HTML-код.  

---

**Пример кода для секции "Любимые предметы":**  
```html
<section id="subjects">
  <h2>Любимые предметы</h2>
  <div class="subject-card">
    <article>
      <h3>Математика</h3>
      <p>Люблю решать задачи по алгебре и геометрии.</p>
    </article>
  </div>
</section>
```

**Примечание:** CSS можно подключить, но фокус — на HTML-структуре.
