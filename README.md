# Jaya
jaya/
├── jaya.py
├── README.md
└── .gitignore
def greet(name):
    print(f"Hello, {name}! Welcome to your first GitHub project.")

if __name__ == "__main__":
    greet("Jaya")
    ---

### 📄 `.gitignore`
```bash
__pycache__/
*.pyc
.env
# Go to the folder where your project is
cd path/to/jaya

# Initialize Git
git init

# Add your files
git add .

# Commit the changes
git commit -m "Initial commit for Jaya project"

# Set the main branch
git branch -M main

# Connect to your GitHub repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/jaya.git

# Push to GitHub
git push -u origin main
