# NLP Portfolio Website

A beautiful portfolio website for your Natural Language Processing course.

## How to Add Images

### Profile Image
1. Add your profile photo as `profile.jpg` in the same folder as `index.html`
2. The image should be square (recommended: 400x400px or larger)
3. Supported formats: JPG, PNG, WEBP
4. If the image doesn't exist, a placeholder icon will show

### Course/Content Images
1. Add your course-related image as `nlp-image.jpg` in the same folder
2. This image will appear in the "Course Introduction" section
3. Recommended size: 800x600px or larger

### Project Images (Optional)
To add images for your projects in the Achievements section:
1. Uncomment the `<img>` tags in the HTML file (remove `<!-- -->`)
2. Create a `projects` folder in the same directory
3. Add images with these names:
   - `projects/preprocessing.jpg`
   - `projects/sentiment.jpg`
   - `projects/transformer.jpg`
   - `projects/chatbot.jpg`
   - `projects/summarization.jpg`

## Color Scheme

The website uses a soothing blue-teal color scheme:
- Primary: Sky Blue (#0ea5e9)
- Secondary: Cyan (#06b6d4)
- Accent: Teal (#14b8a6)

## Running the Website

Simply open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).

The website works completely offline - no server required!

## File Structure

```
nlp portfolio/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript for interactions
├── profile.jpg         # Your profile image (add this)
├── nlp-image.jpg       # Course image (add this)
└── projects/           # Optional project images folder
    ├── preprocessing.jpg
    ├── sentiment.jpg
    ├── transformer.jpg
    ├── chatbot.jpg
    └── summarization.jpg
```

## Customization

All colors are defined in `styles.css` using CSS variables at the top of the file. You can easily change the color scheme by modifying the `:root` variables.



