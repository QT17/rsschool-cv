![](https://miro.medium.com/max/700/0*ixMavTK_WGBM0OPJ.png)

#Vasiliy Romanenko #

### Software Developer

---

#### PROFILE

I am a software developer with robust problem-solving skills and proven experience in creating and designing software in a test-driven environment.Software Engineer

---

#### CAREER SUMMARY

Mathica Labs May 2020 to present

- Designs and creates software solutions to solve pain points for various clients
- Checks feasibility of software prototypes
- Modifies code to fix errors

---

#### SKILLS

##### Coding Languages

C#, ASP.NET JavaScript, HTML/CSS, Python

##### Frameworks/Systems

MVC, AngularJS, bootstrap, Visual Studio, Team Foundation Server

---

#### Code example:

Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.

```function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```

---

#### HOW TO REACH ME

Home: 123-456-7890
Cell: 123-456-7890
Email: hello@reallygreatsite.com
Address: 123 Anywhere Street, Any City, State
LinkedIn: @reallygreatsite
