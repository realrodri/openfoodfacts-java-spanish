# PLEASE REFFER TO https://github.com/openfoodfacts/openfoodfacts-java FOR LATEST VERSION (not Spanish one)

# Java Wrapper for OpenFoodFacts

##### Java (Maven) wrapper for https://world.openfoodfacts.org

## Current version 0.9.3

## Usage

- Download the .jar on the Releases tab and add it to your modules dependencies.
- Be sure to use Maven for the compiling engine. Otherwise, compatibility is not guaranteed.

## Advisory
The method .getIngredients() has been overwritten to always return the Spanish variation of the ingredients. If you want the English ones, just use the original repository, dependencies and .jar, but if you ONLY want Spanish ingredients, check Release tab to download the jar.
