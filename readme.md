# Background Remover

A client-commissioned web application for removing backgrounds from images using the CutOut.Pro API. This project was developed as a freelance solution for a client requiring efficient image background removal capabilities.

## 🎯 Project Overview

This tool was developed as a custom solution for a client who needed a simple yet powerful way to remove backgrounds from images. The application leverages the CutOut.Pro API to provide professional-grade background removal with a user-friendly interface.

## 🚀 Features

- Simple and intuitive user interface
- Real-time background removal
- Preview functionality
- Download processed images
- Supports various image formats
- Mobile responsive design

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- CutOut.Pro API for image processing

## 📋 Prerequisites

Before you begin, you'll need:
1. A CutOut.Pro API key (Get it from [CutOut.Pro](https://www.cutout.pro/))
2. A modern web browser
3. Basic knowledge of HTML/JavaScript

## 🔧 Setup

1. Clone the repository:
```bash
git clone https://github.com/shakeelkhalid1913/background-remover.git
cd background-remover
```

2. Create a `config.js` file from the example:
```bash
cp config.js.example config.js
```

3. Add your CutOut.Pro API credentials:
Edit `config.js` and replace the placeholder values:
```javascript
const API_KEY = 'your_api_key_here';
const API_ENDPOINT = 'https://www.cutout.pro/api/v1/matting';
```

4. Open `index.html` in your web browser or serve it using a local server.

## 🔑 API Configuration

This project uses the CutOut.Pro API for image processing. To use it:

1. Sign up at [CutOut.Pro](https://www.cutout.pro/)
2. Get your API key from the dashboard
3. Configure the API key in `config.js`
4. Never commit your actual API key to version control

## 🚀 Usage

1. Open the web application
2. Click "Choose File" to select an image
3. Wait for the processing to complete
4. Download the processed image

## 💡 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👤 Author

**Shakeel Khalid**
- GitHub: [@shakeelkhalid1913](https://github.com/shakeelkhalid1913)
- Email: [shakeelkhalid786@gmail.com](mailto:shakeelkhalid786@gmail.com)
- LinkedIn: [Shakeel Khalid](https://www.linkedin.com/in/shakeel-khalid)

## 🙏 Acknowledgments

- [CutOut.Pro](https://www.cutout.pro/) for providing the image processing API