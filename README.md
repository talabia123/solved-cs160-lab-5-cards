Download Link: https://assignmentchef.com/product/solved-cs160-lab-5-cards
<br>
I have placed the CardDeck.py file and the card image files on Blackboard. Place these in your Python directory with your other Python files. After unzipping the cards.zip file, make certain you have a directory named cardset in the same directory as your Python files and that it contains the card image files.The CardDeck.py file contains a CardDeck class with two methods that you will use. The documentation strings for the methods are:

<table width="623">

 <tbody>

  <tr>

   <td width="623">class CardDeck:def shuffle(self):’’’shuffles all 52 cards’’’def dealOne(self):’’’returns the number corresponding to the next card; returns None if there are no cards left to be dealt’’’</td>

  </tr>

 </tbody>

</table>

The following shows an example of how to use the CardDeck class assuming you have the line from CardDeck import * at the top of your file:

d = CardDeck()

d.shuffle()

c = d.dealOne() # c contains a number between 0 and 51

You are to download the cards.py file with the drawCard function I have written for you and the cardInfo function you are to write as described in the documentation string. The cards.py file with a correct cardInfo function must be submitted by Friday 10/26 at 12:01AM for a homework grade. Email it as described below by then. I will then mail my version out in case yours does not work so you can complete the lab.

Modify the file cards.py. Write a function def cardInfo(cardNumber) that takes one integer value between 0 and 51 and returns both the blackjack value for the card and the filename for the card. Here is the documentation string for the method:

<table width="623">

 <tbody>

  <tr>

   <td width="623">def cardInfo(cardNumber):’’’returns the blackjack value and and filename for card specified by cardNumber0-12 are the Ace-King of clubs13-25 are the Ace-King of spades26-38 are the Ace-King of hearts 39-51 are the Ace-King of diamondsthe blackjack value for the cards 2-9 are the corresponding number; 10, Jack, Queen, and King all have blackjack values of 10 and an Ace has a value of 11filename is of the form: ##s.gif where ## is a two digit number (leading 0 if less than 10) and s is a letter corresponding to the suit value c for clubs, s for spades, h for hearts, d for diamonds’’’</td>

  </tr>

 </tbody>

</table>

1

Once you have the cardInfo completed, make the cards.py file display a 600 by 400 GraphWin window when run. In the window, display three cards in a row near the top of the window and three cards in a row near the bottom of the window. At the end of each row, display the blackjack total for the three cards in the row or the message ”busted” if the total is over 21. Below the bottom row of cards display on of the following messages based on the two rows of cards: Both players busted (if both rows are over 21), Player 1 wins (if the top row is the better blackjack hand), Player 2 wins (if the bottom row is the better blackjack hand), Tie (if both players did not bust and have the same total). The better blackjack hand is the total closer to 21 that is not over 21. Wait for a mouse button click before closing the window. Your screen should look similar to the following:

After you have commented and tested your code, submit your cards.py and help.txt files by emailing them to <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="f49086919190b49795849d809598da919081">[email protected]</a> as an attachment with the appropriate subject line. You must use Capital’s webmail as some email systems send attachments differently and I automatically extract the attachment based on the email address. Use the subject CS160-1ATT for the 1PM section and CS160-2ATT for the 2PM section. Do not submit the CardDeck.py file or all the images.

2