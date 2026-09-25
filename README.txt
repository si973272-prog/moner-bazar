# Moner Bazar — starter e-commerce website

এই ফোল্ডারে একটি mobile-friendly e-commerce frontend আছে।

## এখন যা কাজ করে
- Home page
- Category filter
- Product search
- Add to cart
- Quantity change/remove
- Checkout form
- Demo order ID
- Cart/order data localStorage-এ থাকে

## Customer order চালু করতে যা বদলাতে হবে
1. `script.js` খুলে `YOUR_WHATSAPP_NUMBER`-এর জায়গায় তোমার WhatsApp নম্বর বসাও। ভারতের নম্বর হলে `91` + 10 digit নম্বর লিখবে; `+`, space বা শুরুতে `0` দেবে না।
2. Customer checkout করলে WhatsApp খুলবে এবং order details তৈরি থাকবে; customer **Send** চাপলে order তোমার WhatsApp-এ আসবে।
3. এই starter-এ payment method হিসেবে COD রাখা হয়েছে। UPI/online payment চালু করতে payment gateway বা payment link integration লাগবে।

## Live website করার জন্য আরও যা বদলাতে হবে
1. `index.html`-এ YOUR-DOMAIN.example-এর জায়গায় আসল domain বসাতে হবে।
2. `index.html`-এ YOUR-WHATSAPP-NUMBER ও YOUR-EMAIL বসাতে হবে।
3. `script.js`-এর demo `placeOrder()`-কে একটি real order backend / WhatsApp / form service-এর সাথে connect করতে হবে।
4. Payment gateway চাইলে আলাদা merchant account/setup লাগবে।
5. Live site-এর জন্য domain + hosting দরকার।
6. Google Search-এর জন্য live URL, robots.txt, sitemap.xml এবং Search Console setup করতে হবে।

## গুরুত্বপূর্ণ
এটি একটি working starter frontend; শুধু এই ZIP খুললেই public internet-এ live হয় না।
