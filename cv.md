# Jakhongir Ismoilov

##### Junior Frontend Developer

---

##### Contact Information:

- **Phone:** +998 99 817 31 32
- **E-mail:** jahongir780110@gmail.com
- **Telegram:** https://t.me/jakhongir_0305
- **Linkedin:** https://www.linkedin.com/in/jakhongir-ismoilov-9039a5203/
- **GitHub:** https://github.com/Jahongir780110

##### Briefly About Myself:

Junior Frontend Developer with 1+ year of working experience in Frontend Development. Skilled mostly in JavaScript and Vue. Energetic and eager to learn new skills. Clean coding is my priority.

##### Skills and Proficiency:

- HTML
- CSS(Framework Bootstrap, Preprocessor SCSS, Methodology BEM)
- JavaScript(OOP, ES6, DOM)
- Vue.js(Vue Router, Vuex, Vuetify, Framework Nuxt)
- Version Control: Git(Remote Servie GitHUB)
- Figma(for Web Development)
- Node.js basics(Framework Express.js)
- MongoDB basics(ODM Mongoose)

##### Code Example:

**Can Place Flowers Leetcode:** You have a long flowerbed in which some of the plots are planted, and some are not. However, flowers cannot be planted in adjacent plots. Given an integer array flowerbed containing 0's and 1's, where 0 means empty and 1 means not empty, and an integer n, return if n new flowers can be planted in the flowerbed without violating the no-adjacent-flowers rule.

    const canPlaceFlowers = (flowerbed, n) => {
      flowerbed.push(0);
      flowerbed.unshift(0);
      for (let i = 1; i < flowerbed.length - 1 && n !== 0; i++) {
        if (
          flowerbed[i] === 0 &&
          flowerbed[i - 1] === 0 &&
          flowerbed[i + 1] === 0
        ) {
          flowerbed[i] = 1;
          n--;
        }
      }
      return n === 0;
    };

##### Experience:

- ProDVD Company in Tashkent(since 09.02.2021)

##### Education:

- Bachelor, Tashkent University of Information Technologies (_2019 - current_):
  - Software Engineering.
