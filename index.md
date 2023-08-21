Website Integration | Cheat Sheet
1. CCBP UI Kit
It is a collection of reusable code snippets similar to Bootstrap. It is specially designed for CCBP training.

1.1 Adding CCBP UI Kit to the Web Page

<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
  </body>
</html>




The CCBP UI Kit Script Code should be placed just before the HTML body end tag.

1.2 Display Utility
It is a reusable code snippet to display or hide Section Containers based on user actions.


<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div id="section1">
      <p>This is Section One</p>
      <button class="btn btn-primary" onclick="display('section2')">
        Go to Section 2
      </button>
    </div>
    <div id="section2">
      <p>This is Section Two</p>
      <button class="btn btn-primary" onclick="display('section3')">
        Go to Section 3
      </button>
    </div>
    <div id="section3">
      <p>This is Section Three</p>
      <button class="btn btn-primary" onclick="display('section1')">
        Go to Section 1
      </button>
    </div>
   <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
  </body>
</html>






2. Sections in Tourism Website
2.1 Home Section

<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbG+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMM+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div class="bg-container d-flex flex-column justify-content-end">
      <div class="tourism-card">
        <h1 class="main-heading">Tourism</h1>
        <p class="paragraph">Plan your trip.</p>
        <button class="button">
          Get Started
        </button>
      </div>
    </div>
  </body>
</html>


@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
  height: 100vh;
  background-size: cover;
}
.tourism-card {
  text-align: center;
  background-color: white;
  border-top-left-radius: 25px;
  border-top-right-radius: 25px;
  padding: 5px;
}
.button {
  color: white;
  background-color: #25b1cc;
  width: 138px;
  height: 36px;
  border-width: 0px;
  border-radius: 20px;
}
.main-heading {
  font-family: "Roboto";
}
.paragraph {
  font-family: "Roboto";
}




2.2 Favourite Places Section

<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div class="favourite-places-bg-container">
      <h1 class="favourite-places-heading">Favourite Places</h1>
      <div class="favourite-place-card-container d-flex flex-row">
        <div>
          <h1 class="favourite-place-card-heading">Taj Mahal</h1>
          <p class="favourite-place-card-description">
            If there was just one symbol to represent all of India, it would be the
            Taj Mahal
          </p>
        </div>
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png" class="favourite-place-card-image" />
      </div>
      <div class="favourite-place-card-container d-flex flex-row">
        <div>
          <h1 class="favourite-place-card-heading">Golden Temple</h1>
          <p class="favourite-place-card-description">
            Amritsar is world-famous for the beautiful and highly revered Golden
            Temple
          </p>
        </div>
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/golden-temple-img.png" class="favourite-place-card-image" />
      </div>
      <div class="favourite-place-card-container d-flex flex-row">
        <div>
          <h1 class="favourite-place-card-heading">Mysore Palace</h1>
          <p class="favourite-place-card-description">
            The Mysore Palace is a historical palace and the royal residence at
            Mysore .
          </p>
        </div>
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace-img.png" class="favourite-place-card-image" />
      </div>
      <div class="favourite-place-card-container d-flex flex-row">
        <div>
          <h1 class="favourite-place-card-heading">Varanasi Temple</h1>
          <p class="favourite-place-card-description">
            Varanasi Temple is most famous Hindu temples dedicated to Lord Shiva
          </p>
        </div>
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi-temple-img.png" class="favourite-place-card-image" />
      </div>
    </div>
  </body>
</html>


@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.favourite-places-bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/towerbg.png");
  height: 100vh;
  background-size: cover;
  padding: 24px;
}
.favourite-places-heading {
  color: white;
  font-family: "Roboto";
  font-size: 28px;
  font-weight: bold;
}
.favourite-place-card-container {
  background-color: white;
  border-radius: 8px;
  padding: 16px;
  margin-bottom: 15px;
}
.favourite-place-card-heading {
  color: #0f0e46;
  font-family: "Roboto";
  font-size: 23px;
  font-weight: bold;
}
.favourite-place-card-description {
  color: #6c6b70;
  font-family: "Roboto";
  font-size: 13px;
}
.favourite-place-card-image {
  width: 80px;
  height: 100px;
}
.favourite-place-card-text-container {
  margin-right: 15px;
}



Note
To occupy the background image to the entire content in the above output, remove the height specified to the favourite-places-bg-container.

The background image takes the height of the content of an HTML element if you don't specify the height to it.




2.3 Detailed View Section

<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div class="detailed-view-bg-container">
      <h1 class="detailed-view-heading">Detailed View</h1>
      <div class="detailed-view-card-container">
        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
          <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
          </ol>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c1-img.png" class="d-block w-100" alt="..." />
            </div>
            <div class="carousel-item">
              <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c2-img.png" class="d-block w-100" alt="..." />
            </div>
            <div class="carousel-item">
              <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c3-img.png" class="d-block w-100" alt="..." />
            </div>
          </div>
          <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
        <div class="detailed-view-card-text-container">
          <h1 class="detailed-view-card-heading">Taj Mahal</h1>
          <p class="detailed-view-card-description">
            The Taj Mahal is considered to be the greatest architectural
            achievement in the whole range of Indo-Islamic architecture. Its
            recognised architectonic beauty has a rhythmic combination of solids
            and voids, concave and convex and light shadow; such as arches and
            domes further increases the aesthetic aspect. Not a piece of
            architecture, as other buildings are, but the proud passions of an
            emperor’s love wrought in living stones.
          </p>
        </div>
      </div>
    </div>
  </body>
</html>



@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.detailed-view-bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/seabg.png");
  height: 100vh;
  background-size: cover;
}
.detailed-view-heading {
  color: white;
  font-family: "Roboto";
  font-size: 28px;
  font-weight: bold;
  padding: 24px;
}
.detailed-view-card-container {
  background-color: white;
  border-bottom-right-radius: 8px;
  border-bottom-left-radius: 8px;
  margin: 24px;
}
.detailed-view-card-heading {
  color: #0f0e46;
  font-family: "Roboto";
  font-size: 23px;
  font-weight: bold;
}
.detailed-view-card-description {
  color: #6c6b70;
  font-family: "Roboto";
  font-size: 13px;
}
.detailed-view-card-text-container {
  padding: 16px;
}



3. HTML Attributes
3.1 The HTML id Attribute
The HTML id attribute specifies a unique id for an HTML element. The value of the id attribute must be unique within the HTML document.

<div id="section1">Section 1</div>



Warning
The CCBP UI kit works only if the value of the HTML id attribute of the container section has the prefix as section.

So, the id which we specify for any section should always contain its prefix as section if you are using CCBP UI Kit.







3.2 The HTML onclick Attribute
The onclick event occurs when the user clicks on an HTML Element.

<button class="btn btn-primary" onclick="display('section3')">
  Go to Section 3
</button>



The value of an HTML onclick attribute should be enclosed in double-quotes and the value inside the brackets of display() should be enclosed in single quotes.

4. Website Integration
4.1 Integration of Home and Favourite Places Sections
To display Favourite Places Section when we are in the Home Section:

Step-1: Change ids of Section Containers. All the ids must start with section
Step-2: Add HTML code of Home Section and corresponding CSS styles to Display Utility
Step-3: Add HTML code of Favourite Places Section and corresponding  CSS styles to Display Utility
Step-4: Add an HTML onclick attribute to the HTML button element in the Home Section

To display the Home Section when we are in the Favourite Places Section:

Step-5: Add an HTML button element in Favourite places Section
Step-6: Add an HTML onclick attribute to it




<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div id="sectionHome">
      <div class="bg-container d-flex flex-column justify-content-end">
        <div class="tourism-card">
          <h1 class="main-heading">Tourism</h1>
          <p class="paragraph">Plan your trip.</p>
          <button class="button" onclick="display('sectionFavouritePlaces')">
            Get Started
          </button>
        </div>
      </div>
    </div>
    <div id="sectionFavouritePlaces">
      <div class="favourite-places-bg-container">
        <h1 class="favourite-places-heading">Favourite Places</h1>
        <div class="favourite-place-card-container d-flex flex-row">
          <div>
            <h1 class="favourite-place-card-heading">Taj Mahal</h1>
            <p class="favourite-place-card-description">
              If there was just one symbol to represent all of India, it would
              be the Taj Mahal
            </p>
          </div>
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png"
            class="favourite-place-card-image"
          />
        </div>
        <div class="favourite-place-card-container d-flex flex-row">
          <div>
            <h1 class="favourite-place-card-heading">Golden Temple</h1>
            <p class="favourite-place-card-description">
              Amritsar is world-famous for the beautiful and highly revered
              Golden Temple
            </p>
          </div>
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/golden-temple-img.png"
            class="favourite-place-card-image"
          />
        </div>
        <div class="favourite-place-card-container d-flex flex-row">
          <div>
            <h1 class="favourite-place-card-heading">Mysore Palace</h1>
            <p class="favourite-place-card-description">
              The Mysore Palace is a historical palace and the royal residence
              at Mysore .
            </p>
          </div>
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace-img.png"
            class="favourite-place-card-image"
          />
        </div>
        <div class="favourite-place-card-container d-flex flex-row">
          <div>
            <h1 class="favourite-place-card-heading">Varanasi Temple</h1>
            <p class="favourite-place-card-description">
              Varanasi Temple is most famous Hindu temples dedicated to Lord
              Shiva
            </p>
          </div>
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi-temple-img.png"
            class="favourite-place-card-image"
          />
        </div>
        <button class="btn btn-dark" onclick="display('sectionHome')">
          back
        </button>
      </div>
    </div>
    <div id="sectionTajMahalDetailedView"></div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
  </body>
</html>



@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
  height: 100vh;
  background-size: cover;
}
.tourism-card {
  text-align: center;
  background-color: white;
  border-top-left-radius: 25px;
  border-top-right-radius: 25px;
  padding: 5px;
}
.button {
  color: white;
  background-color: #25b1cc;
  width: 138px;
  height: 36px;
  border-width: 0px;
  border-radius: 20px;
}
.main-heading {
  font-family: "Roboto";
}
.paragraph {
  font-family: "Roboto";
}
.favourite-places-bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/towerbg.png");
  height: 100vh;
  background-size: cover;
  padding: 24px;
}
.favourite-places-heading {
  color: white;
  font-family: "Roboto";
  font-size: 28px;
  font-weight: bold;
}
.favourite-place-card-container {
  background-color: white;
  border-radius: 8px;
  padding: 16px;
  margin-bottom: 15px;
}
.favourite-place-card-heading {
  color: #0f0e46;
  font-family: "Roboto";
  font-size: 23px;
  font-weight: bold;
}
.favourite-place-card-description {
  color: #6c6b70;
  font-family: "Roboto";
  font-size: 13px;
}
.favourite-place-card-image {
  width: 80px;
  height: 100px;
}
.favourite-place-card-text-container {
  margin-right: 15px;
}



Note
While Integrating the sections with CCBP UI Kit, the ids of the section container must have a prefix section. Otherwise it doesn't work.







4.2 Integration of Favourite Places and Detailed View Sections
To display the Detailed View Section when we click on Taj Mahal Card:

Step-1: Add HTML code of Detailed View Section code to the Display Utility
Step-2: Add corresponding styles to the CSS file
Step-3: Add an HTML onclick attribute to the Taj Mahal Card in the Favourite Places Section

To display the Favourite Places Section when we are in the Detailed View Section:

Step-4: Add an HTML button element in the Detailed View Section
Step-5: Add an HTML onclick attribute to the HTML button element




<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div id="sectionHome">
      <div class="bg-container d-flex flex-column justify-content-end">
        <div class="tourism-card">
          <h1 class="main-heading">Tourism</h1>
          <p class="paragraph">Plan your trip.</p>
          <button class="button" onclick="display('sectionFavouritePlaces')">
            Get Started
          </button>
        </div>
      </div>
    </div>
    <div id="sectionFavouritePlaces">
      <div class="favourite-places-bg-container">
        <h1 class="favourite-places-heading">Favourite Places</h1>
        <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionTajMahalDetailedView')">
          <div>
            <h1 class="favourite-place-card-heading">Taj Mahal</h1>
            <p class="favourite-place-card-description">
              If there was just one symbol to represent all of India, it would
              be the Taj Mahal
            </p>
          </div>
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png"
            class="favourite-place-card-image"
          />
        </div>
        <div class="favourite-place-card-container d-flex flex-row">
          <div>
            <h1 class="favourite-place-card-heading">Golden Temple</h1>
            <p class="favourite-place-card-description">
              Amritsar is world-famous for the beautiful and highly revered
              Golden Temple
            </p>
          </div>
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/golden-temple-img.png"
            class="favourite-place-card-image"
          />
        </div>
        <div class="favourite-place-card-container d-flex flex-row">
          <div>
            <h1 class="favourite-place-card-heading">Mysore Palace</h1>
            <p class="favourite-place-card-description">
              The Mysore Palace is a historical palace and the royal residence
              at Mysore .
            </p>
          </div>
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace-img.png"
            class="favourite-place-card-image"
          />
        </div>
        <div class="favourite-place-card-container d-flex flex-row">
          <div>
            <h1 class="favourite-place-card-heading">Varanasi Temple</h1>
            <p class="favourite-place-card-description">
              Varanasi Temple is most famous Hindu temples dedicated to Lord
              Shiva
            </p>
          </div>
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi-temple-img.png"
            class="favourite-place-card-image"
          />
        </div>
        <button class="btn btn-dark" onclick="display('sectionHome')">
          back
        </button>
      </div>
    </div>
    <div id="sectionTajMahalDetailedView">
      <div class="detailed-view-bg-container">
        <h1 class="detailed-view-heading">Detailed View</h1>
        <div class="detailed-view-card-container">
          <div id="carouselExampleIndicators1" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
              <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
              <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
              <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img
                  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c1-img.png"
                  class="d-block w-100"
                  alt="..."
                />
              </div>
              <div class="carousel-item">
                <img
                  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c2-img.png"
                  class="d-block w-100"
                  alt="..."
                />
              </div>
              <div class="carousel-item">
                <img
                  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c3-img.png"
                  class="d-block w-100"
                  alt="..."
                />
              </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleIndicators1" role="button" data-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleIndicators1" role="button" data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>
          <div class="detailed-view-card-text-container">
            <h1 class="detailed-view-card-heading">Taj Mahal</h1>
            <p class="detailed-view-card-description">
              The Taj Mahal is considered to be the greatest architectural
              achievement in the whole range of Indo-Islamic architecture. Its
              recognised architectonic beauty has a rhythmic combination of
              solids and voids, concave and convex and light shadow; such as
              arches and domes further increases the aesthetic aspect. Not a
              piece of architecture, as other buildings are, but the proud
              passions of an emperor’s love wrought in living stones.
            </p>
          </div>
        </div>
        <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
          back
        </button>
      </div>
    </div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
  </body>
</html>



@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
  height: 100vh;
  background-size: cover;
}
.tourism-card {
  text-align: center;
  background-color: white;
  border-top-left-radius: 25px;
  border-top-right-radius: 25px;
  padding: 5px;
}
.button {
  color: white;
  background-color: #25b1cc;
  width: 138px;
  height: 36px;
  border-width: 0px;
  border-radius: 20px;
}
.main-heading {
  font-family: "Roboto";
}
.paragraph {
  font-family: "Roboto";
}
.favourite-places-bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/towerbg.png");
  height: 100vh;
  background-size: cover;
  padding: 24px;
}
.favourite-places-heading {
  color: white;
  font-family: "Roboto";
  font-size: 28px;
  font-weight: bold;
}
.favourite-place-card-container {
  background-color: white;
  border-radius: 8px;
  padding: 16px;
  margin-bottom: 15px;
}
.favourite-place-card-heading {
  color: #0f0e46;
  font-family: "Roboto";
  font-size: 23px;
  font-weight: bold;
}
.favourite-place-card-description {
  color: #6c6b70;
  font-family: "Roboto";
  font-size: 13px;
}
.favourite-place-card-image {
  width: 80px;
  height: 100px;
}
.favourite-place-card-text-container {
  margin-right: 15px;
}
.detailed-view-bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/seabg.png");
  height: 100vh;
  background-size: cover;
}
.detailed-view-heading {
  color: white;
  font-family: "Roboto";
  font-size: 28px;
  font-weight: bold;
  padding: 24px;
}
.detailed-view-card-container {
  background-color: white;
  border-bottom-right-radius: 8px;
  border-bottom-left-radius: 8px;
  margin: 24px;
}
.detailed-view-card-heading {
  color: #0f0e46;
  font-family: "Roboto";
  font-size: 23px;
  font-weight: bold;
}
.detailed-view-card-description {
  color: #6c6b70;
  font-family: "Roboto";
  font-size: 13px;
}
.detailed-view-card-text-container {
  padding: 16px;
}