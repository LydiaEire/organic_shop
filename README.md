## Organic Food Website
This is a website dedicated to promoting and showcasing organic food products. It has been developed using HTML, CSS, BEM methodology, and SCSS to ensure maintainability and scalability of the codebase. The backend is powered by Flask, a Python web framework.

### Features
- Home Page: Introduction to organic food and featured products.
- Shop Page: Details about various organic products available.
- Shop Single Page: A product card. 
- Our Team: Some details about people involved. 
- About Us: Information about the company or organization behind the website.
- Contact Page: A form for users to get in touch or provide feedback.

### Technologies Used
HTML5: Provides the structure of the web pages.
CSS3: Styles the elements and layouts of the website.
BEM Methodology: Organizes and names CSS classes for better maintainability.
SCSS: Utilized to write more structured and efficient CSS code.

### How to Use
Clone the repository: git clone https://github.com/yourusername/organic-food-website.git

### Contributors
- Contributor: https://github.com/AnzhelaR2202
- Contributor: https://github.com/NataParis
- Contributor: https://github.com/yana-mysh
- Contributor: https://github.com/alinarbcv

### License
This project is licensed under the MIT License.


## Методология оформления

Данный проект использует методологию BEM (Block-Element-Modifier) для структурирования CSS и HTML кода.

### BEM (Block-Element-Modifier)

BEM предполагает деление ваших компонентов на блоки, элементы и модификаторы. Это помогает упростить именование классов и сделать ваш код более понятным и поддерживаемым.

#### Пример структуры классов BEM:

- `.block` - это основной блок, например, `.product-card`.
- `.block__element` - элемент внутри блока, например, `.product-card__title`.
- `.block--modifier` - модификатор блока, например, `.product-card--highlighted`.

При написании новых стилей, пожалуйста, следуйте методологии BEM для удобства сопровождения и расширения проекта.

### Использование SCSS (Sass)
Данный проект использует SCSS (Sass) для удобства написания стилей CSS с использованием препроцессора. SCSS предоставляет множество дополнительных возможностей и инструментов для более эффективной разработки стилей.

### Структура файлов
Файлы SCSS располагаются в директории style и разделены на более мелкие файлы для упрощения поддержки и организации кода:
- `style.scss` - основной файл SCSS, который объединяет все другие файлы стилей.
- `_vars.scss` - файл, содержащий переменные (цвета, размеры, шрифты и т.д.).
- `_mixins.scss`- файл с миксинами для повторного использования стилевых правил.
- `_template.scss` - cтили для базовых элементов (например, body, a, header, footer, input и т.д.).
- `_components.scss` - cтили для компонентов страницы (кнопки, карточки продуктов и т.д.).


