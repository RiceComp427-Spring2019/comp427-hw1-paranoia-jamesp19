# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: James Park

_Student NetID_: jwp5

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: {Stadium}
- Assumptions:
  - It's assumed that the team uses this stadium exclusively to practice when they're not playing games in other areas. 
  Furthermore, non-football organizations may occasionally use the stadium as well to practice (e.g. marching band).
- Assets:
  - One of the most important assets to protect is the stadium itself, both when games are being played in it and when it is 
  not in use. Considering the talent of the football team, the 
  stadium will no doubt be packed during games; if an attacker were to compromise the stadium's ability to ensure that 
  both teams play fairly, such as by interfering with the lights or altering the field turf, it could lead to an unfair 
  advantage for either team. In an even more dire scenario, an attacker could take advantage of the public football game schedule
  to know which days the stadium would be filled with people, then plan some kind of terroristic attack to hurt or kill thousands.
  - Another important asset to protect are the football teams themselves, when they are on the field. If an attacker, or perhaps even simply an 
  overzealous fan, were able to make
  their way onto the field during a game and interfere with the players, the best case scenario would be extreme embarrassment for
  the school for their inability to prevent such a thing from happening, and the worst case scenario would be the injuries or deaths of 
  players. Such an attack could even happen when the team is practicing alone in the stadium, not just during games. Thus, protection should be present at all times.
- Threats:
  - The biggest threat to defend against would be actual people with ill intentions. This would be comprised of 
  various levels of severity, with the more minor category being comprised of 
  unruly fans, hecklers, aggressively drunk people, etc., and more severe categories being comprised of people with more sinister intentions, such as shooters or bombers.
  A person that falls into any of these categories has potential to cause serious harm to themselves, the stadium, other spectators,
  the teams, and the reputation of the university- in short, all of the assets we care about. Thus it's our top priority to prevent these types of people from being allowed access.
  
  - Another threat, albeit more minor than the previous one, consists of unauthorized remote surveillance of the football team when they
  practice (or anybody else using the stadium, for that matter) via drone. This falls in line with the second point in the Assets category: protecting the teams by preventing an unfair advantage. If someone were able to observe the team's training regimen and what plays they
  were practicing, they could very well leak that information to rival teams, who could then devise their own counter-strategies. Such a
  threat has become a very real possibility these days (the Gatwick Airport shutdown due to drones comes to mind), and steps should be
  taken to protect against it.
- Countermeasures:
  - The most reasonable defense that should be immediately implemented would be physical barriers- walls, gates, partitions, and the
  like, both outside the stadium and around the field itself. On game days with high traffic, these barriers could be reinforced with on-duty security guards around the stadium and in the stands, who check the belongings of spectators entering the stadium. These defenses are the most simple way of preventing unauthorized entry into the stadium and onto the turf by both low and high-threat people alike, and ensuring the safety and peace of mind of those inside- a necessity well worth investing into. Furthermore, the costs for such defenses are relatively cheap- the physical barriers' financial costs mainly come from the initial order and installation, and do not require constant supervision or maintenance if properly implemented except on game days. As for the security team, costs can be kept low by only increasing the number of people on duty on game days.
  - For the more minor threat of remote surveillance, a simple countermeasure comes to mind: a security guard assigned the task of
  monitoring the surrounding area for drones or other unauthorized equipment. Should he spot any, he would alert the team, who could then refrain from practicing specific plays, as well as law enforcement if necessary. The benefit is that any would-be snoopers are immediately deterred, and anyone else still brave enough to try would be swiftly caught. This ensures the football team may continue to practice without fear of giving away their secrets to others. The costs are relatively minor, as well- it's simply the cost of paying one security guard for their job.
  

## Problem 2
- Scenario: {Documents}
- Assumptions:
  - The employees of the law firm generally work in designated buildings/office spaces during the day. It is not a fully work-from-home environment; however, work-from-home is an option for employees (but they must show up to the office at least a few times a week). Working-from-home is supported via a VPN.
- Assets:
  - Naturally, the most important asset at stake here are the documents themselves. With such sensitive information contained within,
  leaking even a single one of these documents in any way would result in a massive international scandal that would spell doom for the entire international law firm, let alone any chance of you being hired by another company for IT ever again. It doesn't even matter if the document leaked is a non-sensitive one; the simple fact that your system can be breached is proof enough to all current and potential customers that your firm's does not have the ability to protect them and their data. Therefore, safekeeping of all of these documents is top priority.
  - Another asset, whose value is derived from the value of the documents, is the physical hardware of the law firm. This does not just include hardware owned by the law firm, but also all of the hardware owned by the employees of the firm. Desktops, laptops, cellphones, tablets, and all other forms of electronics that can store data are potential avenues of escape for any of the sensitive documents. All of these devices must be closely monitored to ensure that nobody accidentally or intentionally takes some of this hardware out of the office with sensitive material on it. A device with the documents on it that is lost by its owner is just as bad as leaking the document directly.
- Threats:
  - The first threat to be addressed would be the law firm's employees themselves. The employees have the easiest access to the documents, much more so than cyber attackers, because at least some of their jobs naturally necessitate direct access and modification of the files. Thus, they are the highest risk factor for a document leak. Even an employee who has no intention of betraying the law firm and releasing the sensitive documents could very well walk out of the office for the day with sensitive files locally saved on their work-issued laptop, or download files to their local machine while working from home. Proper management and preventative techniques must be enforced to prevent such a dangerous situation from occurring.
  - The other important threat to be addressed are hackers directly targeting the law firm. Due to the law firm's international status, they most likely have a good reputation and a publicly known name; this makes them a prime target for hackers who want to expose personal information for many people at once. As the document management system you control is responsible for storing all of the files that a hacker would be interested in, that makes your system the main target within the law firm. As such, steps must be taken to ensure that unauthorized access is not allowed, and that anyone who does have authorized access is actually who they say they are.
- Countermeasures:
  - The first countermeasure that should be implemented is a role and privilege system within the law firm; that is, a way to only give certain employees the ability to access the files, and only as much as their job requires. This practice, common amongst many companies, benefits the company by ensuring that any employee who is not on a need-to-know basis with the documents cannot access them, thereby drastically reducing the number of people who can tamper or leak the files within the firm, whether they are working in the office or at home. The costs are minimal; a set of privileges can simply be electronically assigned to each job within the company, and only those employees who have jobs with a certain privilege can access the files. Settings these priviliges electronically is financially cheap and also has the benefit of not disrupting the work of anyone who is not doing something they shouldn't.
  - Another countermeasure that should be implemented is to prevent the files from being downloaded locally at all, to any device. They should only be accessed over a secure, encrypted connection, and copying the files directly over the connection should not be allowed. This has the benefit of ensuring that the files themselves never go anywhere except within the document management system that you control, thus further separating the employees from the files and preventing a data breach. This also has the additional benefit of protecting against hackers who might attempt to either read the files as they are being transmitted over the network, or hack an employee's personal computer that they've saved files on and steal them from there. By encrypting the files during transit and not allowing them be downloaded, both of these attacks are thwarted. The costs are again cheap, because the company already has a VPN in place. Thus, no new hardware or functionality needs to be implemented to support this countermeasure beyond adding restrictions that prevent copy or download commands over the VPN.
  - The last countermeasure that should be implemented is two-factor authentication when attempting to access the encrypted connection. This has the benefit of preventing hackers who may have stolen an employee's device, logged on as them, and then accessed the VPN as them remotely to read the files. The costs would be more significant than the previous two countermeasures, as a TFA system would either have to be made or purchased from another company; however, since this countermeasure would protect __every__ employee from identity theft, not just the ones reading the sensitive files, it is a cost whose value to the company can be easily justified, considering the disaster that would occur if a document was leaked without it.

## Problem 3
- Scenario: Game Server Management- You're in charge of the servers for a massively multiplayer online game like World of Warcraft that hosts hundreds of thousands of players a day.
- Assumptions:
  - Servers are centralized; however, there are different data centers that players connect to depending on their location (East Coast servers vs. West Coast, for example). However, any countermeasures that are purely code-based can be rolled out quickly to each of these locations with minimal cost.
- Assets:
  - One of the most important assets is the game data of the players. This data determines the status of each player's characters, their inventory and equipment, their money, and other similar things directly related to in-game play. If this data were able to be accessed and modified, then players would be able to take their own account data or the data of other players and modify them to give themselves items and money that they did not receive legitimately through normal gameplay, or remove them from rival players to put them at a disadvantage. They might also set their health and movement speed values to absurd levels, making them unkillable.
  Naturally, these are scenarios that should be avoided to ensure fair and balanced gameplay amongst players, so the data must be protected at all costs.
  - The other most important asset to protect is the account data of the players. Unlike game data, this represents the status of each player's account: usernames, emails, passwords, payment information, etc. While not directly related to gameplay, if a player were able to obtain access to this information for any user other than themselves, they would be able to access that player's account and do malicious things while posing as them, such as deleting all of the player's items in game or even purchasing in-game items with that player's saved payment information. A breach of this data would be even more severe than a breach of game data because this data has ramifications beyond just the game, such as passwords and credit card information. Therefore it is even more important that we safekeep this data.
- Threats:
  - The first of two threats to protect against are "scripters"- people whose main goal is to modify the game data during gameplay. They might do this by sending forged packets via a modified game client to give their character unfair advantages. A scripter left unchecked could ruin the game for other players by killing them repeatedly to prevent them from being able to play, or removing all of their items. We want to ensure that people like this are not allowed to ruin the fun for others.
  - The second threat to protect against are "hackers"- people whose main goal is to read account data. Unlike game data, hackers would attempt to breach data servers directly, not through the game client. If they were able to do so and read the data, they could then sell that data to others, and the emails, passwords, and credit card information of hundreds of thousands of people would be compromised. We want to ensure that such hackers don't get the chance.
- Countermeasures:
  - One good countermeasure that works against scripters would be to perform all validation of sent game data packets server-side. That is, nothing should be done by the client other than displaying the data and graphics that the server tells it to display, as well as sending some basic information about what actions the player has taken. The benefit of this is that a scripter would have no way of being able to bypass the validation checks that the game employs because they have no access to that through the game client itself, and thus any illegal packets that they send from their client would not be accepted. The cost of this would be that any such checks that already existed in the client would have to be moved to the server, but with proper implementation of the game and client, most of this work should have already been done.
  - One countermeasure against hackers would be to hash the account data in the servers with some kind of hashing algorithm. The benefit of this countermeasure is that a would-be hacker who wants read the data in the servers would not actually be able to decipher that data, even if they were able to access the server. Even if the algorithm used to hash the data was known by the scripter, if the game company never releases the unhashed format of the data, and ensures that all data is unique (via something like a timestamp), it would be near impossible for a hacker to deduce the correct format of the data that they should input into the hashing algorithm. The cost of such a countermeasure would be slim, as many well-defined hashing algorithms exist that can be easily used. Indeed, this countermeasure is something that many companies implement today.

