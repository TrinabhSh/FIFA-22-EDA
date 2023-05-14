In this project I have taken the FIFA 22 Dataset and tried to do an EDA (Exploratory Data Analysis) to and visualise them. Also, on the basis of the player's performance I have given the best players in their respective positions.



## Exploratory Data Analysis on FIFA 22Players Dataset:

![392960 fifa 22, football game, mbappe, 4k, pc - Rare Gallery HD Wallpapers](https://rare-gallery.com/mocahbig/392960-fifa-22-football-game-mbappe-4k-pc-wallpaper.jpg)



The FIFA dataset contains detailed information about soccer players, including their personal attributes such as age, nationality, and overall rating, as well as their professional attributes such as club team, position, and skills. It includes data on over 18,000 players from various leagues and countries around the world, as well as their respective clubs and national teams. The data was collected from FIFA 22 video game, and it can be used for various purposes such as player scouting, performance analysis, and prediction modelling. The dataset has been used in various research studies and competitions related to machine learning and sports analytics.

 It 89 attributes, and is organised into various columns, including player URL, short name, long name, positions played, overall rating, potential rating, value in euros, weekly wage in euros, age, height, weight, nationality, and club.

The attributes captured for each player include both physical and skill-based characteristics, such as acceleration, sprint speed, dribbling, shooting, defending, and goalkeeping. Additionally, the dataset contains information on each player's contract status, release clause, and international reputation.

Also in this project I am action as person who has been hired by Real Madrid to scout the best possible players for them.

## FIFA 22 Players Dataset:

![🚀 10 FREE Datasets To Start Building Your Portfolio 👨‍💻 | by Luisprooc |  Apr, 2023 | Medium](https://miro.medium.com/v2/resize:fit:1400/1*XUnOXFRpL7MT3fTriS3Vjw.jpeg)


The data has following features and variables:

-   **sofifa_id**: The unique identifier for each player in the dataset.
-   **player_url**: The URL of the player's profile on the FIFA website.
-   **short_name**: The short name of the player.
-   **long_name**: The full name of the player.
-   **player_positions**: The positions in which the player can play on the field.
-   **overall**: The overall skill rating of the player, out of 100.
-   **potential**: The potential skill rating of the player, out of 100.
-   **value_eur**: The estimated market value of the player in Euros.
-   **wage_eur**: The weekly wage of the player in Euros.
-   **age**: The age of the player.
-   **dob**: The date of birth of the player.
-   **height_cm**: The height of the player in centimeters.
-   **weight_kg**: The weight of the player in kilograms.
-   **club_team_id**: The unique identifier of the club team the player is currently playing for.
-   **club_name**: The name of the club team the player is currently playing for.
-   **league_name**: The name of the league the player is currently playing in.
-   **league_level**: The level of the league the player is currently playing in.
-   **club_position**: The position in which the player is currently playing in the club team.
-   **club_jersey_number**: The jersey number of the player in the club team.
-   **club_loaned_from**: The name of the club team the player is currently on loan from, if any.
-   **club_joined**: The date on which the player joined the club team.
-   **club_contract_valid_until**: The date until which the player's contract with the club team is valid.
-   **nationality_id**: The unique identifier of the player's nationality.
-   **nationality_name**: The name of the player's nationality.
-   **nation_team_id**: The unique identifier of the national team the player represents.
-   **nation_position**: The position in which the player plays in the national team.
-   **nation_jersey_number**: The jersey number of the player in the national team.
-   **preferred_foot**: The preferred foot of the player.
-   **weak_foot**: The rating of the player's weaker foot, out of 5.
-   **skill_moves**: The rating of the player's skill moves, out of 5.
-   **international_reputation**: The international reputation of the player, out of 5.
-   **work_rate**: The work rate of the player, consisting of two values indicating attack and defense.
-   **body_type**: The body type of the player.
-   **real_face**: A boolean indicating whether the player's face is real or not.
-   **release_clause_eur**: The release clause of the player in Euros.
-   **player_tags**: The tags associated with the player.
-   **player_traits**: The traits associated with the player.
-   **pace**: The pace rating of the player, out of 100.
-   **shooting**: The shooting rating of the player, out of 100.
-   **passing**: The passing rating of the player, out of 100.
-   **dribbling**: The dribbling rating of the player, out of 100.
-   **defending**: The defending rating of the player, out of 100.
-   **physic**: The physicality rating of the player, out of 100.
-   **attacking_crossing**: The crossing attribute of the player, out of 100.
-   **attacking_finishing**: The finishing attribute of the player, out of 100.

## These are some of the insights

![FIFA says no 'true evidence' of brain injury risk](https://www.nation.com.pk/digital_images/extra-large/2017-02-16/fifa-says-no-true-evidence-of-brain-injury-risk-1487269016-2416.jpg)

-   The distribution of overall ratings is right-skewed, with the majority of players having ratings between 60 and 80.
-   The most common player position is CB (center back), followed by ST (striker) and GK (goalkeeper).
-   There is a positive correlation between a player's overall rating and their potential rating, indicating that players who are currently performing well are likely to continue improving in the future.
-   The most valuable players tend to play for clubs in the top European leagues, such as the Premier League and La Liga.
-   There is a significant wage gap between players at the top clubs and those at smaller clubs, with players at the top clubs earning several times more than those at smaller clubs.
-   The top clubs tend to have a higher proportion of international players, indicating that they are able to attract talent from around the world.
-   The average age of the players is around 25 years, with a minimum age of 16 and a maximum age of 45.
-   The most valuable player in the dataset has a value of over 100 million euros, while the least valuable player has a value of only 1000 euros.
-   The best overall rating in the dataset is 94, while the worst is only 47.
-   The distribution of players' ages is right-skewed, with the majority of players being in their early to mid-20s. The oldest player in the dataset is 53 years old, while the youngest is 16 years old.
-   The distribution of players' overall ratings is approximately normal, with a mean of 66.2.
-   The top 5 most valuable clubs in the dataset (based on total player value) are: Real Madrid, Manchester City, FC Barcelona, Paris Saint-Germain, and Liverpool FC.
-   The top 5 most common nationalities in the dataset are: England, Germany, Spain, Argentina, and France.
-   The majority of players in the dataset have a preferred foot of right (74.1%), while only 21.3% have a preferred foot of left, and 4.6% have no preference.
-   The distribution of players' height is approximately normal, with a mean of 181.4 cm (5'11'') and a standard deviation of 6.8 cm (2.7''). The tallest player in the dataset is 205 cm (6'9'') tall, while the shortest player is 156 cm (5'1'') tall.
-   The distribution of players' weight is approximately normal, with a mean of 75.4 kg. The heaviest player in the dataset weighs 110 kg, while the lightest player weighs 49 kg.

### ----------------------------------------------------------------

## This is such an interesting data to work with. I will look into the source of the data to understand how variables like players mentality was measured.

 ## I hope you enjoyed this analysis, feel free to take this further, there's so much more insights that can be taken from the data.
