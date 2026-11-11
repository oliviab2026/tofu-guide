**The Plan**  
I will change the header image on https\://oliviab2026.github.io/tofu-guide/tofu-in-air-fryer.html. Version A (current) will show this illustration, followed by the recipe:
![tofu illustration](air-fryer-tofu-illustration.png)
What You Need

* 1 block (14 to 16 oz) extra-firm or firm tofu  
* 1 tablespoon soy sauce or tamari  
* 1 tablespoon neutral oil, such as avocado or canola  
* 1 tablespoon cornstarch   
* 1/2 teaspoon garlic powder  
* 1/2 teaspoon smoked paprika   
* Black pepper to taste

Step by Step

1. **Press the tofu.** Wrap the block in a clean kitchen towel, set a heavy pan on top, and press for 20 to 30 minutes. Less water means a crispier result.  
2. **Cut it.** Slice into 3/4-inch cubes. Smaller pieces get crunchier, while larger ones stay softer inside.    
3. **Season.** Toss the cubes gently with the soy sauce and oil. Let them sit for 5 minutes.   
4. **Coat.** Sprinkle on the cornstarch, garlic powder, paprika, and pepper. Toss until each cube has a light, even dusting.  
5. **Preheat.** Heat the air fryer to 400°F (200°C) for 3 minutes if your model has a preheat setting.  
6. **Cook.** Arrange the cubes in a single layer with space between them. Cook for 12 to 15 minutes, shaking the basket or flipping the pieces at the halfway point.  
7. **Check.** The tofu is done when the edges are deep golden and the cubes feel firm and crisp when tapped. Add 2 to 3 minutes if needed.

Version B will show this photograph, followed by the recipe:   
![tofu photograph][air-fryer-tofu-photograph.jpg]  
What You Need

* 1 block (14 to 16 oz) extra-firm or firm tofu  
* 1 tablespoon soy sauce or tamari  
* 1 tablespoon neutral oil, such as avocado or canola  
* 1 tablespoon cornstarch   
* 1/2 teaspoon garlic powder  
* 1/2 teaspoon smoked paprika   
* Black pepper to taste

Step by Step

8. **Press the tofu.** Wrap the block in a clean kitchen towel, set a heavy pan on top, and press for 20 to 30 minutes. Less water means a crispier result.  
9. **Cut it.** Slice into 3/4-inch cubes. Smaller pieces get crunchier, while larger ones stay softer inside.    
10. **Season.** Toss the cubes gently with the soy sauce and oil. Let them sit for 5 minutes.   
11. **Coat.** Sprinkle on the cornstarch, garlic powder, paprika, and pepper. Toss until each cube has a light, even dusting.  
12. **Preheat.** Heat the air fryer to 400°F (200°C) for 3 minutes if your model has a preheat setting.  
13. **Cook.** Arrange the cubes in a single layer with space between them. Cook for 12 to 15 minutes, shaking the basket or flipping the pieces at the halfway point.  
14. **Check.** The tofu is done when the edges are deep golden and the cubes feel firm and crisp when tapped. Add 2 to 3 minutes if needed.

(Photograph source: [https\://jessicainthekitchen.com/how-to-make-crispy-air-fryer-tofu/](https://jessicainthekitchen.com/how-to-make-crispy-air-fryer-tofu/))

My hypothesis is that version B’s yes rate will be at least 10 percentage points higher than version A’s yes rate because the photograph is genuine, making the tofu look more appetizing, and visitors can more easily envision themselves cooking and eating the food.

I will use Claude Sonnet 5.5 with the memory off and start a fresh chat for each trial. The exact prompt (including the persona) will read, “You are a busy young-professional in Chicago looking for a quick, easy, and tasty dinner to make using tofu and an air fryer. Read this recipe and look at the image, then decide whether you would make it. Answer yes or no, then give one sentence of reasoning.” \+ \[recipe text\] \+ \[version A illustration or version B photograph attached\]. I will randomly assign each trial to version A or B using the \=IF(RANDBETWEEN(0,1)=0, “A”,“B”) equation and continue until each version has at least 50 trials.

My primary outcome will be the yes rate in each version, measured as \[(yes answers in version B trials / \# of trials in version B) \- (yes answers in version A / \# of trials in version A)\].

I will reach a sample size of at least 50 per version (100 total) by November 20, 2026\. 

I will compare the proportion of “yes” answers in version B versus version A, measured as the difference in proportions (B-A). I will test it with a two-sided two-proportion z-test at a=0.05 significance level, and I will report the observed difference, p-value, and a 95% confidence interval for the difference. I will run this test once, after all trials are complete, with no peeking. Support for my hypothesis would be version B’s yes rate is higher than version A’s and p\<0.05.
