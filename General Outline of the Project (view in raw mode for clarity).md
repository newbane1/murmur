# murmur
Welcome to project Murmur (ehh I'll think of something later)
Parts to the project
><b>Site</b>
/needs the standard website essentials such as/
 Registration page, username/login, profile page, avatar, signature, homepage, etc...
-Needs a sub-profile system in which you can add your friend code (which will be the information that the JAPP imports. Should include your username (for the sub-profile), avatar, signature, win/loss, and any custom chat skins you have unlocked (the skins should be linked to your main profile rathar than your sub-profile).
-Forum (should include the general forum stuff) possibly use an open source forum as a template.
-site promotion links (facebook, twitter, etc).
-possible adds/donation area.
><b>DB</b>
-username, password, susername, profile image* (not sure where this is stored), win, loss, unlocked perks (custom skins, borders, signatures, et.) Probably going to use a 0, 1 way of determining if you have a perk or not. So 0 = locked 1 = unlocked. 
><b>JAPP</b> (pairing app that lets you connect to other people based on a tier)
-needs to innitiate a chat session 
-needs to pull profile data from the db and place it into a specified location for both parties
-needs to have a select profile dropdown option
-needs to have a chat limit of 2 people per chat
-lobby/que based pairing system, people are placed into a waitlist
-a number that indicates how many users are in the waitlist
/<b>Extra Stuff for the JAPP</b>/ 
-Custom Skins (boarders)
-ranking system
  -After a win/loss you can select an option to indicate who won/loss. This will update their profile's win/loss area in the DB.
  Both parties must agree to the same results. If indicated win/loss input is not the same for both parties then the rating    for that session gets thrown out. 
  -Possibly add a check that prevents people from farming wins by adding an hour delay for ranking the same person. Also make    it so that you cannot connect to yourself via a different browser/different session.
