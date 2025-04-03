# VS Code Extensions

This repository contains a curated list of Visual Studio Code extensions that enhance development productivity and support various programming languages and frameworks.

## 📦 Included Extensions

The repository includes extensions for:

- **Frontend Development**: Tailwind CSS, Bootstrap, HTML, and JavaScript snippets.
- **Backend Development**: PHP, Laravel, Python, Django, and Node.js tools.
- **Database Management**: MySQL, PostgreSQL, and SQL tools.
- **Version Control**: Git-related extensions.
- **Productivity Tools**: Code formatting, debugging, and AI-powered assistance.

## 📥 Installation

To install all extensions at once, use the following command in your terminal:

```sh
while read extension; do code --install-extension $extension; done < extensions.txt
```

Or, manually install specific extensions from `extensions.txt` using:

```sh
code --install-extension <extension-name>
```

## 📝 Contribution

Feel free to suggest additional extensions by submitting a pull request or opening an issue.

## 📜 License

This project is open-source and available under the MIT License.

