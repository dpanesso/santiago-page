# Santiago Panesso - Medical Doctor Profile Website

A professional profile website for Dr. Santiago Panesso, showcasing his medical expertise, research publications, and academic background.

## Features

- Professional medical profile design
- Sections for education, expertise, publications, and contact
- Responsive layout for all devices
- Links to research papers and academic profiles
- Easy to customize for medical professionals

## How to View

1. Open `index.html` in your web browser
2. The page will load with the default content

## Customization

### Content
- Edit `index.html` to update personal information, medical background, education, expertise, publications, and contact details
- Replace placeholder text with actual medical credentials and research links
- Add more publications or sections as needed

### Styling
- Modify `css/style.css` to change colors, fonts, layout, etc.
- The design uses CSS Grid for responsive layouts
- Colors are defined using CSS custom properties for easy theming

### Adding Images
- Add your profile picture to the `images/` directory as `profile.jpg` (or update the src in index.html)
- The image should be square for best results (will be cropped to a circle)
- Create additional directories for other images like certificates or research photos
- Update the HTML to include `<img>` tags where appropriate

## Deployment

This is a static website that can be hosted on:
- GitHub Pages
- Netlify
- Vercel
- Any web server

## Jekyll Alternative

If you prefer using Jekyll for easier content management:

1. Install Ruby and Jekyll:
   ```bash
   # On macOS with Homebrew
   brew install ruby
   gem install jekyll bundler
   ```

2. Initialize Jekyll in this directory:
   ```bash
   jekyll new .
   ```

3. Convert the HTML content to Jekyll's Markdown-based structure

Jekyll would be particularly useful if you plan to add a blog or frequently update content.

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- No JavaScript required for basic functionality