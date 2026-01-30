# 📄 LaTeX CV Builder with Docker

> A modern, containerized solution for creating professional CVs, Résumés, and Cover Letters using LaTeX

[![Docker](https://img.shields.io/badge/Docker-Required-blue?logo=docker)](https://www.docker.com/)
[![LaTeX](https://img.shields.io/badge/LaTeX-Awesome--CV-green?logo=latex)](https://github.com/posquit0/Awesome-CV)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## ✨ Features

- 🚀 **Zero Installation**: No need to install LaTeX locally
- 🐳 **Docker-based**: Consistent builds across all platforms
- 📝 **Professional Templates**: Based on the popular Awesome-CV template
- 🔄 **Cross-platform**: Works on Linux, macOS, and Windows
- ⚡ **Fast**: Quick compilation with pre-configured Docker image

## 🔧 Prerequisites

Before you begin, ensure you have:

- [Docker](https://www.docker.com/get-started) installed and running on your system

## 🚀 Quick Start

### For Linux/macOS/WSL (Bash)

```bash
docker run -u $UID:$GID --rm -v $PWD:/work csmith/awesome-cv-builder
```

### For Windows (PowerShell)

```powershell
docker run --rm -v ${PWD}:/work csmith/awesome-cv-builder
```

### Output

After running the command, you'll find your compiled CV at:
```
📁 Current Directory
└── 📄 cv.pdf
```

## 📖 Usage Guide

1. **Clone or download** this repository
2. **Edit** the `.tex` files with your information
3. **Run** the appropriate Docker command for your OS
4. **View** your generated `cv.pdf`

## 🎨 Customization

Edit the following files to personalize your CV:

- `cv.tex` - Main CV content
- `cv/` - Individual CV sections
- `awesome-cv.cls` - Styling and formatting

## 🛠️ Troubleshooting

### Docker not running
```bash
# Check if Docker is running
docker --version
```

### Permission issues (Linux/macOS)
The `-u $UID:$GID` flag ensures output files have correct permissions.

### Volume mounting issues (Windows)
Make sure Docker Desktop has access to your drive in Settings → Resources → File Sharing.

## 📚 Resources

- [Awesome-CV Template](https://github.com/posquit0/Awesome-CV) - Original template
- [Docker Documentation](https://docs.docker.com/) - Learn more about Docker
- [LaTeX Documentation](https://www.latex-project.org/help/documentation/) - LaTeX guides

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⭐ Acknowledgments

- [Awesome-CV](https://github.com/posquit0/Awesome-CV) by Claud D. Park
- [csmith/awesome-cv-builder](https://hub.docker.com/r/csmith/awesome-cv-builder) Docker image

---

<div align="center">
  <sub>Built with ❤️ using LaTeX and Docker</sub>
</div>