---
id: 587d7b90367417b2b2512b65
title: Return Part of an Array Using the slice Method
challengeType: 1
videoUrl: ''
localeTitle: عودة جزء من صفيف باستخدام طريقة شريحة
---

## Description
<section id="description"> ترجع طريقة <code>slice</code> نسخة من عناصر معينة لصفيف. يمكن أن يستغرق الأمر اثنين من الحجج ، الأول يعطي مؤشر من أين تبدأ شريحة ، والثاني هو مؤشر لمكان إنهاء الشريحة (وهو غير شامل). إذا لم يتم توفير الوسيطات ، فسيكون الإعداد الافتراضي هو البدء في بداية المصفوفة حتى النهاية ، وهي طريقة سهلة لعمل نسخة من الصفيف بأكمله. لا تقوم طريقة <code>slice</code> بتحويل الصفيف الأصلي ، بل تقوم بإرجاع واحدة جديدة. إليك مثال على ذلك: <blockquote style=";text-align:right;direction:rtl"> var arr = [&quot;Cat&quot;، &quot;Dog&quot;، &quot;Tiger&quot;، &quot;Zebra&quot;]؛ <br> var newArray = arr.slice (1، 3)؛ <br> // يعين NewArray to [&quot;Dog&quot;، &quot;Tiger&quot;] </blockquote></section>

## Instructions
undefined

## Tests
<section id='tests'>

```yml
tests:
  - text: يجب أن تستخدم شفرتك طريقة <code>slice</code> .
    testString: 'assert(code.match(/\.slice/g), "Your code should use the <code>slice</code> method.");'
  - text: ''
    testString: 'assert(JSON.stringify(inputAnim) === JSON.stringify(["Cat", "Dog", "Tiger", "Zebra", "Ant"]), "The <code>inputAnim</code> variable should not change.");'
  - text: ''
    testString: 'assert(JSON.stringify(sliceArray(["Cat", "Dog", "Tiger", "Zebra", "Ant"], 1, 3)) === JSON.stringify(["Dog", "Tiger"]), "<code>sliceArray(["Cat", "Dog", "Tiger", "Zebra", "Ant"], 1, 3)</code> should return <code>["Dog", "Tiger"]</code>.");'
  - text: '<code>sliceArray([&quot;Cat&quot;, &quot;Dog&quot;, &quot;Tiger&quot;, &quot;Zebra&quot;, &quot;Ant&quot;], 0, 1)</code> يجب أن تعود <code>[&quot;Cat&quot;]</code> .'
    testString: 'assert(JSON.stringify(sliceArray(["Cat", "Dog", "Tiger", "Zebra", "Ant"], 0, 1)) === JSON.stringify(["Cat"]), "<code>sliceArray(["Cat", "Dog", "Tiger", "Zebra", "Ant"], 0, 1)</code> should return <code>["Cat"]</code>.");'
  - text: '<code>sliceArray([&quot;Cat&quot;, &quot;Dog&quot;, &quot;Tiger&quot;, &quot;Zebra&quot;, &quot;Ant&quot;], 1, 4)</code> يجب أن تعود <code>[&quot;Dog&quot;, &quot;Tiger&quot;, &quot;Zebra&quot;]</code> .'
    testString: 'assert(JSON.stringify(sliceArray(["Cat", "Dog", "Tiger", "Zebra", "Ant"], 1, 4)) === JSON.stringify(["Dog", "Tiger", "Zebra"]), "<code>sliceArray(["Cat", "Dog", "Tiger", "Zebra", "Ant"], 1, 4)</code> should return <code>["Dog", "Tiger", "Zebra"]</code>.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function sliceArray(anim, beginSlice, endSlice) {
  // Add your code below this line


  // Add your code above this line
}
var inputAnim = ["Cat", "Dog", "Tiger", "Zebra", "Ant"];
sliceArray(inputAnim, 1, 3);

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
