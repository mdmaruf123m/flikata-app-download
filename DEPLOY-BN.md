# ফ্লিকাটা সাইট ফ্রি প্রকাশের নির্দেশনা

Cloudflare Pages-এ account খুলে Workers & Pages → Create application → Pages → Upload assets বেছে নিন। ZIP ফাইলটি extract করে এর ভেতরের সব site file upload করুন। তারপর Cloudflare একটি বিনামূল্যের `pages.dev` URL দেবে। কোনো paid domain বা hosting কেনার দরকার নেই।

প্রকাশের পর পাওয়া আসল URL দিয়ে `robots.txt`-এর `PUBLIC_SITE_URL` এবং `sitemap.xml`-এর `PUBLIC_SITE_URL` বদলে আবার upload করুন। এরপর Google Search Console-এ ওই URL যোগ করে `https://আপনার-pages-url/sitemap.xml` submit করুন এবং homepage URL-এর indexing request দিন।

সাইটে `flikata.apk` root folder-এ থাকতে হবে। এটি ২২.৮ MB-এর Android APK; website-এর download button একই-origin direct download হিসেবে সেট করা আছে।

Google-এ প্রথমে আসা নিশ্চিত করা যায় না। নামটি নতুন বা কম প্রতিযোগিতার হলে ভালোভাবে index হওয়ার সম্ভাবনা বেশি, কিন্তু ranking Google-এর algorithm নির্ধারণ করে।
