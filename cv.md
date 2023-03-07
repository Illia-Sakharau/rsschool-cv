
# Sakharau Illia
<img src="https://raw.githubusercontent.com/Illia-Sakharau/rsschool-cv/gh-pages/src/avatar.png"  width="110" style="float:left; z-index:9999; margin-right: 20px">

## UX/UI Designer


I am a UX/UI designer with 2 years of commercial experience who wants to understand the front-end better in order to improve my work. 
And perhaps in the future I will completely relearn to be a front-end developer.

I expect that this course will expand my  JS/Front-end knowledge 
ㅤㅤ
ㅤㅤ
ㅤㅤ

---

## Contacts

##### Email
[sakharovia0204@gmail.com](sakharovia0204@gmail.com "Email")
##### Telegram
[@IliyaSakharov](https://t.me/IliyaSakharov "Telegram")
##### LinkedIn
[linkedin.com/in/sakharoviliya0204/](https://www.linkedin.com/in/sakharoviliya0204/ "LinkedIn")
##### GitHub
[Illia-Sakharau](https://github.com/Illia-Sakharau "GitHub")
##### Discord (RSSchool)
Illia Sakharau (@Illia-Sakharau)

---

## Skills

* HTML
* CSS/SASS
* JavaScript (Basic)
* Git (Basic)

---

## Languages

* **Russian** (Native)
* **English** (A2+)

---

## Experience

##### 2021 - 2023   |   GoDigital Media Group (Terrascale)
**UI/UX Designer**
* YogaWorks (Key designer of the project)
    * UX researching;
    * Merging websites with restructuring and redesign;
    * Developing and supporting of the design system;
    * Designing of streaming platform for online yoga classes based on daily.co API;
    * Usability testing and hypothesis testing through Maze.co;
    * Supervising a supportive junior designer;
    * Reviewing front-end developer's work as designer.
* SoundRoyalties customer portal
    * Developing UI-Kit based on soundroyalties.com brand guidelines and visual style;
    * Designed the first MVP of the advance payment managing system.
* Financial and analytical microservices of The Kraken internal portal of GDMD
    * Designing of interfaces related to the display (tables), processing and visualization (charts) of multilevel datasets.
* Media Library for The Kraken and Cinq Music WebApp
    * Participated in the redesign of the service as a supportive designer.

##### 2020 - 2021   |   Freelance
**UI/UX Designer**
* Zapchasti (pet-project)
    * Full design developing (more in Portfolio).

##### 2021 - 2023   |   Belarusian Railway
**Engineer**
* Working with technical documentation;
* Inspection and control of repair work of locomotives;
* Working with the SAP system;
* Automation of processes based on the SAP system.


---

## Education

##### 2020 - 2021    |   UpSkill Lab (EPAM)
**UI/UX Design**

##### 2011 - 2016    |   BELARUSIAN STATE UNIVERSITY OF TRANSPORT
**Bachelor of Science in Engineering**

---

## Projects

* CV - [Link to GitHub](https://github.com/Illia-Sakharau/rsschool-cv/blob/38e2c4f5882ec0d1ef5fd971705809adebf7d425/cv.md "GitHub - CV - Illia Sakharau")
* Animate SVG Loader - Link to CodePen: [CSS](https://codepen.io/Sakharau/pen/jOxwgXR "Animate SVG by CSS") | [SMIL](https://codepen.io/Sakharau/pen/yLjbKER "Animate SVG by SMIL")


---

## Code Example

#### Human readable duration format

```
function formatDuration (seconds) {
  if (seconds == 0){
    return "now";
  }
  
  let text = [];
  let year = Math.floor(seconds/31536000);
  let day = Math.floor((seconds%31536000)/86400);
  let hour = Math.floor((seconds%86400)/3600);
  let min = Math.floor((seconds%3600)/60);
  let sec = Math.floor(seconds%60);
    
  // год - года  
  if (year > 0){
    if (year == 1) {
      year = "1 year";
    } else {
      year = year + " years";
    }
  } else {
    year = "";
  }
  
  // день - дни
  if (day > 0){
    if (day == 1) {
      day = "1 day";
    } else {
      day = day + " days";
    }
  } else {
    day = "";
  }
  
  // час - часы
  if (hour > 0){
    if (hour == 1) {
      hour = "1 hour";
    } else {
      hour = hour + " hours";
    }
  } else {
    hour = "";
  }
    
  // минута - минуты 
  if (min > 0){
    if (min == 1) {
      min = "1 minute";
    } else {
      min = min + " minutes";
    }
  } else {
    min = "";
  }
  
// секунда - секунды 
  if (sec > 0){
    if (sec == 1) {
      sec = "1 second";
    } else {
      sec = sec + " seconds";
    }
  } else {
    sec = "";
  }
  
  //отфильтровывка пустых и объединение
  text = [year, day, hour, min, sec].filter(x => x !== "").join(', ')
  
  //замена последней запятой на and
  if (text.lastIndexOf(",") > 0) {
      text = text.substring(0, text.lastIndexOf(",")) + " and" + text.substring(text.lastIndexOf(",") + 1);
  }
  
  return text;
}
``` 