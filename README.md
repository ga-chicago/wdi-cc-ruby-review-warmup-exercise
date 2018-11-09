## Ruby warmup exercise

Given the following nested collection:

```
pokemon =
[
  {
    name: "Bulbasaur",
    national_id: 1,
    sp_atk: 65,
    sp_def: 65,
    species: "seed pokemon",
    speed: 45,
    types: {
      type_a: "grass",
      type_b: "poison"
    },
    weight: "15.2lbs"
  },
  {
    name: "Charmander",
    national_id: 4,
    pkdx_id: 4,
    sp_atk: 60,
    sp_def: 50,
    species: "flammable pokemon",
    speed: 65,
    types: {
      type_a: "fire",
      type_b: "lizard"
    },
    weight: "85lbs"
  },
  {
    name: "Squirtle",
    national_id: 7,
    pkdx_id: 7,
    sp_atk: 50,
    sp_def: 64,
    species: "water pokemon",
    speed: 43,
    types: {
      type_a: "water",
      type_b: "turtle"
    },
    weight: "90lbs"
  }
]
```

> Write a program that will return a string with the following information:
- The name of each Pokemon and it's ID number separated by a `|`
- The species with every word capitalized and the weight separated by a `|`
- The types separated by a `//`

**Example**:

```bash
Bulbasaur | 1
Species: Seed Pokemon | Weight: 15.2lbs
Types: grass // poison
```
