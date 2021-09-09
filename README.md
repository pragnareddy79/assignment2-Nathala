# assignment2-Nathala
# Pragna Reddy Nathala
###### My favourite place is ooty.
The ooty is the **coolest place** and it has many tea factories and coffee factories and it has the highest peakmpoint known as **Doddabetta**

***

# Directions for my favourite place
1. Firstly, my favourite is in india so we book a flight and reach the place Hyderabad.
2. From hyderbad we going reach banglore and then from the next stop place would be mysore.

    1.In mysore we can also visit various places like mysore place.

    2.Brindavan Gardens.

    3.Chamundeshwari Temple.

3. The distance from mysore to ooty would be around 125km.
                
     1.Avalanche Lake

     2.Ooty Lake

     3.Doddabetta peak
* The main we need to carry the music system.
* Play cards.
* Snacks.

[click here to view my aboutme page](https://github.com/pragnareddy79/assignment2-Nathala/blob/main/AboutMe.md)

****

# Below are the Food/Drinks that I recommend
In the below table I am going to describe about two food items and two drink items.
| Item Name  | Location | Amount |
| --- | --- | ---: |
| Haleem | Hyderabad House | 10 |
| Birayani | Ruchi | 12 |
| oreo milkshake | Mc Donald's| 4 |
| Mango Lassi | Bawarchi | 3 |

****

# Quotes that I like 
> The purpose of our lifes is to be happy *Seneca*

> Not how long but how well you have lived is the main thing *Dalai Lama*

****

# Code Fencing
```
vector<vector<int>> adj;  // adjacency list representation
int n; // number of nodes
int s; // source vertex

queue<int> q;
vector<bool> used(n);
vector<int> d(n), p(n);

q.push(s);
used[s] = true;
p[s] = -1;
while (!q.empty()) {
    int v = q.front();
    q.pop();
    for (int u : adj[v]) {
        if (!used[u]) {
            used[u] = true;
            q.push(u);
            d[u] = d[v] + 1;
            p[u] = v;
        }
    }
}
```
Here is the link for my quick-link for the code source<https://cp-algorithms.com/graph/breadth-first-search.html>