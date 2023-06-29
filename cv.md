# Alexey Shakinko

***

## Contact info:
 [**e-mail: *alexejshakinko@gmail.com***](e-mail:alexejshakinko@gmail.com)

[**tel: *+375 (25) 000 00 00***](tel:+375291112233)

***

## About me:

Engineer of heating, ventilation and air conditioning systems. Want to learn JS and become a FE developer. 

***

## My skills:
* **NodeJS** *basic*
* **HTML**   *basic*
* **CSS**    *basic*
* **JS**     *basic* 
* **Git**    *basic*

***

##  Code exapmle:
 1. **Caesar's cipher encrypting code**

 ```function encrypt(text, key) {
    if(typeof text !== 'string' || typeof key !== 'number') {
        throwError('Wrong encryption parametors!', 1);
    }

    return text.split('').map(letter => {
        if(letter.charCodeAt() >= upperCaseStartCode && letter.charCodeAt() <= upperCaseEndCode) {
            return String.fromCharCode(upperCaseStartCode + (letter.charCodeAt() - upperCaseStartCode + key) % alphLength);
        }
        else if(letter.charCodeAt() >= lowerCaseStartCode && letter.charCodeAt() <= lowerCaseEndCode) {
            return String.fromCharCode(lowerCaseStartCode + (letter.charCodeAt() - lowerCaseStartCode + key) % alphLength);  
        }

        return letter;
    }).join('');
 } 

 ```

***

##  Education: 
 1. **BNTU**: 
    * Faculty of Energy Construction


***

## Languages: 
* *English* **(upper intermediate)** 
* *Russian* **(native)**
* *German* **(intermediate)**