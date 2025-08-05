# error-pages-ui
Custom HTML Error Pages Designed by Team Elite-1111

---

## Overview

This repository hosts a collection of **custom error pages** for Awarcrown platforms, designed to be creative, engaging, and functional. Each team member is responsible for developing specific HTTP error code pages.

---

## Objective

Develop **35 custom error pages** for various HTTP errors using HTML, CSS, and optional animations. The pages must:
- Clearly communicate the error
- Incorporate humor, creativity, or localized elements (e.g., "Desi style")
- Be lightweight and optimized for fast loading
- Use only royalty-free or original content to avoid copyright issues

---

## Project Structure

Each error page is organized in a dedicated folder named after its corresponding HTTP error code:

```
error-pages-ui/
├── your_name/
│   └── 400.shtml
├── your_name/
│   └── 500.shtml
└── ...
```

---

## Team Assignments

| Member      | Assigned Error Codes                              |
|-------------|--------------------------------------------------|
| **Siri**    | 400, 401, 402, 403, 404, 405, 406, 407, 408, 409, 410, 411 |
| **Mahesh**  | 412, 413, 414, 415, 416, 417, 418, 421, 422, 423, 424, 425 |
| **Jahanavi**| 426, 428, 429, 431, 444, 451, 499, 500, 501, 502, 503     |

---

## Sample Error Page Code

Below is an example of a 403 error page:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Vanguard 403</title>
    <link rel="icon" href="https://awarcrown.com/images/awarcrown-logo.png" />
    <meta name="robots" content="noindex, nofollow">
    <style>
        body {
            font-family: "Inter", system-ui, -apple-system, sans-serif;
            background-color: #fff;
            text-align: center;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        header {
            background-color: #1f1f5a;
            color: #fff;
            padding: 15px;
        }
        .header-content {
            display: flex;
            align-items: center;
        }
        .logo {
            width: 60px;
            height: 60px;
            margin-right: 10px;
        }
        .cmp-name {
            font-size: 28px;
            font-weight: 700;
            color: #ffff;
            padding: 0;
        }
        .error-container {
            max-width: 600px;
            margin: 41px auto;
        }
        .logo-error {
            width: 200px;
            margin-bottom: 20px;
        }
        .error-code {
            font-size: 50px;
            color: #dc3545;
            margin-bottom: 1rem;
        }
        .error-message {
            font-size: 24px;
            color: #6c757d;
            margin-bottom: 1rem;
        }
        .error-description {
            font-size: 18px;
            color: #6c757d;
            margin-top: 10px;
        }
        a {
            color: #007bff;
            text-decoration: none;
        }
        footer {
            margin-top: auto;
            background-color: #1f1f5a;
            color: #d0dfe7;
            padding: 37px;
            text-align: center;
            padding-bottom: 25px;
        }
        footer p {
            margin-top: -10px;
        }
        footer a {
            color: #007bff;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
        .footer-social a {
            margin: 0 10px;
        }
        .footer-social img {
            width: 30px;
            height: 30px;
        }
        .footer-bottom {
            margin-top: 20px;
        }
        .footer-bottom p {
            margin: 0;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <img src="https://awarcrown.com/images/awarcrown-logo.png" alt="Awarcrown logo" class="logo">
            <h1 class="cmp-name">Awarcrown Corporations</h1>
        </div>
    </header>
    <div class="error-container">
        <img src="{error_image_url}" alt="image" class="logo-error">
        <div class="error-msg-img-container">
            <div class="error-code">Vanguard 403</div>
        </div>
        <div class="error-message">You don't have permission to access this resource<br><b>Please try again later or <a href="https://awarcrown.com">return to the homepage</b>.</a></div>
        For further assistance, <a href="mailto:support@awarcrown.com">contact support</a>.
    </div>
    <footer>
        <p>&copy; 2025 Awarcrown Corporations LLP | All rights reserved</p>
        <div class="footer-social">
            <a href="https://www.instagram.com/awarcrown/" target="_blank"><img src="https://awarcrown.com/images/instagram.svg" alt="Instagram"></a>
            <a href="https://chat.whatsapp.com/JTHXEzPfPad2oLl94D87WD" target="_blank"><img src="https://awarcrown.com/images/whatsapp.svg" alt="Whatsapp"></a>
            <a href="https://www.linkedin.com/company/awarcrown/" target="_blank"><img src="https://awarcrown.com/images/linkedin.svg" alt="LinkedIn"></a>
        </div>
    </footer>
</body>
</html>
```

---

## Guidelines

### Design
- Use clean, responsive HTML and CSS
- Incorporate **SVGs or royalty-free images** to avoid copyrighted material
- Include animations or illustrations only when necessary
- Ensure humor is **professional**, inclusive, and appropriate

### Testing
- Verify responsiveness across mobile and desktop devices
- Prioritize simple code, avoiding frameworks unless essential

---

## Workflow

### 1. Clone the Repository
```bash
git clone https://github.com/AWARCROWN-CORPORATIONS-LLP/error-pages-ui.git
cd error-pages-ui
```

### 2. Create a Branch
```bash
git checkout -b {your_name}/404-page
```
*Replace `{your_name}` and `404-page` with your name and the respective error code.*

### 3. Add Your Page
Create a folder for your error code and add an `index.html` file with your design:
```bash
mkdir 404
cd 404
touch index.html
```

### 4. Stage, Commit, and Push
```bash
git add .
git commit -m "Added 404 error page design"
git push origin siri/404-page
```

### 5. Create a Pull Request
Navigate to the GitHub repository, select **"Compare & pull request"**, and submit for review.

---

## Task Status Tracking

Tasks are tracked using **GitHub Issues** with the following status flow:
- [ ] TODO — Not started
- [ ] IN PROGRESS — Work in progress
- [ ] DONE — Completed and merged

Update the relevant checkboxes as you progress or complete your tasks.

---

## Restrictions
- ❌ Do not copy error pages from other websites
- ❌ Avoid using large videos or heavy media files
- ❌ Do not push broken or untested code
- ❌ Do not use paid or stock images without proper licensing

---

## Support
For assistance, reach out via GitHub **Discussions** or the **Team Elite 1111 WhatsApp group**.

*— Awarcrown Corporations LLP*
