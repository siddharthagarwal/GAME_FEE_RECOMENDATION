# GAME_FEE_RECOMENDATION

Here, I have picked up a well known porblem in Online Gaming Industry where based on the User's History of Gaming interactions and it's respective ENTRY FEES that the user is ready to pay, I have developed a RECOMENDATION ENGINE which not only suggests subsequent games but also the respective Tournament Size (ENTRY FEES) based on the user's win-history and playing temperament.

Data:
When a user logs in to the platform, they have to choose from a variety of
tournament types (A / B / C / D). Additionally, different entry fees may be associated with every
tournament. As a platform we must ensure that the most relevant tournaments are suggested to
the user based on their preferences.
Available Data: Given anonymised user gameplay data in the form of 3 csv files.

Fields in the data are as described below:
Gameplay_Data.csv contains following fields:

● Uid: Alphanumeric unique Id assigned to user

● Eventtime: DateTime on which user played the tournament

● Entry_Fee: Entry Fee of tournament

● Win_Loss: ‘W’ if the user won that particular tournament, ‘L’ otherwise

● Winnings: How much money the user won in the tournament (0 for ‘L’)

● Tournament_Type: Type of tournament user played (A / B / C / D)

● Num_Players: Number of players that played in this tournament


Wallet_Balance.csv contains following fields:

● Uid: Alphanumeric unique Id assigned to user

● Timestamp: DateTime at which user’s wallet balance is given

● Wallet_Balance: User’s wallet balance at given time stamp

Demographic.csv contains following fields:

● Uid: Alphanumeric unique Id assigned to user

● Installed_At: Timestamp at which user installed the app

● Connection_Type: User’s internet connection type (Ex: Cellular / Dial Up)

● Cpu_Type: Cpu type of device that the user is playing with

● Network_Type: Network type in encoded form

● Device_Manufacturer: Ex: Realme

● ISP: Internet Service Provider. Ex: Airtel

● Country

● Country_Subdivision

● City

● Postal_Code

● Language: Language that user has selected for gameplay

● Device_Name

● Device_Type

We'll build a basic recommendation system which is able to rank/recommend relevant
tournaments and entry prices to the user.

The main objectives would be:
1. A user should not have to scroll too much before selecting a tournament of their
preference
2. We would like the user to play as high an entry fee tournament as possible.

As part of my project, I have included the following components in my notebook itself:

● Code

● Documentation which outlines the solution approach, assumptions, success metrics

● Areas of improvement
