var ref = new Firebase('https://tutorialsfirebase.firebaseio.com');

var playersRef = ref.child("players");
playersRef.push ({
   name: "John",
   number: 1,
   age: 30
});

playersRef.push ({
   name: "Amanda",
   number: 2,
   age: 20
});
