# MyResume

A clean, simple HTML-based personal resume and portfolio website showcasing professional experience, education, skills, and contact information.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Usage](#usage)
  - [Viewing the Resume](#viewing-the-resume)
  - [Editing the Resume](#editing-the-resume)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

## About

MyResume is a straightforward, static HTML website designed to serve as a personal resume and portfolio. Built with pure HTML, it provides a clean and professional way to showcase your background, skills, and experience to potential employers or collaborators. The website is organized into distinct sections including education, work experience, skills, hobbies, and contact information.

This project demonstrates:
- Clean, semantic HTML structure
- Multi-page navigation
- Responsive design principles
- Easy customization and maintenance

## Features

- **🌐 Pure HTML Resume**: Built with clean, semantic HTML5 for maximum compatibility
- **📱 Responsive Design**: Includes viewport meta tags for mobile-friendly viewing
- **🎨 Easy to Customize**: Simple HTML structure makes it easy to modify content and styling
- **📄 Multi-Page Layout**: Organized into separate pages for different resume sections
- **💾 Downloadable**: Can be easily downloaded and hosted anywhere
- **⚡ Fast Loading**: No external dependencies or heavy frameworks
- **🔗 Navigation**: Simple internal linking between resume sections
- **📧 Contact Integration**: Direct email contact links

## Usage

### Viewing the Resume

1. **Local Viewing**: Open `index.html` in any web browser
2. **Web Server**: For best results, serve the files through a local web server:
   ```bash
   # Using Python
   python3 -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Then open http://localhost:8000 in your browser
   ```

3. **GitHub Pages**: You can host this directly on GitHub Pages by enabling it in your repository settings

### Editing the Resume

1. **Personal Information**: 
   - Edit `index.html` to update the main introduction and navigation
   - Replace the profile image in the `Images/` folder

2. **Individual Sections**:
   - `Public/education.html` - Update your educational background
   - `Public/work.html` - Add your work experience
   - `Public/skills.html` - List your technical and soft skills
   - `Public/hobbies.html` - Share your interests and hobbies
   - `Public/contact.html` - Update your contact information

3. **Customization Tips**:
   - Add CSS files for custom styling
   - Include additional HTML pages for new sections
   - Update navigation links in `index.html` when adding new pages
   - Optimize images for web use

## Project Structure

```
MyResume/
├── index.html              # Main landing page with navigation
├── README.md              # This file
├── Images/                # Profile photos and assets
│   └── IMG_4939.jpeg     # Profile image
└── Public/               # Individual resume section pages
    ├── contact.html      # Contact information
    ├── education.html    # Educational background
    ├── hobbies.html     # Personal interests
    ├── skills.html      # Technical and soft skills
    └── work.html        # Work experience
```

## Contributing

Contributions are welcome! Here's how you can help improve this resume template:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Make** your changes:
   - Improve the HTML structure
   - Add CSS styling
   - Enhance responsiveness
   - Fix any bugs
4. **Commit** your changes (`git commit -m 'Add some amazing feature'`)
5. **Push** to the branch (`git push origin feature/amazing-feature`)
6. **Open** a Pull Request

### Contribution Guidelines

- Keep the code clean and well-commented
- Maintain the simple, accessible structure
- Test changes across different browsers
- Update documentation for any new features
- Follow HTML5 best practices

## Contact

**Anand** - [GitHub Profile](https://github.com/anaidoo1218)

📧 Email: anaidoo1218@gmail.com

Project Link: [https://github.com/anaidoo1218/MyResume](https://github.com/anaidoo1218/MyResume)

## License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2024 Anand

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

⭐ **Star this repository if you found it helpful!** ⭐