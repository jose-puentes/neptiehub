# Landing Page - Salamander Tech Hub

<p align="center">
build🚀. burn 🔥. evolve 🦎
</p>

<p align="center">
<img width="640" alt="Salamander Tech Hub - Landing Page" src="https://github.com/user-attachments/assets/163ba945-d094-44b9-b3f3-56c8fd792b04" />

</p>

<p align="center">
A tech community that brings together learners to grow. Add your name to our directory!
</p>



## 🚀 Quick Start

1. **Fork this repository**
   - Click the "Fork" button in the top right

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR-USERNAME/landing-page.git
   cd salamander
   ```

3. **Add your name**
   ```bash
   # Create your JSON file
   echo '{"name": "your_username"}' > names/your_username.json
   ```

4. **Test locally (optional)**
   
   To test locally, you need to manually add your file to the manifest:
   
   1. Open `names/manifest.json`
   2. Add your filename to the `files` array:
   ```json
   {
     "files": [
       ...,
       "your_username.json",
       ...
     ]
   }
   ```
   
   Then start the server:
   ```bash
   # Start a local server
   python3 -m http.server 8000
   # Visit http://localhost:8000
   ```

5. **Commit and push**
   ```bash
   git add names/your_username.json
   git commit -m "add name: added name to the landing page"
   git push origin main
   ```

6. **Create a Pull Request**
   - Go to the original repository
   - Click "Pull requests" → "New pull request"
   - Select "compare across forks"
   - Choose your fork and branch
   - Click "Create pull request"

## 📝 JSON File Format

Your JSON file should follow this exact format:

```json
{
  "name": "your_username"
}
```

**Important:** 
- Use underscores, not dashes or spaces
- Filename should match: `your_username.json`
- Keep it simple and consistent

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## 🔄 How It Works

- Your JSON file gets added to the `/names/` directory
- GitHub Actions automatically updates the manifest (for production)
- The website loads names dynamically from the manifest
- Changes appear after the deployment completes

## 💡 Note

When you submit a pull request, don't worry about editing the manifest.json file. Our GitHub Action will automatically update it when your pull request is merged!

## 📫 Support

If you need help:
- Open an issue on GitHub
- Contact us via WhatsApp

---

Made with ❤️ by the Salamander Tech Hub Stewards
