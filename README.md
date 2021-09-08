# assignment2-pidaparathy
Second lab assignment
Naruto
# Hemanth Kumar Reddy Pidaparathy
###### Kerala

**Kerala** is referred to as "**God's Own Country**." one of my favorite dishes has been the **Putta (coconut rice)** with squashed bananas, which is a popular breakfast option. A **banana leaf** is used to serve a **traditional Kerala meal**. The scenery is stunning, and the environment is spotless! Traveling through Kerala is like walking into a tropical paradise for me because **I love nature**. I highly recommend a trip to **Munnar's** tea plantations. This region's rolling hills will make you never want to leave Kerala – **everything is green**!

***

### Navigation route from Maryville to Kerala

1. Drive through a car from Maryville to Kansas City.
2. Board a connecting flight from Kansas city to Chicago. 
3. Followed by Chicago to London Heathrow.
    1. AFter reaching Heathrow, if connecting flight is delayed then wait for the flight.
    2. After reaching Heathrow, if connecting flight is missed then book a new flight.
4. Accomplished by the flight London Heathrow to Kerala.
5. Reached the destination

- Indian Currency
    - Credit Card
    - Debit Card
    - Mobile applications for direct transfer of Money
- Local friend or Guide
- DSLR for memories
- Traditional wear
- Knowledge about local language, sceneries and temples
- Famous and authentic restaurants

![Image](Naruto.jpg)


[Click this link to navigate to my AboutMe file](https://github.com/Hemanthkumarreddy/assignment2-pidaparathy/blob/e45f31b7ea67a9c83aa47bcbc7358ad5c9437871/AboutMe.md)

***

### Markdown Tables 

Tables are used to represent the food items and drinks with their prices and localities that I would recommend someone to drink

#### | Food items | Locality (area) | Price |  
| :---: | :---: | :---: |  
| Puttu (Rice steamed Cake) | Sailu's Food | $3 |  
| Parotta and beef | Dharmettan's Beef Curry And Porotta Restaurant | $7 |  
| Coconut Juice | Thiruvendram | $2 |  
|  Gauva Juice | Cochin | $5 | 

***

# My personal quotes 

> Always remember that you are absolutely unique. Just like everyone else. -*Margaret Mead*

> Dream big and dare to fail. -*Norman Vaughan*

> Life is 10% what happens to me and 90% of how I react to it. -*Charles Swindoll*

***

###  Code Fencing

> A data structure is a particular way of organizing data in a computer so that it can be used effectively. For example, we can store a list of items having the same data-type using the array data structure.

[Click this link to get the quoted words about code fencing](https://www.geeksforgeeks.org/data-structures/)

[Click this link to view Data Structures Code](https://cp-algorithms.com/data_structures/segment_tree.html)

  int sum(int v, int tl, int tr, int l, int r) {  
    if (l > r)   
        return 0;  
    if (l == tl && r == tr) {  
        return t[v];  
    }  
    int tm = (tl + tr) / 2;  
    return sum(v*2, tl, tm, l, min(r, tm))  
           + sum(v*2+1, tm+1, tr, max(l, tm+1), r);  
}  