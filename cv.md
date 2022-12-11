# Vitali Kupratsevich
### I'm a Frontend developer
*********
### Contact information
* +375 (33) 325-96-92
* vkuper7@gmail.com 
* [Telegram ](https://t.me/v_kuper)
* [GitHab](https://github.com/vkuper77)
* [LinkedIn](https://www.linkedin.com/in/vitali-kupratsevich-9103b01b8/)
* [Instagram](https://www.instagram.com/vitali_kupratsevich/)
*********
### About Me
My name is Vitaly, I am 27 years old.
I have been working as a mobile developer for 2 years.
But at the same time, I believe that one cannot stop at what has been achieved and one must always develop. That's why I'm here.
*********
### Work experience
#### __Company name:__ [MSA-IT](https://msa-it.ru/)
#### __My position:__ React Native Developer
#### __Work experience:__ _March 2021 - present_
*********
### Skills
- **CSS, SCSS, SASS**
- **Java Script**
- **Type Script**
- **React | React Native | Expo | React Navigation | Reanimated 2 | React Native Gesture Handler**
- **Redux**
- **Git**
- **Firebase | Exponea | AppMetrica**
- **Figma**
*********
### Code Examples
```
function meshRendering (data = []){
  let result = []
  let childArr = []

  for (let i = 0; i <= data.length; i++) {
    if (childArr.length === 3) {
      result.push(childArr)
      childArr = []
    } else if (i === data.length) {
      result.push(childArr)
      childArr = []
      break
    }
    childArr.push(data[i])
  }

  return result.filter((it) => it.length)
}
```