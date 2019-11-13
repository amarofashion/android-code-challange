# Amaro Android Code Challenge

## About the challenge
This is a code challenge of 7 days duration. Please read all the instructions carefully.

## Setup
Before starting make sure to setup and run our [pairing API code](https://github.com/amarofashion/android-pairing-api)

## Requirements
- Must use: 
1. An architecture pattern
2. Kotlin

- Must have at least:
1. One unit test
2. One integration test

## Description
Our pairing API delivers a GuideShop CRUD, in AMARO app this CRUD is used in two differents [scenarios](https://imgur.com/a/gNqT2yN): 
1. BottomNavigationBar, display GuideShops with information purpose
2. Checkout, allow GuideShop pickup

That said the Challenge consist in the development of a component that will be used in these two different scenarios, each scenario have some particularities:
1. BottomNavigationBar: Display only GuideShop name and address, does not have a click action
2. Checkout: Besides the GuideShop name and address also display the distance between the GuideShop and client, notice that our backend team was not able to deliver this information, so it'll be calculate in app side.

*ps: The component may or may not have a custom header and footer, based on each scenario.

[Scenarios](https://imgur.com/a/gNqT2yN)
