# javascriptverk_2
1.
let toti = { 
nafn:'þórður',
heimasimi:5812345,
gsm:7878042
};
console.log(toti)

#utkomma {nafn: "þórður", heimasimi: 5812345, gsm: 7878042}

2.console.log(family.parents.fathers[1])
#utkomma {name: "Nonni"}

3.

var pizza = [
    { type: "Stór", alegg: "Ostur og skinka", cost: 1500 },
    { type: "Lítl", alegg: "Hakk og Lauk" , cost: 1200 },
    
];

pizza.forEach(function(pizza) {
    console.log(pizza.type +" með " + pizza.alegg +" kostar "+ pizza.cost  );
});
