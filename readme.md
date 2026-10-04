# Rooftop Cat

## Description

**Rooftop Cat** একটি ছোট, browser-based endless runner game। ঝড়ের রাতে একটি বিড়াল শহরের rooftop ধরে দৌড়াতে থাকে, আর player-এর কাজ হলো obstacle এড়িয়ে যত বেশি দূর সম্ভব টিকে থাকা। দূরত্ব যত বাড়ে, score তত বাড়ে এবং প্রতি 1000 মিটারে achievement দেখানো হয়।

এটি কোনো fixed-level game নয়; প্রতিবার নতুনভাবে obstacle তৈরি হয়, তাই প্রতিটি run কিছুটা আলাদা হয়। গেমটি HTML Canvas এবং vanilla JavaScript দিয়ে তৈরি করা হয়েছে, তাই আলাদা কোনো game engine বা installation প্রয়োজন নেই।

## কীভাবে খেলবেন

1. `RooftopCat.html` ফাইলটি যেকোনো আধুনিক web browser-এ খুলুন।
2. শুরুতে পছন্দের cat avatar নির্বাচন করুন। ছয়টি option আছে: Orange, Black, White, Calico, Siamese এবং Tuxedo।
3. দৌড় শুরু হলে cat-কে jump করিয়ে সামনে থাকা box, gap এবং ledge এড়িয়ে চলুন।
4. Jump করার জন্য:
   - Keyboard-এ `Space` অথবা `Arrow Up` চাপুন।
   - Mobile বা touch device-এ screen-এর যেকোনো জায়গায় tap করুন।
   - Browser-এ canvas-এর যেকোনো জায়গায় click করলেও jump হবে।
5. একসঙ্গে সর্বোচ্চ ৩টি jump করা যায়। মাটিতে নামলে jump count আবার reset হয়।
6. Pause করতে উপরের ডানদিকের pause button চাপুন।
7. Box-এ ধাক্কা লাগলে অথবা rooftop থেকে পড়ে গেলে game over হবে। এরপর `run again` button চাপলে নতুন run শুরু করা যাবে।

## Scoring

- Score মিটারে distance হিসেবে দেখানো হয়, যেমন `250 m`।
- যত বেশি সময় বেঁচে থাকবেন, তত বেশি distance এবং score পাবেন।
- প্রতি `1000 m` অতিক্রম করলে achievement notification আসবে।
- আপনার best score browser-এর `localStorage`-এ সংরক্ষিত থাকে, তাই একই browser-এ পরে আবার খেললেও high score দেখা যাবে।
- সময়ের সঙ্গে game speed ধীরে ধীরে বাড়ে, ফলে run যত লম্বা হবে game তত challenging হবে।

## Game Features

- Endless rooftop running gameplay
- ছয় ধরনের playable cat avatar
- Keyboard, mouse এবং touch control
- Triple-jump system
- Randomly generated obstacles
- Pause এবং restart option
- Distance score এবং persistent high score
- 1000 মিটার পরপর achievement
- Night city, stars এবং simple sound effects
- কোনো external library বা build step ছাড়াই চলে

## কীভাবে চালাবেন

এই project চালানোর জন্য installation দরকার নেই।

1. এই repository বা folder download করুন।
2. `RooftopCat.html` ফাইলটি browser-এ open করুন।
3. Cat নির্বাচন করে game শুরু করুন।

## Project Structure

```text
RooftopCat/
├── RooftopCat.html   # সম্পূর্ণ game: HTML, CSS এবং JavaScript
└── readme.md         # Game description এবং playing guide
```

## Technology

- HTML5
- CSS3
- JavaScript
- HTML Canvas API
- Web Audio API
- Browser Local Storage
