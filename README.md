# Learning-projects
Projects I am learning from Codecademy
Kelvin Weather
Deep in his mountain-side meteorology lab, the mad scientist Kelvin has mastered weather prediction.Recently, Kelvin began publishing his weather forecasts on his website. However there’s a problem: All of his forecasts describe the temperature in Kelvin.With our knowledge of JavaScript, let’s convert Kelvin to Celsius, then to Fahrenheit.

const kelvin = 0;
console.log("If Kelvin is " + kelvin);
//we are setting the constant value for kelvin which is equal to 293

const celsius = kelvin - 273;
console.log("Celsius is " + celsius)
//celsius is 273 degree less than kelvin

let fahrenheit = celsius * (9/5) + 32;
fahrenheit = Math.floor(fahrenheit);
console.log("Fahrenheit is "+ fahrenheit)
//adding the formula to convert Celsius into Fahrenheit and then changing it to ground floor

console.log("The temperature is " + fahrenheit + " degrees fahrenheit"+ ".")

let newton = celsius * (33/100);
newton = Math.floor(newton);
console.log("The temperature is " + newton + " degrees Newton")




