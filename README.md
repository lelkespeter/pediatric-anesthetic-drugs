On start screen display a grid of drug categories i a grid. 
If I press on a category I navigate to a screen where I get a list (with FlatList ) of drug where drugName === catId
Then if I press on a drugName I get selectedDrugs which I then output  in another FlatList data={selectedDrugs}

I use Max's Meal App as a basis


LMCategory = [
  {
    catId: "c1",
    catName: "Premedicering",
  },
//.... to catId: 'c8'
]


 DRUGS = [
  {
    drugId: "m1",
    catId: ["c7"],
    drugName: "Klonidin",
    styrka: "15 µg/ml",
    recept: "1 ml catapressan 150 µg/ml + 9 ml NaCl",
    dosIµG: 1,
    obs: "barn > 1 år",
  },
//to drugId: 'm33'
]
