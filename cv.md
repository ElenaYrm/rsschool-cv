# Elena Yaroma
### Frontend Developer

## Contact information:

* **Phone:** +995 595 10 67 51
* **E-mail:** yaroma.elena@gmail.com
* **Telegram:** @Elena_Yaroma
* **LinkedIn:** [Elena Yaroma](https://www.linkedin.com/in/elena-yaroma-716a30a2/)
* **GitHub:** [ElenaYrm](https://github.com/ElenaYrm?tab=repositories)

## About me:

I have experience in analytics and production planning, which has taught me to be adaptable, multitasking and stress tolerant.
First of all, I try to understand task and how certain things work and thanks to that I am a fast learner.
I am ready for hard work and study for my further growth as a Frontend developer.

## Key skills:

* HTML
* CSS/Sass
* JavaScript
* TypeScript
* React
* Redux/Redux Toolkit
* Jest
* Git
* Webpack

## Code example:
I tried to write the Flat method for array by myself:

* _example with a loop:_
  ```
  function flatArr(array) {
    let result = [];
    for (let i = 0; i < array.length; i++) {
      if (Array.isArray(array[i])) {
        result = [...result, ...flatArr(array[i])];
      } else {
        result = [...result, array[i]];
      }
    }
    return result;
  }
  ```

* _example with the array method:_
  ```
  function flatArr(array) {
    return array.reduce((acc, item) => Array.isArray(item) ? [...acc, ...flatArr(item)] : [...acc, item] , []);
  }
  ```
  
## Projects:

You can see the project that I am working now:
* [CookBook](https://recipes.elenportfolio.net/)
* [Repository](https://github.com/ElenaYrm/recipes-react)

The main idea is to work with Redux Toolkit, React Router, Jest, types of optimization and color switcher.
_Now I am still working on tests and optimization._

## Education and courses:

* **Self-study** _(2022-2023)_
  * JavaScript, TypeScript, React

* **Skillbox** _(2022, final project in progress)_
  * HTML, CSS, JavaScript, React

* **Belarusian State University** _(2012-2016)_
  * Business Administration

## Experience:

* **Alivaria** _(2016-2022)_
  * Production planning manager _(the last position)_

## Languages:

1. **English** - Intermediate
2. **Russian** - Native
