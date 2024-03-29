 🚀 LEARN CSS "POSITION" PROPERTY 

# POSITION AT A GLANCE: ![Alt Text](https://cdn.hashnode.com/res/hashnode/image/upload/v1622462308884/fwFzqxheC.png?auto=compress,format&format=webp)

## 1️⃣ POSITION: STATIC  
![Alt Text](https://miro.medium.com/v2/resize:fit:640/format:webp/1*CWx27jdXYYrxBvWfNY_HBA.png)
  - This is the default value.
   - Elements are positioned according to the normal flow of the document.
   - The `top`, `right`, `bottom`, `left`, and `z-index` properties have no effect.

## 2️⃣ POSITION: RELATIVE 
![Alt Text](https://miro.medium.com/v2/resize:fit:640/format:webp/1*JdTu1O7EZUOF0h2J0h6Cdw.png)
- Elements are positioned relative to their normal position in the document flow.
- Setting `top`, `right`, `bottom`, or `left` will move the element from its original position, but the space it originally occupied remains.
- Other elements are not affected by the position of the element.

## 3️⃣ POSITION: ABSOLUTE
![Alt Text](https://miro.medium.com/v2/resize:fit:640/format:webp/1*iH6AbKAKvOBMWysijVCUpw.png)
   - Elements are removed from the normal document flow.
   - Positioned relative to the nearest positioned ancestor (an ancestor with a `position` other than `static`) or to the initial containing block if no positioned ancestor is found.
   - Does not leave a gap in the layout where it would normally have been positioned.

## 4️⃣ POSITION: FIXED 
![Alt Text](https://miro.medium.com/v2/resize:fit:640/format:webp/1*kBHiFgVKn298bovAyZF8eg.png)
 - Similar to `absolute`, but positioned relative to the initial containing block established by the viewport.
- The element remains fixed in its position even when the page is scrolled.

## 5️⃣ POSITION: STICKY
![Alt Text](https://raw.githubusercontent.com/filamentgroup/fixed-sticky/HEAD/demos/gifs/sticky-top-on.gif)
   - Acts like `relative` within its parent container, until a specified offset threshold is met.
   - Then it behaves like `fixed`, remaining in place within the viewport as the user scrolls.

## ✅ Understanding and utilizing these `position` property values allows for precise control over the layout and positioning of elements on a webpage, enabling you to create complex and dynamic layouts.
