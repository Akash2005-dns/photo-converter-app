# Photo Converter Web Application

A full-stack web application that converts images to multiple formats including ZIP, PDF, Word documents, animated GIFs, and various image formats.

## 🚀 Features

- **Multi-format conversion**: ZIP, PDF, DOCX, GIF, JPEG, PNG, WebP, BMP, TIFF
- **Drag & Drop Interface**: Easy file upload with visual feedback
- **Batch Processing**: Handle up to 10 files simultaneously (50MB each)
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Validation**: Instant file type and size checking
- **Automatic Cleanup**: Temporary files are automatically removed

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Image Processing**: Sharp
- **File Handling**: Multer
- **Document Generation**: PDFKit, DOCX library
- **Frontend**: HTML5, CSS3, JavaScript
- **Compression**: JSZip, Archiver

## 📦 Installation

1. Clone the repository
```bash
git clone <your-repo-url>
cd photo-converter
```

2. Install dependencies
```bash
npm install
```

3. Start the server
```bash
npm start
```

4. Open your browser and navigate to `https://photo-converter-app.onrender.com/

## 🎯 Usage

1. **Upload Photos**: Click the upload area or drag and drop image files
2. **Select Format**: Choose your desired conversion format
3. **Download**: Your converted file will automatically download

## 🌐 Supported Formats

### Input Formats
- JPEG/JPG
- PNG
- GIF
- BMP
- WebP
- TIFF

### Output Formats
- **ZIP**: Compressed archive of all photos
- **PDF**: Multi-page PDF document
- **Word**: DOCX file with embedded images
- **GIF**: Animated GIF from multiple images
- **Image Formats**: Convert between any supported format

## 🔧 API Endpoints

- `GET /` - Main application
- `GET /photo-converter` - Alternative route
- `POST /upload` - File upload endpoint
- `POST /convert/zip` - Convert to ZIP
- `POST /convert/pdf` - Convert to PDF
- `POST /convert/word` - Convert to Word
- `POST /convert/gif` - Convert to GIF
- `POST /convert/image/:format` - Convert to image format

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Developer

Created by S.AKASH

---

⭐ Star this repository if you found it helpful!
