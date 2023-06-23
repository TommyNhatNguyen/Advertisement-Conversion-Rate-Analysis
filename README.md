# Advertisement Conversion Rate Analysis 
### **1. Context:** 
- Online store of sporting goods: clothing, shoes, accessories and sports nutrition. **On the main page of the store they show users banners in order to stimulate their sales.** Now one of 5 banners is randomly displayed there. Each banner advertises a specific product or the entire company. Our marketers believe that the experience with banners can vary by segment, and their effectiveness may depend on the characteristics of user behavior.
- Source code: ![My code file](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/blob/main/Product_Conversion_Rate_EDA.ipynb)
### **2. Business goals:** 
- Recommend how/when/what to show advertising banners on the store's main page to increase sales.
### 3. Forming questions & EDA:
**Overview data:**
![image](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/assets/86128966/3a271b93-fefa-4164-b53e-8804b26710a2)

![image](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/assets/86128966/583f29a6-b5aa-440c-9995-1085b2dae08d)
- Each product accounts for 19% - 20% of total data.
![image](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/assets/86128966/c365a237-7680-4df3-b2a1-c7d2c29f82f3)
- More than 71% users prefer using mobile phone than desktop (only 28%)
**Forming questions & EDA:**
1. Which product has the highest conversion rate?
![image](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/assets/86128966/c2771149-3255-4a76-9baf-f0d23beadab7)
- **clothes and sneakers** have highest conversion rate.
- **Insights:** cusomters buy more clothes and sneakers when being advertised than others.  
3. Which site has the highest conversion rate?
![image](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/assets/86128966/02ccf7c9-d54c-4028-a75a-f94f95a2284e)
- Total conversion rate of desktop and mobile are nearly the same. However, **conversion rate of desktop is much higher than that of mobile**
- **Insight:** People tend to use their mobile to access the web to get information, then go to the website to make a purchase -> **Mobile leads traffic, desktop delivers sales** (According to: https://www.digitalcommerce360.com/2019/07/24/consumers-order-more-on-desktop-than-mobile-for-online-retailers/)
4. Which month has the highest conversion rate?
![image](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/assets/86128966/8ab512c3-b726-4210-8ffe-341cb40268c6)
- Febuary has the highest conversion rate, January and May are the lowest.
- April has the highest total conversion, slightly lower rate compare to Febuary.
5. Which day has the highest conversion rate?
![image](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/assets/86128966/8f1ace1d-3da5-4893-9324-65b9f2647e57)
- All of the days have nearly the same total conversion.
**Insight:** Conversion rate on wednesday is the lowest. This is because customers will have to wait until next week to get their order, since shipping company wont ship on saturday and sunday.
6. Which hour has the highest conversion rate?
![image](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/assets/86128966/d4070eaf-d369-4405-9138-63892d6ad9ad)
- Customers tend to purchase more during midnight and afternoon. This is because most people (especially white-collar workers) are free during these timeframe.
- **Insight:** During 4a.m - 10a.m and 4p.m - 7p.m, customers tend to purchase less because they'll have to go to work and having dinner with family.
7. Conversion rate trend by product?
![image](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/assets/86128966/d1a06f62-2070-4ec7-ae0d-9457621334b9)
- Clothes have the highest conversion rate as well as total conversion overtime.
- Sport nutrition is the lowest.
- All products tend to have an up-trend at the first quarter, then start to plateau and will decline at the start of May. However, it quickly bounce back at the start of the third quarter.
- **Insight:** People will want to buy more new things for a new year.
8. Conversion rate trend by site version?
![image](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/assets/86128966/0114c382-e73f-4403-9e93-5d9da8027e9a)
- Site version have exactly the same trend as that of product.
- Desktop has much higher conversion rate than that of mobile
9. Is there a significant difference in conversion rate between each site version?
![image](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/assets/86128966/0b528763-6c70-4190-b3e9-3e460cbe0e73)
- P-value < 0.05 => There's a significant difference in coversion rate between desktop and mobile => desktop has much higher conversion rate!
- This confirms people tend to buy using desktop than mobile phone. 
10. Is there a significant difference in conversion rate between each product?
![image](https://github.com/TommyNhatNguyen/Product-Conversion-Rate-Analysis/assets/86128966/fa66a923-d3d0-403d-a4c5-39301d8c9d4a)
- P-value < 0.05 => There's a significant difference in coversion rate between each products => clothes is the highest, sneakers is the second, then accessories and sport nutrition.
- This confirms clothes and sneakers have the highest conversion rate. 
### 4. Conclusion & Recommendation
**Overview of the data:**
- Each product accounts for 19% - 20% of total data.
- More than 71% users prefer using mobile phone than desktop (only 28%)
- Nearly 3% of users have purchased, the click rate is about 10%.
  
**Recommendation:**
- **Put more advertising banners on the first quarter, especially on Febuary** because users tend to buy more products at the start of a new year.
- **Focus on pushing clothes and sneakers advertising banners in 2 timeframes: 8p.m - 3a.m and 11p.m - 3.am** on both website and mobile to increase conversion rate.
- We have to **put advertising banners on both website and mobile**, because users will check information using mobile device, then go to the website to buy. Therefore, we have to constantly remind customers about the products across platforms to turn leads into sales.
