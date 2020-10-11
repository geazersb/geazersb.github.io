<head>    
    <link rel="icon" href="/favicon.ico" type="image/gif" >
</head>

## Preface
---

### Introduction
Welcome to the Geazer (Discord) Selfbot website. A Discrete, cheap and full of features discord selfbot made in Python! 
Some of our best features include: 
* Very fast nitro and privnote sniper (0.12s/0.15s) + more snipers ✓
* Custom commands, listeners and embeds ✓
* Creating and loading backups ✓
* Controlling hundreds of bot/user accounts (for raiding) ✓
* Loads of exploit/abuse commands ✓
* Extensive optimization and ingenuity (Abiding [PEP-8](https://www.python.org/dev/peps/pep-0008/ "PEP-8 definition") rules) ✓
* Cheap price ✓
* Frequent updates ✓
* Good support ✓
* Discrete webhooked logging ✓

### References
* Join our discord [here](https://discord.gg/ZGrYnNB "Support, suggestions, questions and more")
* Buy the selfbot [here](https://autobuy.io/@Geazer-Selfbot/Product/a2bb2869-46d4-48af-8f49-08d842cf9dbd "My autobuy.io shop")
* View our features quickly [here](https://pastebin.com/raw/7f4RHTeH "Discrete pastebin with features")

### Disclaimer
Using a selfbot is __against__ [discord TOS](https://support.discord.com/hc/en-us/articles/115002192352-Automated-user-accounts-self-bots- "TOS article on selfbots"). Though I have made this selfbot very __discrete__ by logging into a separate channel, and giving the option to disable embeds. You will __not__ be banned, unless you get reported with proof (e.g screen of embed/you saying you used abusive commands).

### Requirements
<details>
    <ul>
        <li>Python: <a href="https://www.python.org/ftp/python/3.8.5/python-3.8.5-amd64.exe">Python 3.8.5</a> </li>
        <li>OS: Windows 10 (64-bit), Linux distro, MacOS </li>
        <li>Having joined <a href="https://discord.gg/ZGrYnNB">our discord</a> </li>
        <li>Having an activation code </li>
    </ul>
</details>

## Features
---

### Commands
<details>
    <ul>
        <details>
            <summary>Abuse</summary>
            <li> charbypass  ⟶  Will send a ~6000 char long message </li>
            <li> glitchdescription &lt;channel&gt; ⟶  Will glitch a channels topic/description </li>
            <li> viewbot &lt;link&gt; [amount=50] ⟶  Will have &lt;amount&gt; bots viewing &lt;link&gt;, will work with ebay listings etc. </li>
            <li> maskmsg [m...] ⟶  Will hide a message inside another message. </li>
            <li> bantoken &lt;token&gt; ⟶  Will make a discord token invalid </li>
            <li> bantoken2 &lt;token&gt; ⟶  Will disable a discord account </li>
            <li> tokeninfo &lt;token&gt; ⟶  Will show information about a token </li>
            <li> tokenspam &lt;token&gt; [name=B̩̮̘y͍̲̤̳͔̰͈ ̠͎̩͉̫G͓̭̩͔͔̖̱e̟̩̦a͙̪͉̱̮̖ͅz̴̻̬͇̫e̼r̤̤͙̹̰̝] ⟶  Will flash someones screen and change settings by using their token </li>
            <li> destroyserver  ⟶  Will destroy a server by deleting it's channels and creating random new ones </li>
            <li> crashcall  ⟶  Base command for crashing calls </li>
            <ul>
                <li>  start  ⟶  Will start the callcrash by rapidly changing it's voice region </li>
            </ul>
            <ul>
                <li>  stop  ⟶  Will stop the callcrash. If command doesn't respond, try again in a different channel </li>
            </ul>
            <li> channel  ⟶  Base command for creating or removing a lot of channels in a guild </li>
            <ul>
                <li>  create &lt;amount&gt; &lt;type&gt; [name] ⟶  Will spam create specified amount of either tc or vc with specified name </li>
            </ul>
            <ul>
                <li>  remove &lt;amount&gt; ⟶  Will attempt to remove specified amount of channels in a guild </li>
            </ul>
            <li> role  ⟶  Base command for creating or removing a lot of roles in a guild </li>
            <ul>
                <li>  create &lt;amount&gt; [name] ⟶  Will create specified amount of roles with random colour and specified name </li>
            </ul>
            <ul>
                <li>  remove &lt;amount&gt; ⟶  Will attempt to remove specified amount of roles in a guild </li>
            </ul>
            <ul>
                <li>  add &lt;amount&gt; &lt;member&gt; ⟶  Will attempt to add &lt;amount&gt; of roles to specified member </li>
            </ul>
            <li> webhook  ⟶  Base command for creating webhooks, spamming with webhooks and stopping that spam. </li>
            <ul>
                <li>  delete2 &lt;webhookurl&gt; ⟶  Will delete any webhook using it's URL, including ones you shouldn't be able to delete </li>
            </ul>
            <ul>
                <li>  spam_stop  ⟶  Will stop the webhook spam </li>
            </ul>
            <ul>
                <li>  create [name=🤫] ⟶  Will create a webhook for the current channel, can be used to send messages with </li>
            </ul>
            <ul>
                <li>  send &lt;username&gt; &lt;avatar&gt; &lt;m&gt; ⟶  Will send a message with the created webhook </li>
            </ul>
            <ul>
                <li>  create2 &lt;amount&gt; &lt;mc&gt; &lt;dc&gt; [name=🤫] ⟶  Will spam create webhooks on channels by making it on one channel and moving it to another </li>
            </ul>
            <ul>
                <li>  spam_start  ⟶  Will spam (weak) insults with the created webhook as random guild members </li>
            </ul>
            <ul>
                <li>  send2 &lt;url&gt; &lt;username&gt; &lt;message&gt; ⟶  Will create a partial webhook from a wh URL and send messages with it </li>
            </ul>
            <ul>
                <li>  delete &lt;channel&gt; ⟶  Will delete all webhooks on a specific channel </li>
            </ul>
            <li> blocked  ⟶  Base command for sending messages to blocked users </li>
            <ul>
                <li>  send &lt;message&gt; ⟶  Will send a message to user that is blocked </li>
            </ul>
            <ul>
                <li>  setid [id] ⟶  Will set the (DM) channel to send messages to </li>
            </ul>
            <li> email  ⟶  Base command for adding emails and spamming targets with them </li>
            <ul>
                <li>  spam &lt;target&gt; &lt;amount&gt; &lt;message&gt; ⟶  Will spam &lt;target&gt; with &lt;amount&gt; emails containing &lt;message&gt; </li>
            </ul>
            <ul>
                <li>  add &lt;username&gt; &lt;password&gt; ⟶  Will add a email to the list of possible emails used to spam with </li>
            </ul>
            <ul>
                <li>  remove &lt;username&gt; ⟶  Will remove a email from the list of possible emails used to spam with </li>
            </ul>
            <ul>
                <li>  list  ⟶  Will log the amount of email:password combinations in file </li>
            </ul>
        </details>
        <details>
            <summary>Fun</summary>
            <li> embed &lt;title&gt; &lt;description&gt; ⟶  Will send a rainbow embed with &lt;title&gt; and &lt;description&gt; </li>
            <li> worm &lt;amount&gt; &lt;message&gt; ⟶  Will send your &lt;message&gt; &lt;amount&gt; times in the form of a sinewave </li>
            <li> snipe [channel] ⟶  Will send the latest deleted message from any guild text channel </li>
            <li> dice  ⟶  Will send a random dice image </li>
            <li> fact  ⟶  Will send a random fact </li>
            <li> emojify &lt;emote&gt; &lt;message&gt; ⟶  Will send a message joining your input with &lt;emote&gt; </li>
            <li> combine &lt;word1&gt; &lt;word2&gt; ⟶  Will combine &lt;word1&gt; and &lt;word2&gt; into one word </li>
            <li> novowel &lt;message&gt; ⟶  Will send a &lt;message&gt; with all vowels removed from your input </li>
            <li> vowelreplace &lt;letter&gt; &lt;message&gt; ⟶  Will send a &lt;message&gt; where it's vowels are placed with &lt;letter&gt; </li>
            <li> 1337 &lt;message&gt; ⟶  Will send your &lt;message&gt; as leet (unreadable) </li>
            <li> uni &lt;message&gt; ⟶  Will send bold letters for each letter/number/!? in your input </li>
            <li> gif &lt;message&gt; ⟶  Will send dancing letters in gifs for each letter/number/!@$& of your input </li>
            <li> invis &lt;message&gt; ⟶  Will convert each letter from your input to be invisible </li>
            <li> reverse &lt;message&gt; ⟶  Will send the input &lt;message&gt; reversed </li>
            <li> ascii &lt;random&gt; &lt;message&gt; ⟶  Will convert your &lt;message&gt; to look like ascii art </li>
            <li> edit &lt;message&gt; ⟶  Will edit &lt;message&gt; to show a new letter </li>
            <li> lmgtfy &lt;message&gt; ⟶  Will send a let me google that for the &lt;message&gt; </li>
            <li> poll &lt;message&gt; ⟶  Will create poll with the &lt;message&gt; </li>
            <li> 8ball &lt;question&gt; ⟶  Will pick a random response from a list </li>
            <li> notfunny  ⟶  Will send a not funny message (~2100 chars) </li>
            <li> editnick  ⟶  Base command for editing through a nickname untill stopped </li>
            <ul>
                <li>  start &lt;nickname&gt; ⟶  Will loop through &lt;nickname&gt; and reveal a new letter every second and reset untill stopped </li>
            </ul>
            <ul>
                <li>  stop  ⟶  Will stop the editnick and return to the old nickname </li>
            </ul>
            <li> cyclestatus  ⟶  Base command for cycling through a set of statuses periodically </li>
            <ul>
                <li>  stop  ⟶  Will stop the cyclestatus </li>
            </ul>
            <ul>
                <li>  start &lt;interval&gt; [statuses...] ⟶  Will cycle trough a list of &lt;statuses&gt; and change every &lt;interval&gt; seconds untill stopped </li>
            </ul>
            <li> joke  ⟶  Base command for sending jokes </li>
            <ul>
                <li>  programming  ⟶  Will send a random programming related joke from sv443.net/jokeapi </li>
            </ul>
            <ul>
                <li>  dad  ⟶  Will send a random dad joke from icanhazdadjoke.com </li>
            </ul>
            <ul>
                <li>  misc  ⟶  Will send a random miscellaneous joke from sv443.net/jokeapi </li>
            </ul>
            <ul>
                <li>  dark  ⟶  Will send a random dark joke from sv443.net/jokeapi </li>
            </ul>
            <ul>
                <li>  pun  ⟶  Will send a random pun joke from sv443.net/jokeapi </li>
            </ul>
        </details>
        <details>
            <summary>Help</summary>
            <li> showall  ⟶  Will link to a pastebin showing all the commands </li>
            <li> help [command] ⟶  Shows this message </li>
        </details>
        <details>
            <summary>Images</summary>
            <li> whowouldwin &lt;user1&gt; &lt;user2&gt; ⟶  Will send an image with the profile pictures of the provided users </li>
            <li> avatar &lt;user&gt; ⟶  Will send a enlarged users avatar in chat </li>
            <li> spongebob &lt;random&gt; &lt;message&gt; ⟶  Will send an image of mocking spongebob by default, or another random one </li>
            <li> cat  ⟶  Will send a random cat image </li>
            <li> dog  ⟶  Will send a random dog image </li>
            <li> random_screen  ⟶  Will send a random screen from prnt.sc, not guaranteed to contain anything </li>
            <li> phcomment &lt;user&gt; &lt;message&gt; ⟶  Will send an image containing a pornhub comment by the &lt;user&gt;'s profile picture saying &lt;message&gt; </li>
            <li> changemymind &lt;message&gt; ⟶  Will send an image with in the change my mind meme context with the text input </li>
            <li> magik  ⟶  Base command for magikyzing user profile pictures and other images </li>
            <ul>
                <li>  image &lt;link&gt; [intensity=5] ⟶  Will send the &lt;link&gt;'s image deformed with &lt;intensity&gt; </li>
            </ul>
            <ul>
                <li>  user &lt;user&gt; [intensity=5] ⟶  Will send the &lt;user&gt;'s profile picture deformed with &lt;intensity&gt; </li>
            </ul>
            <li> blurpify  ⟶  Base command for blurpifying user profile pictures and other images </li>
            <ul>
                <li>  user &lt;user&gt; ⟶  Will send the &lt;user&gt;'s users profile picture deformed </li>
            </ul>
            <ul>
                <li>  image &lt;link&gt; ⟶  Will send the &lt;link&gt;'s image deformed </li>
            </ul>
            <li> deepfry  ⟶  Base command for deepfrying user profile pictures and other images </li>
            <ul>
                <li>  user &lt;user&gt; ⟶  Will send the &lt;user&gt;'s profile picture deepfried </li>
            </ul>
            <ul>
                <li>  image &lt;link&gt; ⟶  Will send the &lt;link&gt;'s image deepfried </li>
            </ul>
            <li> tweet  ⟶  Base command for sending tweets as trump or normal </li>
            <ul>
                <li>  normal &lt;username&gt; &lt;message&gt; ⟶  Will send an image with the input text as a tweet </li>
            </ul>
            <ul>
                <li>  trump &lt;message&gt; ⟶  Will send an image with the input text as a tweet </li>
            </ul>
        </details>
        <details>
            <summary>IPTools</summary>
            <li> ipinfo &lt;host&gt; ⟶  Will display information about a host by ip/hostname </li>
            <li> unshorten &lt;link&gt; ⟶  Wil unshorten ad.fly, sh.st and adfoc.us links, they might've patched this idk </li>
            <li> icmpping &lt;host&gt; ⟶  Will ICMP ping &lt;host&gt; using ICMP packets </li>
            <li> tcpping &lt;host&gt; [port=80] ⟶  Will ping &lt;host&gt; on port &lt;port&gt; using TCP packets </li>
            <li> dnsresolve &lt;apikey&gt; [hostnames..] ⟶  Will resolve a DNS by hostname </li>
            <li> showheaders &lt;apikey&gt;  ⟶  Will show the HTTP headers that your client sends when connecting to a webserver </li>
            <li> portscan &lt;apikey&gt; &lt;host&gt; ⟶  Will scan the common ports of a &lt;host&gt;. </li>
            <li> traceroute &lt;apikey&gt; &lt;host&gt; ⟶  Will determine what servers data traverses through before reaching the &lt;host&gt; </li>
            <li> maclookup &lt;apikey&gt; &lt;mac&gt; ⟶  Will search for the manufacturer of a product based on it's MAC address </li>
            <li> proxies  ⟶  Base command for sending txt files containing proxies </li>
            <ul>
                <li>  socks5 [proxytimeoutms=1000] ⟶  Scrapes socks5 proxies (IP:PORT) and sends the file in chat </li>
            </ul>
            <ul>
                <li>  http [proxytimeoutms=1000] ⟶  Scrapes HTTP proxies (IP:PORT) and sends the file in chat </li>
            </ul>
            <ul>
                <li>  https [proxytimeoutms=1000] ⟶  Scrapes HTTPS proxies (IP:PORT) and sends the file in chat </li>
            </ul>
            <ul>
                <li>  socks4 [proxytimeoutms=1000] ⟶  Scrapes socks4 proxies (IP:PORT) and sends the file in chat </li>
            </ul>
        </details>
        <details>
            <summary>Other</summary>
            <li> eval &lt;body&gt; ⟶  Will evaluate python code and discord.py code. This means you can basically run any script anywhere anytime. </li>
            <li> fakeperson [gender] [nationality] ⟶  Will generate a random person with &lt;nationality&gt; and &lt;gender&gt; </li>
            <li> metrics  ⟶  Will show the top 10 most used commands by you in a graph in an embed </li>
            <li> exportchat  ⟶  Will backup an entire chat history as an HTML file </li>
            <li> channelinfo [serverid] ⟶  Will show all channels in a guild and send it to logging channel </li>
            <li> roleinfo &lt;role&gt; ⟶  Will show information about the specified &lt;role&gt; </li>
            <li> serverinfo [serverid] ⟶  Will display some information about a server in your logging channel </li>
            <li> userinfo [user] ⟶  Will show the specified &lt;user&gt;s account data </li>
            <li> emojiinfo  ⟶  Will list all the emotes in a server </li>
            <li> pinfo  ⟶  Will show the process info of your bot, including cpu usage, memory usage and latencies </li>
            <li> declineall  ⟶  Will decline all incoming friend requests </li>
            <li> reload  ⟶  Will reload all cogs </li>
            <li> getavatars &lt;guildid&gt; ⟶  Will scrape all avatars in a guild for the random avatars list </li>
            <li> getemojis &lt;fromguildid&gt; &lt;toguildid&gt; ⟶  Will scrape all emojis from &lt;fromguildid&gt; guild and put them in &lt;toguildid&gt; guild </li>
            <li> settings  ⟶  Base command for changing your selfbot settings </li>
            <ul>
                <li>  embed &lt;embed&gt; &lt;state&gt; ⟶  Will enable or disable sending some command output in embeds. </li>
            </ul>
            <ul>
                <li>  sniping &lt;sniping&gt; &lt;state&gt; ⟶  Will enable or disable sniping discordgifts, privnotes, tokens and giveaways </li>
            </ul>
            <li> cc  ⟶  Base command for adding/removing/listing all the custom commands </li>
            <ul>
                <li>  add &lt;commandname&gt; &lt;content&gt; ⟶  Will add the custom command named &lt;command_name&gt; sending &lt;content&gt; </li>
            </ul>
            <ul>
                <li>  remove &lt;commandname&gt; ⟶  Will remove the custom command named &lt;command_name&gt;  </li>
            </ul>
            <ul>
                <li>  list  ⟶  Will list all the custom command names </li>
            </ul>
            <li> backup  ⟶  Base command for making and loading backups </li>
            <ul>
                <li>  make  ⟶  Sub-base command for backing up friends, blocked users and joined servers </li>
            </ul>
            <ul>
                <ul>
                    <li> friends  ⟶  Will create a backup of all your friends in a txt file as ids </li>
                    <li> blocked  ⟶  Will create a backup of all your blocked users in a txt file as ids </li>
                    <li> servers  ⟶  Will create a backup of all your joined servers in a txt file as invites </li>
                </ul>
            </ul>
            <ul>
                <li>  load  ⟶  Sub-base command for adding backed up friends, blocking blocked users and joining servers </li>
            </ul>
            <ul>
                <ul>
                    <li> friends  ⟶  Will add all friends from the backed up txt file </li>
                    <li> blocked  ⟶  Will block all users from the backed up txt file </li>
                    <li> servers  ⟶  Will join all servers from the backed up txt file </li>
                </ul>
            </ul>
        </details>
        <details>
            <summary>Raid</summary>
            <li> raid  ⟶  Base command for logging and and logging out all the raid accounts </li>
            <ul>
                <li>  amount  ⟶  Will give the amount of id:token combinations </li>
            </ul>
            <ul>
                <li>  add [tokens...] ⟶  Will add tokens to the list of useraccounts that can be used to log in </li>
            </ul>
            <ul>
                <li>  logout  ⟶  Will log out all the raid user instances accounts  </li>
            </ul>
            <ul>
                <li>  remove [ids...] ⟶  Will remove the specified token from the json file </li>
            </ul>
            <ul>
                <li>  login [type=False]  ⟶  Will log in all the raid accounts (bot or user) from the user account and join your guild </li>
            </ul>
        </details>
        <details>
            <summary>Trolling</summary>
            <li> virus  ⟶  Will send an editing virus message </li>
            <li> stfu  ⟶  Will send an editing stfu message </li>
            <li> noonecares  ⟶  Will send an editing no one cares message </li>
            <li> 911  ⟶  Will send an editing 911 image </li>
            <li> cum  ⟶  Will send an editing masturbating image 😳 </li>
            <li> tokencalc &lt;user&gt; ⟶  Will calculate the first part of a users token based on their account information </li>
            <li> glitchmention [length=1977] ⟶  Will send a &lt;length&gt; long mention looking message </li>
            <li> typing  ⟶  Will make it look like you are typing indefinitely (Send a message to make it stop) </li>
            <li> freenitro [customurl] [gifurl] ⟶  Will send an embedded gif that if added to favourites will send the customurl gif instead</li>
            <li> editpos &lt;message&gt; ⟶  Will send a &lt;message&gt; where it's edited tag is on the left instead of right </li>
            <li> massping  ⟶  Will massping everybody in the guild (in groups of 100) </li>
            <li> spam &lt;amount&gt; &lt;message&gt; ⟶  Will send &lt;message&gt; &lt;amount&gt; times in a row </li>
            <li> uclone &lt;user&gt; ⟶  Will copy &lt;user&gt;'s nick/pfp/role else username/pfp </li>
            <li> blank  ⟶  Base command for sending ~2000 char long whitespace message </li>
            <ul>
                <li>  guild  ⟶  Will send a ~2000 char long blank message after every message send in a guild </li>
            </ul>
            <li> noleave  ⟶  Base command for instantly adding users back after leaving a group channel </li>
            <ul>
                <li>  user &lt;user&gt; ⟶  Will instantly add the &lt;user&gt; back to the group channel upon leaving. </li>
            </ul>
            <ul>
                <li>  stop  ⟶  Will allow user to leave the group channel again </li>
            </ul>
            <li> annoy  ⟶  Base command for annoying entire guilds or specific users by reacting with emoji's and stopping that listener</li>
            <ul>
                <li>  user &lt;user&gt; [emojis...] ⟶  Will react with &lt;emojis&gt; to every message &lt;user&gt; </li>
            </ul>
            <ul>
                <li>  guild [emojis...] ⟶  Will attempt to react with &lt;emojis&gt; to every send message in current guild </li>
            </ul>
            <ul>
                <li>  stop  ⟶  Will stop all annoy listeners </li>
            </ul>
            <li> copy  ⟶  Base command for copying users messages or channels messages and stopping that listener</li>
            <ul>
                <li>  user &lt;user&gt; [message] ⟶  Will copy every &lt;user&gt;'s message by default, else it will send the provided &lt;message&gt; </li>
            </ul>
            <ul>
                <li>  channel &lt;channel&gt; [message] ⟶  Will copy everybody in &lt;channel&gt; or send the provided &lt;message&gt; </li>
            </ul>
            <ul>
                <li>  stop  ⟶  Will stop the copy listener </li>
            </ul>
            <li> step  ⟶  Base command step reacting to a user and stopping that listener </li>
            <ul>
                <li>  user &lt;user&gt; [message...] ⟶  Will step through &lt;message&gt; by sending it word for word after every message by &lt;user&gt; </li>
            </ul>
            <ul>
                <li>  stop  ⟶  Will stop all step listeners </li>
            </ul>
            <li> automute  ⟶  Base command for automuting members and stopping that listener </li>
            <ul>
                <li>  start &lt;member&gt; ⟶  Will start automatically muting &lt;member&gt; every time they unmute </li>
            </ul>
            <ul>
                <li>  stop  ⟶  Will stop all automute listeners </li>
            </ul>
            <li> autodeafen  ⟶  Base command for automuting members and stopping that listener </li>
            <ul>
                <li>  start &lt;member&gt; ⟶  Will start automatically muting &lt;member&gt; every time they unmute </li>
            </ul>
            <ul>
                <li>  stop  ⟶  Will stop all autodeafen listeners </li>
            </ul>
        </details>
        <details>
            <summary>Utilities</summary>
            <li> youtubesearch &lt;search&gt; ⟶  Will search for a video on YouTube by given title </li>
            <li> tobtc &lt;amount&gt; [currencycode=USD] ⟶  Will convert provided currency to it's bitcoin equivalent </li>
            <li> btc [currencycode=USD] ⟶  Will convert a bitcoin to the provided currency equivalent </li>
            <li> commandtimer &lt;interval&gt; &lt;amount&gt; &lt;command&gt; ⟶  Will use &lt;command&gt; every &lt;interval&gt; seconds &lt;amount&gt; times </li>
            <li> timer &lt;time&gt; &lt;interval&gt; ⟶  Will count down from &lt;_time&gt; and update in an embed every &lt;interval&gt; seconds </li>
            <li> nitro &lt;amount&gt; ⟶  Will generate &lt;amount&gt; discord nitro codes </li>
            <li> invite &lt;amount&gt; ⟶  Will generate &lt;amount&gt; discord invites </li>
            <li> tinyurl &lt;link&gt; ⟶  Will generate and send a tinyurl link from &lt;link&gt; </li>
            <li> charinfo &lt;message&gt; ⟶  Will send info about your &lt;message&gt; unicode </li>
            <li> urban &lt;search&gt; ⟶  Will search your &lt;search&gt; on urban dictionary and send its definition </li>
            <li> purge &lt;amount&gt; [keywords...] ⟶  Will delete &lt;amount&gt; of messages send by, can filter to &lt;keywords&gt; </li>
            <li> rand &lt;num1&gt; &lt;num2&gt; ⟶  Will send a random number between &lt;num1&gt; and &lt;num2&gt; </li>
            <li> passgen &lt;length&gt; ⟶  Will generate a random password with &lt;length&gt; long </li>
            <li> logout  ⟶  Will log out the self bot </li>
            <li> reboot  ⟶  Will restart the selfbot </li>
            <li> reverse_search &lt;user&gt; ⟶  Will reverse image search the &lt;user&gt; profile picture with google </li>
            <li> loop  ⟶  Base command for looping messages </li>
            <ul>
                <li>  start &lt;delay&gt; &lt;message&gt; ⟶  Will start the loop function with the given &lt;delay&gt; and &lt;message&gt; </li>
            </ul>
            <ul>
                <li>  stop  ⟶  Will stop the currently playing loop function </li>
            </ul>
            <li> dstatus  ⟶  Base command for changing your discord status </li>
            <ul>
                <li>  playing &lt;message&gt; ⟶  Will change your status playing &lt;message&gt; </li>
            </ul>
            <ul>
                <li>  listening &lt;message&gt; ⟶  Will change your status to listening to &lt;message&gt; </li>
            </ul>
            <ul>
                <li>  watching &lt;message&gt; ⟶  Will change your status to watching &lt;message&gt; </li>
            </ul>
            <ul>
                <li>  streaming &lt;streamurl&gt; &lt;message&gt; ⟶  Will change your status to streaming &lt;message&gt; with link &lt;stream_url&gt; </li>
            </ul>
            <li> autodel  ⟶  Base command for automatically deleting any (new) messages send by you over the provided limit </li>
            <ul>
                <li>  start &lt;limit&gt; ⟶  Will delete any messages send by you over the provided &lt;limit&gt; </li>
            </ul>
            <ul>
                <li>  stop  ⟶  Will stop the autodelete messages </li>
            </ul>
            <li> clistener  ⟶  Base command for adding custom listeners for words globally or guild specifically </li>
            <ul>
                <li>  start &lt;guild&gt; [keywords...] ⟶  Will start a custom listener for specified words </li>
            </ul>
            <ul>
                <li>  stop  ⟶  Will stop all custom listeners </li>
            </ul>
        </details>
    </ul>
</details>
  
### Events
<details>
    <ul>
        <details>
            <summary>Nitro sniper</summary>
            Our nitro sniper has build in anti-spam methods, you won't ever be banned by using this!
            The speed (depending on your internetspeed and discords server load) is between 0.12s and 0.15s from beginning to end.
        </details>
        <details>
            <summary>Privnote sniper</summary>
            The privnotes snipe speed are about the same as the nitro snipe speeds. The contents of these privnotes
            are saved in a folder in .txt files.
        </details>
        <details>
            <summary>Token sniper</summary>
            If someone pastes a bot or user token, it will instantly be logged to the logging channel.
        </details>
        <details>
            <summary>Giveaway sniper</summary>
            If there is a giveaway from one of the 4 recognized bots, it will attempt to join it by reacting
            with the emote after a random delay.
        </details>
        <details>
            <summary>Auto delete</summary>
            Every sentence/word starting with your custom prefix will instantly be deleted. There is no way to turn this off.
        </details>
    </ul>
</details>

### Other
<details>
    <ul>
        <details>
            <summary>Customizability</summary>
            <ul>
                <li> Some commands could send their output in an embed form depending on whether you have enabled that.
                     If so, you can specify the footer icon, text and colour it will show up with. 
                </li>
                <li>The prefix is customizable as well</li>
            </ul>
        </details>
        <details>
            <summary>Extensions</summary>
            I have made 2 optional extensions. This includes the Moderation (8 commands) and the NSFW extension (2 commands).
            They can be downloaded in our guild upon buying the selfbot.
        </details>  
    </ul>
</details>

<img style="float: right;" src="https://i.imgur.com/UsrLN7k.gif" width="150" height="150" />
