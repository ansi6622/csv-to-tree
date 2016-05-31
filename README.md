# Employee CSV Tree Parser

Your job is to use the .csv file in the `data` directory to construct a tree of employee hierarchy.
The result should be a string, indented appropriately to show the hierarchy.

## Examples

Employee       | Manager
-------------- | ----------
Al Dente       |
Anne Teak      | Al Dente
Barb Dwyer     | Al Dente
Bill Ding      | Barb Dwyer
Chris Cross    | Barb Dwyer
Jay Walker     |
Joy Rider      |
Kenny Penny    | Joy Rider
Les Moore      | Kenny Penny
Lou Pole       | Joy Rider
M. Balmer      | Lou Pole
Sonny Day      | Lou Pole
Tim Burr       | Sonny Day


For the given set of data above, your final result should look like the following:


```
Al Dente
  Anne Teak
  Barb Dwyer
    Bill Ding
    Chris Cross
Jay Walker
Joy Rider
  Kenny Penny
    Les Moore
  Lou Pole
    M. Balmer
    Sonny Day
      Tim Burr
```
