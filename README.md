# SwiftStyle

**SwiftStyle** is a lightweight, efficient, and easy-to-use CSS utility library that helps you build responsive, flexible, and well-aligned layouts with minimal effort. With predefined utility classes for layout, spacing, alignment, and more, SwiftStyle is perfect for rapid prototyping and building clean, modern web designs.

## Features

- **Responsive Containers**: Flexible container classes for all screen sizes.
- **Box Styling**: Quick box styling with borders, padding, shadows, and rounded corners.
- **Alignment Utilities**: Flexbox and text alignment utilities for centering and aligning elements.
- **Grid System**: Simple grid system for responsive layouts.
- **Spacing Utilities**: Predefined margin and padding classes.
- **Positioning**: Relative, absolute, and fixed positioning utilities.
- **Visibility Control**: Show or hide elements with ease.
- **Text Styling**: Quick utilities for text transformations, weights, and sizes.

## Installation

### Option 1: Download the CSS File

To use **SwiftStyle**, simply download the `styles.css` file and link it in the `<head>` section of your HTML file:

```html
<link rel="stylesheet" href="path-to-your-file/styles.css">
### Option 2: Copy and Paste CSS

Alternatively, you can copy the contents of the `styles.css` file and paste it directly inside a `<style>` tag in your HTML file:

```html
<style>
  /* Paste the contents of styles.css here */
</style>
```

## Usage

### Basic Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SwiftStyle Example</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <div class="container">
    <h1 class="text-center">SwiftStyle Example</h1>
    <p class="text-center">This page demonstrates how the utility classes work from SwiftStyle.</p>

    <div class="box center">
      <p>This box is centered both horizontally and vertically.</p>
    </div>

    <div class="box align-left">
      <p>This box is aligned to the left.</p>
    </div>

    <div class="box v-center">
      <p>This box's content is vertically centered.</p>
    </div>

    <div class="row">
      <div class="col box">
        <p>Column 1</p>
      </div>
      <div class="col box">
        <p>Column 2</p>
      </div>
      <div class="col box">
        <p>Column 3</p>
      </div>
    </div>
  </div>

</body>
</html>
```

### Available Classes

Here are some of the key utility classes available in **SwiftStyle**:

#### Container Classes

- `.container`
- `.container-sm`
- `.container-md`
- `.container-lg`
- `.container-xl`

#### Box Styling

- `.box`
- `.border-1`
- `.shadow-sm`
- `.shadow-lg`
- `.border-radius`

#### Alignment Utilities

- `.text-left`, `.text-right`, `.text-center`, `.text-justify`
- `.center`, `.center-horizontal`, `.center-vertical`
- `.align-start`, `.align-center`, `.align-end`
- `.justify-start`, `.justify-center`, `.justify-end`

#### Flexbox & Grid Layout

- `.flex-row`, `.flex-column`, `.flex-wrap`
- `.grid`, `.grid-2`, `.grid-3`, `.grid-4`

#### Spacing Utilities

- `.mt-20`, `.mb-10`, `.p-10`, `.ml-20`, `.mr-30`

#### Positioning

- `.position-relative`, `.position-absolute`, `.position-fixed`

#### Visibility

- `.hidden`, `.visible`

#### Text Styling

- `.text-bold`, `.text-italic`, `.text-uppercase`, `.text-large`, `.text-small`

### Responsive Design

**SwiftStyle** includes several responsive classes to ensure your layout adapts seamlessly to different screen sizes:

- `.container-sm` — for small screens (max-width: 576px)
- `.container-md` — for medium screens (max-width: 768px)
- `.container-lg` — for large screens (max-width: 992px)
- `.container-xl` — for extra-large screens (max-width: 1200px)

### Example of Responsive Usage

```html
<div class="container-sm">
  <p>This container will be responsive on small screens.</p>
</div>
```

## Contributing

We welcome contributions! If you find any bugs or have ideas for new features, feel free to fork the repository, make your changes, and submit a pull request.

## License

**SwiftStyle** is licensed under the [MIT License](LICENSE).
```

---

### How to use it:

1. **Create a file named `README.md`** in the root directory of your GitHub repository.
2. **Copy and paste** the above code into your `README.md` file.
3. **Save** the file.
4. **Push** it to your GitHub repository.

This will provide users with clear instructions on how to install, use, and contribute to the **SwiftStyle** CSS library. Let me know if you need any changes or additions!
