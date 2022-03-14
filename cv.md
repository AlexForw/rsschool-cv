# Alexey Mityushkin
# My Contact:

* **Phone:** +7 991 626-88-48
* **E-mail:** [My Mail](lmityushkin@mail.ru)
* **GitHub:** [AlexForw](https://github.com/AlexForw)
* **Discord:** [AlexForw](https://t.me/sasukevernisvderevny)

# About Me
I am 19 years old. Interesting tasks it's my weakness, a lot of time I spend on Eng YouTube for improving my english skills and finding useful information about programming. Also I spend my time into learning mathematics I believe that math can help us in more aspects. 

* **My Soft Skills:**
    * Communicative
    * Quick learner
    * Ready to help other people
    * Team playing
    * Hard-working

# Skills
* HTML/CSS
* JavaScript 
* Git/GitHub
* Avocode, Zeplin, Figma

# Code Examples
It is last function which I was written(function from Tic Tac Toe game)
```
function checkWinCross(){

    return winCombination.some(comb => {
        let combination = comb.every(i =>cellElem[i].classList.contains('crossCell'))
        if(combination){
            comb.forEach((item)=>{
                cellElem[item].classList.add('winCombinationStyle')
            })
            
            cellElem.forEach(item =>{
                item.classList.remove('hover')
                item.removeEventListener('click', clicker)
            })
        }
        return combination
    })
}
```
# Education
* **RS School**
* **The Odin project**

# Languages
* **Russian** - native speaker.
* **English** - B1 (B2 in process...)
