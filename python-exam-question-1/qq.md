---
description: 'Answer:'
---

# 1. What are the rules of naming and using variables. What can you do to avoid name errors? mark: 5

 ভ্যারিয়েবলের নিয়ম:

 1. ভ্যারিয়েবলের নাম অবশ্যই এক শব্দের হতে হবে ।

2. প্রথম অক্ষর অবশ্যই একটি alphabetic letter\(uppercase or lowercase\) অথবা underscore \( `_` \) হতে হবে । যেমনঃ `nafis`, `a`, `b`, `_variable` লেখা যাবে ভ্যারিয়েবল হিসেবে কিন্তু `1name`, `@nafis`, `7a`, `%b`এই ভাবে লেখা যাবে না । প্রথম অক্ষর ছাড়া পরে letter, underscore, number ব্যবহার করা যাবে। যেমনঃ `variable1`, `my_variable`, `not_Very_Good_Name10` যদিও ভ্যারিয়েবলের শুরুতে underscore ব্যবহার করা যায়, কিন্তু পাইথনের কনভেনশন হচ্ছে ভ্যারিয়েবলের নাম সবসময় lowercase letter দিয়ে শুরু করা।

3. পাইথন Case Sensitive অর্থাৎ `a = 4` এবং `A = 4` একই ভ্যারিয়েবল না।

4. পাইথনের কিছু reserved কী-ওয়ার্ড আছে, এগুলো ব্যবহার করা যাবে না । যেমনঃ `if`, `else`, `elif`, `for`, `while`, `break`, `continue`, `except`, `as`, `in`, `is`, `True`, `False`, `yield`, `None`, `def`, `del`, `class` ইত্যাদি।

 ভ্যারিয়েবলের এরর :

আমরা প্রথমবার যখন কোনো একটা ভ্যারিয়েবলে কোনো ভ্যালু এসাইন করি তখন সেই ভ্যারিয়েবলটা initialize হয়। পরবর্তীতে আমরা ঐ ভ্যারিয়েবলটাতেই আবার বিভিন্ন ভ্যালু রেখে কাজ করতে পারবো। কিন্তু যদি আমরা ভ্যালু এসাইন করে initialize করিনি এই রকম কোনো ভ্যারিয়েবল নিয়ে কাজ করার চেষ্টা করি তাহলে এরর দিবে।

