# Saving Inscriber graphics into database

  - Make sure you are using a computer in Master Control not Edit 2 or Studio
  - Make sure you are in directory mode in Inscribe
  - Type  your Graphic
  - If you are updating a graphic check to see if scribefile is set to Read-only 
     - Go to **D:\PCN Graphics\Public Affairs**
     - Find the ScribeFile that has the same number as the one you are updating
     - Right click the file select Properties
     - Under Attributes uncheck "Read-only"
  - type in the number you are saving and press ```F5 ```
  - If updating a graphic you will get a warning about the image file already existing overwrite file, click ```yes```
  - Set the scribefile to Read-only if it is a file you do not want changed by accident
  - Log onto google drive and go to **Paperless INSCRIBER BOOK** Google Sheet
  - Sheet1 contains a list of all the graphics in the directory
  - If this is an update of a graphic search for the graphic number or name ``` Ctrl F ```
  - If this is new type in graphic information in empty row
  - Use Proper format reference example
 
| Number | Last Name | First Name |	Organization/Representating |	Title |	Category |	Leader |	Image |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | 
| 23 | Doe | John | PCN | Vice President | Generic | No | http:pcntv.com/image/johndoe.jpg|

  - Each Number must be a unique value 
  - The Category allows the graphic to be added to a section for print out **example** Election, PA House
  - The Leader is a boolean (true or false) that is only used for PA House or Senate Graphics to indicate if it is a leadership graphic
  - The Image is a html link to the image This could be from google drive or the pa house website
  - After you type in the graphic it will be available in the APPSHEET APP *App sheet may not work after May 2019 unless sign up for a paid account*


