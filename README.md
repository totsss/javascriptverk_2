# javascriptverk_2
1.
let toti = { 
nafn:'þórður',
heimasimi:5812345,
gsm:7878042
};
console.log(toti)

#utkomma {nafn: "þórður", heimasimi: 5812345, gsm: 7878042}

-----------------------------

2.console.log(family.parents.fathers[1])
#utkomma {name: "Nonni"}

-----------------------------

3.

breakfast= {
    name:"The Lumberjack",
    price:9.95,
    ingredients:["eggs","sausage","toast","hashbrowns","pancakes"]
};
console.log(breakfast)

-----------------------------

4.var savingsAccount = {
  balance: 1000,
  interestRatePercent: 1,
  deposit: function addMoney(amount) {
    if (amount > 0) {
      savingsAccount.balance += amount;
    }
  },
  
  withdraw: function removeMoney(amount) {
    var verifyBalance = savingsAccount.balance - amount;
    if (amount > 0 && verifyBalance >= 0) {
      savingsAccount.balance -= amount;
    }
  },
  printAccountSummary() {
   "Welcome!\nYour balance is currently $"+savingsAccount.balance+" and your interest rate is "+ savingsAccount.interestRatePercent+"%."; 
  },
}; 

console.log(savingsAccount.printAccountSummary());
donuts.forEach(function(donuts) {
  console.log(donuts.type +" donuts cost $"+ donuts.cost + " each");
});

-----------------------------

5.var donuts = [
    { type: "Jelly", cost: 1.22 },
    { type: "Chocolate", cost: 2.45 },
    { type: "Cider", cost: 1.59 },
    { type: "Boston Cream", cost: 5.99 }
];

donuts.forEach(function(donuts) {
  console.log(donuts.type +" donuts cost $"+ donuts.cost + " each");
});

-----------------------------

6.function Pizza (staerd, alegg,verd) {
        this.staerd = staerd;
        this.alegg = alegg;
        this.verd = verd;
        this.getPizzaDetails = function() {
            return (pizza.staerd + 'hefur : ' + pizza.alegg.toString()+' kostnaður :' + pizza.verd + 'kr.');
        }
  }
    pizza = new Pizza('stór',['ostur','hakk','skinka'],2100);
    pizza2 = new Pizza('lítil',['ostur','annanas','skinka'],1200);
    console.log(pizza);
    console.log(pizza2);
