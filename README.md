# Complete Static Website (GitHub Pages Ready)

यह फ़ोल्डर किसी भी GitHub रिपॉजिटरी में सीधे अपलोड करके GitHub Pages पर चलाने के लिए पूरी तरह तैयार है।

---

## 📁 फ़ोल्डर में क्या-क्या शामिल है:
1. `index.html` - मुख्य लैंडिंग पेज (100% Identical Replica)
2. `thanks-you.html` - 18+ आयु पुष्टि और थैंक-यू पेज
3. `agewarning.png` - 18+ वार्निंग ग्राफ़िक
4. `.nojekyll` - GitHub Pages पर Jekyll प्रोसेसिंग बंद रखने के लिए
5. `indexss_files/` - सभी CSS, JavaScript, SVGs, और इमेज फाइल्स
6. `webfonts/` - FontAwesome 5 आइकॉन्स के लिए सभी webfont फाइल्स
7. `.github/workflows/static.yml` - GitHub Pages ऑटो-डिप्लॉयमेंट वर्कफ़्लो

---

## 🚀 किसी भी नए GitHub Repo पर कैसे चलाएं:

### तरीका 1 (GitHub Web Interface से):
1. GitHub पर जाएं और एक नया रिपॉजिटरी बनाएं (जैसे: `go` या `my-landing-page`)।
2. रिपॉजिटरी में **"Add file"** -> **"Upload files"** पर क्लिक करें।
3. इस फ़ोल्डर के अंदर की सभी फ़ाइलें और सब-फ़ोल्डर्स (`index.html`, `thanks-you.html`, `agewarning.png`, `.nojekyll`, `indexss_files`, `webfonts`, `.github`) ड्रैग और ड्रॉप करें।
4. **Commit changes** पर क्लिक करें।
5. रिपॉजिटरी के **Settings** -> **Pages** में जाएं:
   - **Source** में **GitHub Actions** सिलेक्ट करें।
6. 1-2 मिनट में Actions रन होकर आपकी वेबसाइट लाइव हो जाएगी!

### तरीका 2 (Git Command Line से):
```bash
cd website-github-upload
git init
git add .
git commit -m "Initial commit for GitHub Pages"
git branch -M main
git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git
git push -u origin main
```
इसके बाद रिपॉजिटरी के **Settings** -> **Pages** में **Source** को **GitHub Actions** सेट करें।
