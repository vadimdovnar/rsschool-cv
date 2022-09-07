# **Vadim Dovnar**
## **Contacts**

* **Phone:** +375 (44) 733-98-03
* **Skype:** live:vadimdvv154
* **Discord:** Vadim Dovnar#4303
* **Telegram:** @vadimdovnar
* **Twitter:** @dovnar_vadim
* **Email:** vadim.dovnar.93@gmail.ru
* **LinkedIn:** https://www.linkedin.com/in/vadimdovnar
* **facebook:** https://www.facebook.com/profile.php?id=100015330672443

## **About myself**

Organized and communicative person. Studied Frontend and Salesforce development independently.  Cooperate with people easily. Approachable, optimistic, reliable, good social skills. Interested in psychology, education, sports. I really like traveling, because it is a good opportunity to know another culture, meet with new people and, of course, see new places. I like to spend time with my family and friends. Attracted by winter sports activities: skiing, snowboarding, skating. Prefer outdoor activities.

## **Code example**

```
function convertToBinary (number) {
    let num = number;
    let binary = (num % 2).toString();
    for (; num > 1; ) {
        num = parseInt(num / 2);
        binary =  (num % 2) + (binary);
    }
    return binary;
}

function sortByBit(arr) {
    
    let newArr = arr.sort(function (a, b) {
        let result = (convertToBinary(a).split('1').length - 1) - 
                     (convertToBinary(b).split('1').length - 1)

        if(result === 0) result = a - b;

        return result;
    })
    return newArr
}
```
