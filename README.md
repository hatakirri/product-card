# product-card 

My name is hatakiri


![My photo](https://dota2.ru/img/heroes/spirit_breaker/portrait.jpg)

*Example of my code*
```javascript

class Product{
    imgLink;
    productName;
    productPrice;

    constructor(imgLink, productName, productPrice){
        this.imgLink = imgLink;
        this.productName = productName;
        this.productPrice = productPrice;
        const container = document.createElement("div");
        container.innerHTML = `
        <div><img src = "${this.imgLink}">
        <h3>Имя: ${this.productName}</h3>
        <h5>Цена: ${this.productPrice}</h5>
        <button> Купить </button>
        </div>
        `
        document.body.append(container);
    }
}

new Product("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSWfmRp-QOhqBek2fpsHeDvEMItE3WGT9Gibw&usqp=CAU.jpg", "Aizen", "infinity Bucks");
```


