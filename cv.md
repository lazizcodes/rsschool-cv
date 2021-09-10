# Laziz Abdullaev

# Contact

- Phone: +998 90 979 29 77
- E-mail: lazizabdullaev02@gmail.com
- GitHub: [lazizcodes](https://github.com/lazizcodes)
- Telegram: [@laziz_akajon](https://t.me/laziz_akajon)

# About Me

After starting my bachelor's degree at the National University of Uzbekistan, I have been a prize-winner at many international olympiads such as NCUMC, Open Mathematical Olympiad for Univeristy Students, IMC to name but a few. Also, I am currently ranked in Top 0.1% of Mathematics Stack Exchange ([account](https://math.stackexchange.com/users/752069/vivid)). Currently, I am intending to become a software engineer majoring in back-end but with front-end minor too.

- My Strength
  - Quick learning (international mathematical contests medalist in just two years starting with fundamental knowledge)
  - Problem-solving
  - Research potential

# Skills

- **JavaScript**
  - Completed a full course on JavaScript. Currently, learning NodeJS
    (+ExpressJS) for backend development
- **Python**
  - Mainly algorithms and data structures with Python. Have been solving
    interview problems on leetcode.com for over a year.
- **C++**
  - Took a "C++ fundamentals" course at high school and university (one
    semester)

# Awards

- **Bronze Medal** - _International Mathematics Competition 2021_ (2021)
- **Gold Medal** - _4th Open Mathematical Olympiad for University Students_ (2021)
- **Silver Medal** - _3th Open Mathematical Olympiad for University Students_ (2020)
- **Gold Honour Diploma** - _International Youth Math Challenge_ (2019)

# Code Example

```
function canConstruct(s, k) {
    if (k >s.length) {
        return false;
    }
    if (s.length === k) {
        return true;
    }

    const map = {};
    const a = 97
    for (let i=0; i<=25; i++) {
        map[String.fromCharCode(a + i)] = 0;
    }
    for (let i=0; i<s.length; i++) {
        map[s[i]]++;
    }

    return Object.values(map).filter(x => x%2).length <= k

}
```

# Education

- National University of Uzbekistan
  - Bechelor, Mathematics
- Al-Xorazmiy Specialized IT School
  - High School, Exact Sciences and IT

# Languages

- **Uzbek** - native
- **English** - proficient (IELTS 7.0)
- **Russion** - intermediate
