---
chapter: अध्याय २
pageNumber: ११
titleIndex: २.१
---
# टिप्पणीहरू

टिप्पणीहरू (comments) बयानहरू हुन् जसले अन्य प्रोग्रामरहरू वा के कोडले के गर्दछ भनेर सहज बनाउँदछन्।

जाभास्क्रिप्टमा, टिप्पणीहरू २  तरीकाले लेख्न सकिन्छ:

* _एकल रेखा टिप्पणीहरू_: यो दुई फरवार्ड स्ल्याशहरू (`//`) बाट सुरु हुन्छ र रेखाको अन्त्यसम्म जारी रहन्छ। स्ल्याशहरू पछिको कुनै पनि कुरा जाभास्क्रिप्ट इन्तेर्प्रेटरद्वारा उपेक्षा गरिएको छ। उदाहरणका लागि:

```javascript
// This is a comment, it will be ignored by the interpreter
let a = "this is a variable defined in a statement";
```

* बहु-रेखा टिप्पणीहरू: अगाडिको स्लेश र तारांकन (`/*`) बाट सुरु हुन्छ र तारांकन र अगाडिको स्लेश (`*/`) सँग समाप्त हुन्छ। उद्घाटन र समापन मार्करहरू बीचको कुनै पनि कुरा जाभास्क्रिप्ट इन्तेर्प्रेटरद्वारा उपेक्षा गरिएको छ। उदाहरणका लागि:

```javascript
/*
This is a multi-line comment,
it will be ignored by the interpreter
*/
let a = "this is a variable defined in a statement";
```