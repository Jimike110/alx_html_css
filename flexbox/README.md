# Flexbox Project

This project was part of the ALX Introduction to Software Engineering program, focusing on mastering CSS Flexbox for web layout.

## Project Description

In this project, I applied CSS Flexbox to create flexible and responsive layouts for webpages. Flexbox is a powerful CSS feature that simplifies the arrangement and alignment of elements within a container.

### Project Tasks

#### Task 0: Add display flex

- Utilized the `display: flex` property on the container to make all direct children become flex-items.
- Removed the `float: left` inside `[class*='col-']` to ensure elements appeared as expected without using float.
- Removed the `row::after` declaration.

#### Task 1: Add new classes on sections

- Added specific classes to the outermost section tags for different sections of the webpage.

#### Task 2: Reverse order Latest news cards

- Set the `flex-direction` property to `row-reverse` for the row class inside section-latest-news to display the Latest news cards in reverse order.

#### Task 3: Simplify services list

- Combined the two ul elements in the Services section into a single ul.
- Applied the `flex-wrap` property with a value of `wrap` to the row class inside the section-services to ensure proper wrapping of items.

#### Task 4: Playing around with the spacing between flex service items

- Adjusted the width of `.col-1-3` and `.col-1-2` selectors using `calc` to create proper spacing.
- Replaced padding with margin in `[class*='col-']` selectors.
- Updated the margin in the ul.row declaration.

#### Task 5: Flexify the header

- Wrapped the divs with class header-logo and navbar-menu with a div having the class header-container.
- Set the `display: flex` and `justify-content: space-between` properties for the header-container class.
- Removed unnecessary CSS rules for header-logo and navbar-menu.

#### Task 6: Flexify the navbar

- Applied `display: flex` to the nav class selector.
- Removed the display declaration within .nav .nav-item selector.
- Modified the margin declaration for .nav-item + .nav-item.
- Adjusted the value of the nav-item-margin variable.

#### Task 7: Align center logo and navbar

- Set the `align-items` property to `center` for the header-container class.

### Project Structure

- **Directory:** `flexbox`
- **Files:** (These files were created and modified as part of the project)
  - `0-index.html`
  - `0-styles.css`
  - `1-index.html`
  - `1-styles.css`
  - `2-index.html`
  - `2-styles.css`
  - `3-index.html`
  - `3-styles.css`
  - `4-index.html`
  - `4-styles.css`
  - `5-index.html`
  - `5-styles.css`
  - `6-index.html`
  - `6-styles.css`
  - `7-index.html`
  - `7-styles.css`

## License
This project is licensed under the MIT License - see the [LICENSE](https://mit-license.org/) page for details.

## Contact

For any inquiries or questions, feel free to contact me:

- Name: Michael Oladoye
- Email: [email me](mailto:oladoyemike@gmail.com)
- LinkedIn: [Michael Oladoye](https://www.linkedin.com/in/jimike/)
- X (formerly Twitter): [@jimikeCodes](https://twitter.com/jimikeCodes)
