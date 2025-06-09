# 🛠️ File Organizer CLI Tool

A simple Python CLI tool to organize files in a directory by type (e.g., Images, Videos, Documents).

## 🚀 Features

- Categorizes files based on their extensions.
- Creates folders like `Images`, `Videos`, `Documents`, etc.
- Moves files into respective folders.
- Easy to run from the command line.

## 📦 File Categories

| Category   | Extensions                                  |
|------------|---------------------------------------------|
| Images     | .jpg, .jpeg, .png, .gif, .bmp, .tiff         |
| Videos     | .mp4, .mov, .avi, .mkv, .flv                 |
| Documents  | .pdf, .docx, .txt, .xlsx, .pptx              |
| Audio      | .mp3, .wav, .aac, .flac                      |
| Archives   | .zip, .tar, .gz, .rar                        |
| Scripts    | .py, .js, .sh, .bat                          |
| Others     | Everything else                              |

## 🔧 Installation

```bash
git clone https://github.com/yourusername/file-organizer-cli.git
cd file-organizer-cli
python -m venv venv
source venv/bin/activate  # or venv\\Scripts\\activate on Windows
pip install -r requirements.txt  # optional, if you add dependencies
