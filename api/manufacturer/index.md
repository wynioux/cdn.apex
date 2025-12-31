---
title: manufacturer
---

# Manufacturer

Total: 74

## List
```
GET /api/manufacturer/list.json
```

### Response Scheme
```json
[
  {
    "id": Int,
    "name": String,
    "region": String,
    "country": String,
    "city": String,
    "logo": {
      "width": Int,
      "height": Int,
      "darkURL": String,
      "lightURL": String
    }
  }
]
```

## Detail
```
GET /api/manufacturer/{id}/detail.json
```

### Response Scheme
```json
{
  "id": Int,
  "name": String,
  "region": String,
  "country": String,
  "city": String,
  "logo": {
    "width": Int,
    "height": Int,
    "darkURL": String,
    "lightURL": String
  },
  "website": String,
  "wikipedia": String
}
```

## Table

| ID | Name | Detail |
|----|------|--------|
| 3 | Alfa Romeo | [JSON](/api/manufacturer/3/detail.json) |
| 4 | Aston Martin | [JSON](/api/manufacturer/4/detail.json) |
| 5 | Audi | [JSON](/api/manufacturer/5/detail.json) |
| 6 | BMW | [JSON](/api/manufacturer/6/detail.json) |
| 7 | Chevrolet | [JSON](/api/manufacturer/7/detail.json) |
| 9 | Citroën | [JSON](/api/manufacturer/9/detail.json) |
| 10 | Daihatsu | [JSON](/api/manufacturer/10/detail.json) |
| 11 | Dodge | [JSON](/api/manufacturer/11/detail.json) |
| 12 | Fiat | [JSON](/api/manufacturer/12/detail.json) |
| 13 | Ford | [JSON](/api/manufacturer/13/detail.json) |
| 15 | Honda | [JSON](/api/manufacturer/15/detail.json) |
| 16 | Hyundai | [JSON](/api/manufacturer/16/detail.json) |
| 17 | Jaguar | [JSON](/api/manufacturer/17/detail.json) |
| 18 | Lancia | [JSON](/api/manufacturer/18/detail.json) |
| 21 | Mazda | [JSON](/api/manufacturer/21/detail.json) |
| 22 | Mercedes-Benz | [JSON](/api/manufacturer/22/detail.json) |
| 25 | Mitsubishi | [JSON](/api/manufacturer/25/detail.json) |
| 28 | Nissan | [JSON](/api/manufacturer/28/detail.json) |
| 30 | Pagani | [JSON](/api/manufacturer/30/detail.json) |
| 32 | Peugeot | [JSON](/api/manufacturer/32/detail.json) |
| 33 | Gran Turismo | [JSON](/api/manufacturer/33/detail.json) |
| 34 | Renault | [JSON](/api/manufacturer/34/detail.json) |
| 35 | RUF | [JSON](/api/manufacturer/35/detail.json) |
| 36 | Shelby | [JSON](/api/manufacturer/36/detail.json) |
| 38 | Subaru | [JSON](/api/manufacturer/38/detail.json) |
| 39 | Suzuki | [JSON](/api/manufacturer/39/detail.json) |
| 43 | Toyota | [JSON](/api/manufacturer/43/detail.json) |
| 44 | TVR | [JSON](/api/manufacturer/44/detail.json) |
| 46 | Volkswagen | [JSON](/api/manufacturer/46/detail.json) |
| 49 | Infiniti | [JSON](/api/manufacturer/49/detail.json) |
| 50 | Lexus | [JSON](/api/manufacturer/50/detail.json) |
| 51 | Mini | [JSON](/api/manufacturer/51/detail.json) |
| 52 | Pontiac | [JSON](/api/manufacturer/52/detail.json) |
| 55 | Plymouth | [JSON](/api/manufacturer/55/detail.json) |
| 57 | Autobianchi | [JSON](/api/manufacturer/57/detail.json) |
| 59 | Amuse | [JSON](/api/manufacturer/59/detail.json) |
| 65 | DMC | [JSON](/api/manufacturer/65/detail.json) |
| 69 | Volvo | [JSON](/api/manufacturer/69/detail.json) |
| 86 | Alpine | [JSON](/api/manufacturer/86/detail.json) |
| 87 | RE Amemiya | [JSON](/api/manufacturer/87/detail.json) |
| 93 | Chaparral | [JSON](/api/manufacturer/93/detail.json) |
| 110 | Ferrari | [JSON](/api/manufacturer/110/detail.json) |
| 112 | Lamborghini | [JSON](/api/manufacturer/112/detail.json) |
| 113 | Bugatti | [JSON](/api/manufacturer/113/detail.json) |
| 116 | Maserati | [JSON](/api/manufacturer/116/detail.json) |
| 117 | McLaren | [JSON](/api/manufacturer/117/detail.json) |
| 119 | Tesla Motors | [JSON](/api/manufacturer/119/detail.json) |
| 121 | KTM | [JSON](/api/manufacturer/121/detail.json) |
| 125 | Abarth | [JSON](/api/manufacturer/125/detail.json) |
| 134 | Zagato | [JSON](/api/manufacturer/134/detail.json) |
| 135 | Italdesign | [JSON](/api/manufacturer/135/detail.json) |
| 136 | Porsche | [JSON](/api/manufacturer/136/detail.json) |
| 140 | De Tomaso | [JSON](/api/manufacturer/140/detail.json) |
| 141 | Radical | [JSON](/api/manufacturer/141/detail.json) |
| 143 | Super Formula | [JSON](/api/manufacturer/143/detail.json) |
| 144 | BAC | [JSON](/api/manufacturer/144/detail.json) |
| 146 | Jeep | [JSON](/api/manufacturer/146/detail.json) |
| 147 | Chris Holstrom Concepts | [JSON](/api/manufacturer/147/detail.json) |
| 148 | Eckert's Rod & Custom Inc. | [JSON](/api/manufacturer/148/detail.json) |
| 149 | GReddy | [JSON](/api/manufacturer/149/detail.json) |
| 150 | Wicked Fabrication | [JSON](/api/manufacturer/150/detail.json) |
| 151 | Roadster Shop | [JSON](/api/manufacturer/151/detail.json) |
| 152 | Genesis | [JSON](/api/manufacturer/152/detail.json) |
| 153 | AMG | [JSON](/api/manufacturer/153/detail.json) |
| 154 | DS Automobiles | [JSON](/api/manufacturer/154/detail.json) |
| 155 | Nismo | [JSON](/api/manufacturer/155/detail.json) |
| 156 | Greening Auto Company | [JSON](/api/manufacturer/156/detail.json) |
| 157 | Garage RCR | [JSON](/api/manufacturer/157/detail.json) |
| 158 | BVLGARI | [JSON](/api/manufacturer/158/detail.json) |
| 159 | Škoda | [JSON](/api/manufacturer/159/detail.json) |
| 160 | AFEELA | [JSON](/api/manufacturer/160/detail.json) |
| 161 | Opel | [JSON](/api/manufacturer/161/detail.json) |
| 162 | Polestar | [JSON](/api/manufacturer/162/detail.json) |
| 163 | Mine's | [JSON](/api/manufacturer/163/detail.json) |
