HRIDOY AI — প্রথম ওয়েবসাইট

ফাইল:
- index.html: সম্পূর্ণ responsive ওয়েবসাইট (একটি ফাইলেই HTML/CSS/JavaScript)

চালানোর নিয়ম:
1. ZIP extract করো।
2. index.html ফাইল Chrome-এ খোলো।
3. ভয়েস ইনপুটের জন্য microphone permission Allow করো।
4. Speech Recognition সব ব্রাউজারে সমানভাবে কাজ নাও করতে পারে; Chrome-এ HTTPS বা localhost প্রয়োজন হতে পারে।

গুরুত্বপূর্ণ সীমাবদ্ধতা:
- এই সংস্করণে বাংলা ভয়েস ইনপুট/আউটপুট ব্রাউজারের সুবিধা দিয়ে এবং কিছু নির্দিষ্ট ডেমো কমান্ড দিয়ে কাজ করে।
- এটি এখনো পূর্ণ AI নয়; সব প্রশ্নের উত্তর দিতে পরের ধাপে backend-এ AI API যুক্ত করতে হবে। API key কখনো index.html-এ রাখবে না।
- ওয়েবসাইট একা Android ফোনের সব অ্যাপ/সেটিংস নিয়ন্ত্রণ করতে পারে না। তার জন্য পরবর্তী Android app wrapper/native Kotlin-Java code, user-granted permissions এবং নিরাপদ confirmation flow লাগবে।
- কোনো action গোপনে চালানো হবে না; কল/মেসেজ/গুরুত্বপূর্ণ পরিবর্তনে ব্যবহারকারীর নিশ্চিতকরণ রাখা উচিত।
