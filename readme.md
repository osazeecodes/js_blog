# Vanilla JavaScript Blog with ButterCMS

## Project Overview

Welcome to my Vanilla JavaScript blog project powered by ButterCMS! In this project, I've leveraged the simplicity and power of Vanilla JavaScript along with the flexibility of ButterCMS to create a fully functional blog. Whether you're a seasoned developer or just getting started, this project provides a straightforward yet robust solution for building your own blog.

## Features

- **JavaScript Powerhouse**: Harnessing the popularity and versatility of JavaScript, this blog project showcases the capability of creating content-heavy applications with just Vanilla JavaScript, HTML, and CSS.

- **ButterCMS Integration**: The blog is seamlessly integrated with ButterCMS, an API-first headless CMS. ButterCMS's features, including flexible content modeling, page types, and collections, provide a developer-friendly environment.

- **Dynamic Routing**: Implementing a basic custom routing system, the project intelligently differentiates between the main blog page and individual blog posts, ensuring a smooth navigation experience.

## Project Setup

### Prerequisites

- ButterCMS trial account
- Code editor (e.g., Visual Studio Code or Sublime)
- Basic knowledge of JavaScript
- Node.js installed on your system

### Getting Started

1. **Setting up the Development Environment:**
   - Create a new folder: `mkdir buttercms-javascriptblog`
   - Navigate to the project folder: `cd buttercms-javascriptblog`
   - Initialize Node.js project: `npm init`

2. **Installing Dependencies:**
   - Install Parcel as a dev dependency: `npm install --save-dev parcel`
   - Create the folder structure and files in the `src` directory.

3. **ButterCMS Configuration:**
   - Sign up for a ButterCMS account.
   - Log in to your ButterCMS dashboard and create a new blog post.

4. **Rendering Data from the ButterCMS API:**
   - Save your ButterCMS Read API Token as an environmental variable in a `.env` file.
   - Set up the API fetch operation in `src/api.js`.
   - Update styling in `index.html` and `css/main.css`.

5. **Dynamic Routing:**
   - Implement basic custom routing in `js/main.js` to differentiate between the main blog page and individual blog posts.

### Running the Project

- Run the development server: `npm start`
- Access the blog at `http://localhost:1234`

## Additional Features

Feel free to explore and enhance the project by adding features like on-site search or pagination to further personalize your blog.

## Conclusion

Congratulations! You've explored my Vanilla JavaScript blog project, a testament to the simplicity and effectiveness of combining Vanilla JavaScript with ButterCMS. Use this project as a foundation to customize and build your blog tailored to your unique needs.

For more details and customization options, refer to the [GitHub repository](#link-to-your-github-repository).

Happy coding!
