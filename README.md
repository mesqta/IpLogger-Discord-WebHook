## Explanation:
- This repository is only used for study purposes. I do not take responsibility for your actions!

- This HTML and JavaScript code aims to gather information about the user's IP address and send it to a server. I will describe in detail the functions present in the code:

---

- 1 - **get_information(link, callback):**
This function is responsible for making an XMLHttpRequest request to obtain information from a specific link. It accepts two parameters:

- **link**: The URL to which the request is made.
callback: A callback function that will be called when the request response is ready. This function takes one argument, which is the response text.

- 2 - **ipLogByAlv():**
This function is called after a certain time (defined by setTimeout) and is responsible for sending a POST request with some specific information to a determined destination (wbhk). It does not accept any parameters.
---
In addition, there are some DOM (Document Object Model) manipulations to dynamically create HTML elements and add them to the page:

- After receiving the responses from the HTTP requests, the content is inserted into new `<div>` elements that are created dynamically. These elements are then assigned specific IDs: `'alvaroolog'` and `'ip'`.


- Then, these elements are added as children of the element with the class 'header' (an empty `<header>`), which is already present in the HTML page.

The CSS within the `<style>` tag is used to hide elements from the `HTML` page, with the classes .header and `.map-container`, by setting display: none for both, which means they will not be displayed on the page.

---

Add the code however you like, whether you want to implement it in your own project or use this repository as a basis for the project and build upon it.

---

![Exemplo](https://media.discordapp.net/attachments/1155932525366099990/1208356800450011196/image.png?ex=65e2fcf7&is=65d087f7&hm=882636c308419c3e30f0ad173aa9522a648b333dece149e6f76a047143a4d3ef&=&format=webp&quality=lossless&width=408&height=82)