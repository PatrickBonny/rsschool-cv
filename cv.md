# Anastasiia Davidenko

## Frontend Developer


![Portrait photo of Anastasiia Davidenko](assets/photo.jpg)

---


## Contacts

- **Email:** [vishka9989@gmail.com](mailto:vishka9989@gmail.com)
- **GitHub:** [github.com/ВАШ-НИК](https://github.com/PatrickBonny)
- **Location:** Dnipro, Ukraine 

---

## About Me

I am an open and positive person who enjoys trying new things and keeps moving forward.
I love understanding how everything works — which is exactly what brought me from applied mathematics to business analysis, and from business analysis to frontend development.

---

## Skills

**Technical**

- HTML5, CSS3, semantic markup
- JavaScript
- REST API — specification, integration, testing
- Git, GitHub
- Low Code automation (n8n, make, Zapier)
- Figma, Photoshop, Illustrator, 3ds Max

**Working with people**

- Requirements analysis
- Project management
- Technical writing
- Problem solving and critical thinking
- Fast learner

---

## Code Example

**Codewars — "Sum of Digits / Digital Root"**

Repeatedly sum the digits of a positive integer until a single digit is left.
For example, `942` → `9+4+2=15` → `1+5=6`.

```javascript
const digitalRoot = (n) => {
  while (n > 9) {
    n = String(n)
      .split('')
      .reduce((sum, digit) => sum + Number(digit), 0);
  }
  return n;
};

console.log(digitalRoot(16));     // 7
console.log(digitalRoot(942));    // 6
console.log(digitalRoot(132189)); // 6
```