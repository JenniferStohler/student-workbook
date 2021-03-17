## DAILY JOURNAL DAY 2

<b>1. What is a Pseudo-Class and what are some of the most common ones you think you will use</b>

  Pseudo-classes are keywords that are attached to a selector. They assign to the selector a special function. For example, :hover allows a button to change color when the cursor hovers over it. I think I will use that one the most, along with :link, :visited, and :checked. 

<b>2. What is Specificity and how might you use it to your benefit?</b>

  Specificity refers to when many rules in a code apply to the same element and its property. It is used to ensure that the correct rule gets applied. For example:

    div {
      background-color: yellow;
    }

    div {
      background-color: red;
    }

    While both elements are divs and have the same property, only the second div will get printed out. The first div still runs, but it doesn't get printed out because it's overruled by the second div. However, if the code were to look like this:
    
      div.container {
        background-color: red;
      }

      .container {
        background-color: green;
      }
    
  the rule of Specificty dictates that only the 1st div will print out. This is because it is targeting an element and a class instead of just one or the other. One benefit of Specificity is that it allows the developer to easily change their CSS code. 

<b>3. What problems do you think you could run into if you over-utilized the !important feature?</b>

  It would interfere with the code in the external stylesheet. The code could possibly have many errors or just wouldn't run. 
