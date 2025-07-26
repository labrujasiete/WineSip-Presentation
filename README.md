# WineSip
[Download App at WineSip.com](https://winesipapp.com/)

## Goal
The core objective(goal) of the "WineSip" application is to enhance the depth and precision of flavor descriptions during wine tasting. —Concurrently serving as a digital repository, akin to a personal notebook or log. This functionality is presented through a thoughtfully crafted user interface (UI) designed for optimal user experience.

![Frame 231](https://github.com/user-attachments/assets/e6642dc3-1fce-473f-8b22-b1ed2a9dbf21)

As part of the "XXIV Festival de las Conchas y el Vino Nuevo", our platform was awarded second place for Best Startup—an acknowledgment that highlights our contribution to the wine world through technological innovation and artisanal design. This event, recognized as one of the most important for the wine industry in Ensenada, B.C., and the "Valle de Guadalupe", brought together key players driving the sector’s development, including the Ministry of Agriculture, SEPESCA, COMEPESCA, the ProVino Committee of Baja California, CETYS University, and the Center for Viticulture Studies (CEVIT).

The festival not only celebrates excellence in wine and gastronomy but also recognizes initiatives that redefine how this culture is experienced and shared. Our platform stood out for its innovative approach, merging technology and user experience to enable wine enthusiasts to record, explore, and share their tastings in an intuitive and personalized way. This recognition underscores the importance of creating digital tools that connect the wine community—from producers to consumers.

The evaluation, conducted by experts and representatives from these institutions, highlights the significance of our platform as a bridge between tradition and modernity, demonstrating how new technologies can enhance an age-old experience like wine appreciation. Being recognized in a space where tradition, education, and wine culture converge strengthens our vision of continuing to innovate and bring value to the wine industry.

This award not only motivates us to keep refining our platform but also solidifies our position as a key player in the digital transformation of wine culture.

![Frame 267](https://github.com/user-attachments/assets/5ec5cb83-4e4b-4570-aed1-20db7694a99a)

## Dev Backlog & Development Progress
[Click here for Devlog & Development Progress <---](Dev_Backlog.md)

## Technical matters

This Flutter project has been developed to simplify the process of wine tasting and note-taking by providing an elegant and user-friendly experience. The app utilizes several key technologies and features, Here are a few noteworthy:

- **Flutter:** Open-source UI software development kit (SDK) created by Google for building natively compiled, cross-platform mobile applications with a single codebase.

- **Dart (Primary programming language):** Modern, object-oriented programming language developed by Google, known for its efficiency and suitability for building web and mobile applications.

- **Authentication:** Google login functionality is already implemented, allowing users to log in using their Google accounts. Support for other common social networks is still pending.

- **State Management:** The app uses the Provider package as a state manager, ensuring efficient and organized state management throughout the application.

- **Backend:** The functionality of the app relies heavily on Firebase, including Firebase Firestore for data storage and Firebase Storage for handling media assets.

- **flutter_screenutil:** The Flutter Screen Util package simplifies responsive layout development in Flutter by providing functions to adapt UI elements to different screen sizes, improving user experience.

- **cross-platform:** This app is being developed for both Android and iOS platforms, ensuring a wide reach and accessibility for users on different mobile devices.  

&nbsp;

# Current Features of WineSip

WineSip was originally designed as a simple way to replace notebooks and pens for wine lovers. It started as a basic app where users could log in and record wine tastings with plain text inputs. Over time, it has evolved into a social, AI-powered, and feature-rich platform to manage, share, and explore wine tasting experiences. Below is a detailed list of its current features:

## Authentication
**Google & Apple Sign-In**  
Users can securely log in using Google or Apple accounts. Authentication is powered by Firebase Authentication.

## Firebase Integration
**Firebase-Backed Infrastructure**  
WineSip is built on Firebase, using Firebase Authentication, Firestore for data, Cloud Storage for images, and Cloud Functions to power backend logic.

## User Profile
**Personalized Profile Page**  
Displays the user's avatar, username, title, level, and XP points. XP increases as users log wine tastings.

**Bio & Stats Overview**  
Users can write a short bio and view their total number of favorite wines, followers, and following.

**Wine Cards List**  
A descending chronological list of the wines you’ve logged. Each item displays the tasting date, star rating, wine name, and a flag icon for the wine’s country of origin.

## Notifications
**Activity Notifications**  
Users receive real-time updates when someone follows them, comments on their wines, or logs new wines.

## Floating Action Buttons (FABs)
**Quick Actions**  
Two FABs are available throughout the app to:
- Scan a wine label using AI (Gemini)
- Manually log a wine tasting

## AI Wine Scanner
**Gemini AI Label Reader**  
Users can take or upload a photo of a wine label. Gemini extracts structured data such as:
- Wine name
- Country & flag
- Grape variety
- Alcohol content
- Wine type (red, white, etc.)
- Vintage
- Suggested rating (out of 5 stars)

The AI fills a tasting form automatically, allowing the user to focus on sensory notes.

## Wine Tasting Form
**Detailed Sensory Logging**  
Users can log visual, nose, and palate impressions. Specialized widgets are available for:
- Selecting primary and secondary aromas
- Rating Body, Sweetness, Tannins, Acidity, Alcohol via sliders

More detailed tasting logs result in more XP points.

## Wine Page
**Detailed Wine Card View**  
Displays all the information about a specific wine tasting including:
- Wine name, user info, wine type, alcohol level, grape variety
- Tasting notes and sensory observations
- Floating buttons for: delete (if it’s your wine), like, and comment

**Find Matching Wines**  
Matches your wine tasting with entries from other users using wine name. Results appear in a bottom sheet.

## Comments & Likes
**Interaction Tools**  
Users can comment on wine tastings and like their own or others’ entries. Comments are accessible through a dedicated button.

## Profile Menu
**Editable User Data**  
- Edit Profile: Change avatar, username, title, bio, and country
- About WineSip: General information and IP notice
- Feature Development: A news page about upcoming features
- Sharing is Caring: Link to donation page

**Private Settings**  
- End User License Agreement (EULA) and Privacy Policy
- Choose visibility (whether you can be followed/found)
- Manage email verification or update email
- Blocked users list
- Delete Account: Initiates a 14-day deletion window with cancel option upon re-login

**Support & Feedback**  
- Report Bug or Suggest Feature: Take screenshots, annotate, and describe issues
- Logout option

## Bottom Navigation Bar
**Persistent UI Navigation**  
The app contains four main sections accessible at all times:

### Profile
Your personal tasting log and social hub (described above).

### People
**User Discovery & Social**  
- Search and follow other WineSip users
- View public profiles, wine lists, and tasting entries of others

### Feed
**Social Wine Timeline**  
- Instagram-style feed showing wine tastings from people you follow
- Cards include wine photo, user details, rating, tasting date, and report button

### Wines
**All Your Tastings in One Place**  
A full list of your wine tastings with search functionality. Also allows viewing public tastings from other users.

---

WineSip continues to grow, but its core idea remains the same: an easy and elegant way to store your wine tastings in the cloud, and discover what others are enjoying—replacing notebooks with an AI-powered, social wine journal.

## Future Development - We are actively working on further enhancing WineSip with advanced features.

- **Virtual Cellar (My Cellar)**: WineSip's premium Virtual Cellar – WineSip's tool for effortless wine collection management. Scan, customize, and engage with a vibrant community. Enhance your wine-tasting journey. Pricing and release updates coming soon!

- **Wine Label Recognition**: Snap a wine label, get instant details. WineSip's Label Recognition API brings expert convenience to your tasting experience!

- **Speech to Text Integration**: Users will have the option to verbally describe their wine tasting experiences, and the app will transcribe their spoken words into text. This feature will save time and make it easier for users to record their thoughts and impressions while tasting various wines.



&nbsp;
## Screenshots

### Homepage
![banner-1-1_ad_Apr_24](https://github.com/user-attachments/assets/9d49a738-e8eb-4ba5-87c4-d49b5cc473e6)

### New Wine - Traits and Aromas Selector
![WineSip_Presentation_02](https://github.com/labrujasiete/wine_tasting_app_presentation/assets/48364518/a5a86c96-19ab-45c8-847b-b864402c85c3)

### This is our specialized design for the Grape Selector tool
![WineSip_Presentation_03](https://github.com/labrujasiete/wine_tasting_app_presentation/assets/48364518/bd5afb3b-0c38-4311-9454-16f6084828aa)

### Review your already tasted wines



&nbsp;
## Unique Selling Proposition (USP) for WineSip: Elevate Your Wine Tasting Experience

### "At WineSip, we redefine the art of wine tasting with a meticulously crafted fusion of technology and passion. Our application goes beyond the conventional, serving as your digital companion in the world of wines. What sets us apart?

Precision in Flavor Descriptions: WineSip empowers you to articulate the intricate nuances of each sip with unparalleled depth. Our innovative features guide you through a journey of flavors, enhancing your tasting experience and enabling you to express the subtleties that make each wine unique.

Digital Repository of Memories: Say goodbye to the limitations of traditional notebooks. WineSip doubles as a digital repository, preserving your tasting notes securely in the cloud. Your wine journey is now immortalized, easily accessible anytime, anywhere, reflecting the ever-evolving nature of your palate.

Thoughtfully Crafted User Interface (UI): Immerse yourself in a seamless and visually captivating interface designed for optimal user experience. WineSip's UI is not just functional; it's an aesthetic extension of your passion for wine, making the exploration of flavors a delightful and intuitive experience.

Fusion of Heritage and Technology: Born from the intersection of a deep-rooted connection to Baja California's wine culture and cutting-edge programming skills, WineSip encapsulates the best of both worlds. Our founder, Cristian Delgadillo, seamlessly integrates tradition and technology to bring you an application that resonates with the richness of wine culture and the precision of modern development.

Continuous Evolution: WineSip is not just an application; it's a living, evolving entity. Backed by a developer with a background in the technological boom, expect regular updates and enhancements that keep pace with the dynamic world of wines and technology.

### Experience the future of wine tasting with WineSip — where precision meets passion, and tradition dances with technology."






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
