<h1>👋 Hello World!</h1>
<h1>My Favorite Animal: Cats</h1>

<p>Cats are wonderful pets. They are playful, affectionate, and independent. I love watching them explore and play with toys.</p>

<h2>Why I Love Cats</h2>
<ul>
  <li>They are cute and cuddly.</li>
  <li>They are great companions.</li>
  <li>They have unique personalities.</li>
</ul>

<img src="https://i.postimg.cc/kGZjVNfY/ragdoll-cat-names.jpg" alt="Cute cat" class="centered">

<p>Here are some fun facts about cats:</p>
<ol>
  <li>Cats sleep 12-16 hours a day.</li>
  <li>They can rotate their ears 180 degrees.</li>
  <li>Cats have excellent night vision.</li>
</ol>

<!-- New normal images (not centered) -->
<img src="https://i.postimg.cc/Dw5xLKj8/catoutside.jpg" alt="Cat outside">
<img src="https://i.postimg.cc/DyRXNpS1/Cat.jpg" alt="Another cat">



body {
  font-family: system-ui;
  background: #f06d06;
  color: white;
  text-align: center;
}

.centered {
  display: block;
  margin: auto;
  max-width: 300px;
  border-radius: 12px;
}
/* Center the parent container */
.parent {
  max-width: 600px;
  margin: 40px auto;      /* centers the box */
  padding: 20px;
  border: 3px dotted #444;
  border-radius: 10px;
  background: #fafafa;
}

/* Style the children */
.child {
  background: #e3f2fd;
  padding: 15px;
  margin-bottom: 15px;
  border: 2px solid #90caf9;
  border-radius: 8px;
}

/* Make it responsive */
@media (max-width: 500px) {
  .parent {
    max-width: 90%;
    padding: 10px;
  }

  .child {
    padding: 10px;
    margin-bottom: 10px;
  }
}
