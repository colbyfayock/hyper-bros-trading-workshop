# 📓 Lesson 05: Integrate Snipcart sitewide

Some websites might limit their stores to a single page or section, but our goal is to expand beyond the homepage with pages for each product.

That means we need to move Snipcart from only being available on the homepage to loading it for every page to have access to.

## Getting Started

In this lesson, we'll learn how to load scripts globally in a Next.js app and wire up our product pages.

While doing so, we'll actually hit a snag! 😱 As the Snipcart installation will have trouble working alongside clientside routing.

So we'll also review why that's happening and how we can resolve that issue with React hooks.

## Objectives
* Move Snipcart installation to a global file
* Add Snipcart to product pages
* Review clientside limitations with Snipcart
* Install useSnipcart from npm
* Review useSnipcart implementation
* Manage global state with useSnipcart

## Exercises

### 1. Move Snipcart to application root document

Because we need to load Snipcart globally, we need to find a place to stick it.

Next.js supports adding a custom \_document.js file, which is a perfect place to add a globally need external script.

#### Goal

Create a custom \_document.js and move the scripts that initalize Snipcart to that file.

#### Where We'll Make Changes
* `src/pages/_document.js`
* `src/pages/index.js`

#### Resources
* [Custom Document - Next.js](https://nextjs.org/docs/advanced-features/custom-document)

### 2. Configure product pages to use Snipcart

Now that we have Snipcart loading globally, we can use it to set up our product pages so that we can additionally allow customers to Add to Cart there.

> Tip: Implementation should look very similar to our homepage!

#### Goal

Configure the product page Add to Cart buttons for Snipcart

#### Where We'll Make Changes
*

#### Resources
*

### 3. Review Snipcart limitations with clientside routing


#### Goal

Understand integration issues with Snipcart and clientside routing in apps

#### Where We'll Make Changes
*

#### Resources
*

### 4. Install useSnipcart React hook from npm


#### Goal

Install npm package use-snipcart

#### Where We'll Make Changes
* Terminal

#### Resources
* [use-snipcart - GitHub](https://github.com/colbyfayock/use-snipcart)

### 5. Use the useSnipcart hook to manage global cart state


#### Goal

Manage Snipcart state globally with the useSnipcart hook

#### Where We'll Make Changes
*

#### Resources
* [use-snipcart - GitHub](https://github.com/colbyfayock/use-snipcart)


## Extra Credit

### 1.


#### Goal



#### Where We'll Make Changes
*

#### Resources
*
