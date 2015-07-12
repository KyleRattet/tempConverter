Temperature Convertor Write code that asks the user for a temperature in Celsius and converts it to Fahrenheit. Bonus: ask the user first if they want to convert from F to C or C to F.

//var choice = prompt ("Would you like to convert from F to C or C to F?");
{
  if (choice === "F to C") {
    var tempF = prompt ("Enter Fahrenheit temperature to be converted to Celcius");
    alert ("Your Fahrenheit temperature equates to "+((tempF - 32)* (5/9))+"\xB0C");
  }
  else if (choice === "C to F") {
    var tempC = prompt ("Enter Celcius temperature to be converted to Fahrenheit");
    alert ("Your Celcius temperature equates to "+((tempC*(9/5))+32)+"\xB0F");
  }
  else {
    alert ("Incorrect format. Refresh page to try again");
  }
}
