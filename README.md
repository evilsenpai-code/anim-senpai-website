# Anim Senpai Website Documentation

## Introduction
Welcome to the Anim Senpai website setup and customization guide. This document provides all the necessary steps and information required to set up and customize your Anim Senpai website.

## Prerequisites
- Ensure you have the latest version of Node.js installed.
- You will need access to a terminal or command prompt.

## Installation Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/evilsenpai-code/anim-senpai-website.git
   cd anim-senpai-website
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Build the Project**:
   ```bash
   npm run build
   ```

4. **Start the Development Server**:
   ```bash
   npm start
   ```

## Customization
### Changing the Theme
- Navigate to the `src/styles` directory.
- Modify the CSS files as needed to change the look and feel of your website.

### Adding New Pages
- To add a new page, create a new file in the `src/pages` directory and configure the routing in the `src/App.js` file.

### Updating Content
- You can update content in the `src/content` directory. Ensure to follow the structure of existing files for consistency.

## Deployment
1. Build the project as mentioned in the installation steps.
2. Deploy the `dist` folder to your preferred hosting provider.

## Conclusion
You are now ready to set up and customize your Anim Senpai website! If you encounter any issues, feel free to reach out for help.