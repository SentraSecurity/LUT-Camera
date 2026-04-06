# Clone the empty repo
git clone https://github.com/BLACK-CYBER-TOOLS/LUT-Camera.git
cd LUT-Camera

# Remove existing files if any
rm -rf *
rm -rf .github

# Create project structure
mkdir -p .github/workflows
mkdir -p app/src/main/java/com/blackcyber/lutcamera
mkdir -p app/src/main/res/{layout,values,drawable-v24,mipmap-anydpi-v33}
mkdir -p gradle/wrapper
