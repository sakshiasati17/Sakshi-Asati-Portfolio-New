# Portfolio Website - Streamlit Edition

A simple, professional, and elegant portfolio website built with Streamlit, showcasing skills, experience, and projects.

## Features

- 🎨 **Modern Design**: Clean and minimalist interface with gradient backgrounds
- 📱 **Responsive Layout**: Works perfectly on all devices
- 👤 **Profile Picture Support**: Add your profile picture (profile_picture.jpg)
- 📄 **Resume Download**: Download resume directly from the portfolio
- 🚀 **Creative Hero Section**: Eye-catching introduction with creative headline
- 📊 **Interactive Sections**:
  - Hero section with profile picture and creative tagline
  - About section with education highlights
  - Technical skills showcase with categorized tags
  - Professional experience timeline
  - Featured projects with key metrics
  - Contact information with social links

## Getting Started

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Installation

1. **Clone or download this repository**

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Add your files** (optional):
   - Add your profile picture as `profile_picture.jpg` (recommended size: 200x200px or square)
   - Add your resume as `resume.pdf` (for download functionality)

4. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

5. **Open in browser**:
   The app will automatically open in your default browser at `http://localhost:8501`

## File Structure

```
portfolio/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── README.md             # This file
├── profile_picture.jpg    # Your profile picture (optional)
└── resume.pdf            # Your resume (optional)
```

## Customization

### Profile Picture

1. Add your profile picture as `profile_picture.jpg` in the root directory
2. Recommended size: 200x200px or any square dimension
3. Supported formats: JPG, PNG
4. If no picture is provided, a placeholder icon will be shown

### Resume

1. Add your resume as `resume.pdf` in the root directory
2. The download button will appear in both the Hero section and Contact section
3. If no resume is provided, the button will be disabled

### Content

Edit the content in `app.py` to update:
- Personal information
- Education details
- Skills and technologies
- Experience and projects
- Contact information
- Creative headlines and descriptions

### Colors and Styling

Modify the CSS in the `st.markdown()` sections at the top of `app.py` to customize:
- Color scheme (currently using purple gradient)
- Fonts and typography
- Spacing and layout
- Button styles

## Deployment

### Streamlit Cloud (Recommended)

1. Push your code to GitHub
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Sign in with GitHub
4. Click "New app"
5. Select your repository and branch
6. Set main file to `app.py`
7. Click "Deploy"

### Other Platforms

You can deploy to:
- **Heroku**: Use the Streamlit buildpack
- **AWS EC2**: Run as a service
- **Google Cloud Run**: Containerized deployment
- **Azure App Service**: Python web app
- **DigitalOcean**: App Platform or Droplet

## Requirements

- streamlit >= 1.28.0
- streamlit-option-menu >= 0.3.6
- Pillow >= 10.0.0 (for image handling)

## Tips

1. **Profile Picture**: Use a professional headshot with good lighting
2. **Resume**: Keep your PDF resume updated with latest information
3. **Projects**: Highlight key metrics and achievements in project descriptions
4. **Colors**: The current purple gradient can be changed to match your brand
5. **Responsiveness**: Test on mobile devices for best experience

## Support

For issues or questions:
- Check Streamlit documentation: [docs.streamlit.io](https://docs.streamlit.io)
- Streamlit community forum: [discuss.streamlit.io](https://discuss.streamlit.io)

---

Built with ❤️ using Streamlit by Sakshi Asati