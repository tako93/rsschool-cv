## Tako Gegechkori

- - - - 

**Tel:** +995 571 777 062

**Email:** takog1993@gmail.com

**Summary:**

for me writing code is challenging interesting and pleasant. Nothing compares to the feeling of achievement when you overcome difficulties or see the product of your thinking. Getting that feeling is my main motivation. Having the aim, willpower and never giving up is what only strong people have. Be developer = be strong, stubborn and thinker. 

**Skills:**

* HTML, CSS,  
* Angular, (basic)
* Javascript, Typescript (basic)
* Git
* Firebase,
* Figma,

**Code example:**

```
 function debounce (func, wait, immediate) {
  var timeout
  return function () {
    var context = this, args = arguments
    var later = function () {
      timeout = null
      if (!immediate) func.apply(context, args)
    }
    var callNow = immediate && !timeout
    clearTimeout(timeout)
    timeout = setTimeout(later, wait)
    if (callNow) func.apply(context, args)
  }
}

const searchFn = () => {
  countriesList.innerHTML = null

  window.fetchCountries.fetchData(`https://restcountries.eu/rest/v2/name/${search.value}?fullText=true`)

  renderCountriesList(countries)
  console.log(search.value)
}
var myEfficientFn = debounce(searchFn, 250)

search.addEventListener('keyup', myEfficientFn)
```

**Experience:** 

https://elegant-albattani-12bc96.netlify.app

https://upbeat-lalande-f8d15f.netlify.app

https://hungry-raman-bf8902.netlify.app


**education:**

Ilia state university (Social Sciences – Clinical Psychology) 2015–2017 

Women’s Coding School 10/2020 – 5/2021
