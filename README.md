<h1>PDF-AccessiblePDF</h1>
<h2>AccessiblePDF Example Project</h2>
<p>This project demonstrates how to tag a PDF and make it accessible. The methods used are based around Section 508 compliance and the PDF/UA standard. </p>
<p>The basis of this project is the use of the <a href="../8-abcpdf.operations/C-accessibilityoperation/1-methods/makeaccessible.htm">AccessibilityOperation and the MakeAccessible method.</a> You can read more about  these  and the types of information that is added,  under the documentation for those methods.</p>
<p>However a one function method  can only ever achieve so much in the context of complicated and semantically ambiguous documents. For example the reading order of any complex document is likely to vary between people - there is no absolutely correct answer. ABCpdf will come up with a reasonable method but it may not be the one you want.</p>
<p>The AccessiblePDF project shows how to use  knowledge of your documents to take the base data and enhance it. It shows how to detect and insert structure based on your understanding   of the document and supports the following structure types.</p>
<ul>
  <li>Headers and Footers</li>
  <li>Tables</li>
  <li>Lists</li>
  <li>Sections</li>
  <li>Artifacts</li>
</ul>
<p>It shows how to use the tags in a PDF document to detect and change content within it. This includes some code relevant to eSignLive signatures.</p>
<p>It contains code to show how to add content and tags to an already tagged document, merging these tags with the existing structure in the style of the base document.</p>
<p>Usefully it provides a method of extracting the tagged structure of any PDF document to an HTML-like format you can  easily examine.</p>
<p><em>The ABCpdf Team</em></p>
