# 🌮 The Little Taco Shop

A simple, multi-page website for **The Little Taco Shop (LTS)**, a fictional taco restaurant in Kansas City, MO. Built with plain HTML and a small amount of CSS as part of the [HTML for Beginners](https://www.youtube.com/playlist?list=PL0Zuz27SZ-6OlAwitnFUubtE93DO-l0vu) tutorial series by Dave Gray.

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | About the shop, a collapsible "Taco Trivia" section, and the menu table |
| Store Hours | `hours.html` | Opening hours, shown with a description list |
| Contact | `contact.html` | Contact form, shop address, and phone number |

## Features

- Semantic HTML5 structure (`header`, `nav`, `main`, `article`, `section`, `aside`, `footer`)
- Navigation links between all pages, plus in-page anchors (`#about`, `#menu`)
- Accessible images using `figure`, `figcaption`, and descriptive `alt` text
- Menu table with `caption`, `thead`, `tbody`, `tfoot`, `rowspan`, and `colspan`
- Expandable trivia using `<details>` and `<summary>`
- Contact form with labels, placeholders, required fields, and Send/Reset buttons
- Clickable phone number using a `tel:` link
- Favicon on every page

## Project Structure

```
.
├── index.html
├── hours.html
├── contact.html
├── favicon.ico
├── css/
│   └── style.css
├── img/
│   ├── tacos_and_drink_400x267.png
│   ├── tacos_close_up_400x260.png
│   └── tacos_tray_400x267.png
├── examples/
│   ├── home-example.png
│   ├── hours-example.png
│   └── contact-example.png
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open the project folder.
3. Open `index.html` in your web browser. No build step or dependencies are required.

## Technologies Used

- HTML5
- CSS3

## Notes

- The contact form submits to [httpbin.org](https://httpbin.org/get) for demonstration purposes only; no messages are actually delivered to a shop.
- The address, phone number, and shop details are placeholders.

## Credits

- Project challenge and tutorial: [Dave Gray](https://www.youtube.com/DaveGrayTeachesCode)
- Taco trivia source: [Smithsonian Magazine](https://www.smithsonianmag.com/arts-culture/where-did-the-taco-come-from-81228162/)
- Author: Mirshahin Ismayilov

## License

This project was created for learning purposes.
