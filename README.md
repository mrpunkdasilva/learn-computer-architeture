# Learn Computer Architecture

A comprehensive educational resource about computer architecture concepts, built with JetBrains Writerside.

## 📚 About

This project provides educational materials covering fundamental concepts of computer architecture, from numerical systems to processor organization. The content is structured in a logical progression, making it suitable for students, educators, and anyone interested in understanding how computers work at a fundamental level.

## 🧠 Topics Covered

- Evolution of Computers
- Numerical Systems and Conversions
- Components of a Basic PC
- Truth Tables and Logic
- Logic Ports
- Types of Memory
- Processor Organization
- Data Representation
- I/O Devices

## 🛠️ Built With

- **JetBrains Writerside** - Documentation authoring tool
- **Markdown** - Content source format
- **Shell Scripts** - Build and deployment automation

## 🚀 Getting Started

### Prerequisites

- JetBrains Writerside (for editing and building the documentation)
- A web browser (for viewing the documentation)

### Viewing the Documentation

1. Clone this repository
2. Open the `docs/index.html` file in your web browser

### Editing the Documentation

1. Open the project in JetBrains Writerside
2. Edit the Markdown files in the `Writerside/topics` directory
3. Build the documentation using Writerside

## 📦 Building and Deployment

The project includes scripts to automate the build and deployment process:

```bash
# Run the main build and deployment script
./scripts/main.sh
```

This script:
1. Extracts the latest documentation build
2. Commits and pushes changes to the remote repository

## 📂 Project Structure

- `Writerside/` - Source files for the documentation
  - `topics/` - Markdown content files
  - `images/` - Images used in the documentation
  - `cfg/` - Configuration files
- `docs/` - Generated HTML documentation
- `scripts/` - Utility scripts for building and deployment

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the content or add new topics:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-topic`)
3. Commit your changes (`git commit -m 'Add some amazing topic'`)
4. Push to the branch (`git push origin feature/amazing-topic`)
5. Open a Pull Request

## 📄 License

This project is available as an open educational resource.

## 📞 Contact

If you have any questions or suggestions, feel free to open an issue in this repository.