--- 
layout: docs
title: News item
description: Newslist description
group: components
--- 

## Types ## 

### Default news item ### 

{% example html %}

<article class="sv-news-item">
   <div class="sv-news-item__media">
      <img src="https://unsplash.it/467/300/?blur" />
   </div>
   <header class="sv-news-item__headline">
      <div class="sv-news-item__headline__title">
         <h2 class="sv-font sv-font--title">
            <a href="#" class="sv-link sv-link--title">Lorem ipsum</a>
         </h2>
         <p class="sv-font sv-font--tagline">Eric Ericsson, aug 12 12:56</p>
      </div>
   </header>
   <section class="sv-news-item__preamble">
      <p class="sv-font">Bacon ipsum dolor amet leberkas jowl tail, cow rump pork loin pancetta corned beef. Drumstick pork shank, salami turkey
         t-bone jerky corned beef picanha jowl brisket frankfurter shankle. Meatball jowl sausage pork belly chicken hamburger,
         andouille pork loin capicola.</p>
   </section>
   <footer class="sv-news-item__footer">
      <a href="#" class="sv-link sv-link--base">Like</a>
      <i class="sv-icon--dot"></i>
      <a href="#" class="sv-link sv-link--base">Reply</a>
      <i class="sv-icon--dot"></i>
      <span class="sv-link sv-link--base">12:56</span>
   </footer>
</article>

{% endexample %} 
### Example: Vertical list ### 
`.sv-list`
   <ul class="sv-list">
      <li class="sv-list__item">
         <article class="sv-news-item">
            <div class="sv-news-item__media">
               <img src="https://unsplash.it/467/300/?blur" />
            </div>
            <header class="sv-news-item__headline">
               <div class="sv-news-item__headline__title">
                  <h2 class="sv-font sv-font--title">
                     <a href="#" class="sv-link sv-link--title">Lorem ipsum</a>
                  </h2>
                  <p class="sv-font sv-font--tagline">Eric Ericsson, aug 12 12:56</p>
               </div>
            </header>
            <div class="sv-news-item__preamble">
               <p class="sv-font">Bacon ipsum dolor amet leberkas jowl tail, cow rump pork loin pancetta corned beef. Drumstick pork shank,
                  salami turkey t-bone jerky corned beef picanha jowl brisket frankfurter shankle. Meatball jowl sausage
                  pork belly chicken hamburger, andouille pork loin capicola.</p>
            </div>
            <footer class="sv-news-item__footer">
               <a href="#" class="sv-link sv-link--base">Like</a>
               <i class="sv-icon--dot"></i>
               <a href="#" class="sv-link sv-link--base">Reply</a>
               <i class="sv-icon--dot"></i>
               <span class="sv-link sv-link--base">12:56</span>
            </footer>
         </article>
      </li>
      <li class="sv-list__item">
         <article class="sv-news-item">
            <div class="sv-news-item__media">
               <img src="https://unsplash.it/467/300/?blur" />
            </div>
            <header class="sv-news-item__headline">
               <div class="sv-news-item__headline__title">
                  <h2 class="sv-font sv-font--title">
                     <a href="#" class="sv-link sv-link--title">Lorem ipsum</a>
                  </h2>
                  <p class="sv-font sv-font--tagline">Eric Ericsson, aug 12 12:56</p>
               </div>
            </header>
            <div class="sv-news-item__preamble">
               <p class="sv-font">Bacon ipsum dolor amet leberkas jowl tail, cow rump pork loin pancetta corned beef. Drumstick pork shank,
                  salami turkey t-bone jerky corned beef picanha jowl brisket frankfurter shankle. Meatball jowl sausage
                  pork belly chicken hamburger, andouille pork loin capicola.</p>
            </div>
            <footer class="sv-news-item__footer">
               <a href="#" class="sv-link sv-link--base">Like</a>
               <i class="sv-icon--dot"></i>
               <a href="#" class="sv-link sv-link--base">Reply</a>
               <i class="sv-icon--dot"></i>
               <span class="sv-link sv-link--base">12:56</span>
            </footer>
         </article>
      </li>
      <li class="sv-list__item">
         <article class="sv-news-item">
            <div class="sv-news-item__media">
               <img src="https://unsplash.it/467/300/?blur" />
            </div>
            <header class="sv-news-item__headline">
               <div class="sv-news-item__headline__title">
                  <h2 class="sv-font sv-font--title">
                     <a href="#" class="sv-link sv-link--title">Lorem ipsum</a>
                  </h2>
                  <p class="sv-font sv-font--tagline">Eric Ericsson, aug 12 12:56</p>
               </div>
            </header>
            <div class="sv-news-item__preamble">
               <p class="sv-font">Bacon ipsum dolor amet leberkas jowl tail, cow rump pork loin pancetta corned beef. Drumstick pork shank,
                  salami turkey t-bone jerky corned beef picanha jowl brisket frankfurter shankle. Meatball jowl sausage
                  pork belly chicken hamburger, andouille pork loin capicola.</p>
            </div>
            <footer class="sv-news-item__footer">
               <a href="#" class="sv-link sv-link--base">Like</a>
               <i class="sv-icon--dot"></i>
               <a href="#" class="sv-link sv-link--base">Reply</a>
               <i class="sv-icon--dot"></i>
               <span class="sv-link sv-link--base">12:56</span>
            </footer>
         </article>
      </li>
   </ul>


### Example: Horizontal list ###
`sv-list sv-list--horizontal`
<ul class="sv-list sv-list--horizontal">
   <li class="sv-list__item" style="max-width:420px">
      <article class="sv-news-item">
         <div class="sv-news-item__media">
            <img src="https://unsplash.it/400/300/?blur" />
         </div>
         <header class="sv-news-item__headline">
            <div class="sv-news-item__headline__title">
               <h2 class="sv-font sv-font--title">
                  <a href="#" class="sv-link sv-link--title">Lorem ipsum</a>
               </h2>
               <p class="sv-font sv-font--tagline">Eric Ericsson, aug 12 12:56</p>
            </div>
         </header>
         <div class="sv-news-item__preamble">
            <p class="sv-font">Bacon ipsum dolor amet leberkas jowl tail, cow rump pork loin pancetta corned beef. Drumstick pork shank,
               salami turkey t-bone jerky corned beef picanha jowl brisket frankfurter shankle. Meatball jowl sausage
               pork belly chicken hamburger, andouille pork loin capicola.</p>
         </div>
         <footer class="sv-news-item__footer">
            <a href="#" class="sv-link sv-link--base">Like</a>
            <i class="sv-icon--dot"></i>
            <a href="#" class="sv-link sv-link--base">Reply</a>
            <i class="sv-icon--dot"></i>
            <span class="sv-link sv-link--base">12:56</span>
         </footer>
      </article>
   </li>
   <li class="sv-list__item" style="max-width:420px">
      <article class="sv-news-item">
         <div class="sv-news-item__media">
            <img src="https://unsplash.it/400/300/?blur" />
         </div>
         <header class="sv-news-item__headline">
            <div class="sv-news-item__headline__title">
               <h2 class="sv-font sv-font--title">
                  <a href="#" class="sv-link sv-link--title">Lorem ipsum</a>
               </h2>
               <p class="sv-font sv-font--tagline">Eric Ericsson, aug 12 12:56</p>
            </div>
         </header>
         <div class="sv-news-item__preamble">
            <p class="sv-font">Bacon ipsum dolor amet leberkas jowl tail, cow rump pork loin pancetta corned beef. Drumstick pork shank,
               salami turkey t-bone jerky corned beef picanha jowl brisket frankfurter shankle. Meatball jowl sausage
               pork belly chicken hamburger, andouille pork loin capicola.</p>
         </div>
         <footer class="sv-news-item__footer">
            <a href="#" class="sv-link sv-link--base">Like</a>
            <i class="sv-icon--dot"></i>
            <a href="#" class="sv-link sv-link--base">Reply</a>
            <i class="sv-icon--dot"></i>
            <span class="sv-link sv-link--base">12:56</span>
         </footer>
      </article>
   </li>
   <li class="sv-list__item" style="max-width:420px">
      <article class="sv-news-item">
         <div class="sv-news-item__media">
            <img src="https://unsplash.it/400/300/?blur" />
         </div>
         <header class="sv-news-item__headline">
            <div class="sv-news-item__headline__title">
               <h2 class="sv-font sv-font--title">
                  <a href="#" class="sv-link sv-link--title">Lorem ipsum</a>
               </h2>
               <p class="sv-font sv-font--tagline">Eric Ericsson, aug 12 12:56</p>
            </div>
         </header>
         <div class="sv-news-item__preamble">
            <p class="sv-font">Bacon ipsum dolor amet leberkas jowl tail, cow rump pork loin pancetta corned beef. Drumstick pork shank,
               salami turkey t-bone jerky corned beef picanha jowl brisket frankfurter shankle. Meatball jowl sausage
               pork belly chicken hamburger, andouille pork loin capicola.</p>
         </div>
         <footer class="sv-news-item__footer">
            <a href="#" class="sv-link sv-link--base">Like</a>
            <i class="sv-icon--dot"></i>
            <a href="#" class="sv-link sv-link--base">Reply</a>
            <i class="sv-icon--dot"></i>
            <span class="sv-link sv-link--base">12:56</span>
         </footer>
      </article>
   </li>
   <li class="sv-list__item" style="max-width:420px">
      <article class="sv-news-item">
         <div class="sv-news-item__media">
            <img src="https://unsplash.it/400/300/?blur" />
         </div>
         <header class="sv-news-item__headline">
            <div class="sv-news-item__headline__title">
               <h2 class="sv-font sv-font--title">
                  <a href="#" class="sv-link sv-link--title">Lorem ipsum</a>
               </h2>
               <p class="sv-font sv-font--tagline">Eric Ericsson, aug 12 12:56</p>
            </div>
         </header>
         <div class="sv-news-item__preamble">
            <p class="sv-font">Bacon ipsum dolor amet leberkas jowl tail, cow rump pork loin pancetta corned beef. Drumstick pork shank,
               salami turkey t-bone jerky corned beef picanha jowl brisket frankfurter shankle. Meatball jowl sausage
               pork belly chicken hamburger, andouille pork loin capicola.</p>
         </div>
         <footer class="sv-news-item__footer">
            <a href="#" class="sv-link sv-link--base">Like</a>
            <i class="sv-icon--dot"></i>
            <a href="#" class="sv-link sv-link--base">Reply</a>
            <i class="sv-icon--dot"></i>
            <span class="sv-link sv-link--base">12:56</span>
         </footer>
      </article>
   </li>
   <li class="sv-list__item" style="max-width:420px">
      <article class="sv-news-item">
         <div class="sv-news-item__media">
            <img src="https://unsplash.it/400/300/?blur" />
         </div>
         <header class="sv-news-item__headline">
            <div class="sv-news-item__headline__title">
               <h2 class="sv-font sv-font--title">
                  <a href="#" class="sv-link sv-link--title">Lorem ipsum</a>
               </h2>
               <p class="sv-font sv-font--tagline">Eric Ericsson, aug 12 12:56</p>
            </div>
         </header>
         <div class="sv-news-item__preamble">
            <p class="sv-font">Bacon ipsum dolor amet leberkas jowl tail, cow rump pork loin pancetta corned beef. Drumstick pork shank,
               salami turkey t-bone jerky corned beef picanha jowl brisket frankfurter shankle. Meatball jowl sausage
               pork belly chicken hamburger, andouille pork loin capicola.</p>
         </div>
         <footer class="sv-news-item__footer">
            <a href="#" class="sv-link sv-link--base">Like</a>
            <i class="sv-icon--dot"></i>
            <a href="#" class="sv-link sv-link--base">Reply</a>
            <i class="sv-icon--dot"></i>
            <span class="sv-link sv-link--base">12:56</span>
         </footer>
      </article>
   </li>
   <li class="sv-list__item" style="max-width:420px">
      <article class="sv-news-item">
         <div class="sv-news-item__media">
            <img src="https://unsplash.it/400/300/?blur" />
         </div>
         <header class="sv-news-item__headline">
            <div class="sv-news-item__headline__title">
               <h2 class="sv-font sv-font--title">
                  <a href="#" class="sv-link sv-link--title">Lorem ipsum</a>
               </h2>
               <p class="sv-font sv-font--tagline">Eric Ericsson, aug 12 12:56</p>
            </div>
         </header>
         <div class="sv-news-item__preamble">
            <p class="sv-font">Bacon ipsum dolor amet leberkas jowl tail, cow rump pork loin pancetta corned beef. Drumstick pork shank,
               salami turkey t-bone jerky corned beef picanha jowl brisket frankfurter shankle. Meatball jowl sausage
               pork belly chicken hamburger, andouille pork loin capicola.</p>
         </div>
         <footer class="sv-news-item__footer">
            <a href="#" class="sv-link sv-link--base">Like</a>
            <i class="sv-icon--dot"></i>
            <a href="#" class="sv-link sv-link--base">Reply</a>
            <i class="sv-icon--dot"></i>
            <span class="sv-link sv-link--base">12:56</span>
         </footer>
      </article>
   </li>
</ul>