# Global Food Production:
## Sustainability Capstone

<img src='Images\global_food_production_conceptual_image.jpg' width = '65%' />

[Medium Blog Post](https://medium.com/@kailastone/data-science-presentations-storytelling-through-slide-shows-34b42b64104)

[Presentation PDF](C:\Users\kekay\flatiron\Capstone\Capstone\Capstone Presentation.pdf)

[Video Walkthrough](https://youtu.be/3ldZygPHzbQ)

## Purpose
As a professional chef coming into Data Science; my main goal for my career is to fuse my two passions in order to aid in tackling food accessbility and sustainability. My first step towards that journey continues with my Capstone project: researching the issue and developing an intimate understanding of the environment surrounding food sustainability. I've downloaded data that includes information global food production and dispersion. 

My goal with the project is to craft and hone into my own personal work flow; while also starting to get into the mind set that will allow me to succeed in moving on towards tackling deeper issues in this broad category of food sustainability. 

The original data sets can be found on Kaggle:
- [Global Food & Agriculture Statistics](https://www.kaggle.com/unitednations/global-food-agriculture-statistics)

- [World Food & Feed Production](https://www.kaggle.com/dorbicycle/world-foodfeed-production)

- [Environmental Impact of Food Production](https://www.kaggle.com/selfvivek/environment-impact-of-food-production)
<!------------------------------------------>
## Data Description

<details><summary style="font-size: 18px"> 
List of Files:</summary> 
Due to the large file size, I have only added my final datasets to my github repo. All changes are documented in the CRISP-DM notebook.

```
| 
| 
```
</details>
<!------------------------------------------>

### Main Questions:


<details><summary style="font-size: 24px">
Diving into a half-century of production </summary> 
[Notebook Link]()

#### Tables Used:

```
| who_eats_food_we_grow.csv
```


With production data ranging from 1961 through 2013; I found that China, India, and the USA have consistently been the top producers of the global food/feed supply. The two maps below show the side-by-side comparison of production in 1961 vs 2013. The darker the color, the higher the production amount.

<table>
  <tr>
    <td>1961 World Production</td>
    <td>2013 World Production</td>
  </tr>
  <tr>
    <td><img src='Images\1961_world_production.png' size=125%></td>
    <td><img src='Images\2013_world_production.png' size=100%></td>
  </tr>
 </table>

 [1961 Interactive Map](Images\HTML\1961_world_production.html)
 |
 [2013 Interactive Map](Images\HTML\2013_world_production.html)

While all three countries have continued to grow their production numbers; the United States has not managed to keep up with the growth in scale of China or India. 

<img src='Images\percentage of world prod.png' size=125%>
</details>

<!------------------------------------------>

<details><summary style="font-size: 24px">
Exploring emissions by country </summary> 

[Question 2 Notebook Link]()

### Tables Used:

```
| 
| 
```

### EDA 

Unsurprisingly, Beef products have the highest emissions score, sitting more than twice as high as the second highest score - lamb. I found it interesting that both Chocolate and Coffee came in as the 5th and 6th highest scores respectively. I am interested to see whether or not those scores change over time, as we move towards more responsible and sustainable sourcing as a whole. 

After tracking emissions of products to each countries production, I was able to calculate the approximate emissions per country over the course of 50 years. With the same top 3 countires, Brazil also comes in as a top offender. As seen below, the pattern of emissions pretty much mimics the pattern of production.

<img src='Images\percentage of world em.png' size=125%>

The only difference being that the United States emissions rates appear a lot higher than those of China in comparison to the production output over the years. In the notebook there are bar charts for all four of the top countries; but here are the top 5 products contributing to emissions over the time-frame for China and the United States:

<img src='Images\china top em.png' size=150%>
<img src='Images\usa top em.png' size=125%>

Interestingly, the U.S. has been reliant on the production of Beef whereas China has carried a more diverse production portfolio.

</details>
<!------------------------------------------>

# Wrap Up

# Future Work
- Labor Rates
- 


