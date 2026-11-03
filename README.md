CSS Architecture Package 

1.	Refactoring evidence

    1. Instead of having different spacing values such as --gutter: 20px, I made a set of spacing design tokens, from “—space-none” to “—space-2.5rem” to ensure visual consistency. 
    2. I made a set of font sizes into a design token, so that I can choose a size based on the role of the text. 
    3. I added a white background color and black font color values to the print setting because I had changed some background color on the website to dark color. 

2.	Architecture notes: a short explanation of your layer/order strategy, token decisions, naming approach, and browser checks.

    I followed “reset, base, layout, components, utilities, and overrides” layer order. I created design tokens for repeatable values and used the same naming convention when naming tokens. The website works intentionally with Chrome and Safari. 

3.	AI disclosure: if used, document purpose, output considered, verification, and what changed.	

    I used Claude to clarify the different purposes of each layer and to decide which layer to place certain styles. 
