# Monsters vs. Automatons: A Genetic Algorithm Simulation

This project is a fascinating demonstration of a **genetic algorithm** applied to a flocking simulation. It showcases how a population of virtual agents (automatons) can evolve over time to become more adept at a specific task—in this case, surviving against a group of predators (monsters).

The simulation begins with a diverse population of automatons, each with a unique set of behaviors governed by the classic flocking rules:

  * **Separation:** Avoiding crowding with neighbors, mapped by the amount of the automatons blue tone.
  * **Alignment:** Matching the velocity of neighbors, mapped by the amount of the automatons red tone.
  * **Cohesion:** Moving toward the center of the group, mapped by the amount of the automatons green tone.

The automatons that successfully evade the monsters are deemed the "fittest." The next generation is then created by breeding these successful automatons, allowing their traits (the values for separation, alignment, and cohesion) to be passed on and **mutated** for diversity. This process of natural selection and mutation drives the population's evolution, leading to a smarter, more resilient flock.

This project is a strong example of applying machine learning principles to a physical simulation, demonstrating a solid understanding of evolutionary computation and object-oriented design.

-----

## 🛠️ Technologies Used

  * **JavaScript:** The entire simulation logic, from agent movement to the genetic algorithm, is written in vanilla JavaScript, highlighting core programming proficiency.
  * **p5.js**: Used for rendering and manipulation of bodies in the system
  * **HTML5:** Provides the canvas where the simulation is rendered.
  * **CSS3:** Used for any styling of the user interface.

-----

## 🚀 Live Demo
Click the image to give it a try

[![image](https://github.com/user-attachments/assets/66d6f920-1340-4329-80d1-f4693da4daaa)](https://asafdov.github.io/Monsters_vs_Automatons_Genetic_Aglorithm/)

More about it on my website at [Asaf's Laboratory](https://asafslaboratory.com/?p=194)


-----

## 🙏 Acknowledgments

This project is a creative extension of the concepts taught by **[The Coding Train](https://github.com/shiffman/thecodingtrain.com)**, particularly their work on flocking simulations and genetic algorithms. Their educational content was instrumental in the development of this project.
