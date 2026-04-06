# Clone the empty repo
```bash
git clone https://github.com/SentraSecurity/LUT-Camera.git
cd LUT-Camera
```
# Unzip the file
```bash
unzip LUT-Camera.zip
```
# Remove existing files if any
```bash
rm -rf *
rm -rf .github
```
# Create project structure
```bash
mkdir -p .github/workflows
mkdir -p app/src/main/java/com/blackcyber/lutcamera
mkdir -p app/src/main/res/{layout,values,drawable-v24,mipmap-anydpi-v33}
mkdir -p gradle/wrapper
