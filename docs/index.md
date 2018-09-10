<html>
<head>
  <title>Serena Cutler Art</title>
</head>
<body>
  <h1>Serena Cutler Art</h1>
  <div id='product-component-d14dd423295'></div>
<script type="text/javascript">
/*<![CDATA[*/

(function () {
  var scriptURL = 'https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js';
  if (window.ShopifyBuy) {
    if (window.ShopifyBuy.UI) {
      ShopifyBuyInit();
    } else {
      loadScript();
    }
  } else {
    loadScript();
  }

  function loadScript() {
    var script = document.createElement('script');
    script.async = true;
    script.src = scriptURL;
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(script);
    script.onload = ShopifyBuyInit;
  }

  function ShopifyBuyInit() {
    var client = ShopifyBuy.buildClient({
      domain: 'serena-cutler-art.myshopify.com',
      storefrontAccessToken: 'ede31e934cdd2f52521c40ef6443cea8',
    });

    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('product', {
        id: [1513287909443],
        node: document.getElementById('product-component-d14dd423295'),
        moneyFormat: '%C2%A3%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "layout": "horizontal",
    "variantId": "all",
    "width": "100%",
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "variantTitle": false,
      "description": true,
      "buttonWithQuantity": false,
      "quantity": false
    },
    "styles": {
      "product": {
        "text-align": "left",
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0",
          "margin-bottom": "50px"
        },
        "carousel-button": {
          "display": "block"
        }
      },
      "button": {
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal"
      },
      "variantTitle": {
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal"
      },
      "title": {
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal",
        "font-size": "26px"
      },
      "description": {
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal"
      },
      "price": {
        "font-family": "Raleway, sans-serif",
        "font-size": "18px",
        "font-weight": "normal"
      },
      "compareAt": {
        "font-size": "15px",
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal"
      }
    },
    "googleFonts": [
      "Raleway",
      "Raleway",
      "Raleway",
      "Raleway",
      "Raleway",
      "Raleway"
    ]
  },
  "cart": {
    "contents": {
      "button": true
    },
    "styles": {
      "button": {
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal"
      },
      "footer": {
        "background-color": "#ffffff"
      }
    },
    "googleFonts": [
      "Raleway"
    ]
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "variantTitle": false,
      "buttonWithQuantity": true,
      "button": false,
      "quantity": false
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      },
      "button": {
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal"
      },
      "variantTitle": {
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal"
      },
      "title": {
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal"
      },
      "description": {
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal"
      },
      "price": {
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal"
      },
      "compareAt": {
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal"
      }
    },
    "googleFonts": [
      "Raleway",
      "Raleway",
      "Raleway",
      "Raleway",
      "Raleway",
      "Raleway"
    ]
  },
  "toggle": {
    "styles": {
      "toggle": {
        "font-family": "Raleway, sans-serif",
        "font-weight": "normal"
      }
    },
    "googleFonts": [
      "Raleway"
    ]
  },
  "option": {
    "styles": {
      "label": {
        "font-family": "Raleway, sans-serif"
      },
      "select": {
        "font-family": "Raleway, sans-serif"
      }
    },
    "googleFonts": [
      "Raleway",
      "Raleway"
    ]
  },
  "productSet": {
    "styles": {
      "products": {
        "@media (min-width: 601px)": {
          "margin-left": "-20px"
        }
      }
    }
  }
}
      });
    });
  }
})();
/*]]>*/
</script>
</body>
</html>
