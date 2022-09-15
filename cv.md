# Zaichko Mihail 

## Contact

* Phone: +998900024586
* E-mail: zm91672@gmail.com
* GitHub: Mikhail1JS

## About me

Hello , my name is Mihail. I'm web developer with experience in creating several frontend and backend projects. Moreover currently i work as freelancer. I like study javascript in all its aspects and i aspire to excellence in my profession. I am conscientious, responsive, balanced, considerate and purposeful. My priorities are experience and knowledge.

## Skills

* HTML
* Responsive Design & Mobile-First Websites
* CSS & CSS Preprocessors (Sass, LESS)
* JavaScript (ES6+)
* JS Libraries & Frameworks (JQuery,Vue.js,React)
* Module Bundlers: Gulp, Webpack.
* PHP
* MySQL,sqlite.
* WordPress
* Search Engine Optimization (SEO)
* Productivity (Asana)
* Version Control (Git)

## Code Example

```

class ProductsToCart extends List {
  constructor(url = apis.cartProducts, container = ".item-cart__counter") {
    super(url, container);
  }

  //Add products to cart

  addProduct(element) {
    let itemToAdd = {
      id: element.dataset["id"],
      name: element.dataset["name"],
      price: element.dataset["price"],
      img: element.dataset["img"],
      quantity: 1,
    };

    if (this.goods.contents.find((el) => +el.id === +itemToAdd.id)) {
      this.putJson(apis.updateProd, itemToAdd).then((data) =>
        this.handleData(data)
      );
    } else {
      this.postJson(apis.addProd, itemToAdd).then((data) =>
        this.handleData(data)
      );
    }
  }

  render() {
    let cartCounterBox = document.querySelector(this.container);
    if (this.goods.countGoods > 0) {
      if (!cartCounterBox.classList.contains("active-counter")) {
        cartCounterBox.classList.add("active-counter");
      }
    } else if (this.goods.countGoods <= 0) {
      if (cartCounterBox.classList.contains("active-counter")) {
        cartCounterBox.classList.remove("active-counter");
      }
    }
    cartCounterBox.textContent = this.goods.countGoods;
  }
}

```

## Work Experience

* Freelancer web developer - May 2021 - Present
    + Development, design and layout of sites, branding, optimization and site promotion, implementation of content management system (CMS).
* SEO specialist - Sep 2019 - May 2021.
    + Administration of websites on CMS Wordpress , page layout, interaction with American content exchanges , analysis and selection of keywords , editorial articles.

## Education

* GeekBrains
    + Professional html/css
    + Geekuniversity. Javascript
    + Databases. Basics
    + Basics of PHP

* The 2nd academic lyceum under Tashkent  Institute of textile and  light industry.
    + Foreign philology

## Languages

* **Russian** - native speaker
* **English** - intermediate level
    + i have had a lot of practice when i studied in university in Cyprus , this experience was very useful to me. Add that i had a great practice when i worked as a project manager in Oil company , there were many cases of communication with foreign companies. 





