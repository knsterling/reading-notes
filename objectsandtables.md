Domain modeling is the creation of a model that applies specific attributes to a particular element- being a person, thing, or problem for example. 

//   var EpicFailVideo = function(epicRating, hasAnimals) {
//   this.epicRating = epicRating;
//   this.hasAnimals = hasAnimals;
// }

// var parkourFail = new EpicFailVideo(7, false);
// var corgiFail = new EpicFailVideo(4, true);

// console.log(parkourFail);
// console.log(corgiFail);
  
  
A table is creating a grid format, like Keynote on a Mac, or Microsoft excel. 

  
Functions gather a group of related statememts to perform a task, An Object is a series of variables attributed to something and withing the object are functions but known as methods.
  
  /* The script is placed inside an immediately invoked function expression
   which helps protect the scope of variables */

(function() {

  // PART ONE: CREATE HOTEL OBJECT AND WRITE OUT THE OFFER DETAILS

  // Create a hotel object using object literal syntax
  var hotel = {
    name: 'Park',
    roomRate: 240, // Amount in dollars
    discount: 15,  // Percentage discount
    offerPrice: function() {
      var offerRate = this.roomRate * ((100 - this.discount) / 100);
      return offerRate;
    }
  };

MY name is Kafele Sterling and here's the link to my github page: https://knsterling.github.io/reading-notes/
