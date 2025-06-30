
---
[README](https://github.com/dkssud-dus/webRedesign-WildRift/blob/main/README.md) | [README_en](https://github.com/dkssud-dus/webRedesign-WildRift/blob/main/README_en.md)

<br/>

`#RedesignProject` `#GameWebsite` `#TeamProject` `#4PeopleTeam` `#PCOnly` 
# **Website Redesign Project Details:**
### Wild Rift

<br/>
<br/>
<br/>

## **Role**
| Name         | Responsibility Area           | Main Page Work                                          | Sub Page Work                                                  |
|--------------|-------------------------------|---------------------------------------------------------|----------------------------------------------------------------|
| 👑 박서영, Park seo young | Info Delivery                 | Game Info, Event, Footer                                | Notice List, Notice Detail (Text/Video)                            |
| 김채연, Kim chae yeon | Visual & Audio Content        | Header + Main Visual, Playlist                          | Monster List, Monster Detail                 |
| 엄지승, Eom Ji Seung   | Visual + Info Blend           | New Champ (Zilean), Game Mode                           | Skin                                                           |
| 조효희, Jo hyo hee   | Info & Banner Presentation    | Character List, Patch Note, Riot Games Section          | Character Detail                                    |

</br>

> README Author & Final Compiler: 김채연, Kim chae yeon

<br/>
<br/>
<br/>

## Table of Contents

1. [Project Overview](#1-Project-Overview)   
2. [Core Features](#2-Core-Features)   
3. [Page-wise Features](#3-Page-wise-Features)    
   
</br>
</br>
</br>

---

## 1. Project Overview
### 1.1. Background
Wild Rift is the mobile version of League of Legends, gaining popularity for its fast-paced gameplay and mobile-optimized controls. However, the official website and related promotional pages were not effectively conveying the brand's unique worldview, character personalities, and gameplay styles, with room for improvement in terms of visual immersion and information delivery. Particularly for new users, the complex information structure and lack of visual guidance made access difficult, while for existing users, content updates and event information delivery was fragmented.

</br>

The purpose of this project is as follows:

</br>

1. Actively utilize League of Legends IP to visually emphasize the worldview and character personalities.     
2. Design a structure that clearly delivers game content information.         
3. Implement a design that provides an immersive user experience for both new and existing users.    

</br>
</br>
</br>

### 1.2. Keywords
1. **Brand Identity**      
    1.1. Actively reflect League of Legends' unique colors, illustrations, and UI styles          
    1.2. Utilize various IP content such as champion voices, music, and videos to provide sensory immersion          
    
</br>

2. **Accessibility**     
    2.1. Restructuring information hierarchy      
    
</br>

3. **User Acquisition and Retention**    
    3.1. Visually emphasize the latest content such as new champions and seasonal events to attract user interest          
    3.2. Naturally induce user acquisition by incorporating familiar elements (worldview, champion backgrounds, etc.) for existing PC players         
    

</br>
</br>
</br>

---

## 2. Core Features
### Media Content and Audio Content Control
1. Generating interest through expansion of League of Legends worldview
2. Gameplay videos / Character voices / Related music
   
</br>
</br>
</br>

### Tab Structure Using JavaScript
1. Screen simplification, allowing users to check only desired information
2. Utilized in each description section / page   
   
</br>
</br>
</br>

---

## 3. Page-wise Features

### 3.1. [Main Page](https://dkssud-dus.github.io/webRedesign-WildRift/index.html)

---

### 3.1.1. Header + Main Visual
![18](https://github.com/user-attachments/assets/74ac15a7-dda1-4737-aa56-935b721e83f3)

<br/>

#### Purpose        
1. Designed to induce user curiosity and encourage scrolling.

<br/>
   
#### Implementation Summary 
1.  Header           
   1.1. Created to enable simple navigation to sub-pages.
2.  Main Visual       
   2.1. When first accessing the main page, a game trailer video appears below the logo.         
   2.2. When scrolling, the logo and video scale together, the logo disappears, and the video fills the entire screen.        
   2.3. The Wild Rift logo appears once, followed by a download button that emerges.   

<br/>

> Lead: 김채연, Kim chae yeon

<br/>
<br/>
<br/>

---

### 3.1.2. Game Info
![19](https://github.com/user-attachments/assets/4fe7ca97-d735-47e2-a3c7-88a9df7d7820)

<br/>

#### Purpose
1.  Emphasized Wild Rift's mobile game identity and effectively delivered important content.

<br/>

#### Implementation Summary
1.  Used a tab format where content changes when clicking the icon at the bottom left.
2.  Used a mobile phone frame to emphasize Wild Rift's mobile game identity.
3.  Applied color and bold formatting to emphasis points to prioritize content flow importance.

</br>

> Lead: 박서영, Park seo young

</br>
</br>
</br>

---

### 3.1.3. New Character (Zilean)
![20](https://github.com/user-attachments/assets/cca5ff51-0b90-4def-ac0b-bf375df27275)

<br/>

#### Purpose
1.  Introduced basic information and skills of the new character 'Zilean, the Chronokeeper'.

<br/>

#### Implementation Summary
1.  Composed of sections introducing character name, story, and skill settings.
2.  Champion video and skill buttons are located on the right, with corresponding descriptions appearing when skill buttons are clicked.

</br>

> Lead: 엄지승, Eom Ji Seung

</br>
</br>
</br>


---

### 3.1.4. Event
![21](https://github.com/user-attachments/assets/f6cf4656-bf8d-41e1-ac4b-b3f4fe695131)

<br/>

#### Purpose
1.  Delivered event information concisely while providing users with dynamic experiences.

<br/>

#### Implementation Summary
1.  Used accordion format where clicking cards changes the `flex` width values.
2.  Images when the accordion menu is collapsed and expanded have different width values.
3.  Contained only essential information needed on the main page for more concise reading by users.

</br>

> Lead: 박서영, Park seo young

</br>
</br>
</br>

---

### 3.1.5. Game Mode
![22](https://github.com/user-attachments/assets/e7d53109-8031-4525-beb4-70a0aeae500b)

#### Purpose
1.  Introduced Wild Rift's various game modes and provided information.

<br/>

#### Implementation Summary
1.  Divided into main game mode and adventure mode with corresponding videos and descriptions.
2.  When adventure mode is clicked, various mode icons appear on the left, and videos and descriptions change when icons are clicked.

</br>

> Lead: 엄지승, Eom Ji Seung

</br>
</br>
</br>


---

### 3.1.6. Character List
![23](https://github.com/user-attachments/assets/5b9f08f6-335d-47da-a6ec-e98db084cda0)

#### Purpose
1.  Introduced popular characters by lane and facilitated access to detailed information.

<br/>

#### Implementation Summary
1.  Left side       
   1.1. Contains character names and descriptions, with color changes on 'View Details' button hover and navigation to sub-pages on click.         
   1.2. Box shadows appear when hovering over skill button boxes.        
2.  Center       
   2.1. Characters are created to appear dynamically using AOS that emerges from the right side.        
3.  Right side      
   3.1. Features a swiper showing five popular characters by lane, with auto-play and navigation.         
4.  Bottom        
   4.1. Lane selection buttons change color on hover and display popular characters of the selected lane when clicked.        
   4.2. Character voices play when lane buttons are clicked.       

</br>

> Lead: 조효희, Jo hyo hee

</br>
</br>
</br>

---

### 3.1.7. Playlist
![24](https://github.com/user-attachments/assets/f190ff3a-d676-4e5d-aada-029135021622)

#### Purpose
1.  Provided functionality to directly listen to League of Legends music while adding visual enjoyment.

<br/>

#### Implementation Summary
1.  Title        
   1.1. Composed of different fonts to express the diverse genres of music and the unique character image of League of Legends game.      
2.  Central discs are created in slide format using swiper.      
3.  Disc hover       
   3.1. Scale and blur values change.       
   3.2. When hovering over non-active central discs, scale values increase and music title and artist name appear.      
4.  Music control       
   4.1. Play and pause buttons can be clicked to control music playback of the active disc.     
   4.2. When music plays, the central disc animation plays to create audio visualizer effects.             
   4.3. Music playback time changes to the corresponding position when clicking the music progress bar.         
6.  Disc movement          
   5.1. Navigation in `< >` shape allows movement to the next record disc.        
   5.2. Music playback automatically stops when moving discs.       
   5.3. Background changes when moving discs.      
7.  Other features        
   6.1. Clicking the left hamburger button brings up the disc list as a left side menu, allowing movement to the corresponding music disc when clicking music.       
   6.2. Currently playing music can be confirmed in the side menu.   
   6.3. The right link connection button performs the function of moving to official music videos, etc. (not implemented).     

<br/>

> Lead: 김채연, Kim chae yeon

<br/>
<br/>
<br/>

---

### 3.1.8. Patch Note
![25](https://github.com/user-attachments/assets/e1f6cfc4-53fa-434e-9b7f-f12e5fd24d28)


#### Purpose
1.  Effectively delivered Wild Rift patch note information.

<br/>

#### Implementation Summary
1.  Created with the latest update version, with title on the left and logo on the right for design.

</br>

> Lead: 조효희, Jo hyo hee

</br>
</br>
</br>

---

### 3.1.9. Riot Games
![26](https://github.com/user-attachments/assets/4927b500-79cb-45a2-81e3-2806fbc9cfda)


#### Purpose
1.  Introduced games related to Riot Games.

<br/>

#### Implementation Summary
1.  When hovering over game cards, the title box length extends and an explore button appears.

</br>

> Lead: 조효희, Jo hyo hee

</br>
</br>
</br>

---

### 3.1.10. Footer
![27](https://github.com/user-attachments/assets/1b221671-fedb-478f-a0b3-a86295abb5d3)

#### Purpose
1.  Provided website footer information and improved user convenience for moving to the top.

<br/>

#### Implementation Summary
1.  Footer         
   1.1. Generally maintained the existing footer structure, but excluded SNS items as they were deemed unnecessary.       
2.  Top button         
   2.1. The top button appears only after a certain scroll amount and smoothly moves to the top when clicked, providing visual convenience to users.       
   2.2. Also, when hovering over the top button, a shadow-like box appears below the arrow, allowing intuitive recognition of mouse usage.        

</br>

> Lead: 박서영, Park seo young

</br>
</br>
</br>

---

### 3.2. Sub Pages (7)

---

### 3.2.1. [Notice List](https://dkssud-dus.github.io/webRedesign-WildRift/pages/notice.html)
![28](https://github.com/user-attachments/assets/adaaf521-72c8-405e-b6c6-67e855e6920e)

#### Purpose
1.  Provided users with a unique notice exploration experience and clearly delivered core information.

<br/>

#### Implementation Summary
1.  Departed from conventional bulletin board and gallery-style notice formats, utilizing card flip format to provide users with a unique experience.
2.  The front of each card includes image, title, summary content, and date, allowing users to recognize core information from the front alone.
3.  The back of each card contains title, date, detailed content or images, with natural navigation to detail pages through 'View Details' buttons.
4.  Applied card-flipping animation on mouse hover to visually convey the need for user clicks.

</br>

> Lead: 박서영, Park seo young

</br>
</br>
</br>

---

### 3.2.2. Notice Detail ([Text](https://dkssud-dus.github.io/webRedesign-WildRift/pages/notice-sub-text.html) / [Video](https://dkssud-dus.github.io/webRedesign-WildRift/pages/notice-sub-video.html))
![29](https://github.com/user-attachments/assets/5a61d677-00b0-4fa5-8f08-b6e214fa000d)

#### Purpose
1.  Effectively delivered detailed notice content and improved user navigation convenience.

<br/>

#### Implementation Summary
1.  Placed breadcrumbs at the top to allow users to easily navigate to the notice page or main page.
2.  Prominently displayed representative images from the notice page at the top of the detail page for intuitive content recognition.
3.  Text-based detail pages were designed with clean layouts to focus on information delivery.
4.  Video-based detail pages included video content within the page, expanding from simple link connections to improve information delivery.
5.  Provided 'Previous' and 'Next' article functions for continuous content exploration, with different color values when there are no next articles to prevent click induction.

</br>

> Lead: 박서영, Park seo young

</br>
</br>
</br>

---

### 3.2.3. [Monster List](https://dkssud-dus.github.io/webRedesign-WildRift/pages/monster-list.html)
![30](https://github.com/user-attachments/assets/0599691c-ff9f-4a58-878e-5b09fe06feba)

#### Purpose
1.  Categorized monster information and enabled users to easily and quickly check information.

<br/>

#### Implementation Summary
1.  Used tab structure to divide monster categories.
2.  Placed brief category descriptions to understand the overall concept of monsters.
3.  Used swiper to make monster information easier and faster to recognize.         
   3.1. Slides include not only monster appearance but also names, descriptions, and appearance locations, allowing basic information to be checked immediately without accessing detail pages.        
   3.2. Content required for game understanding and play is tagged with 'TIP' to attract attention.         
   3.3. Clicking monster icons at the bottom moves to corresponding slides, with opacity adjustment to clearly show the hierarchy of information users are 'viewing', 'want to view', and 'not viewing'.        
4.  Three content items below the swiper are images that move to Wild Rift informational articles, not implemented.        

<br/>

> Lead: 김채연, Kim chae yeon

<br/>
<br/>
<br/>

---

### 3.2.4. [Monster Detail](https://dkssud-dus.github.io/webRedesign-WildRift/pages/monster-epic01.html)
![31](https://github.com/user-attachments/assets/1f053dbb-27cb-46b3-997c-2b5f87224cc6)

#### Purpose
1.  Visually emphasized detailed information of specific monsters while improving user convenience.

<br/>

#### Implementation Summary
1.  This is the page accessed when clicking the 'More' button on the monster list page.
2.  Emphasized visual elements with monster backgrounds, 3D modeling, and prominently placed monster names.
3.  Placed navigation to each information section directly below the name to improve user convenience.
4.  After brief monster descriptions and map appearance locations, detailed monster information becomes available, designed with reference to 'Teamfight Tactics', a League of Legends game series.
5.  Each information disappears at specific scroll values while visual elements continue to be emphasized.       
6.  When the information section ends, a swiper that can move to other monster pages in the same category is placed directly within the page.        
   2.1. Each slide features monster images, 3D modeling, names, and brief descriptions.        
   2.1. Scale values change when hovering over active slides.      

<br/>

> Lead: 김채연, Kim chae yeon

<br/>
<br/>
<br/>

---

### 3.2.5. [Character Detail](https://dkssud-dus.github.io/webRedesign-WildRift/pages/character.html)
![32](https://github.com/user-attachments/assets/90b14767-9ef5-4d84-9fc8-f08406198d7b)

#### Purpose
1.  Dynamically showed detailed information of the specific character 'Darius' and provided skill information.

<br/>

#### Implementation Summary
1.  Used character images as background with character names, features, and logos to further emphasize the main visual.
2.  Strived for dynamic implementation of character descriptions.              
   2.1. Left side uses AOS to make characters appear from the left.                  
   2.2. Right side consists of character description parts including character quotes, descriptions, and features. Skill images have hover animations that move upward.            
3.  In the character skills section, clicking skill images makes corresponding videos appear on the right with descriptions placed below.            
4.  At the bottom, Wild Rift characters are connected with animations and overlays to create a dark atmosphere.        

</br>

> Lead: 조효희, Jo hyo hee

</br>
</br>
</br>

---

### 3.2.6. [Skin](https://dkssud-dus.github.io/webRedesign-WildRift/pages/skinCharacterSelection.html)
![33](https://github.com/user-attachments/assets/7cd58f18-ba1d-451c-ae7e-cb869a0690dc)

#### Purpose
1.  Enabled convenient exploration of skin information owned by characters.

<br/>

#### Implementation Summary
1.  Placed categories and search fields at the top to improve user convenience.
2.  Character card images enlarge on hover to provide dynamic feeling.
3.  When selecting character cards, skins owned by the character can be viewed in swiper format.

</br>

> Lead: 엄지승, Eom Ji Seung

</br>
</br>
</br>


---
