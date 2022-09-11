# Bilokrynytsyi Stefan-Mykhailo Vasyliovych
---
## Contact information:  
**Phone:** +380969164618  
**Email:** stb3002@gmail.com  
**Telegram:**@stefikuuuuus  
---
## About Myself
I am 18 years old, i am beginner programmer. My strengths are: hardworking, creative, I just want to work hard to improve my skills in programing.
## Skills: 
- Basic knowledge of C++  
- Basic knowledge of JS
- Git  
## Code Example  
```js
function queueTime(customers, n) {
  if(customers.length == 0) return 0;
  if (customers.length <= n) {
    let max = 0;
    for (let i = 0; i < customers.length; i++) {
      if (max < customers[i]) max = customers[i];
    }
    return max;
  }
  const arr = customers.splice(0, n);

  for (let i = 0; i < customers.length; i++) {
    let min = arr[0];
    let ind = 0;
    for (let j = 0; j < arr.length; j++) {
      if (min > arr[j]) {
        min = arr[j];
        ind = j;
      }
    }
    arr[ind] += customers[i];
  }
  let max = 0;
    for (let i = 0; i < arr.length; i++) {
      if (max < arr[i]) max = arr[i];
    }
    return max;
}
```
## Experience 
My first JS project(coursework): [Class-Cache](https://github.com/Stefan-Bilokrynytskyi/Class-Cache)  
## Education 
I am a second-year student of **National Technical University of Ukraine “Igor Sikorsky Kyiv Polytechnic Institute”**.  
Specialty: software development.  
## English
Intermediate(B1)
