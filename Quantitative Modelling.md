# Quantitative Modelling [back](https://tvoozmagnificent.github.io/NonTrivial/nontrivial.html)

> | Problem                 | Summary                                                                                                                                                                                                                                                                                          |
> |-------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
> | Internet Safety         | Internet safety is crucial in today's digital age, where the internet plays a significant role in daily life, from communication and education to entertainment and business.                                                                                                                    |
> | Artificial Intelligence | Artificial Intelligence (AI) has the potential to revolutionize many aspects of society, from healthcare and transportation to education and entertainment. However, its development and deployment come with several significant challenges and issues.                                         |
> | Farm Animals            | Farm animals play a critical role in agriculture and human society by providing food, fiber, labor, and other products. The care, management, and welfare of farm animals are essential to sustainable farming practices and have significant ethical, environmental, and economic implications. |

```cpp
// Let's use the ITN framework on Raising Artificial Intelligence Awareness

// Scale

//let us focus on positive impacts only:
positivelyaffectedbeings = 5200000000 to 5300000000 // This means that you're 90% confident the value is between those two quantities a and b.
//If the problem involves non-existing-human beings, how much do you weight their welfare 
beingdiscount = 1 //this is a value where 1 is human and 0.1 is a tenth of a human and 10 is ten times, etc

//Consider the average being affected, how many Quality-adjusted life years would fully solving this problem (do not discount these) give this being?
//One QALY equates to one year in perfect health. 
avQALY = 0.1 to 1

//all again for negatively-affected beings...
negativelyaffectedbeings2 = 100000 to 1000000 // This means that you're 90% confident the value is between those two quantities a and b.
beingdiscount2 = 1 //this is a value where 1 is human and 0.1 is a tenth of a human and 10 is ten times, etc
avQALY2 = 0.0001 to 0.001

scale = positivelyaffectedbeings * beingdiscount * avQALY - negativelyaffectedbeings2 * beingdiscount2 * avQALY2
// ––––––––––––––––––––––––––––––––

// Tractability
//If we doubled the amount of resources allocated to the problem, what percentage of the problem would be solved? 
progressIfResourcesDouble = 10 to 15 //insert range here

tractability = progressIfResourcesDouble * 0.01
// ––––––––––––––––––––––––––––––––

// Neglectedness

//How much total funding (in dollars) is currently being dedicated to solving the problem?
funding = 1000000 to 10000000
neglectedness = 1/funding

scale * tractability * neglectedness
```


