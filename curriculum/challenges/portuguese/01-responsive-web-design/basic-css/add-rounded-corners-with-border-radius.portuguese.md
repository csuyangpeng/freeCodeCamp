---
id: bad87fee1348bd9aedf08814
title: Add Rounded Corners with border-radius
challengeType: 0
videoUrl: ''
localeTitle: Adicionar cantos arredondados com raio de borda
---

## Description
<section id="description"> Sua foto de gato atualmente tem cantos afiados. Podemos arredondar esses cantos com uma propriedade CSS chamada <code>border-radius</code> . </section>

## Instructions
<section id="instructions"> Você pode especificar um <code>border-radius</code> com pixels. Dê ao seu gato uma foto <code>border-radius</code> de 10 <code>10px</code> . Nota: este desafio permite múltiplas soluções possíveis. Por exemplo, você pode adicionar <code>border-radius</code> à classe <code>.smaller-image</code> <code>.thick-green-border</code> ou à classe <code>.smaller-image</code> . </section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Seu elemento de imagem deve ter a classe "borda verde espessa".
    testString: 'assert($("img").hasClass("thick-green-border"), "Your image element should have the class "thick-green-border".");'
  - text: Sua imagem deve ter um raio de 10 <code>10px</code>
    testString: 'assert(parseInt($("img").css("border-top-left-radius")) > 8, "Your image should have a border radius of <code>10px</code>");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, monospace;
  }

  p {
    font-size: 16px;
    font-family: monospace;
  }

  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
  }

  .smaller-image {
    width: 100px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>
<main>
  <p class="red-text">Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <div>
    <p>Things cats love:</p>
    <ul>
      <li>cat nip</li>
      <li>laser pointers</li>
      <li>lasagna</li>
    </ul>
    <p>Top 3 things cats hate:</p>
    <ol>
      <li>flea treatment</li>
      <li>thunder</li>
      <li>other cats</li>
    </ol>
  </div>

  <form action="/submit-cat-photo">
    <label><input type="radio" name="indoor-outdoor" checked> Indoor</label>
    <label><input type="radio" name="indoor-outdoor"> Outdoor</label><br>
    <label><input type="checkbox" name="personality" checked> Loving</label>
    <label><input type="checkbox" name="personality"> Lazy</label>
    <label><input type="checkbox" name="personality"> Energetic</label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
