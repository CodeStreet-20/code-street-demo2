# Project Book-worm

CodeStreet'20.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


## Problem statement:

The Cities of tomorrow will be full of voracious readers and insatiable biblophiles. Reading real books is still as popular as ever despite the coming of E-books, with the young generation being a major chunk of this romanticist reading community.   

Today there is a trend of **BOOK EXCHANGE  in India**, the scale of which has never been seen before.The whole process, while novel, is **Disoriented and Uncentralized** with no way to keep track of things .
If we go deeper, we will find that the problem also lies in the **degrading LIBRARY SYSTEM in India**. Most cities have neglected this particular area even while preparing to be a smart city under present government initiative. 
*There is a need to **revive the Library System**, making it accessible and popular among people, and Improvising Book-Exchange into an organised and user-friendly system, with the help of modern technologies, that is able to serve the current wave of book lovers*. 

## Description of desired application:

At the Initial Stage we want to make an app that  has catalogued all the books in different libraries in a particular city(filter option available: City, Library name, Genre..etc), we plan to cover Many more cities after initial release.
Users would be able to issue a book online. The Librarian will get the request and will get the book ready for collection as and when demanded by the user. The missing and return date will be strictly monitored and will be available in the app for another person to send an issuing request accordingly. 
There would be an option for individuals to make their own mini-library platform to exchange and lend the books with almost the same rules as applied for Public/Private libraries.
We will also provide a section for any book vendors interested in selling the books through our app and provide comparison for rates and exchange values that assist users in the process.
User Review system: It enables libraries to meet members demands more efficiently and attract more members to the reading community. This would enable librarians to run the library more smoothly, maintain book quality and deal with shortages and demands for books easily.
A discussion forum for popular books strictly upon demand, there will be channels for different book to be discussed separately

## Solutioning and Methodology:

**Cataloguing in the App:**
A retrieval system would be needed to form a database, in case the library has the records in written format.
If the library is already equipped with a modern database system, then we would just need to access  the pre existing databases.

 **Online issuing and book tracking:** 
A **real-time updating database** that monitors every transaction of books in the library.
Every time a book is issued or returned, it gets updated in the database.
Users can make **issue requests**, which will be accepted or rejected based on availability. Users would be **notified later when the book is available**.

**Virtual mini-library for each user: **
Allows users to make  a list of the books they want to share, i.e. **The basket** and a list of books they want to read, i.e. **The wishlist**.
Other users can view other users’ **Basket** and **Wishlist**, and request, lend or exchange books accordingly.

 **Section for book vendors and rate comparison for users:** 
Vendors will be given a separate type of account that  is **specifically made to sell** new as well as second hand books.
A **comparison for rates and exchange values** will be  provided that **assist users** in the process.

** A User review system to determine reading trends:** 
The app would take **reviews from users** and other review sites, and analyze them **to determine the demands and requirements** of the local audience.
Trends will be decided **on the basis of geographical distance**, and higher priority will be given to **local reading-trends**.

**A discussion forum for popular books**: 
The App will have  a **discussion forum** feature that allows readers to discuss a** book or genre**.
This feature will be available to users for a **selected number of books/genres**, whose  **activity and participation crosses a threshold**.

### Constraints: 
Apps built with flutter are generally **larger in size** than it’s native counterparts hence, **downloading size  would be larger**. Hence would **require more space** in the user's device.
An **Initial investment** of capital would be required from our side  to provide the best user experience to the small user base which we would have at the beginning. With proper marketing and advertising, the popularity of the App is expected to boost within no time. 
Using Optical character recognition (OCR) may face challenges, since library **records may be very old, unorganised  and in poor condition**. 
The suggestion feature has Location as a parameter, so there would be certain **constraints in the information we ask users** in order to provide them the best service, **without compromising their privacy**.

## Tech Stack: 

We would be using **Flutter** to build our app, which uses **DART** as it’s programming language. It is a **hybrid app development** process which helps deploying **apps for web, android, iOS** all through a single codebase. Flutter **renders the app independently** on the device hence performance would be at par with native apps. 
We would integrate our app, with Google’s **Firebase**, which is a cloud service. We would use it to store our data on their servers. Hence, **scalability and security** are of no concern. Our app would be able to scale to any amount of users with any problems and would be completely secure. 
We would be using **Firestore**, to store and sync users app data to a global scale and would be using **Firebase ML**, for suggesting further books to read on the basis of what genre of books is generally issued by the user and the ratings given to them. No other personal data would be used in this process hence **respecting user’s privacy**. 
Users can login to our app, and we would use the  **Lowest geolocation signal** which would help us identify the user’s city location and it would help us navigate them to the best rated libraries around them. This way we won’t get the exact user’s location but instead just the city where the user is located, and the user could use Google Maps which we would integrate in our app to go to that library, **without any compromise on user’s privacy and data**. 
All of the above would be maintained through a **single codebase**, hence updating and maintaining our app would be easy. 
For the review system, we are going to implement **Sentiment Analysis** using Natural Language Processing (NLP)** Techniques.  This will help us identify and segregate positive and negative reviews from each other and improve the services of the libraries. Performing Sentiment Analysis on book reviews would also help the libraries in better managing their itinerary. For this application, we are going to use: **REST API to gather reviews data and user-related information**.
For the data retrieval from libraries with handwritten records, we are going to use **Optical character recognition (OCR)**, a computer vision application that can be used to convert images of digital or hand-written text images to a **machine-readable text format that can be processed, stored and edited**. 

## Future prospects:
We can approach the various cities under **Smart-City Project** that have their **SPV's** to pitch the idea, get necessary approval and get it implemented. 
Many Cities have provision of citizens’ contribution and this can be seen as **Community Outreach**. The system would be **open to all**, specifically book lovers who have a system made to cater their needs.
 It will be a Community Outreach program for smart cities **for a more read and engaged society**. Thus, any progressive governance would be willing to include it in their goals.

Visualisations:

https://imgur.com/a/nkxHegW

