# নিউ সিটি টেইলাস – অ্যাপ

## APK বানানোর ধাপ (GitHub দিয়ে)
1. github.com এ নতুন Repository খুলুন (নাম যেমন: `new-city-tailors`, Private রাখতে পারেন)।
2. Repository-তে **Add file → Upload files** চাপুন এবং এই zip-এর ভেতরের **সব ফাইল ও ফোল্ডার** (`.github` ফোল্ডার সহ) টেনে আনুন → **Commit changes**।
   - `.github` ফোল্ডার না দেখালে/আপলোড না হলে: **Add file → Create new file** → নাম লিখুন `.github/workflows/build-apk.yml` → ফাইলের লেখা পেস্ট করে Commit করুন। তারপর বাকি ফাইল আপলোড করুন।
   - বিকল্প: `app.zip` নামের পুরো zip আর `.github/workflows/build-apk.yml` – শুধু এই দুটো আপলোড করলেও হবে; workflow নিজে zip খুলে নেবে।
3. **Actions** ট্যাবে যান → "Build Android APK" চলছে দেখবেন (৫–১০ মিনিট)।
4. শেষ হলে Repository-র ডান পাশে **Releases** → সর্বশেষ build থেকে `NewCityTailors.apk` ডাউনলোড করুন (অথবা Actions → run → Artifacts)।
5. ফোনে APK ইনস্টল করুন (প্রয়োজনে "Unknown sources / এই উৎস থেকে ইনস্টল" অনুমতি দিন)।

## প্রথম ব্যবহার
- অ্যাপ খুলে পাসওয়ার্ড সেট করুন।
- সেটিংস → থার্মাল প্রিন্টার → "প্রিন্টার খুঁজুন" → আপনার প্রিন্টার বেছে সংযুক্ত করুন (আগে ফোনের ব্লুটুথ চালু ও প্রিন্টার অন রাখুন)।
- কাগজ ৫৮mm বা ৮০mm বেছে "টেস্ট প্রিন্ট" দিন।
- নিয়মিত "অনলাইন ব্যাকআপ" থেকে ব্যাকআপ ফাইল Google Drive/WhatsApp-এ পাঠিয়ে রাখুন।

## নতুন সংস্করণ
ফাইল বদলে Commit করলেই আবার নিজে থেকে APK তৈরি হবে।
