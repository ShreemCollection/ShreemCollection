# 🌸 Shreem Collection — Product Catalog App

**Tagline:** स्वास्थ्य • सौंदर्य • वेलनेस • केयर

यह GitHub Pages पर चलने वाला mobile-friendly product catalog है।

## इसमें क्या है?
- Product search
- Category filter
- Product photo
- MRP / selling / special price
- Product details
- Benefits / highlights
- Usage information
- Add to Cart
- WhatsApp order
- Mobile responsive design
- New Products / Offers के लिए आसानी से products जोड़ने की सुविधा

## GitHub पर कैसे चलाएँ?
1. GitHub में नया repository बनाएं, जैसे `shreem-collection`.
2. इस folder की सभी files upload करें.
3. Repository में **Settings → Pages** खोलें.
4. Source में **Deploy from a branch** चुनें.
5. `main` branch और `/ (root)` चुनकर Save करें.
6. कुछ समय बाद आपका online store link बन जाएगा.

## सबसे जरूरी बदलाव
`app.js` में:
`const WA="91XXXXXXXXXX";`
को अपने WhatsApp number से बदलें। उदाहरण: `919876543210`

`products.js` में products की:
- photo
- name
- category
- MRP
- price
- offer
- details
- benefits
- usage

बदल सकती हैं।

## Note
अभी product images placeholder हैं। अपनी original product photos लगाने के लिए `products.js` में image URL बदलें। Product के health/medical claims केवल verified packaging या authorized information के अनुसार रखें।
