# Popular_chess_openings

I’ve started playing chess recently, and I have realized that learning chess openings can save time and mental energy in the beginning of the game. 

I have found data set for over 20,000 online games in Lichess from Kaggle and I set out to explore the most used chess openings and their winning ratio.

For this project I did a bunch of data wrangling, cleaning, and transformation.

Here are the most used chess openings separated by expertise level:![chess_by_level](https://user-images.githubusercontent.com/94130159/151088809-d111cd99-3626-4bee-bcdb-ab22a229c3f1.jpg)



![Opening_names](https://user-images.githubusercontent.com/94130159/151088709-dd522369-2b50-4bbb-8758-e8fff65566e2.jpg)


The graphics above clearly show that most of the games were played in the intermediate level, which is rated at 1250 - 1800. I have manipulated data set to only include openings that were played at least 230 times, that’s why there are only ten opening codes on the x-axis which correspond to an opening name that can be seen in the table above.


In the Beginner quadrant one can see that the Van’t Kruijs opening (A00 opening eco chess code) has the highest winning rate for black. In the Intermediate column, the Scandinavian Defense: Mieses-Kotroc Variation opening (B01) has the highest winning rate for white, while in the Advanced quadrant the highest winning rate for white is French Defense: Knight Variation opening (C00). There is not a lot of game data at the Master level, which is rated at 2400-2600+, but one can still see that Scandinavian Defense: Mieses-Kotroc Variation Opening (B01) has the highest winning rate for white, while Queen’s Pawn Game: Mason Attack (D00) has the highest winning rate for black.


I want to note that some openings had several different opening codes. In the table above, one can see that there are four Sicilian Defense openings and two Scotch Game opening that have different codes. I have checked these codes and they represent different variations of the particular opening. For some reason this data set didn’t inlcude these variations and that’s why I have four Sicilian Defense openings and two Scotch game openings.
