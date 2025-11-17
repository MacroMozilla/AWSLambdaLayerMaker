# Auto AWS Lambda Layer Maker

This project automatically packages your Python dependencies into a ZIP file that can be uploaded directly as an AWS Lambda Layer.

## 🚀 How it works

1. You list your Python dependencies in `requirements.txt`.
2. The build process installs the dependencies and zips them into a `layer.zip` file.
3. The artifact (`aws_package.zip`) is available in the build output — ready to upload to AWS Lambda as a layer.

## 🧩 Usage

### 1. Write your requirements
Edit the `requirements.txt` file with the Python packages you need, for example:
