# purified-commands

```
General:
help: Displays a list of available commands, or detailed information for a specified command.

Admin:
ahelp: shows the admin help menu
disable: Disables a command or command group.
enable: Enables a command or command group.
message: Enables or disables the levelup message.
prefix: Shows or sets the command prefix.
reward: Manages the reward system
update: Updates all user reward roles on this server. Fixes missing roles.

Moderation:
kick {@user}
ban {@user}
hugban {@user} : softban removing 7 days of messages


Util:
user-info: Gets information about a user.
blacklist-user: Prohibit a user from using commando
bot-info: Responds with detailed bot information.
channel: Gets information about a channel.
launch-cybernuke: Bans all members that have joined recently, with new accounts.
remindme: Reminds you of something.
ridea: Creates a random idea.
search: Searches google.
server-info: Gets information about a server.
split: Sends split messages with a specific total length.
strawpoll: Create a strawpoll.
weather: Responds with detailed weather.
whitelist-user: Remove a user from the blacklist

Item:
item-add: Adds an item to the store.
buy-item: Buys an item at the store.
give: Give your items to another user.
item-info: Displays price of an item.
inventory: Displays the items you have in your inventory
store: Displays price of all items.
item-trade: Trade items with another user.

Math:
add-numbers: Adds numbers together.

Tags:
add-example: Adds an example.
add-server-tag: Adds a server tag.
add-tag: Adds a tag.
delete-tag: Deletes a tag.
tag-info: Displays information about a tag.
tag-list-all: Lists all tags.
tag-list: Lists all server tags.
tag-source: Displays a tags source.
tag: Displays a tag.

Random:
advice-slip: Responds with a random bit of advice.
bird: Responds with a random bird image.
cat-fact: Responds with a random cat fact.
cat: Responds with a random cat image.
charlie-charlie-challenge: Asks your question to Charlie.
choose: Chooses between options you provide.
chuck-norris: Responds with a random Chuck Norris joke.
coin: Flips a coin.
compliment: Compliments a user.
discord-email-fun-fact: Responds with a random fun fact from the Discord emails.
dog-fact: Responds with a random dog fact.
dog: Responds with a random dog image.
draw-cards: Draws a random hand of playing cards.
duck: Responds with a random duck image.
fact-core: Responds with a random Fact Core quote.
fact: Responds with a random fact.
fidget: Responds with a random image of Fidget.
fortune: Responds with a random fortune.
fox: Responds with a random fox image.
github-zen: Responds with a random GitHub design philosophy.
joke: Responds with a random joke.
karen: Responds with a random image of Karen.
kiss-marry-kill: Determines who to kiss, who to marry, and who to kill.
magic-conch: Asks your question to the Magic Conch.
meme: Responds with a random meme.
name: Responds with a random name, with the gender of your choice.
number-fact: Responds with a random fact about a specific number.
offspring: Determines if your new child will be a boy or a girl.
opinion: Determines the opinion on something.
oracle-turret: Responds with a random Oracle Turret quote.
pun: Responds with a random pun.
quantum-coin: Flips a coin that lands on some form of nothing.
quote: Responds with a random quote.
rate: Rates something.
reddit: Responds with a random post from a subreddit.
roast: Roasts a user.
roll: Rolls a dice with a maximum value of your choice.
security-key: Responds with a random security key.
shiba: Responds with a random image of a Shiba Inu.
shower-thought: Responds with a random shower thought, directly from r/Showerthoughts.
suggest-command: Suggests a random command for you to try.
superpower: Responds with a random superpower.
this-for-that: So, basically, it's like a bot command for this dumb meme.
user-roulette: Randomly chooses a member of the server.
would-you-rather: Responds with a random "Would you rather ...?" question.

Single:
can-you-not: Can YOU not?
dark-theme-light-theme: Determines whether you use dark or light theme.
eat-pant: Eat pant.
eggs-get-laid: Sends the ultimate roast.
fly: Sends a fake fly that looks surprisngly real.
give-flower: Gives Xiao Pai a flower.
hi: Hello.
isnt-joke: Isn't joke...
its-joke: It's joke!
just-do-it: Sends a link to the "Just Do It!" motivational speech.
lenny: Responds with the lenny face.
spam: Responds with a picture of Spam.
tableflip: Flips a table... With animation!
wynaut: Why not? Wynaut?

Text-edit:
alphabet-reverse: Reverses the alphabet of text.
base64: Converts text to/from Base64.
binary: Converts text to/from binary.
braille: Converts text to braille.
brony-speak: Converts text to brony speak.
clap: Sends :clap: text :clap: like :clap: this.
cow-say: Makes a cow say your text.
cursive: Converts text to cursive.
dvorak: Converts text to Dvorak encoding.
emojify: Converts text to emoji form.
fancy: Converts text to fancy letters.
hex: Converts text to hex.
latlmes: Creates a Latlmes fake link that redirects to a rickroll.
lmgtfy: Creates a LMGTFY link with the query you provide.
lowercase: Converts text to lowercase.
md5: Creates a hash of text with the MD5 algorithm.
mocking: SenDs TexT lIkE ThiS.
morse: Converts text to morse code.
organization-xiii-name: Converts a name into the Organization XIII style.
owo: OwO.
pig-latin: Converts text to pig latin.
pirate: Converts text to pirate.
portal-send: Send a message to a portal channel.
repeat: Repeat text over and over and over and over (etc).
reverse: Reverses text.
say: Make me say what you want, master.
sha-1: Creates a hash of text with the SHA-1 algorithm.
sha-256: Creates a hash of text with the SHA-256 algorithm.
ship-name: Creates a ship name from two names.
shorten-url: Creates a goo.gl short URL from another URL.
shuffle: Shuffles text.
snake-speak: Convertsssss text to sssssnake ssssspeak.
superscript: Converts text to tiny text.
temmie: Converts text to Temmie speak.
translate: Translates text to a specific language.
uppercase: Converts text to uppercase.
upside-down: Flips text upside-down.
url-encode: Encodes text to URL-friendly characters.
webhook: Posts a message to the webhook defined in the bot owner's process.env.
yoda: Converts text to Yoda speak.
zalgo: Converts text to zalgo.

Stats:
userstats

Economy Stuff:
daily
balance
leaderboard
transfer
coinflip
dice
delete
work

Music:
play: Queues some music
queue: Shows the queue
pause: Pauses the music
resume: Resumes the music
stop: Stops the music
skip: Skips the music
volume {number}: Changes the volume
np: Shows the currently playing song

Image:
owo
baka
triggered
pout
awoo
blush
neko
sleepy
smile
greet
wag
cat
jojo
meow
avatar {@user}
dance
hug {@user}
cry
nom
dab
poi
shoot {@user}
cuddle {@user}
tickle {@user}
kiss {@user}
punch {@user}
pat {@user}
slap {@user}
likc {@user}
poke {@user}


```
