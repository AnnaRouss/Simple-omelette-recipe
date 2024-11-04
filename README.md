# Simple-omelette-recipe

Had to create a Simple Omelette Recipe website using fonts, images, wording, and colors specific to this challenge. I did my very best as it is my first HTML/CSS challenge that I have ever done. It was challenging even though it was supposed to be newbie-friendly.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Frontend Mentor | Recipe page</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" type="image/png" sizes="32x32" href="./assets/images/favicon-32x32.png">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Young+Serif&display=swap" rel="stylesheet">
</head>
    <body>
        <main id="container">
                <div class="img">
                    <img src="/Users/anastasiaroussakis/Downloads/recipe-page-main 2/assets/images/image-omelette.jpeg" alt="center-image" width="900">
                </div>
          
                <div class="recipe">
          
                  <h1>Simple Omelette Recipe</h1>
          
                  <p>An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked 
                    to perfection, optionally filled with your choice of cheese, vegetables, or meats.</p>
          
                </div>
          
                <div class="preparation">
                  <h2 id="prep">Preparation time</h2>
                    <ul>
                      <li><strong>Total:</strong> Approximately 10 minutes</li><br>
                      <li><strong>Preparation:</strong> 5 minutes</li><br>
                      <li><strong>Cooking:</strong> 5 minutes</li><br>
                    </ul>
                </div>
                
                <div class="ingredients">
                  <h2>Ingredients</h2>
          
                  <ul>
                    <li>2-3 large eggs</li><br>
                    <li>Salt, to taste</li><br>
                    <li>Pepper, to taste</li><br>
                    <li>1 tablespoon of butter or oil</li><br>
                    <li>Optional fillings: cheese, diced vegetables, cooked meats, herbs</li>
                  </ul>
                </div>
          
                <div class="line"></div>
          
                <div class="instructions">
                  <h2>Instructions</h2>
          
                  <ol>
                    <li><strong>Beat the eggs:</strong> In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed. 
                      You can add a tablespoon of water or milk for a fluffier texture.</li><br>
                    <li><strong>Heat the pan:</strong> Place a non-stick frying pan over medium heat and add butter or oil.</li><br>
                    <li><strong>Cook the omelette:</strong> Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure 
                      the eggs evenly coat the surface.</li><br>
                    <li><strong>Add fillings (optional):</strong> When the eggs begin to set at the edges but are still slightly runny in the 
                      middle, sprinkle your chosen fillings over one half of the omelette.</li><br>
                    <li><strong>Fold and serve:</strong> As the omelette continues to cook, carefully lift one edge and fold it over the 
                      fillings. Let it cook for another minute, then slide it onto a plate.</li><br>
                    <li><strong>Enjoy:</strong> Serve hot, with additional salt and pepper if needed.</li>
                  </ol>
    </div>
    <h2 class="font-hd">Nutrition</h2>
    <p>The table below shows nutritional values per serving without the additional fillings.</p>

    <table class="font-hd1 table" id="blue-gd1">
      <tr>
        <td class="table-space">Calories</td>
        <td class="table-space1"><strong>277kcal</strong></td>
      </tr>
      <tr>
        <td class="table-space">Carbs</td>
        <td class="table-space1"><strong>0g</strong></td>
      </tr>
      <tr>
        <td class="table-space">Proteins</td>
        <td class="table-space1"><strong>20g</strong></td>
      </tr>
      <tr>
        <td class="table-space">Fat</td>
        <td class="table-space1"><strong>22g</strong></td>
      </tr>
    </table>
  </div>
</main>
</body>
</html>
