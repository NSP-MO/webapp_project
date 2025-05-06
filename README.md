# RPL Project
## Progress

## Preview Homepage-User
![Preview](https://drive.google.com/uc?id=1n-Z93BAMVkHutM41Wa6QjBpAF3nvp_NG)

## Preview Dashboard-Admin
![Preview](https://drive.google.com/uc?id=1bOl0yZI1DH8PY251BBeVL2MsnNEqwf02)

## Instalisasi
Buat directorynya (namanya bebas) :
```sh
mkdir rplproject
cd rplproject
```

Install packagenya :
```sh
npm init
npm i projectrpl
```

Edit script di package.json :
![Preview](https://drive.google.com/uc?id=16Y_UKNSIOIGaKUxZFebo4REozlJY1T43)

"scripts": {

    "setup": "evershop install",
    "build": "evershop build",
    "start": "evershop start",
    "start:debug": "evershop start --debug",
    "dev": "evershop dev",
    "user:create": "evershop user:create",
    "user:changePassword": "evershop user:changePassword"
},

Jalanan setup :
```sh
npm run setup
```

Jalanin program :
```sh
npm run dev
```


