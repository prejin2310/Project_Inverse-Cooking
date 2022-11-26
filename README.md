<h1 align="center">INVERSE COOKING-Recipe Generation from Food Images”</h1>

### Description
In this project introduces an inverse cooking system that takes a food image and recreate a cooking recipes consisting of a title, ingredients, sequence of cooking instructions, Calorie, Cooking time.
This model predicts ingredients as sets by means of `DenseNet201` and `Recipe Retrieval Algorithm`. Generates cooking instructions by attending to both image and its inferred ingredients simultaneously.


### Dataset
The recipes from the website are scraped and saved as a JSON file, google_images_download library is used to download images. For each recipe 10 images are downloaded for training and 2 for testing. </br>
A total of 9432 images are downloaded (7860 train and 1572 test)


### Workflow Diagram
There is no real time web portal available to predict the food based on uploaded image. Currently entertainment portal like YouTube are used to find the recipe of a food item but it  only works while we know the name of the food item. 
<img src = "https://github.com/prejin2310/Inverse-Cooking/blob/d686306472e671c7a65d4b4d07e0dc45f0aaba6c/Screenshots/work1.jpg" alt = "" width="700px"/>


### Working Screenshots
<div align="center">
  <img src = "https://github.com/prejin2310/Inverse-Cooking/blob/f1c2669526468a88e57682c5de087537e73743f7/Screenshots/home.jpg" alt = "" width="700px"/>
  <img src = "https://github.com/prejin2310/Inverse-Cooking/blob/f1c2669526468a88e57682c5de087537e73743f7/Screenshots/upload.jpg" alt = "" width="700px"/>
</div>
<br/>
<div align="center">
  <img src = "https://github.com/prejin2310/Inverse-Cooking/blob/f1c2669526468a88e57682c5de087537e73743f7/Screenshots/mobile.jpg" alt = "" width="200px"/>
  <img src = "https://github.com/prejin2310/Inverse-Cooking/blob/f1c2669526468a88e57682c5de087537e73743f7/Screenshots/cam.jpg" alt = "" width="200px"/>
  <img src = "https://github.com/prejin2310/Inverse-Cooking/blob/f1c2669526468a88e57682c5de087537e73743f7/Screenshots/outmobile.jpg" alt = "" width="200px"/>
</div>
<br/>

  
### Reference
- [pic2recipe](http://pic2recipe.csail.mit.edu/)
- [Meta Researcher](https://ai.facebook.com/blog/inverse-cooking/)
- [Meta AI](https://research.facebook.com/file/1033483384091768/Inverse-Cooking-Recipe-Generation-from-Food-Images.pdf)
- [IEEE Paper](https://ieeexplore.ieee.org/document/8953192)
