# Thiranex Internship Task: Accessible Personal Portfolio

A responsive, multi-page personal portfolio built with semantic HTML5, CSS, and vanilla JavaScript.

## Pages
- `index.html` — Home
- `about.html` — About, skills, education, certifications
- `projects.html` — Projects and internship experience
- `contact.html` — Accessible contact form

## Run locally
1. Extract the ZIP file.
2. Open the `thiranex-portfolio` folder in Visual Studio Code.
3. Install the **Live Server** extension if it is not already installed.
4. Right-click `index.html` and choose **Open with Live Server**.
5. Test all four pages and the contact form.

You can also open `index.html` directly in a browser, but a local server is recommended.

## Personalise before submitting
- Replace `your-email@example.com` in `js/script.js` with your email address.
- Replace `https://your-domain.example/` canonical URLs in all HTML files after you have a real published domain. If you do not have a domain yet, remove the canonical link elements.
- Replace the LinkedIn placeholder URL in `contact.html` with your exact profile URL.
- Add your real internship organisation, dates, responsibilities, and project status.
- Add a profile photo only if you want one; provide meaningful alt text for informative images.
- Check that all details and claims are accurate.

## Accessibility features
- Semantic `header`, `nav`, `main`, `section`, `article`, `aside`, and `footer` elements.
- One clear page-level `h1` and logical heading order.
- Skip-to-main-content link.
- Native links, buttons, labels, inputs, and textarea controls.
- Visible keyboard focus and responsive navigation.
- Form instructions, native validation, and an announced status message.
- Reduced-motion preference support.
- Descriptive page titles and meta descriptions.

## Contact form note
The form validates fields in the browser and prepares an email using the visitor's default email application. It does **not** send or store messages on a server. For a production website, connect it to a secure form backend or form service.

## Accessibility and SEO testing
1. Open each page in Chrome.
2. Press `Tab` repeatedly and confirm the focus indicator is visible and the skip link works.
3. Test the contact form with empty, invalid, and valid values.
4. Run Lighthouse in Chrome DevTools on each page, using the Accessibility and SEO categories.
5. Fix any audit issues reported by the browser. Lighthouse scores can vary by browser version, environment, and page content; a score of 100 cannot be guaranteed without testing the final deployed site.

## Standards reference
- WCAG 2.2: https://www.w3.org/TR/WCAG22/
- W3C semantic HTML technique: https://www.w3.org/WAI/WCAG22/Techniques/html/H101
- W3C form labels tutorial: https://www.w3.org/WAI/tutorials/forms/labels/
