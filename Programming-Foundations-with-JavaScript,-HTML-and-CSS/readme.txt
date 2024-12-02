HTML (Hyper Text Markup Language) provides the content to webpages.
HTML element syntax: <html_element_name attribute_name="attribute_value">content</html_element_name>, but img element doesn't have ending tag. where tag is a text enclosed by angle brackets (<...>).
em, strong tags have semantics that b, i tags don't have
WYSIWYG (What You See Is What You Get) is not applicable in markup languages.
Hotlink (Inline link) is an object typically an image directly linked to from another site. this can cause unwanted storage and bandwidth usage in case of website with lot of traffic.
HTML entities are represent special characters which are name or unicode enclosed with ampersand (&) and semi-colon (;) symbols. such as &amp;, &#59;, &#8377;, &#9829;, &gt;, &lt;, &#47;, &#92;. HTML entities are used to avoid interference in the HTML structure.
Composition refers to the process of combining simpler components to create more complex systems. examples are nested lists, list element have images, etc.,
Block-level elements start on a new line and take up the full width available, while inline elements flow within text, taking up only the necessary width.

CSS (Cascading Style Sheets) describes how HTML elements are to be presented. 
Instead of embedding style directly within each HTML elements in form of a attribute, the style components are placed in a CSS file. This approach provides reusability and maintainability.
CSS syntax: Selector {property1: value1; property2: value2}.
CSS selectors: 1. 'html element name', 2. '.' + 'class name', 3. '#' + 'id name', etc.,
The purpose of the id attribute is to identify a single HTML element, but the class attribute is to identify specific elements.
In CSS, colors can be represented in rgba() (Red-Green-Blue-Alpha, Alpha stands for opaqueness, all four values varies from 0 to 256), Hexadecimal (#RRGGBBAA, each two digit represents 256 different values), HSLA (Hue-Saturation-Lightness-Alpha where these are represented in degree, percentage, percentage respectively), etc...
Margin defines the space outside an element, while Padding defines the space inside an element.

Computers excel at tasks that require speed, accuracy, tireless repetition, huge computation than humans.
Abstraction is a separation of interface (What it does) and implementation (How it does it?). Generally, Abstraction is of multiple layers.
Computers at the lowest level only work with binary numbers (0 and 1, where each binary number is a bit and 8 bits are one byte). Therefore, everything is represented as numbers for computers from a character, text, image, audio, video, etc.,
Cryptography uses mathematical techniques to transform readable information (plaintext) into an unreadable format (ciphertext) and can only be read by reversing the process using a decryption key to secure communication of information.
Algorithm is a step-by-step instructions for accomplishing a specific task where it takes a input and produces the desired output. Pseudocode is a way of representing program's algorithm in a form that humans can easily understand.
"You can't write a program (which explains the computer what it needs do) until you completely understand how to do in a precise step by step fashion". Therefore, if algorithm works as excepted then it is time to start programming.
Programming starts from a problem statement to working code (which can be broken down into seven step approach if we can't directly start programming to solve a problem statement){
    1. Work input example by hand (requires domain knownledge and the input example should be easily solvable by hand)
    2. Write down what you did
    3. Find the algorithm (be generalized about the input)
    4. Check by hand for that input example
    5. Translate to code in a programming language (there can be multiple different algorithms but pick one)
    6. Run test cases
    7. Debug failed test cases (if algorithmic problem got to step 3, else if implementation problem go to step 5)
}
The Chroma key (Green Screen) technique is the process by which a specific color is removed from an image, allowing that portion of the image to be replaced. The Chroma key Algorithm:
1. Start with the foreground image (fgImage) and the background image (bgImage) of same size i want.
2. Make a blank image of the same size (output).
3. For each pixal (currentPixal) in fgImage
    a) If currentPixal is green then 
        i) Look at same position in bgImage
        ii) Set output's corresponding pixal as the bgImage's pixal
    b) Else set output's corresponding pixal as the fgImage's pixal 

