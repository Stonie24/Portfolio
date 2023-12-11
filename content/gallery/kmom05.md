---
Title: Kmom05
Description: This is out kmom05 page.
---


<div class="gallery"> 
    <!-- Om du bara har en bild  -->
    <picture>
        <img src="%base_url%/image/sheep.jpg&w=667" alt="A sheep">
    </picture>
    <!-- Om du vill skilja mellan små och stora -->
    <picture>
        <source media="(min-width: 668px)" srcset="%base_url%/image/sheep.jpg">
        <img src="%base_url%/image/sheep.jpg&w=667" alt="A sheep">
    </picture>
    <!-- Om du vill fitta bilden för mobilanpassning -->
     <picture>
        <source media="(min-width: 668px)" srcset="%base_url%/image/sheep.jpg">
        <img src="%base_url%/image/sheep.jpg?w=667&h=300&crop-to-fit&area=0,25,0,0" alt="A sheep">
    </picture>
</div>






