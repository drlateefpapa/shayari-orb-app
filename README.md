# Shayari Orb

मूड के अनुसार चमकता ओर्ब और क्लासिक शायरी वाला PWA।

## फ़ाइलें
- `index.html` — मुख्य ऐप
- `shayaris.json` — शायरी डेटा (~480 शेर)
- `manifest.json` — PWA मैनिफ़ेस्ट
- `sw.js` — सर्विस वर्कर (ऑफ़लाइन सपोर्ट)

## कैसे चलाएँ / पब्लिश करें

### लोकल
किसी स्टैटिक सर्वर से खोलें (फ़ाइल:// से JSON लोड नहीं होगा):
```bash
npx serve shayari-orb-app
# या
python3 -m http.server 8080
```

### पब्लिश (मुफ़्त)
1. **GitHub Pages**: रेपो बनाएँ → फ़ाइलें अपलोड करें → Settings → Pages → Deploy from main branch.
2. **Netlify / Vercel**: ड्रैग-एंड-ड्रॉप या Git कनेक्ट करें।
3. **Firebase Hosting** या कोई भी स्टैटिक होस्ट।

### होम स्क्रीन पर ऐप जैसा
मोबाइल ब्राउज़र में खोलें → मेनू → **Add to Home Screen**।

## नोट
- TTS (सुनाएं) Android Chrome पर सबसे अच्छा काम करता है।
- आइकन के लिए `icon-192.png` और `icon-512.png` जोड़ सकते हो (या मौजूदा SVG फेविकॉन काम करेगा)।
- और शायरी जोड़ने के लिए `shayaris.json` एडिट करो।

आनंद लो! ✨
