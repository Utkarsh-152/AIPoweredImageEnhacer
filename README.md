# AI-Powered Image Enhancer

[Live Demo](https://ai-powered-image-enhacer.vercel.app/)

A modern web application that enhances image quality using AI technology. Built with React and powered by the PicWish API.

## 🚀 Features

- Real-time image enhancement
- Support for multiple image formats (PNG, JPG, JPEG)
- Modern UI with animated background
- Drag and drop image upload
- Dark mode support
- Responsive design

## 🛠️ Tech Stack

- **Frontend Framework:** React.js
- **Styling:** TailwindCSS
- **Animation:** Motion
- **HTTP Client:** Axios
- **Environment Variables:** dotenv
- **Build Tool:** Vite
- **API:** PicWish Image Enhancement API
- **Package Manager:** npm

## 🏗️ Installation

1. Clone the repository:
```bash
git clone https://github.com/Utkarsh-152/AIPoweredImageEnhacer.git
cd image-enhancer
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```env
VITE_PICWISH_API_KEY=your_picwish_api_key_here
```

4. Run the development server:
```bash
npm run dev
```

## 🔑 Environment Variables

Create a `.env` file in the root directory with the following variables:

```env
VITE_PICWISH_API_KEY=your_picwish_api_key_here
```

> Note: You'll need to obtain an API key from [PicWish](https://picwish.com/)

## 🏃‍♂️ Running the Project

```bash
# Development mode
npm run dev

# Build for production
npm run build or npm i

```

## 📁 Project Structure

```
image-enhancer/
├── src/
│   ├── components/
│   │   ├── Home.jsx
│   │   ├── ImgUpload.jsx
│   │   ├── ImgPreview.jsx
│   │   └── Loading.jsx
│   ├── utils/
│   │   └── enhanceImageApi.js
│   ├── App.jsx
│   └── main.jsx
├── .env
├── package.json
└── vite.config.js
```

## 🔧 Configuration

The project uses Vite as the build tool and includes configurations for:
- ESLint for code linting
- TailwindCSS for styling
- Environment variables

## 🤝 Contributing

Feel free to contribute to this project. Pull requests are welcome.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Utkarsh Tripathi**
- Email: shreytripathi2004@gmail.com
- GitHub: [Your GitHub Profile](https://github.com/Utkarsh-152)

## 🙏 Acknowledgments

- [PicWish API](https://picwish.com/) for providing the image enhancement capabilities
- [TailwindCSS](https://tailwindcss.com/) for the utility-first CSS framework
- [React](https://reactjs.org/) for the frontend library

---

Made with ❤️ by Utkarsh Tripathi
