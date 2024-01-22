# WordPress Developer Guideline (Bangla Version)
সুদক্ষ WordPress ডেভেলপার গড়ার লক্ষ্যে এই লেখা। এই গাইডলাইনে সময়সীমা অনুসরণ, বিষয়ভিত্তিক পর্যায়, অপ্রয়োজনীয় পয়েন্টগুলোকে ফিল্টার, প্রোজেক্ট, সিভি তৈরিসহ অনেক গুরুতপূর্ন বিষয় তুলে ধরা হয়েছে।

## শুরুতে কিছু কথাঃ
আমরা ওয়ার্ডপ্রেস ডেভেলপার হওয়ার জন্য অনেকেই সঠিক গাইডলাইন পাই না, যার ফলে আমরা ক্যারিয়ার গড়তে গিয়ে টেনশন এ পরে যাই, আবার অনেকে লাইন থেকে ঝড়েও যাই। প্রফেশনাল সঠিক গাইডলাইন পেলে অনেকেই অনেক সময় বাঁচিয়ে হয়ে উঠতে পারেন ভালো একজন ওয়ার্ডপ্রেস ডেভেলপার। এই লক্ষ্যে এই ক্ষুদ্র কন্ট্রিভিউশান করার চেষ্টা করেছি। 

এই পাইপলাইন টা আমার একান্ত নিজস্ব মতামত। এর সাথে কারোকারো মতের অমিল হতেই পারে। কিন্তু আমার ৮ বছর+ অভিজ্ঞতা থেকে ও মার্কেট এর চাহিদা ও বাস্তবতা থেকে আমি মনে করি এই পাইপলাইন টা সেরা গাইডলাইনগুলোর মধ্যে একটি গাইডলাইন, ইনশাআল্লাহ।

চলেন শুরু করা যাক!

## গাইডলাইন নিয়ে গুরুত্বপুর্ণ কিছু কথাঃ
অনেকেই থিম ও প্লাগিন ডেভেলপমেন্ট এর কমন বিষয়গুলো আলাদা আলাদা করে অনেক এলো মেলো সময়ে শিখে থাকে, যা তার ক্যারিয়ার গড়তে বেশি সময় লাগিয়ে দেয় এবং সে বিষয়টা জটিল মনে করে।

এই গাইডলাইন এ আমরা Hot Topics আগে শিখবো। যাতে থিম ও প্লাগিন এর শতকরা ৮০% আগেই শেখা হয়ে যাবে ইনশাআল্লাহ। থিম ও প্লাগিন এর অনেক বিষয় কিন্তু একদম একই রকম। তাই এদের আলাদা করে শিখার প্রয়োজন নেই।

একটি চ্যাপ্টার শেষ না করে পরের চ্যাপ্টার এ যাওয়া যাবে না। প্রতিটি চ্যাপ্টার শেষে একটি করে প্রোজেক্ট অবশ্যই করতে হবে।

## কোন ভিডিও থেকে শিখবো? কার ভিডিও দেখবো?
এভাবে না ভেবে আপনি ভাবেন যে আপনি কি কি শিখবেন। নিচে বর্নিত এক একটি টপিক নিয়ে ইউটিউব বা ব্লগ থেকে একাধিক ভিডিও দেখুন আর শিখুন। ১-২ টি ভিডিও এর বেশি ফলো না করাই ভালো। আপনার কাছে টপিক আছে মানে যেকোনো ভালো ট্রেইনার এর ভিডিও দেখতে আপনার কোনো বাধা নাই। টপিক বাই টপিক শিখে ফেলবেন।

## প্রোজেক্ট এর ডিজাইন কোথায় পাবেন?
যেকোনো প্রোজেক্ট করতে Mockup / UI লাগে। এই UI নিজে করতে গিয়ে সময় নষ্ট করবেন না। কিছু ওয়েবসাইটে প্রফেশনাল UI ডিজাইনার ভাইয়েরা দিয়েই থাকেন। সেখান থেকে আপনার পছন্দের UI ডাউনলোড করে নিন।

**UI Sources:**
* [Dribble](https://dribbble.com)
* [Behance](https://www.behance.net)
* [Themeforest](https://themeforest.net/category/ui-templates)

## FrontEnd Development
* HTML5
* CSS3
    * Basic +
    * Pseudo Class
    * Display Property
    * Position
    * Flex
    * Grid
    * Animation with KeyFrames
    * Responsive (Media Query)

* SASS/SCSS (Optional but Helpful for Career)
* Bootstrap / Tailwind CSS (Optional)
* Javascript
  * Basic +
  * Debugging
  * DOM Creation
  * DOM Manipulation [Most Important]
  * Fetch API
  * Event Handling
  * Event Bubbling, (stopPropagation)
  * Function (types, making, calling, passing arguments inside, return)
  * Form Validation
  * Trigger an Event
  * AJAX (Asynchronous JavaScript - Part 1) [Most Important]
  * Promise (Asynchronous JavaScript - Part 2)
  * ES6+ Features - (Arrow functions, let/const, classes, destructuring, spread/rest operators etc etc.)
* jQuery
  * Repeat All the Javascript Chapter in JQuery Syntax

### ⏰ Project Time (FrontEnd)
এখন আপনার ফ্রন্টএন্ড প্রোজেক্ট করার সময়। যে কোনো পছন্দের UI (উপরে UI Sources সেকশন এর যেকোনো সাইট থেকে নামানো) থেকে একটি সিলেক্ট করুন। সেখানে HTML5, CSS3, SASS ও Javascript এর যা যা টপিক শিখেছেন সেগুলো এপ্লাই করার প্লান করুন। মোবাইল ও ডেক্সটপ ডিভাইস সহ সম্পূর্ণ Responsive করে ফেলুন। আপনার প্রোজেক্ট টি Git এ আপলোড করে রাখুন।

## Tool Chapter
এই তিনটি টুল প্রোজেক্ট ম্যানেজমেন্ট এবং লাইভ্রেরি ব্যবহারের জন্য বিখ্যাত। ডেভেলপার হিসেবে আপনাকে এইগুলো তে পারদর্শি হতে হবে। যে কোনো প্লেলিস্ট থেকে এই ৩টি টপিক দেখে নিন। আপনার প্রোজেক্ট এ ব্যবহার করুন।
* Git (আপনার প্রোজেক্ট হোস্ট, ম্যানেজমেন্ট, প্লান ইত্যাদি ইত্যাদি, এর ব্যবহার অনেক সমৃদ্ধ)
* NPM (জাবাস্ক্রিপ্ট লাইব্রেরি/প্যাকেজগুলো এখানে থাকে)
* Composer (পিএইচপি লাইব্রেরি/প্যাকেজগুলো এখানে থাকে)

## BackEnd Development
ফ্রন্টএন্ড না করে কেউ ব্যাকএন্ড এ আশা যাবেনা। এখন আপনার একটা প্রোগ্রামিং ল্যাংগুয়েজ শেখা খুব জরুরি, যার নাম PHP। Facebook, Youtube থেকে শুরু করে Wikipedia ও PHP ব্যবহার করেছে, তাহলে এর জনপ্রিয়তা বুঝে নিতে পারেন।

### Programming Language Chapter
* PHP Basic (যে কোনো প্রোগ্রামিং ল্যঙ্গুয়েজ এর বেসিক অনেকটাই একই রকম, যেকোনো প্লেলিস্ট থেকে PHP বেসিক শিখে নিন এখানে ফিল্টার করার তেমন কিছু নেই)
* MySQL (Basic) (এটি ডাটাবেজ এর ডাটা নিয়ে আশা ও পাঠানোর ল্যাংগুয়েজ, ডাটা ছাড়া কোনো কাজ হবে? যেকোনো প্লেলিস্ট থেকে MySQL এর বেসিক শিখে নিন, নিচের বিষয়গুলো যাতে সেখানে থাকে)
  * Select Query
  * Insert Query
  * Update Query
  * Delete Query
  * Inner Join
  * Left Join
  * Right Join
  * Use of `DISTINCT`
  * Use of `GROUP`
  * Use of `WHERE`
* PHP OOP (Object Oreiented Programming) (OOP মানেই এডবান্সড পিএইচপি, এই পর্যায়ে শেখার সময় অনেক কিছু না বোঝা বা ভুলে যেতে পারেন, ভয় পাবেন না, এটা সবার ক্ষেত্রেই হয়। নিচের বিষয়গূলো তে ধারনা রাখুন, হেন্ড কোড প্রেক্টিস করুন)
  * Classes
  * Methods
  * Objects
  * Properties
  * Instance
  * Access Modifiers (public, private, and protected)
  * Magic Methods
  * Encapsulation
  * Inheritance
  * Polymorphism
  * Abstraction
  * Trait
  * Interfaces
  * AutoLoading classes with Composer
  * SOLID Principles (Learn Later, After First Job)
  * Design Patterns (Learn Later, After First Job)

### ⏰ Project Time (Language) CRUD and Mini
CRUD প্রোজেক্ট লিখলে ইউটিউবে অনেক দারুন দারুন প্লেলিস্ট পেয়ে যাবেন। সব আপনার করা লাগবেনা। লেটেস্ট যেকোনো একটী ধরে, আগের করা ছোট ফ্রন্টেন্ড প্রোজেক্টটাই ডাইনামিক করে ফেলুন। সেটা না করলে UI Resources থেকে এমন একটা ছোট UI নামান যেট করতে বেশি সময় লাগবেনা। মনে রাখবেন, প্রোজেক্ট যেনো বড় না হয়। অনেক সময় বড় প্রোজেক্ট কমপ্লিট না করায় অনেকে হতাশ হয়ে যায়। আপনি শুধু পিএইচপি এর বেসিক আর OOP দিয়ে CRUD করে একটা ছোট প্রোজেক্ট করে ফেলুন। যদি OOP ব্যবহার না ও করেন সমস্যা নাই, OOP আপনার আরো পরেও শিখে যেতে হবে। তখন, পিএইচপি বেসিক আর Mysql ব্যবহার করে আপনার প্রোজেক্ট টি করে ফেলুন। অবশ্যই প্রোজেক্ট করার সময় Git ব্যবহার করবেন। এটী আপনার জব পেতে সাহায্য করবে ইনশাআল্লাহ।

### 🔸 WordPress Chapter
এখন WordPress শেখার সময় চলে এসেছে। আগে Introduction টা করে নিন পরে Hot Topics গুলো একটা একটা করে সেরে ফেলুন। Hot Topics গুলো করলে কিন্তু আপনার থিম ও প্লাগিন ডেভেলপমেন্ট এর ৮০% শেখা হয়ে যাবে ইনশাআল্লাহ। মানে, পরে থিম আর প্লাগিন শিখতে খুব কম সময় লাগবে ইনশাআল্লাহ।
* Introduction
  * WordPress Dashboard Introduction
  * WordPress Database Table Introduction
* WordPress Hot Topics
  * Debugging (Learn at 1st)
  * Hooks
  * Ajax with WordPres
  * Sanitization & Escaping & Validation
  * [WordPress APIs](https://codex.wordpress.org/WordPress_APIs)
    * MetaData API (Metabox Management)
    * Settings API
    * Option API
  * Creating Shortcode
  * I18n: Translation Functions
  * [Conditional Tags](https://codex.wordpress.org/Conditional_Tags)
  * [Coding Standards](https://developer.wordpress.org/coding-standards)
* WordPress Theme Development
  * Template Hierarchy
  * Post Types Register
  * Taxonomy Register
  * [WordPress APIs](https://codex.wordpress.org/WordPress_APIs)
    * Customization API (Theme)
  * WP_Query & get_posts()
  * Child Theme (How to create & manage)

### ⏰ Project Time (Theme): A Theme where max Hot Topics are used
এখন আপনি একটি থিম ডেভেলপমেন্ট করবেন। থিম করার জন্য যে কোনো একটি ফ্রি এইচটিএমএল প্রোজেক্ট নামিয়ে নিন, Free HTML Template লিখলে গূগলে অনেক ফ্রি প্রোজেক্ট পেয়ে যাবেন। একের অধিক প্রোজেক্ট করার প্লান করবেন না। এতে আপনারই ক্ষতি। আগে ১ টি শেষ করুন।

যতগুলো Hot Topics শিখেছেন আপনার থিম এ সেগুলো রাখার চেষ্টা করুন। প্লান আপনি নিজেই করুন। বেস্ট কোডিং স্ট্যান্ডার্ড এপ্লাই করার চেষ্টা করুন। প্রোজেক্ট হয়ে গেলে, যেকোনো সিনিয়র ভাই অথবা গ্রুপ এ পোস্ট করে কারো কাছ থেকে ভেরিফাই করিয়ে নিন।

* WordPress Plugin Development
  * [Admin Menu Management](https://developer.wordpress.org/plugins/administration-menus)
  * Asset Management / Enqueue assets
  * [WordPress APIs](https://codex.wordpress.org/WordPress_APIs)
    * WordPress Rest API (< Mid Level)
    * Transients API (< Mid Level)
  * [Cron Management](https://developer.wordpress.org/plugins/cron)
  * Working with Third-Party APIs
  * WP_List_Table class (Optional)
  * Gutenberg Block Development
    * React (Intermediate)

### ⏰ Project Time (Plugin): A Plugin where max Hot Topics are used
ছোট একটি প্লাগিন প্লান করুন। বড় প্লান করলে একাই এক্সিকিউট করার সময় না পেতেই পারেন। সেই ছোট্ট প্লাগিন এ এই চ্যাপ্টার থেকে যা যা শিখেছেন তা এপ্লাই করুন।

## চ্যাপ্টার তো কমপ্লিট এখন কি করবো?
এখন আপনি Intern করবেন। ৩ মাস থেকে ৬ মাসের ইন্টার্ণশিপ এ জয়েন করতে হবে। আপনি একা একাই প্রোফেশনাল প্রোজেক্ট এর একদম যোগ্য হতে পারবেন না। আপনাকে যেকোনো টিম এর সাথে কাজ করতে হবে। ফেসবুক গ্রুপগুলো তে নজর রাখুন, কোথায় ইন্টার্ন নিলে এপ্লাই করুন। আর মিনিমাম ৩ টা ইন্টার্ভিউ দিন। ইন্টার্ভিউ দিলে অভিজ্ঞতা বাড়ে। হতাশ হবেন না, এই পর্যন্ত যা শিখেছেন তা আপনার আয়ত্তে থাকলে, হাল্কা একটা ইন্টার্ন করার পর আপনি ভালো পর্যায়ে ভালো স্যালারিতে চলে যাবেন ইনশাআল্লাহ। এখন আর বেশি সময় লাগবে না।

## কিছু PRO টিপসঃ
শুধু কোড লিখেই কিন্তু ভালো ডেভেলপার হওয়া যায় না। পাশাপাশি অনেক আনঅফিসিয়াল কাজকর্ম করতে হয়। নিচের টিপসগুলো অনুসরণ করুন।

* সিনিয়র ডেভেলপারদের সাথে কথোপকথন করার চেষ্টা করুন। অযথা তাদের মেসেজ দিয়ে ডিস্টার্ভ করবেন না। তাদের সোশিয়াল মিডিয়াতে অনুসরণ করুন। এগুলো আপনার অনুপ্রেরণা জোগাবে ইনশাআল্লাহ।
* WordPress Meetup, Event এগুলোতে জয়েন করার চেষ্টা করুন। বেশিরভাগ ইভেন্টই কিন্তু ফ্রি। এগুলোতে অনেক আইডিয়া ও জ্ঞান শেয়ার করা হয়।
* Facebook, LinkedIn এ ডেভেলপারদের সাথে কানেক্ট হন। যত বেশি ডেভেলপার এর সাথে কানেক্ট হবেন, ততবেশি আইডিয়া, জব পোস্ট, ইভেন্ট ইত্যাদি সম্পর্কে জানবেন ইনশাআল্লাহ।
* আপনি যেভাবে বোঝেন সেভাবে শিখুন, টিউটূরিয়াল ব্লগ সব ফলও করুন। অন্যের কান দিবেন না।
* আপনি কি কি শিখছেন তা মিডিয়া তে শেয়ার করুন। শেখার সময় কোন ইগো পুশবেন না, এতে আপনার ই ক্ষতি।
* আপনার পার্সোনাল ওয়েবসাইট এর থেকে আপনার করা প্রোজেক্ট এর গুরুত্ব বেশি। সময় থাকলে পার্সোনাল ওয়েবসাইট করে ফেলুন। নইলে প্রয়োজন নেই।
* Github এ আপনার করা প্রোজেক্টগুলো পাবলিক করে রাখুন। অনেক কোম্পানি এগুলো দেখতে চাইতে পারে।
* ইংরেজি তে নিজের দক্ষতা বাড়ান, ইংরেজি যত ভালো জানবেন, আপনার উন্নতির দরজা আর বেশি খুলে যাবে ইনশাআল্লাহ।
* আপনার মত জুনিয়রদের সাথে নিয়মিত আড্ডা দিন। ক্যারিয়ার নিয়ে আলাপ করুন। এখান থেকে অনেক আশা ও অনুপ্রেরণা পাওয়া যায়।

## সিভি কিভাবে বানাবো?
আমি বলবো LinkedIn থেকে। LinkedIn খুব প্রফেশনাল রিজিউমি/সিভি তৈরি করে দেয় আপনার প্রোফাইল এর থেকে তথ্য নিয়ে। সেজন্য আগে LinkedIn প্রোফাইল টা সুন্দর করে গুছিয়ে নিতে হবে।

## ইতি কথাঃ
আমার এই লেখা থেকে যদি ১ জনেরও জীবন সুন্দর হয় তাহলেই আমার এই কষ্ট সার্থক হবে ইনশাআল্লাহ।আপনাদের মতামত ও পরামর্শ দিয়ে আমার পাশে থাকবেন আর দোয়া করবেন আমার জন্য। আপনাদের দোয়া ও ভালোবাসা আমাকে অনেক অনুপ্রেরণা জোগাবে ইনশাআল্লাহ।

এই লিংকটি শেয়ার করবেন। কমিউনিটিতে আপনার একটি শেয়ারও অনেকের সফলতার জন্য অবদান রাখতে পারে।

ধন্যবাদ সবাইকে। হ্যাপি কোডিং।

### **Contributed By**
![nazrul_islam_nayan_7](https://github.com/nayanchamp7/wordpress-developer-guideline-bangla/assets/43903460/4906defd-6ea2-4f14-801f-8609640e5202) <br>
Nazrul Islam Nayan <br>
Senior WordPress Developer @storepress <br>
Educator [@Learn With Nayan](https://www.facebook.com/learnwithnayan) <br>
[Mail](nazrulislamnayan7@gmail.com) |
[Facebook](https://www.facebook.com/nazrulislamnayan2023) |
[LinkedIn](https://www.linkedin.com/in/nazrul-islam-nayan) |
[Youtube](https://www.youtube.com/@learnwithnayan4u)

## Stay With WordPress Tips

<p align="left">
<a href="https://www.facebook.com/learnwithnayan"><img src="https://github.com/nayanchamp7/wordpress-developer-guideline-bangla/assets/43903460/4a288244-1e36-4f5a-a9ef-e7b53bdf9975" width="600"></a>
</p>




 
 
