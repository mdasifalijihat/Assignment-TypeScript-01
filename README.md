<!--  -->

1. What are some differences between interfaces and types in TypeScript?

Ans: TypeScript-এ interface এবং type— object-এর গঠন নির্ধারণ করতে ব্যবহৃত হয়। যদি ও এদের কাজ অনেকটা একই, তবু কিছু গুরুত্বপূর্ণ পার্থক্য রয়েছে।

<!--  -->

2. What is the use of the keyof keyword in TypeScript? Provide an example.

Ans: keyof TypeScript-এর একটি powerful operator, যা কোনো object-এর সব key-কে একটি union টাইপ হিসেবে return করে।

ব্যবহার করা হয়:

1.  Object-এর property name গুলোকে টাইপ হিসেবে পেতে।
2.  Type-safe access নিশ্চিত করতে।
3.  Dynamic property reference এর জন্য।

Example: type User = {
id: number;
name: string;
email: string;
};

<!--  -->

3. Explain the difference between any, unknown, and never types in TypeScript.

Ans: TypeScript-এ এই তিনটি টাইপ দেখতে হলেও এগুলোর উদ্দেশ্য এবং আচরণ সম্পূর্ণ আলাদা। এগুলো বুঝলে type-safety বৃদ্ধি পায়।

any মানে: এই ভ্যারিয়েবল যেকোনো কিছু হতে পারে, আর TypeScript কোনো চেক করবে না।
unknown: যেকোনো মান রাখতে পারে, কিন্তু ব্যবহার করার আগে টাইপ চেক বাধ্যতামূলক।
never: যে ফাংশন কখনো কোনো মান return করে না তার return টাইপ হলো never।

<!--  -->

4. What is the use of enums in TypeScript? Provide an example of a numeric and string enum.

Ans: TypeScript-এ enum (Enumeration) হলো একটি বিশেষ টাইপ যা নির্দিষ্ট মানের একটি group তৈরি করতে ব্যবহৃত হয়। যখন কোনো মানকে একটি নির্দিষ্ট সেটের মধ্যে রাখতে চাই, তখন enum ব্যবহার করা হয়।
-->কোড আরও readable করার জন্য |
-->Fixed মানগুলোকে একটি গ্রুপে সাজানোর জন্য |
-->Magic number/string দূর করার জন্য |
-->Developer mistakes কমানোর জন্য |
-->Autocomplete এবং type-safety পাওয়ার জন্য |
