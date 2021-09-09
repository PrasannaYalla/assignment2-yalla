# assignment2-yalla
# prasanna yalla
###### vizag

Visakhapatnam is considered the 3rd biggest city situated on the east coast of India. This city is also the main hub for various activities related to finance. Various offices of the public sector, as well as a defence, are present in this city that makes this city well-known throughout India. Its population already went past 2,000,000 within ten years, which justifies its name, i.e., **“City of Destiny.”**

---

### Route map

1. Go to MCI airport, Kansas city
2. Bored into flight to RGIA airport, India    
3. catch another flight to vizag airport
    1. Catch a Ola cab
    2. Go to vizag beach to enjoy there
* Sunscreen
* Camera 
* Clothes 


[AboutMeLink](AbouMe.md)

---

### Recommended food

Below table shows the food items and their locations and price of them.

|    Food Items   |     Location     |   Amount    |
|   -----------   |    ----------    |  --------   |
|Chicken Biryani  |   Hyderabad      |    250      |
|Keema Pulav      |   vizag          |    200      |
|Mutton Biryani   |   New Delhi      |    600      |
|Kaju Barfi       |   Bengalore      |    550      |

---

### quotes

Live as if you were to die tomorrow,Learn as if you were to live forever.-
*Gandhi*   
All our dreams can come true, if we have the courage to pursue them-*swamy vivekananda*   

---

## code fencing

### Algebra

> Algebra is a branch of mathematics dealing with symbols and the rules for manipulating those symbols. In elementary algebra, those symbols (today written as Latin and Greek letters) represent quantities without fixed values, known as variables. Just as sentences describe relationships between specific words, in algebra, equations describe relationships between variables

> (https://www.livescience.com/50258-algebra.html)

---

pair<int, int> fib (int n) {
    if (n == 0)
        return {0, 1};

    auto p = fib(n >> 1);
    int c = p.first * (2 * p.second - p.first);
    int d = p.first * p.first + p.second * p.second;
    if (n & 1)
        return {d, c + d};
    else
        return {c, d};
}

---
Link : (<https://cp-algorithms.com/algebra/fibonacci-numbers.html>)
