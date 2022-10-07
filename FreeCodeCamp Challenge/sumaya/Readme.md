# -Filan-FreeCodeCaomp-Challenge
FreeCodeCamp Challenge  Responsive Web  learn html by creating cat photo

Khulaaso


Add a button as the last element of your form element with a type of submit, and "Submit" as its text.-->
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>
  
  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
  
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <input type="text" placeholder="cat photo URL">
    <button type="submit">Submit</button>
  </form>
</main>
AddImagesToYourWebside.html
<!--You can add images to your website by using the img element, and point to a specific image's URL using the src attribute.
An example of this would be:
<img src="https://www.your-image-source.com/your-image.jpg">
Note that img elements are self-closing.
All img elements must have an alt attribute. The text inside an alt attribute is used for screen readers to improve accessibility and is displayed if the image fails to load.
Note: If the image is purely decorative, using an empty alt attribute is a best practice.
Ideally the alt attribute should not contain special characters unless needed.
Let's add an alt attribute to our img example above:
<img src="https://www.your-image-source.com/your-image.jpg" alt="Author standing on a beach with two thumbs up.">
TASK:
Let's try to add an image to our website:
Insert an img tag, before the h2 element.
Now set the src attribute so that it points to this url:
https://bit.ly/fcc-relaxing-cat
Finally don't forget to give your image an alt text.-->

<img src="https://bit.ly/fcc-relaxing-cat" alt="cat">
<h2>CatPhotoApp</h2>
<main>
  
  
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
AddPlaceholderTextToATextField.html
<!--Add Placeholder Text to a Text Field
Placeholder text is what is displayed in your input element before your user has inputted anything.
You can create placeholder text like so:
<input type="text" placeholder="this is placeholder text">
TASK:
Set the placeholder value of your text input to "cat photo URL".-->
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>
  
  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
  
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <input type="text" placeholder="cat photo URL">
</main>
CheckRadioButtonsAndCheckboxesByDefault.html
<!--Check Radio Buttons and Checkboxes by Default
You can set a checkbox or radio button to be checked by default using the checked attribute.
To do this, just add the word "checked" to the inside of an input element. For example:
<input type="radio" name="test-name" checked>
TASK:
Set the first of your radio buttons and the first of your checkboxes to both be checked by default.-->
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>
  
  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
  
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <label><input type="radio" name="indoor-outdoor" checked> Indoor</label>
    <label><input type="radio" name="indoor-outdoor"> Outdoor</label><br>
    <label><input type="checkbox" name="personality" checked> Loving</label>
    <label><input type="checkbox" name="personality"> Lazy</label>
    <label><input type="checkbox" name="personality"> Energetic</label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>
CommentOut.html
<!--Comment out your h1 element and your p element, but not your h2 element.-->
<!--
<h1>Hello World</h1>
-->
<h2>CatPhotoApp</h2>
<!--
<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
-->
CreateABulletedUnorderedList.html
<!--Create a Bulleted Unordered List
HTML has a special element for creating unordered lists, or bullet point style lists.
Unordered lists start with an opening <ul> element, followed by any number of <li> elements. Finally, unordered lists close with a </ul>
For example:
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
would create a bullet point style list of "milk" and "cheese".
Remove the last two p elements and create an unordered list of three things that cats love at the bottom of the page.-->
<h2>CatPhotoApp</h2>
<main>
 <!-- <p>Click here to view more <a href="#">cat photos</a>.</p>
  
  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
  
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
 -->
  <ul>
        <li>Milk</li>
        <li>Mouse</li>
        <li>Play</li>
      </ul>
</main>
CreateAFormElement.html
<form action="/submit-cat-photo">
    <input type="text" placeholder="cat photo URL">
</form>
CreateAnOrderedList.html
<!--Create an Ordered List
HTML has another special element for creating ordered lists, or numbered lists.
Ordered lists start with an opening <ol> element, followed by any number of <li> elements. Finally, ordered lists close with a </ol>
For example:
<ol>
  <li>Garfield</li>
  <li>Sylvester</li>
</ol>
would create a numbered list of "Garfield" and "Sylvester".
Create an ordered list of the top 3 things cats hate the most.-->
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>
  
  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
  
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
      <li>Dogs</li>
      <li>Water</li>
      <li>Cars</li>
  </ol>
  
</main>
CreateASetOfCheckbox.html
<label for="1"><input id="1" type="checkbox" name="personality"> 1</label>
    <label for="2"><input id="2" type="checkbox" name="personality"> 2</label>
    <label for="3"><input id="3" type="checkbox" name="personality"> 3</label>
CreateASetOfRadioButtons.html
<!--Create a Set of Radio Buttons
You can use radio buttons for questions where you want the user to only give you one answer out of multiple options.
Radio buttons are a type of input.
Each of your radio buttons can be nested within its own label element. By wrapping an input element inside of a label element it will automatically associate the radio button input with the label element surrounding it.
All related radio buttons should have the same name attribute to create a radio button group. By creating a radio group, selecting any single radio button will automatically deselect the other buttons within the same group ensuring only one answer is provided by the user.
Here's an example of a radio button:
<label> 
  <input type="radio" name="indoor-outdoor">Indoor 
</label>
It is considered best practice to set a for attribute on the label element, with a value that matches the value of the id attribute of the input element. This allows assistive technologies to create a linked relationship between the label and the child input element. For example:
<label for="indoor"> 
  <input id="indoor" type="radio" name="indoor-outdoor">Indoor 
</label>
TASK:
Add a pair of radio buttons to your form, each nested in its own label element. One should have the option of indoor and the other should have the option of outdoor. Both should share the name attribute of indoor-outdoor to create a radio group.-->
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>
  
  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
  
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
    <label for="indoor">
       <input id="indoor" type="radio" name="indoor-outdoor">Indoor
    </label>
    <label for="outdoor">
       <input id="outdoor" type="radio" name="indoor-outdoor">Outdoor
    </label>
  </form>
</main>
CreateATextField.html
<!--Create a Text Field
Now let's create a web form.
Input elements are a convenient way to get input from your user.
You can create a text input like this:
<input type="text">
Note that input elements are self-closing.
Create an input element of type text below your lists.-->
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>
  
  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
  
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <input type="text"> 
  
</main>
DeclareTheDoctypeOfAnHTMLDocument.html
<!--Declare the Doctype of an HTML Document
The challenges so far have covered specific HTML elements and their uses. However, there are a few elements that give overall structure to your page, and should be included in every HTML document.
At the top of your document, you need to tell the browser which version of HTML your page is using. HTML is an evolving language, and is updated regularly. Most major browsers support the latest specification, which is HTML5. However, older web pages may use previous versions of the language.
You tell the browser this information by adding the <!DOCTYPE ...> tag on the first line, where the "..." part is the version of HTML. For HTML5, you use <!DOCTYPE html>.
The ! and uppercase DOCTYPE is important, especially for older browsers. The html is not case sensitive.
Next, the rest of your HTML code needs to be wrapped in html tags. The opening <html> goes directly below the <!DOCTYPE html> line, and the closing </html> goes at the end of the page.
Here's an example of the page structure:
Add a DOCTYPE tag for HTML5 to the top of the blank HTML document in the code editor. Under it, add opening and closing html tags, which wrap around an h1 element. The heading can include any text.-->

<!DOCTYPE html>
<html>
  <h1></h1>
</html>
DefineTheHeadAndBodyOfAnHTMLDocument.html
<!--Define the Head and Body of an HTML Document
You can add another level of organization in your HTML document within the html tags with the head and body elements. Any markup with information about your page would go into the head tag. Then any markup with the content of the page (what displays for a user) would go into the body tag.
Metadata elements, such as link, meta, title, and style, typically go inside the head element.
Here's an example of a page's layout:
Edit the markup so there's a head and a body. The head element should only include the title, and the body element should only include the h1 and p.-->
<!DOCTYPE html>
<html>
    <head>
            <title>The best page ever</title>
    </head>
  
  <body>
        <h1>The best page ever</h1>
        <p>Cat ipsum dolor sit amet, jump launch to pounce upon little yarn mouse, bare fangs at toy run hide in litter box until treats are fed. Go into a room to decide you didn't want to be in there anyway. I like big cats and i can not lie kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Meow i could pee on this if i had the energy for slap owner's face at 5am until human fills food dish yet scamper. Knock dish off table head butt cant eat out of my own dish scratch the furniture. Make meme, make cute face. Sleep in the bathroom sink chase laser but pee in the shoe. Paw at your fat belly licks your face and eat grass, throw it back up kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  </body>
  
  
</html>  
DeleteHTML.html
<!--Delete your h1 element so we can simplify our view.-->
<!--<h1>Hello World</h1>-->

<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
FillInTheBlank.html
<!--Replace the text inside your p element with the first few words of this kitty ipsum text: Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.-->
<h1>Hello World</h1>

<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
HeadlineWithH2.html
<!--Add an h2 tag that says "CatPhotoApp" to create a second HTML element below your "Hello World" h1 element.-->
<h1>Hello World</h1>
<p>CatPhotoApp</p>
InformWithTheP.html
<!--Create a p element below your h2 element, and give it the text "Hello Paragraph".-->
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
<p>Hello Paragraph</p>
IntroductionToHTML5.html
<!--HTML5 introduces more descriptive HTML tags. These include header, footer, nav, video, article, section and others.
These tags make your HTML easier to read, and also help with Search Engine Optimization (SEO) and accessibility.
The main HTML5 tag helps search engines and other developers find the main content of your page.
Note
Many of the new HTML5 tags and their benefits are covered in the Applied Accessibility section.
TASK:
Create a second p element after the existing p element with the following kitty ipsum text: Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.
Wrap the paragraphs with an opening and closing main tag.-->
<h2>CatPhotoApp</h2>
<main>
    <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
    <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
LinkToExternalPagesWithAnchorElements.html
<!--You can use anchor elements to link to content outside of your web page.
anchor elements need a destination web address called an href attribute. They also need anchor text. Here's an example:
<a href="https://freecodecamp.org">this links to freecodecamp.org</a>
Then your browser will display the text "this links to freecodecamp.org" as a link you can click. And that link will take you to the web address https://www.freecodecamp.org.
Create an a element that links to http://freecatphotoapp.com and has "cat photos" as its anchor text.-->
<h2>CatPhotoApp</h2>
<main>
    <a href="http://freecatphotoapp.com">cat photos</a>
  
  
  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">
  
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
LinkToInternalSectionsOfAPageWithAnchorElements.html
<!--Link to Internal Sections of a Page with Anchor Elements
Anchor elements can also be used to create internal links to jump to different sections within a webpage.
To create an internal link, you assign a link's href attribute to a hash symbol # plus the value of the id attribute for the element that you want to internally link to, usually further down the page. You then need to add the same id attribute to the element you are linking to. An id is an attribute that uniquely describes an element.
Below is an example of an internal anchor link and its target element:
<a href="#contacts-header">Contacts</a>
...
<h2 id="contacts-header">Contacts</h2>
When users click the Contacts link, they'll be taken to the section of the webpage with the Contacts header element.
TASK:
Change your external link to an internal link by changing the href attribute to "#footer" and the text from "cat photos" to "Jump to Bottom".
Remove the target="_blank" attribute from the anchor tag since this causes the linked document to open in a new window tab.
Then add an id attribute with a value of "footer" to the <footer> element at the bottom of the page.-->
        <h2>CatPhotoApp</h2>
        <main>
          <a href="#footer" >Jump to Bottom</a>
          <!--<a href="http://freecatphotoapp.com" target="_blank">cat photos</a>-->
          
          <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">
          
          <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
          <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
          <p>Meowwww loved it, hated it, loved it, hated it yet spill litter box, scratch at owner, destroy all furniture, especially couch or lay on arms while you're using the keyboard. Missing until dinner time toy mouse squeak roll over. With tail in the air lounge in doorway. Man running from cops stops to pet cats, goes to jail.</p>
          <p>Intently stare at the same spot poop in the plant pot but kitten is playing with dead mouse. Get video posted to internet for chasing red dot leave fur on owners clothes meow to be let out and mesmerizing birds leave fur on owners clothes or favor packaging over toy so purr for no reason. Meow to be let out play time intently sniff hand run outside as soon as door open yet destroy couch.</p>
          
        </main>
          
        <footer id="footer">Copyright Cat Photo App</footer>
MakeDeadLinksUsingTheHashSymbols.html
<!--Make Dead Links Using the Hash Symbol
Sometimes you want to add a elements to your website before you know where they will link.
This is also handy when you're changing the behavior of a link using JavaScript, which we'll learn about later.
The current value of the href attribute is a link that points to "http://freecatphotoapp.com". Replace the href attribute value with a #, also known as a hash symbol, to create a dead link.
For example: href="#"-->
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#" target="_blank">cat photos</a>.</p>
  
  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">
  
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
NestAnAnchorElementWithinAParagraph.html
<!--Nest an Anchor Element within a Paragraph
You can nest links within other text elements.
<p>
Here's a <a target="_blank" href="http://freecodecamp.org"> link to freecodecamp.org</a> for you to follow.
</p>
Let's break down the example:
Normal text is wrapped in the p element:
<p> Here's a ... for you to follow. </p>
Next is the anchor element <a> (which requires a closing tag </a>):
<a> ... </a>
target is an anchor tag attribute that specifies where to open the link and the value "_blank" specifies to open the link in a new tab
href is an anchor tag attribute that contains the URL address of the link:
<a href="http://freecodecamp.org"> ... </a>
The text, "link to freecodecamp.org", within the anchor element called anchor text, will display a link to click:
<a href=" ... ">link to freecodecamp.org</a>
The final output of the example will look like this:
Here's a link to freecodecamp.org for you to follow.
TASK:
Now nest your existing a element within a new p element (just after the existing main element). The new paragraph should have text that says "View more cat photos", where "cat photos" is a link, and the rest of the text is plain text.-->
<h2>CatPhotoApp</h2>
<main>
  
  <a href="http://freecatphotoapp.com" target="_blank">cat photos</a>
  
  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">
  
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
  <p>View more <a href="http://freecatphotoapp.com">cat photos</a></p>
</main>
NestManyElementsWithinASingleDivElement.html
<!--Nest Many Elements within a Single div Element
The div element, also known as a division element, is a general purpose container for other elements.
The div element is probably the most commonly used HTML element of all.
Just like any other non-self-closing element, you can open a div element with <div> and close it on another line with </div>.
TASK:
Nest your "Things cats love" and "Things cats hate" lists all within a single div element.
Hint: Try putting your opening div tag above your "Things cats love" p element and your closing div tag after your closing ol tag so that both of your lists are within one div.-->
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>
  
  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
  <div>
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
</div>
  <form action="/submit-cat-photo">
    <label><input type="radio" name="indoor-outdoor" checked> Indoor</label>
    <label><input type="radio" name="indoor-outdoor"> Outdoor</label><br>
    <label><input type="checkbox" name="personality" checked> Loving</label>
    <label><input type="checkbox" name="personality"> Lazy</label>
    <label><input type="checkbox" name="personality"> Energetic</label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>
SayHello.html
<!--To pass the test on this challenge, change your h1 element's text to say "Hello World".-->

<h1>Hello World</h1>
TurnAnImageIntoaLink.html
<!--Turn an Image into a Link
You can make elements into links by nesting them within an a element.
Nest your image within an a element. Here's an example:
<a href="#"><img src="https://bit.ly/fcc-running-cats" alt="Three kittens running towards the camera."></a>
Remember to use # as your a element's href property in order to turn it into a dead link.
Place the existing image element within an anchor element.
Once you've done this, hover over your image with your cursor. Your cursor's normal pointer should become the link clicking pointer. The photo is now a link.-->
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">cat photos</a>.</p>
  
  
  
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
Uncomment.html
<!--Uncomment your h1, h2 and p elements.-->


<h1>Hello World</h1>

<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
UseHTML5ToRequireAField.html
<!--Use HTML5 to Require a Field
You can require specific form fields so that your user will not be able to submit your form until he or she has filled them out.
For example, if you wanted to make a text input field required, you can just add the attribute required within your input element, like this: <input type="text" required>
Make your text input a required field, so that your user can't submit the form without completing this field.
Then try to submit the form without inputting any text. See how your HTML5 form notifies you that the field is required?-->
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>
  
  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>
  
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <input type="text" required placeholder="cat photo URL">
    <button type="submit">Submit</button>
  </form>
</main>