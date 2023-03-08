# Fizzwidget-Feed-O-Matic  
Features  
Makes feeding your pet quick, easy, and fun:  
  
Automatic feeding: Feeds your pet whenever his happiness falls below a certain level (”content” by default), automatically choosing an appropriate food.
Manual feeding: Bind a key to “Feed Pet”, and Feed-O-Matic will automatically choose an appropriate food and give it to the pet whenever you press it.  
  
Can use an emote to notify you when it’s feeding your pet, with custom randomized messages. See FeedOMatic_Emotes.lua to customize them to your characters!
Helps you manage all the pet food in your inventory:  
  
Keeps track of which foods your pet likes more, and prioritizes “better” foods when choosing what to feed the pet. Also remembers what foods your pet has “outgrown”, and doesn’t choose them in the future (unless you’ve switched to a pet who might have different tastes).  
  
If you’re on a quest to collect several of a certain item which also happens to be something your pet likes to eat, Feed-O-Matic can avoid consuming it. (Unless you’re carrying more than is needed for the quest or there’s nothing else for your pet to eat.) Type /feedomatic savequest on to enable this feature.  
  
Feed-O-Matic can keep track of what foods are used by the Cooking recipes you know and avoid choosing food you’d rather cook. To enable this feature, type /feedomatic saveforcook followed by the difficulty color you want to save ingredients for. (For example, /feedomatic saveforcook orange will cause Feed-O-Matic to avoid choosing food items you’re guaranteed to get a skillup from cooking; foods used in lower-level recipes won’t be given special attention.)  
  
If you’d prefer to save the better food (that is, those which provide a “well fed” bonus or other effect when eaten) for yourself, Feed-O-Matic can also avoid it when looking for pet food.  
  
All other things being equal, Feed-O-Matic will try to pick foods from smaller stacks, making sure your food supply doesn’t take up all your bag space. When your bags get close to full, Feed-O-Matic will start ignoring other criteria and always choosing the smallest stack so that you won’t run out of inventory sooner.  
  
Chat Commands  
/feedomatic (or /fom or /feed) where can be any of the following:  
help - Print this helplist.  
status - Check current settings.  
reset - Reset to default settings.  
alert chat|emote|off - Alert via chat window or emote channel when feeding.  
on|off - Turn automatic feeding on or off.  
level content||happy - Set happiness level for automatic feeding.  
saveforcook orange|yellow|green|gray|off - Avoid foods used in cooking recipes (based on their difficulty).  
savequest on|off - Avoid foods you need to collect for a quest.  
savebonus on|off - Avoid foods that provide a bonus efffect when consumed by a player.   
keepopen <number> - If you have more than number inventory slots open, Feed-O-Matic will prefer foods your pet likes more. If you have number or fewer slots left, Feed-O-Matic will always pull foods from the smallest stack (so space is freed up sooner).  
feed - Feed your pet (automatically finds an appropriate food).  
feed <name> - Feed your pet a specific food.  
add <diet> <name> - Add food to the list for a specific diet (meat, fish, fruit, etc).  
remove <diet> <name> - Remove food from the list.  
show <diet> - Show food list for a specific diet (or for all).    
    
Feed-O-Matic was created by the wonderful Gazmik Fizzwidget, He's got what you need!   
  
As my Hunter friends can readily attest, keeping a wild pet can be a full-time job. Why, just feeding the critter when he gets hungry can throw off your routine — you’ve got to rummage around in your bags, find a piece of food, make sure it’s appropriate for his diet, and check your aim before tossing it to him (lest you accidentally destroy a tasty morsel). So inconvenient! Not to mention potentially dangerous… you don’t want to spend so long digging through your bags that you or your pet become someone else’s snack.  
  
Never fear, Gazmik Fizzwidget is here with a new gadget to automate all your pet-food-management tasks! My incredible Feed-O-Matic features state-of-the-art nutritional analyzers to make sure your pet’s hunger is satisfied with a minimum of fuss, advanced selective logic to make your pet doesn’t eat anything you have another use for, and a weight optimizer to make sure the food in your bags stays well organized! You can have it automatically feed your pet when needed — or, if you’re worried about running out of food while you take a nap, you can opt to manually press the “Feed Now” button and it’ll intelligently choose a food and accurately toss it to your pet. This is actually one of the first gizmos I started work on… but because I’m a perfectionist I haven’t considered it ready for release until now.   
