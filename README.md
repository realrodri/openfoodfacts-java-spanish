# PLEASE REFFER TO https://github.com/openfoodfacts/openfoodfacts-java FOR LATEST VERSION (not Spanish one)

# Java Wrapper for OpenFoodFacts

##### Java (Maven) wrapper for https://world.openfoodfacts.org

## Current version 0.9.3

## Usage

Add one dependency to your POM file:

```xml
<dependencies>
    <dependency>
        <groupId>pl.coderion</groupId>
        <artifactId>openfoodfacts-java-wrapper</artifactId>
        <version>0.9.3</version>
    </dependency>
</dependencies>
```

Create wrapper object and find product by its barcode:

```javascript
OpenFoodFactsWrapper wrapper = new OpenFoodFactsWrapperImpl();
ProductResponse productResponse = wrapper.fetchProductByCode("737628064502");
```

## Demo
Check also [Demo application](https://github.com/openfoodfacts/openfoodfacts-java-demo) how to do it.

## Advisory
The method .getIngredients() has been overwritten to always return the Spanish variation of the ingredients. If you want the English ones, just use the original repository, dependencies and .jar, but if you ONLY want Spanish ingredients, check Release tab to download the jar.
