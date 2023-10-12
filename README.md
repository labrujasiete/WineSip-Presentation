# WineSip (Wine tasting app)

## Overview
The core objective of the "WineSip" application is to enhance the depth and precision of flavor descriptions during wine tasting, concurrently serving as a digital repository, akin to a personal notebook or log. This functionality is presented through a thoughtfully crafted user interface (UI) designed for optimal user experience.

## Dev Backlog
[Click here for Dev Backlog](Dev_Backlog.md)


## Technical matters

This Flutter project is currently in development and aims to simplify the process of wine tasting and note-taking by providing an elegant and user-friendly experience. The app utilizes several key technologies and features:

- **Flutter:** Open-source UI software development kit (SDK) created by Google for building natively compiled, cross-platform mobile applications with a single codebase.

- **Dart (Primary programming language):** Modern, object-oriented programming language developed by Google, known for its efficiency and suitability for building web and mobile applications.

- **Authentication:** Google login functionality is already implemented, allowing users to log in using their Google accounts. Support for other common social networks is still pending.

- **State Management:** The app uses the Provider package as a state manager, ensuring efficient and organized state management throughout the application.

- **Backend:** The functionality of the app relies heavily on Firebase, including Firebase Firestore for data storage and Firebase Storage for handling media assets.

- **flutter_screenutil:** The Flutter Screen Util package simplifies responsive layout development in Flutter by providing functions to adapt UI elements to different screen sizes, improving user experience.

- **cross-platform:** This app is being developed for both Android and iOS platforms, ensuring a wide reach and accessibility for users on different mobile devices.

## Features

### Wine Tasting Experience

The primary focus of this mobile application is to enhance the depth and precision of flavor descriptions during wine tasting. It achieves this through the following features:

1. **Five-Step Sliders:** Intuitive five-step sliders are provided for key wine traits, including:
   - Body
   - Sweetness
   - Tannins
   - Acidity
   - Alcohol

2. **Aroma Descriptions:** Visually appealing, square-shaped buttons display a variety of wine aromas, each accompanied by relevant icons. Users can select and describe the aromas they perceive during wine tasting.

3. **Grape Variety Selector:** Our app also features a comprehensive grape variety selector to assist users in identifying and recording the wines they taste. By providing this broad range of properties and flavor descriptions, we empower wine enthusiasts to express their tasting experiences more accurately and vividly.

   These detailed notes are not only for personal reference but can also be shared with others, fostering a community of wine enthusiasts who can better understand and appreciate each other's unique perspectives on various wines.



## Development Progress

- Google login functionality is complete.
- Support for other common social networks is pending.
- State management using Provider is implemented and organized.
- Firebase Firestore is used for storing and managing wine-related data.
- Firebase Storage is utilized for handling media assets.

 - HomePage and Profile: The HomePage or Profile page on our app is your gateway to a personalized wine-tasting experience. Here, users can find their profile picture, username, and a quick snapshot of their wine journey, including the number of tasted wines and favorites. The app suggests new wines based on their preferences, making wine discovery a breeze. For those eager to expand their collection, there's a prominent "Taste New Wine" button, ensuring effortless wine cataloging. However, one of the standout features is the list of "Previous Wines Tasted." Each wine in this list is a portal to a treasure trove of tasting information, allowing users to revisit and review their past wine experiences with a simple click. It's a vital tool for refining their palate and making informed wine choices in the future.

  - Taste New Wine Page: Our "Taste New Wine" page is the ultimate hub for wine enthusiasts to document their wine experiences with precision. Users can begin by capturing a picture of their wine bottle, instantly adding a visual touch to their tasting notes, followed by selecting key details such as grape variety, vintage, and region. What sets our app apart is the innovative approach to aroma selection. With over 100 primary and secondary aromas represented by unique icons, users can accurately capture the essence of their wine's bouquet. Additionally, 5 intuitive range sliders allow for effortless categorization of 'body', 'sweetness', 'tannin', 'acidity', and 'alcohol'. To provide a comprehensive tasting profile, we offer three text input boxes for "Visual observation," "Nose," and "Mouth." These text boxes allow users to describe and detail their sensory experiences. As part of our future plans, we are looking to integrate a Speech-to-Text feature for even greater ease and convenience in recording your wine impressions.


## Future Development

In the future, we have ambitious plans to further enhance the Wine Tasting App with advanced features that cater to wine connoisseurs and enthusiasts:

### Virtual Cellar (My Cellar)

Introducing WineSip's premium feature, the Virtual Cellar. Designed for wine aficionados, it simplifies wine collection management. Scan labels or enter wine details effortlessly, customize categories, and benefit from storage guidance. Keep tasting notes and engage with a vibrant wine community. Whether you're a seasoned collector or a casual enthusiast, the Virtual Cellar enhances your wine-tasting journey. Stay tuned for pricing and release updates as we bring this feature to life.

### Wine Label Recognition

We envision implementing a cutting-edge Wine Label Recognition API. Users will be able to simply take a picture of a wine label, and the app will use image recognition technology to identify the wine, providing users with detailed information about the wine's origin, grape variety, and more. This feature will bring a new level of convenience and expertise to wine tasting.

### Speech to Text Integration

Another exciting development on our roadmap is the integration of Speech to Text functionality. Users will have the option to verbally describe their wine tasting experiences, and the app will transcribe their spoken words into text. This feature will save time and make it easier for users to record their thoughts and impressions while tasting various wines.

### Feedback Section

We plan to introduce a feedback section where users can share their thoughts and opinions on news and interests related to wine. Users will also have the opportunity to rate and review wine profiles. This feature will encourage engagement and interaction within the wine enthusiast community.

### Social Sharing

To expand the app's social reach, we intend to add a feature that allows users to share their wine profiles and tasting experiences on popular social networks. This will enable users to showcase their wine discoveries and connect with fellow wine enthusiasts beyond the app.




&nbsp;
## Screenshots

### Login and Homepage
![WineSip_Presentation_01](https://github.com/labrujasiete/wine_tasting_app_presentation/assets/48364518/afac3443-04ce-41d4-8341-67a4f9462d60)

### New Wine - Traits and Aromas Selector
![WineSip_Presentation_02](https://github.com/labrujasiete/wine_tasting_app_presentation/assets/48364518/a5a86c96-19ab-45c8-847b-b864402c85c3)

### This is our specialized design for the Grape Selector tool
![WineSip_Presentation_03](https://github.com/labrujasiete/wine_tasting_app_presentation/assets/48364518/bd5afb3b-0c38-4311-9454-16f6084828aa)

### Review your already tasted wines
![winesip_screenshots](https://github.com/labrujasiete/WineSip-Presentation/assets/48364518/c569a913-c31b-4d01-b970-052e89fbe126)



&nbsp;
## Intellectual Property & Ownership

Cristian Javier Delgadillo Cortés, Fullstack Mobile Developer, Lead Designer & Programmer.

![circled_avatar](https://github.com/labrujasiete/WineSip-Presentation/assets/48364518/d00facb8-c469-4672-934b-bfe2d83b55a4)

### Contact Information:
   
   - Whatsapp: +52 664-477-1595

### About me:

My name is Cristian Delgadillo, and I am a dedicated and passionate designer and developer. My journey began with a simple everyday problem I encountered in my own life: the absence of a notebook and pen when enjoying wines with friends or acquaintances. Traditional notebooks lack permanence, akin to the ever-evolving nature of a cloud-based solution. Despite extensive research into available apps, none precisely aligned with my vision.

Initially, my ambition was to create a straightforward wine cloud notebook. However, as I delved deeper into this endeavor, I quickly grasped the potential for significant enhancement. Fortuitously, my upbringing immersed me in the world of wine, surrounded by the rich culture, familial influences, and friends in Baja California. Simultaneously, my background as a programmer allowed me to witness the technological boom at its zenith, with experiences ranging from backend projects and website development to digital image processing, photography, and vector graphics creation.

These diverse experiences equipped me with the necessary skills to seamlessly transform my initial idea into a reality.


&nbsp;
## Sales representative
Cristian Pascual Serrano, Entrepreneur, Sales-man

![Cristian](https://github.com/labrujasiete/WineSip-Presentation/assets/48364518/b1dd55a8-e4cf-49a5-96f1-f412be08f5ac)

### Contact Information:
   
   - Whatsapp: +52 664-133-4428

### About me:

Hello, I'm Cristian Pascual Serrano, and I serve as a dedicated representative in the fields of entrepreneurship and sales. With a name that carries an air of confidence, I've cultivated a strong presence in the world of business and commerce.

In addition to my thriving professional life, I hold a deep-seated passion for the world of wine. This appreciation for viniculture provides a unique dimension to my life, offering a delightful contrast to the demands of the business world.
