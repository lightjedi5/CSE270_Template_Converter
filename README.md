# CSE270_Template_Converter
Project that converted a word docx to html.

Language: Python
It converted from docx to html via the plugin mammoth. Once it was converted I then wrote and designed the code that would plug in the html into a template. It utilized strings instead of array so that the required sections could be maintained in one string vs being different elements in an array. This presented a design challenge since I had to figure out how to find the first character and last character that needed to be contained in a string. This was resolved by finding the index of the first character and the index of the last character. Due to Python not having a built-in string function that would return a string with the end character, I ended up writing a function that would meet that criteria of including the last character. Additional functions were written that would omit the first character and the last character, omit the first character and include the last character.

The benefit of utlizing strings was the ability to maintain the html that was generated via mammoth. This meant that there was no need to modify the string itself. From there it was identifying patterns in the html template that the could be utilized with the string text. 
