# Adoption Website

## Setup
* Clone this repo to your exercises directory
* Create a setup branch and push up the usual stuff
* Review the [Instructions](instructions.md)

# UPDATE THIS README WHEN THE ASSIGNMENT IS COMPLETED

* Loops 

const petBuilder = (petsArray) => {
        let domString = "";
        petsArray.forEach((pet) => {
          domString += `
          <div class="pets">
          <div class="column">
          <div class="card" style="width: 18rem;">
          <header>${pet.name}</header>
          <img src=${pet.imageUrl} class="card-img-top" alt="image of pet">
          <div class="card-body">
          <h5 class="card-title">${pet.color}</h5>
          <p class="card-text">${pet.specialSkill}</p>
          <footer>${pet.type}</footer>
          `;
        });
      
        renderToDom("#petContainer", domString);
      };


* Event Listeners 

const buttonEvents = () => {
        document
          .querySelector("#buttonContainer")
          .addEventListener("click", handleButtonClick);
        
       
      };

* Credits 
* Aja helped me a ton on not making things to difficult for myself and just relaxing and taking my code slowly to understand what I am doing better so HUGE SHOUT OUT TO AJA!!!!

