# 2.1 Heading Element

## Ülevaade
Selles õpituses käsitletakse HTML päiselementide (`<h1>`, `<h2>`, `<h3>`, `<h4>`) kasutamist dokumendi struktuuri loomisel. Iga päisetaseme element tähistab erinevat hierarhiataset, mis aitab veebilehe sisu selgelt jaotada ja paremini mõista nii kasutajatele kui ka otsingumootoritele.

## Koodi struktuur
Näide failis `index.html`:

```html
<h1>Book</h1>
<h2>Chapter 1</h2>
  <h3>Section 1</h3>
  <h3>Section 2</h3>
<h2>Chapter 2</h2>
  <h3>Section 1</h3>
    <h4>Diagram 1</h4>
<h2>Chapter 3</h2>
  <h3>Section 1</h3>
  <h3>Section 2</h3>

  <h1> - Esimese taseme päis, kasutatakse kogu dokumendi või lehe peamise pealkirja jaoks. Antud näites esindab see raamatu pealkirja "Book".
<h2> - Teise taseme päis, kasutatakse peatükkide jaoks (Chapter 1, Chapter 2, Chapter 3).
<h3> - Kolmanda taseme päis, kasutatakse alajaotiste jaoks (Section 1, Section 2).
<h4> - Neljanda taseme päis, kasutatakse diagrammi või muu spetsiifilise sisu tähistamiseks.

## Kasutamine
Ava index.html fail veebibrauseris, et näha, kuidas päiselemendid visuaalselt hierarhiat loovad.
Koodi saab kasutada näitena, kuidas HTML-is struktuuri loomisel hierarhiliselt õigeid päiselemente rakendada.

## Miks see on oluline ?
Päiselemendid on olulised nii visuaalse struktuuri kui ka veebilehe semantika jaoks. Need aitavad:

Kasutajatel veebilehe sisu kergemini mõista.
Otsingumootoritel (näiteks Google) leida ja mõista lehe olulisi osasid, parandades SEO-d.

## Täiendavad märkused
Päiselementide kasutamisel on oluline hoida hierarhia loogilisena, alustades <h1> elemendist ja minnes järjest väiksemate pealkirjade suunas.
Iga leht peaks sisaldama ainult ühte <h1> elementi, mis tähistab lehe või dokumendi peamist teemat või pealkirja.


# 2.1 Heading Element

## Overview
In this tutorial, we will cover the use of HTML heading elements (`<h1>`, `<h2>`, `<h3>`, `<h4>`) for structuring a document. Each heading level represents a different hierarchy, which helps to clearly organize the content of a webpage, making it easier to understand for both users and search engines.

## Code Structure
Example in the `index.html` file:

```html
<h1>Book</h1>
<h2>Chapter 1</h2>
  <h3>Section 1</h3>
  <h3>Section 2</h3>
<h2>Chapter 2</h2>
  <h3>Section 1</h3>
    <h4>Diagram 1</h4>
<h2>Chapter 3</h2>
  <h3>Section 1</h3>
  <h3>Section 2</h3>

<h1> - First-level heading, used for the main title of the document or page. In this example, it represents the title of the book "Book".
<h2> - Second-level heading, used for chapters (Chapter 1, Chapter 2, Chapter 3).
<h3> - Third-level heading, used for subsections (Section 1, Section 2).
<h4> - Fourth-level heading, used for specific content like a diagram (Diagram 1).

## Usage
Open the index.html file in a web browser to see how heading elements visually create a hierarchy.
This code demonstrates how to properly use heading elements to create structure in HTML.

## Why is this important?
Heading elements are crucial for both the visual structure and the semantics of a webpage. They help:

Users understand the content more easily.
Search engines (such as Google) find and understand the important parts of the page, improving SEO.

## Additional Notes
When using heading elements, it's important to maintain a logical hierarchy, starting with the <h1> element and progressively moving to smaller headings.
Every page should only contain one <h1> element, representing the main theme or title of the page.

