##Daily Journal

April 14th

<b>In simple terms what is a sub-document?</b>

A document nested within another document.

<b>When might you use a sub-document?</b>

You would want to use subdocmunets when you have an object (or objects) that is related to the main object. For example, If you were to create a character, the character becomes the parent object and their skills become the child object. Each child object accesses the main parent object.

<b>How do you add to a collection of sub-documents? What about editing them?</b>

You pass the nested object into a new Model and add properties onto the document, or you create the document first and edit the document to include sub-documents.