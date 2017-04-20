# Things to do in Italy
4/19/2017 test website design by creating a page with things to do in Italy

<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
<!-- you reference a class by using a . in front of the name and reference an id using # -->
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }

  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }

  .smaller-image {
    width: 100px;
  }
  .silver-background {
    background-color: silver;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p>Click here for <a href="#">cat photos</a>.</p>

<a href="#"><img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. "></a>

<p class="red-text">Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p class="red-text">Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>

<!--The div element passes the CSS of its own class declarations down to all the elements it contains -->
<div class="silver-background">
  <p> Things cats love: </p>
  <!-- <ul> are un-ordered lists -->
  <ul>
    <li> cat nip </li>
    <li> lasagna </li>
    <li> scratching </li>
  </ul>
  
  <p>Top 3 things cats hate:</p>
  <!-- <ol> are ordered lists -->
  <ol>
    <li> dogs </li>
    <li> baths </li>
    <li> fleas </li>
  </ol>
</div>

<!-- create input box of type "text"-->
<!-- placeholder is text before user enters it -->
<!-- nest input type inside form. The form places data on the server to URL specified in form's action attribute -->
<!-- button type is a button with text Submit -->
<form id="cat-photo-form" "action="/submit-cat-photo">
  <!-- adding text required makes it require an input -->
  <label><input type="radio" name="indoor-outdoor" checked> Indoor</label>
  <label><input type="radio" name="indoor-outdoor"> Outdoor</label>
  <input type="text" placeholder="cat photo URL" required>
  <button type="submit">Submit</button>

  <label><input type="checkbox" name="personality" checked> Loving</label>
  <label><input type="checkbox" name="personality"> Lazy</label>
  <label><input type="checkbox" name="personality"> Energetic</label>
</form>

