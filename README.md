# Block-15-Workshop

//Froyo Survey

//Create the customer object
let customer = {
    firstName: "jake",
    lastName: "smith",
    email: "jaekSmih!aol.com",
    phone: undefined,
    zipCode: "631",
    favoriteFlavors: 32,
    cupSize: "medium",
    favoriteStore: "Target",
    firstVisit: false,
};

//Correct mistakes in survey
customer ["email"] = "Jak3Smith1992@email.com";
customer ["phone"] = 3195551234;
customer ["zipCode"] = "63132";
customer ["favoriteFlavors"] = ["coffee", "strawberry", "matcha"];

//Remove properties from survey
delete customer ["zipCode"];
delete customer ["favoriteStore"];

//Add new items to the survey using dot notation
customer.toppings = ['chocolate sprinkles, "wafer straws", "gummy bears'];
customer.futureFlavors = ["mango"];
customer.todaysPurchaseCost = 5.32;

//Print keys in survey
const surveyKeys = Object.keys(customer);
console.log(surveyKeys);
