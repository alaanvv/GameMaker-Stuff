# Text System

It has a writting effect, and you can alterate  
almost everything easily.  
<img src="text.gif">  
  
## How to use

- Create a instance of this, and set the struct  
with your configurations (Information in the bottom).  
- It has a `skip` method, that you need to trigger   
manually.  
  
## Configuration  
  
Set four structs: text_struct, font_struct,  
delay_struct and callback_struct.

- Text:  
{  
  text: An array with the texts to show,  
  start: A text to fix in the start,  
  end: A text to fix in the end  
}  
- Font:  
{  
  name: Your font,  
  color: Font color,  
  halign: Horizontal align,  
  valign: Vertical align  
}  
- Delay:  
{  
  start: Before start showing texts,  
  final: Delay in the end,  
  letter: For each letter,  
  text: For each text of your array  
}  
- Callback:  
{  
  start: A function for the start (after start delay),  
  text: In the start of each text, send the index as parameter,  
  final: In the end  
}  
