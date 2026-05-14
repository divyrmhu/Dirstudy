# DIRSTUDY

**DIRSTUDY** is an interactive, responsive educational web application designed to help students access comprehensive study guides and interact with an integrated AI personal tutor.

## Features

- **Comprehensive Study Guides**: Dedicated pages for various academic subjects:
  - Engineering Chemistry
  - Basic Electronics
  - Data Structures
  - Professional Communication (Coming Soon)
- **Integrated AI Personal Tutor**: Each subject page features a built-in AI chatbot powered by the `gemini-2.5-flash` model, ready to answer questions and explain complex topics in real-time.
- **Light & Dark Mode**: A sleek, fully responsive design powered by Tailwind CSS that seamlessly toggles between light and dark themes based on user preference, with state persistence across pages.
- **MathJax Support**: Native rendering of mathematical formulas and equations for STEM subjects.
- **Mobile Responsive**: Carefully crafted layouts that look great on both desktop monitors and mobile screens.

## Technologies Used

- **Frontend**: HTML5, Vanilla JavaScript
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- **AI Integration**: Google Generative AI (Gemini 2.5 Flash)
- **Math Rendering**: [MathJax](https://www.mathjax.org/)
- **Icons**: [Phosphor Icons](https://phosphoricons.com/)

## Getting Started

To run this project locally, simply clone the repository and open the `index.html` file in your preferred modern web browser. No complex build tools or dependencies are required.

```bash
git clone https://github.com/yourusername/dirstudy.git
cd dirstudy
# Open index.html in your browser
```

## Security Note

The Gemini API key is integrated directly into the client-side JavaScript. For production deployments (like GitHub Pages), ensure you configure **HTTP Referrer Restrictions** in the Google AI Studio console to restrict API key usage strictly to your domain to prevent unauthorized usage.

## License

This project is licensed under the MIT License.

---
<div align="center">
  Proudly Made in Bharat ❤️
</div>
