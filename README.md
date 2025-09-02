# Omar Elsadany - Mobile Developer Portfolio

A modern, professional, and responsive portfolio website showcasing my skills and projects as a Mobile Developer, with a focus on Flutter and Android.

## 🌟 Features

- **Clean & Modern Design**: A professional layout optimized to highlight technical skills and projects.
- **Fully Responsive**: Looks great on all devices, from mobile phones to desktops.
- **Interactive Contact Form**: A seamless, asynchronous contact form that provides instant feedback with a responsive toast notification without reloading the page.
- **Dynamic Content**: Sections for an introduction, about me, technical skills, featured projects, and contact information.

## 🛠️ Technologies Used

- **HTML5**: Semantic and accessible markup.
- **CSS3**: Custom styling for a modern look and feel, including responsive design with media queries.
- **JavaScript (ES6+)**: Powers the interactive contact form and toast notifications.
- **Formspree**: Handles the contact form backend to forward messages to my email.
- **Font Awesome**: Provides professional icons throughout the site.
- **Google Fonts**: Uses the "Inter" font family for clean and modern typography.

## 📁 Project Structure

```
portfolio/
│
├── index.html          # Main HTML file containing all content, styles, and scripts
├── style.css           # Main CSS styles for layout and design
└── README.md           # This documentation file
```

## 🚀 Getting Started

1.  **Clone the repository**
    ```bash
    git clone https://github.com/omarelsadanyy/portfolio.git
    cd portfolio
    ```

2.  **Open in your browser**
    Simply open the `index.html` file in your web browser to view the site.

## 🔧 Customization

All content can be easily updated by editing the `index.html` file.

#### Personal Information & Content
- **Update Name/Logo**: Change the text in `<div class="logo">Omar Elsadany</div>`.
- **Update Hero/About Text**: Modify the text in the `#home` and `#about` sections.
- **Update Profile Picture**: Replace the image URL `https://i.postimg.cc/ZnYCpcgX/IMG-1288.jpg` in the `.hero-image` and `.about-image` divs.
- **Update Contact Details**: Change the `href` and text for your Email, LinkedIn, and GitHub in the `#contact` section.

#### Skills & Projects
- **Skills**: Add or remove `<span class="skill-tag">` elements within the `#skills` section.
- **Projects**: Update the `.project-card` divs in the `#projects` section with your own project details and links.

#### Contact Form
- To change the email recipient, create a new form on [Formspree](https://formspree.io/) and replace the URL in the `<form action="...">` attribute.

#### Styling
- General styles can be modified in `style.css`.
- The toast notification styles are located in the `<style>` block in the `<head>` of `index.html`.

## 📱 Responsive Design

The website is built with a mobile-first approach. The toast notification includes a media query to adjust its position based on screen size:
- **Mobile (and default)**: Appears at the bottom-center.
- **Desktop (768px and above)**: Appears at the top-right.

## 🔧 JavaScript Features

The interactive functionality is handled by a `<script>` tag at the bottom of `index.html`.
- **Asynchronous Form Submission**: Uses the Fetch API to send form data to Formspree without a page reload.
- **Toast Notifications**: Displays a success or error message in a pop-up notification after form submission. The notification is responsive and closes automatically.
- **UI Feedback**: The "Send Message" button is disabled and its text changes to "Sending..." during the submission process.

## 🚀 Deployment

This project can be easily deployed on any static site hosting service.

### GitHub Pages (Recommended)
1. Push your code to a GitHub repository named `your-username.github.io`.
2. Go to your repository's **Settings** > **Pages**.
3. Select the `main` branch as the source and click **Save**.
4. Your site will be live at `https://your-username.github.io/`.

## 📄 License

This project is open source. Consider adding a `LICENSE` file and choosing a license like MIT.

## 📞 Contact

Omar Elsadany - [omarelsadany33@gmail.com](mailto:omarelsadany33@gmail.com)
