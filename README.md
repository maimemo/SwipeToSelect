# SwipeToSelect
Implement swipe to select in UITableViewContoller


### Background
You are given a list of words to display. Your client wants to be able to select mutiple words as he moves his finger down the list. This project has a few classes available for you to start with:

- <b>MasterViewController:</b> to display main list of words. This is where the guesture will shine.

- <b>DetailViewController:</b> to display detail of a word (not implemented).

- <b>TableViewCell:</b> custom cell class

- <b>UIStoryboard+Addtion:</b> to provide convenient method to access storyboard items

- <b>WordSource:</b> source of words

Feel free to alter them as you see fit.

### Specifications
1. Selected words will be highlighted with the left-most image: a filled circle indicates selection; empty circle otherwise.

2. Improve the experience of tapping the circle to select.

3. Enable swipe to select/deselect. Cells in the path of swipe guesture should toggle their states.

4. Log selected words when 'OK' is pressed.

5. A simple detail view is needed.

6. Be able to shuffle words, i.e. randomly amend the order of words.

7. <b>Bonus #1:</b> Enable search, in a way you think provides good user experience.

8. <b>Bonus #2:</b> Split the list into two lists which can be viewed by swipping horizontally. E.g. List 1 contains words with initials A-M and List 2 N-Z.

9. <b>Super Bonus #1:</b> Display a text input unit under the word so that a user can type text of any length (e.g. an example sentence) into it. Such text will be displayed in both main & detail view.

10. <b>Super Bonus #2:</b> Write the whole project in Swift 3.0+.
