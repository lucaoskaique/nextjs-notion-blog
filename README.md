# Next.js Notion Blog

This is a Next.js blog template that uses the Notion API for content management.

## Features

- Server-side rendering with Next.js
- Content management with Notion API
- Markdown support for blog posts
- Customizable design and layout

## Getting Started

1. Clone this repository:

  ```bash
  git clone https://github.com/your-username/nextjs-notion-blog.git
  ```

2. Install dependencies:

  ```bash
  cd nextjs-notion-blog
  npm install
  ```

3. Configure your Notion API credentials:

  - Create a new integration in your Notion workspace.
  - Copy the integration token.
  - Rename `.env.example` to `.env` and replace `YOUR_NOTION_API_TOKEN` with your integration token.

4. Start the development server:

  ```bash
  npm run dev
  ```

5. Open your browser and visit `http://localhost:3000` to see the blog.

## Customization

- Modify the design and layout in the `styles` directory.
- Add your own components in the `components` directory.
- Customize the blog settings in the `config.js` file.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
