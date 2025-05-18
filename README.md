# Academic Personal Website

This is a modern, responsive personal website template designed for research scientists and academics. The website features sections for introduction, CV, publications, and blog posts.

## Features

- Clean, professional design suitable for academic purposes
- Responsive layout that works on all devices
- Sections for:
  - Introduction and contact information
  - About Me
  - Curriculum Vitae
  - Publications
  - Blog
- Social media integration
- Modern styling with CSS3
- Font Awesome icons
- Google Fonts integration

## Customization

1. Edit `index.html` to update your personal information:
   - Replace "Your Name" with your actual name
   - Update research area and institution
   - Add your social media links
   - Customize the About Me section
   - Add your CV information
   - List your publications
   - Add your blog posts

2. Customize the styling in `css/style.css`:
   - Modify colors in the CSS variables
   - Adjust spacing and layout
   - Change fonts if desired

## Adding Content

### Publications
Add new publications by copying the publication-item template in the publications section:

```html
<div class="publication-item">
    <h3>Publication Title</h3>
    <p class="authors">Author 1, Author 2, <strong>Your Name</strong>, Author 3</p>
    <p class="venue">Journal/Conference Name, Year</p>
    <div class="publication-links">
        <a href="#" class="btn">Paper</a>
        <a href="#" class="btn">Code</a>
        <a href="#" class="btn">BibTeX</a>
    </div>
</div>
```

### Blog Posts
Add new blog posts by copying the blog-post template in the blog section:

```html
<article class="blog-post">
    <h3>Blog Post Title</h3>
    <p class="date">Date</p>
    <p class="excerpt">Brief description of the blog post...</p>
    <a href="#" class="read-more">Read More</a>
</article>
```

## Maintenance

1. Keep your CV up to date
2. Add new publications as they are published
3. Regularly update your blog with new content
4. Check and update social media links periodically

## License

This template is free to use for personal and academic purposes.

## Credits

- Font Awesome for icons
- Google Fonts for typography
- Source Sans Pro and Roboto fonts