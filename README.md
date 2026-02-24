1---- What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

   getElementById()- ID দিয়ে ১টা element নেয়

   getElementsByClassName() - একই class এর সব element নেয়

   querySelector() - CSS selector দিয়ে প্রথম element নেয়

   querySelectorAll() - CSS selector দিয়ে সব element নেয়



2----How do you create and insert a new element into the DOM?


    createElement() দিয়ে element বানাই এবং appendChild() দিয়ে DOM এ যোগ করি





3---- What is Event Bubbling? And how does it work?

     Event target থেকে parent element এ উপরের দিকে propagate হওয়াকে event bubbling বলে

     যখন কোনো element এ event ঘটে (যেমন click) প্রথমে সেই element এ run হয়  তারপর তার parent element এ তারপর আরও উপরে যেতে থাকে যতক্ষণ না root পর্যন্ত পৌছায়


4----What is Event Delegation in JavaScript? Why is it useful?

    Parent element এ event listener বসিয়ে child element এর event handle করাকে event delegation বলে

    কম event listener লাগে 

    Dynamic/নতুন যোগ হওয়া element এও কাজ করে





5---- What is the difference between preventDefault() and stopPropagation() methods?

    preventDefault() - Default action বন্ধ করে

    stopPropagation() - Event bubbling বন্ধ করে