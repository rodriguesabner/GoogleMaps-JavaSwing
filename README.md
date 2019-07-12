# Google Maps Java (Swing)

Integration of Java Swing + Javascript + Google Maps.

Video: https://www.youtube.com/watch?v=hNrCp675A_I

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Java 1.8 >
Google Maps Javascript API
```

## Running the tests

You need a Google Maps Javascript API, 
to get one, visit the site: https://developers.google.com/maps/documentation/javascript/tutorial.

In the project there is a folder called: ```HTMLGMaps```, inside it there is a file called: ```simple_map.html```. 
Open this file and change this: ```<YOUR_API_KEY>```, by your key you have created.

Move ```HTMLGMaps``` to ```C:/```

This is the secret for you to search on Google Maps using Java:

        DOMDocument doc = browser.getDocument();

        DOMElement address_element = doc.findElement(By.id("address"));
        DOMElement search_element = doc.findElement(By.id("submit"));
        DOMElement button = (DOMElement) search_element;

        DOMInputElement address = (DOMInputElement) address_element;
        address.setValue(jTextField1.getText());

        button.click();

## Built With

* [Google Maps](https://developers.google.com/maps/documentation/javascript/examples/map-simple?hl=pt-br) - API Javascript
* [JXBrowser](https://jxbrowser-support.teamdev.com/release-notes/2018/v6-22.html) - JXBrowser V6.22
* [Netbeans](https://netbeans.org/) - Netbeans

## Authors

* **Abner Rodrigues** - *Initial work* - [kingaspx](https://github.com/kingaspx)

## Screenshots
![image](https://user-images.githubusercontent.com/40338524/61163037-0ed64b80-a4e2-11e9-9028-05c9fd042acb.png)

![image](https://user-images.githubusercontent.com/40338524/61163045-1dbcfe00-a4e2-11e9-8c81-d186c76c3441.png)

![image](https://user-images.githubusercontent.com/40338524/61163049-2ca3b080-a4e2-11e9-84e5-0e93e05d5c8b.png)

StreetView
![image](https://user-images.githubusercontent.com/40338524/61163116-8dcb8400-a4e2-11e9-9cde-5b0f98f9e29c.png)
