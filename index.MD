<head>
    <script src="https://autobuy.io/js/embed.min.js"></script>
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon"/>
    <meta property="og:image" content="https://i.imgur.com/shO8dws.png"/>
</head>

<h1 name="top" style="background: -webkit-linear-gradient(#c45e62, #28526d); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">Preface</h1>
---

<h3 name="introduction">Introduction</h3>
Welcome to the Geazer (Discord) Selfbot website. A cheap and full of features discord selfbot made in Python, made by Buster.

Some of our best features include:
<details open>
<summary>open/close</summary>
    <ul>
        <li> Fast nitro and privnote sniper (<a target="_blank" title="Snipe speeds" href="https://i.imgur.com/GZ8uR5W.png">~0.15s</a>) and more ✓ </li>
        <li> Custom commands, listeners and embeds ✓ </li>
        <li> Creating and loading backups ✓ </li>
        <li> Great semi-interactive <a target="_blank" title="Help command screenshots" href="https://imgur.com/a/MRppIAw">help command</a> ✓ </li>
        <li> Controlling hundreds of bot/user accounts (for raiding) ✓ </li>
        <li> Loads of exploit/abuse commands ✓ </li>
        <li> Extensive optimization and ingenuity (abiding <a target="_blank" title="PEP-8 definition" href="https://www.python.org/dev/peps/pep-0008/">PEP-8</a> rules) ✓ </li>
        <li> Cheap price ✓ </li>
        <li> Frequent updates ✓ </li>
        <li> Good support ✓ </li>
        <li> Discrete webhooked <a target="_blank" title="Webhook logging screenshot" href="https://i.imgur.com/8uR38X2.png">logging</a> ✓ </li>
        <li> <b>And in total over 210 commands! ✓</b> </li>
    </ul>
</details>

<h3 name="references">References</h3>
<details open>
<summary>open/close</summary>
    <ul>
        <li> Join our discord <a target="_blank" title="Support, suggestions, questions and more" href="https://discord.gg/ZGrYnNB">here</a> (<a target="_blank" title="Support, suggestions, questions and more" href="https://discord.gg/22fZqtp">backup</a>)</li>
        <li> View our shop <a target="_blank" title="My autobuy.io shop" href="https://autobuy.io/@Geazer-Selfbot/Product/a2bb2869-46d4-48af-8f49-08d842cf9dbd">here</a> </li>
        <li> View our features quickly <a target="_blank" title="Clear pastebin listing of commands" href="https://pastebin.com/raw/7f4RHTeH">here</a> </li>
    </ul>
</details>

<h3 name="requirements">Requirements</h3>
<details>
<summary>open/close</summary>
    <ul>
        <li>Python: <a target="_blank" title="Direct Python install" href="https://www.python.org/ftp/python/3.8.5/python-3.8.5-amd64.exe">Python 3.8.5</a> </li>
        <li>OS: Windows 10 (64-bit), Linux distro, MacOS </li>
        <li>Having joined <a target="_blank" title="Invite to our Discord" href="https://discord.gg/ZGrYnNB">our discord</a> </li>
        <li>Having an activation code (can be obtained after buying), is based on your HWID</li>
    </ul>
</details>

<h3 name="disclaimer">Disclaimer</h3>
<details>
<summary>open/close</summary>
    <ul>
    <li> Using a selfbot is <b>against</b> Discord's <a target="_blank" title="Discord article on Selfbots" href="https://support.discord.com/hc/en-us/articles/115002192352-Automated-user-accounts-">TOS</a>. Though I have made this selfbot very <b>discrete</b> by logging into a 
separate channel, and giving the option to disable embeds. You will <b>not</b> be banned,
    <b>unless</b> you get <b>reported with proof</b> (e.g screen of embed/you saying you used abusive commands). </li>
    </ul>
</details>

<h3 name="buying">Buying</h3>
The selfbot can be bought on autobuy.io, or right here using the button below. Right now I accept PayPal as the only payment method, though some crypto currency will be accepted soon!

<button class="button button" data-autobuy-product="a2bb2869-46d4-48af-8f49-08d842cf9dbd">Buy now!</button>

<h1 name="features" style="background: -webkit-linear-gradient(#c45e62, #28526d); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">Features</h1>
---

<h3>Commands</h3>

<details open>
<summary> open/close </summary>
    <ul>
    <p> Arguments within greater/smaller than signs (<>) are required, arguments within brackets ([]) are optional. </p>
        <details>
        <summary> Abuse </summary>
        <ul>
        <p> Category with all abuse commands, these include discord exploits and should be used with caution </p>
            <li> charbypass ⟶  Will send a ~6000 char long message </li>
            <li> glitchdescription ⟶  Will glitch a channels topic/description by using a weird link </li>
            <li> maskmsg ⟶  Will hide a message inside another message. The last word will be the hidden word/link/mention etc </li>
            <li> bantoken ⟶  Will make a discord token invalid by uploading it to a public GitHub repo </li>
            <li> deleteaccount ⟶  Will DELETE someones discord account by using their &lt;token&gt; and &lt;password&gt; </li>
            <li> disableaccount ⟶  Will DISABLE someones discord account by using their &lt;token&gt; and &lt;password&gt; </li>
            <li> tokeninfo ⟶  Will show information about a token </li>
            <li> tokenspam ⟶  Will flash screen and changes settings of account by using its token </li>
            <li> destroyserver ⟶  Will destroy a server by banning users, deleting and creating channels/roles </li>
            <li> massban ⟶  Will attempt to ban everybody in specified &lt;guild_id&gt;, ids in [exclusions...] will be ignored </li>
            <li> masskick ⟶  Will attempt to kick everybody in specified &lt;guild_id&gt;, ids in [exclusions...] will be ignored </li>
            <li> massrename ⟶  Will attempt to rename everybody to &lt;nickname&gt; in specified &lt;guild_id&gt; </li>
            <li> crashcall ⟶  Base command for crashing calls </li>
            <ul>
                <li> start ⟶  Will start the callcrash by rapidly changing it's voice region. Works in DMs and groupchannels </li>
                <li> stop ⟶  Will stop the callcrash. If command doesn't respond, try again in a different channel </li>
            </ul>
            <li> channel ⟶  Base command for creating or removing a lot of channels in a guild </li>
            <ul>
                <li> create ⟶  Will spam create specified amount of either tc or vc with specified name </li>
                <li> remove ⟶  Will attempt to remove specified amount of channels in a guild </li>
            </ul>
            <li> role ⟶  Base command for creating or removing a lot of roles in a guild </li>
            <ul>
                <li> create ⟶  Will create &lt;amount&gt; roles with random a colour named &lt;name&gt; </li>
                <li> remove ⟶  Will attempt to remove specified amount of roles in a guild </li>
                <li> add ⟶  Will attempt to add &lt;amount&gt; of roles to &lt;member&gt;, can filter by &lt;name&gt; </li>
            </ul>
            <li> webhook ⟶  Base command for doing stuff with discord webhooks </li>
            <ul>
                <li> spam_start ⟶  Will spam insults with the created webhook as random guild members </li>
                <li> send2 ⟶  Will create a partial webhook from a wh URL and send messages with it </li>
                <li> delete ⟶  Will delete all webhooks on a specific channel </li>
                <li> delete2 ⟶  Will delete any webhook using it's URL </li>
                <li> spam_stop ⟶  Will stop the webhook spam </li>
                <li> create ⟶  Will create a webhook for the current channel, can be used to send messages with </li>
                <li> send ⟶  Will send a message with the created webhook, works from anywhere in discord </li>
                <li> create2 ⟶  Will spam create webhooks on channels exceeding the 10 wh cap </li>
            </ul>
            <li> blocked ⟶  Base command for sending messages to blocked users </li>
            <ul>
                <li> setid ⟶  Will set the (DM) channel to send messages to </li>
                <li> send ⟶  Will send a message to user that is blocked </li>
            </ul>
            <li> email ⟶  Base command for adding emails and spamming targets with them </li>
            <ul>
                <li> add ⟶  Will add a email to the list of possible emails used to spam with </li>
                <li> remove ⟶  Will remove a email from the list of possible emails used to spam with </li>
                <li> list ⟶  Will log all the email:password email combinations </li>
                <li> spam ⟶  Will spam &lt;target&gt; with &lt;amount&gt; emails containing &lt;message&gt; </li>
            </ul>
        </ul>
        </details>
        <details>
        <summary> Fun </summary>
        <ul>
        <p> Category with fun commands, these are mostly text based </p>
            <li> rembed ⟶  Will send an embed with &lt;title&gt; and &lt;description&gt;, who's colour will change every 3 seconds </li>
            <li> nitro ⟶  Will generate &lt;amount&gt; random discord nitro codes </li>
            <li> invite ⟶  Will generate &lt;amount&gt; random discord invites </li>
            <li> worm ⟶  Will send your &lt;message&gt; &lt;amount&gt; times in the form of a wave </li>
            <li> dice ⟶  Will send a random dice image </li>
            <li> fact ⟶  Will send a random useless fact </li>
            <li> emojify ⟶  Will send a message joining your input with &lt;emote&gt; </li>
            <li> embed ⟶  Will allow you to specify certain embed parts </li>
            <li> furrify ⟶  Will convert your &lt;message&gt; into a cancerous incel message </li>
            <li> combine ⟶  Will combine &lt;word1&gt; and &lt;word2&gt; into one word </li>
            <li> novowel ⟶  Will send a &lt;message&gt; with all vowels removed from your input </li>
            <li> letterreplace ⟶  Will replace &lt;letter1&gt; with &lt;letter2&gt; in &lt;message&gt; </li>
            <li> binary ⟶  Will convert your &lt;message&gt; to binary (1s and 0s) </li>
            <li> 1337 ⟶  Will send your &lt;message&gt; as leet (unreadable) </li>
            <li> uni ⟶  Will send bold letters for each letter/number/!? in your &lt;message&gt; </li>
            <li> gif ⟶  Will send dancing letters in gifs for each letter/number/!@$& of your &lt;message&gt; </li>
            <li> invis ⟶  Will convert each letter from your input to be invisible </li>
            <li> reverse ⟶  Will send the input &lt;message&gt; reversed </li>
            <li> ascii ⟶  Will convert your &lt;message&gt; to look like ascii art </li>
            <li> edit ⟶  Will edit &lt;message&gt; to show a new letter </li>
            <li> lmgtfy ⟶  Will send a let me google that for the &lt;message&gt; </li>
            <li> poll ⟶  Will create poll with the &lt;message&gt; </li>
            <li> 8ball ⟶  Will pick a random response from a list </li>
            <li> notfunny ⟶  Will send a not funny message (~2100 chars) </li>
            <li> editnick ⟶  Base command for editing through a nickname untill stopped </li>
            <ul>
                <li> start ⟶  Will loop through &lt;nickname&gt; and reveal a new letter every second and reset untill stopped </li>
                <li> stop ⟶  Will stop the editnick and return to the old nickname </li>
            </ul>
            <li> snipe ⟶  Will send the latest deleted message from any guild channel </li>
            <li> cyclestatus ⟶  Base command for cycling through a set of statuses periodically </li>
            <ul>
                <li> start ⟶  Will cycle trough a list of &lt;statuses&gt; and change every &lt;interval&gt; seconds untill stopped </li>
                <li> stop ⟶  Will stop the cyclestatus listener </li>
            </ul>
            <li> joke ⟶  Base command for sending jokes </li>
            <ul>
                <li> programming ⟶  Will send a random programming related joke from [this website](https://sv443.net/jokeapi) </li>
                <li> dad ⟶  Will send a random dad joke from [this website](https://icanhazdadjoke.com) </li>
                <li> misc ⟶  Will send a random miscellaneous joke from [this website](https://sv443.net/jokeapi) </li>
                <li> dark ⟶  Will send a random dark joke from [this website](https://sv443.net/jokeapi) </li>
                <li> pun ⟶  Will send a random pun joke from [this website](https://sv443.net/jokeapi) </li>
            </ul>
        </ul>
        </details>
        <details>
        <summary> Images </summary>
        <ul>
        <p> Category will all commands that allow images as input and will return a modified result </p>
            <li> whowouldwin ⟶  Will send an image with the profile pictures of &lt;user1&gt; and &lt;user2&gt; </li>
            <li> avatar ⟶  Will send a enlarged users avatar in chat </li>
            <li> spongebob ⟶  Will send an image of mocking spongebob or with &lt;message&gt; </li>
            <li> cat ⟶  Will send a random cat image </li>
            <li> dog ⟶  Will send a random dog image </li>
            <li> random_screen ⟶  Will send a random screen from prnt.sc, not guaranteed to contain anything </li>
            <li> phcomment ⟶  Will send an image containing a pornhub comment by the &lt;user&gt; saying &lt;message&gt; </li>
            <li> changemymind ⟶  Will send an image with in the change my mind meme saying &lt;message&gt; </li>
            <li> magik ⟶  Base command for magikyzing user profile pictures and other images </li>
            <ul>
                <li> user ⟶  Will send the &lt;user&gt;'s profile picture magikized with &lt;intensity&gt; </li>
                <li> image ⟶  Will send the &lt;link&gt;'s image magikized with &lt;intensity&gt; </li>
            </ul>
            <li> blurpify ⟶  Base command for blurpifying user profile pictures and other images </li>
            <ul>
                <li> user ⟶  Will send the &lt;user&gt;'s users profile picture blurpified </li>
                <li> image ⟶  Will send the &lt;link&gt;'s image blurpified </li>
            </ul>
            <li> deepfry ⟶  Base command for deepfrying user profile pictures and other images </li>
            <ul>
                <li> user ⟶  Will send the &lt;user&gt;'s profile picture deepfried </li>
                <li> image ⟶  Will send the &lt;link&gt;'s image deepfried </li>
            </ul>
            <li> tweet ⟶  Base command for sending tweets as trump or normal </li>
            <ul>
                <li> normal ⟶  Will send an image with the input text as a tweet </li>
                <li> trump ⟶  Will send an image with the input text as a tweet </li>
            </ul>
        </ul>
        </details>
        <details>
        <summary> Iptools </summary>
        <ul>
        <p> Category for all commands that have to do with IPs </p>
            <li> ipinfo ⟶  Will display information about &lt;host&gt; </li>
            <li> unshorten ⟶  Wil unshorten ad.fly, sh.st and adfoc.us links </li>
            <li> icmpping ⟶  Will ping &lt;host&gt; using ICMP packets </li>
            <li> tcpping ⟶  Will ping &lt;host&gt; on port &lt;port&gt; using TCP packets </li>
            <li> dnsresolve ⟶  Will resolve a DNS by hostname </li>
            <li> showheaders ⟶  Will show the HTTP headers that your client sends when connecting to a webserver </li>
            <li> portscan ⟶  Will scan the common ports of a &lt;host&gt; </li>
            <li> traceroute ⟶  Will determine what servers data traverses through before reaching the &lt;host&gt; </li>
            <li> maclookup ⟶  Will search for the manufacturer of a product based on it's &lt;mac&gt; address </li>
            <li> screenwebsite ⟶  Will send a screenshot of a website with the provided &lt;url&gt; </li>
            <li> proxies ⟶  Base command for sending txt files containing proxies </li>
            <ul>
                <li> http ⟶  Scrapes HTTP proxies (IP:PORT) and sends the file in chat </li>
                <li> https ⟶  Scrapes HTTPS proxies (IP:PORT) and sends the file in chat </li>
                <li> socks4 ⟶  Scrapes socks4 proxies (IP:PORT) and sends the file in chat </li>
                <li> socks5 ⟶  Scrapes socks5 proxies (IP:PORT) and sends the file in chat </li>
            </ul>
        </ul>
        </details>
        <details>
        <summary> Other </summary>
        <ul>
        <p> Category for all commands without a specific category </p>
            <li> eval ⟶  Will evaluate python code, with discord.py env variables in place </li>
            <li> declineall ⟶  Will decline all incoming friend requests </li>
            <li> fakeperson ⟶  Will generate a random person with &lt;nationality&gt; and &lt;gender&gt; </li>
            <li> metrics ⟶  Will show the top 10 most used commands by you in a graph </li>
            <li> movieinfo ⟶  Will return movie or series info by &lt;query&gt; </li>
            <li> covidinfo ⟶  Will return some data regarding the SARS-CoV-2 virus </li>
            <li> weatherinfo ⟶  Will return weather info by cityname </li>
            <li> processinfo ⟶  Will show some process info of your selfbot instance </li>
            <li> channelinfo ⟶  Will show all channels in a guild and send it to logging channel </li>
            <li> roleinfo ⟶  Will show information about the specified &lt;role&gt; </li>
            <li> serverinfo ⟶  Will display some information about a server in your logging channel </li>
            <li> userinfo ⟶  Will show the specified &lt;user&gt;s account data </li>
            <li> emojiinfo ⟶  Will list all the emotes in a server </li>
            <li> getavatars ⟶  Will scrape all avatars in a guild for the random avatars list </li>
            <li> getemojis ⟶  Will scrape all emojis from &lt;fromguildid&gt; guild and add them to &lt;toguildid&gt; guild </li>
            <li> getfiles ⟶  Will scrape &lt;limit&gt; files with the by you specified [filetypes...] in the current channel </li>
            <li> genhtml ⟶  dook </li>
            <li> settings ⟶  Base command for changing your selfbot settings </li>
            <ul>
                <li> embed ⟶  Will enable or disable sending some command output in embeds. </li>
                <li> sniping ⟶  Will enable or disable sniping discordgifts, privnotes, tokens and giveaways </li>
                <li> prefix ⟶  Will change your current prefix to &lt;prefix&gt; </li>
            </ul>
            <li> cc ⟶  Base command for adding/removing/listing all the custom commands </li>
            <ul>
                <li> add ⟶  Will add the custom command named &lt;command_name&gt; sending &lt;content&gt; </li>
                <li> remove ⟶  Will remove the custom command named &lt;command_name&gt;  </li>
                <li> list ⟶  Will list all the custom commands </li>
            </ul>
            <li> backup ⟶  Base command for making and loading backups </li>
            <ul>
                <li> make ⟶  Sub-base command for backing up friends, blocked users and joined servers </li>
                <ul>
                    <li> friends ⟶  Will create a backup of all your friends in a txt file as ids </li>
                    <li> blocked ⟶  Will create a backup of all your blocked users in a txt file as ids </li>
                    <li> servers ⟶  Will create a backup of all your joined servers in a txt file as invites </li>
                </ul>
                <li> load ⟶  Sub-base command for adding backed up friends, blocking blocked users and joining servers </li>
                <ul>
                    <li> friends ⟶  Will add all friends from the backed up txt file </li>
                    <li> blocked ⟶  Will block all users from the backed up txt file </li>
                    <li> servers ⟶  Will join all servers from the backed up txt file </li>
                </ul>
            </ul>
        </ul>
        </details>
        <details>
        <summary> Raid </summary>
        <ul>
        <p> Category with all the raid commands, use these with caution </p>
            <li> raid ⟶  Base command for logging and and logging out all the raid accounts </li>
            <ul>
                <li> add ⟶  Will add tokens to the list of useraccounts that can be used to log in </li>
                <li> remove ⟶  Will remove a id:token entry from the token list by [ids...] </li>
                <li> login ⟶  Will log in all the raid user accounts from the user account, they will also join your logging guild </li>
                <li> logout ⟶  Will log out all the raid user instances </li>
                <li> amount ⟶  Will give the amount of id:token combinations </li>
            </ul>
        </ul>
        </details>
        <details>
        <summary> Trolling </summary>
        <ul>
        <p> Category will all trolling commands, some should be used with caution </p>
            <li> glitchzalgo ⟶  Will send a glitched zalgo message </li>
            <li> virus ⟶  Will send an editing virus message </li>
            <li> killpresident ⟶  You should use this command in a big server 😂 </li>
            <li> stfu ⟶  Will send an editing stfu message </li>
            <li> noonecares ⟶  Will send an editing no one cares message </li>
            <li> 911 ⟶  Will send an editing 911 image </li>
            <li> cum ⟶  Will send an editing masturbating image 😳 </li>
            <li> tokencalc ⟶  Will calculate someones discord token (last parts random) </li>
            <li> react ⟶  Will react to the last &lt;amount&gt; messages with [emojis...] </li>
            <li> fakeembed ⟶  Will send your &lt;link&gt; + and embed with &lt;description&gt; and &lt;thumbnail&gt; </li>
            <li> glitchmention ⟶  Will send a &lt;length&gt; long mention looking message </li>
            <li> typing ⟶  Will make it look like you are typing indefinitely </li>
            <li> freenitro ⟶  Will send an embedded gif that if added to favourites will send the customurl gif instead. Use Discord CDN links </li>
            <li> editpos ⟶  Will send a &lt;message&gt; with glitched edited tag </li>
            <li> massping ⟶  Will massping everybody in the guild </li>
            <li> spam ⟶  Will send &lt;message&gt; &lt;amount&gt; times in a row </li>
            <li> uclone ⟶  Will copy &lt;user&gt;'s pfp/username in DM and role in a guild </li>
            <li> blank ⟶  Base command for sending ~2000 char long whitespace message </li>
            <ul>
                <li> guild ⟶  Will send a ~2000 blank after every message in a guild </li>
            </ul>
            <li> noleave ⟶  Base command for instantly adding users back after leaving a group channel </li>
            <ul>
                <li> start ⟶  Will instantly add the &lt;user&gt; back to the group channel upon leaving </li>
                <li> stop ⟶  Will allow user to leave the group channel again </li>
            </ul>
            <li> nojoin ⟶  Base command for instantly kicking a user upon being added to a group </li>
            <ul>
                <li> stop ⟶  Will allow a user to join the group again </li>
                <li> start ⟶  Will instantly kick the &lt;user&gt; from the group channel upon joining </li>
            </ul>
            <li> annoy ⟶  Base command for reacting to messages with emoji's </li>
            <ul>
                <li> user ⟶  Will react with [emojis...] to every message by &lt;user&gt; </li>
                <li> guild ⟶  Will attempt to react with [emojis...] to every message in current guild </li>
                <li> stop ⟶  Will stop all annoy listeners </li>
            </ul>
            <li> copy ⟶  Base command for copying users messages or channels messages </li>
            <ul>
                <li> user ⟶  Will copy every &lt;user&gt;'s message by default, else it will send the provided &lt;message&gt; </li>
                <li> channel ⟶  Will copy everybody in &lt;channel&gt; by default, else it will send the provided &lt;message&gt; </li>
                <li> stop ⟶  Will stop all copy listeners </li>
            </ul>
            <li> step ⟶  Base command for stepping through messages and stopping that listener </li>
            <ul>
                <li> user ⟶  Will step through &lt;message&gt; by sending it word for word after every message by &lt;user&gt; </li>
                <li> stop ⟶  Will stop all step listeners </li>
            </ul>
            <li> automute ⟶  Base command for automuting members </li>
            <ul>
                <li> start ⟶  Will automatically mute &lt;member&gt; after a unmute </li>
                <li> stop ⟶  Will stop the automute listener </li>
            </ul>
            <li> autodeafen ⟶  Base command for automuting members </li>
            <ul>
                <li> start ⟶  Will automatically deafen &lt;member&gt; after a undeafen </li>
                <li> stop ⟶  Will stop the autodeafen listener </li>
            </ul>
        </ul>
        </details>
        <details>
        <summary> Utilities </summary>
        <ul>
        <p> Category with all useful commands, this mostly includes informative actions </p>
            <li> youtubesearch ⟶  Will &lt;search&gt; for a video on YouTube by given title </li>
            <li> tobtc ⟶  Will convert provided &lt;currency&gt; to it's bitcoin equivalent </li>
            <li> charcount ⟶  Will return the amount of chars, words and paragraphs in your &lt;message&gt; </li>
            <li> btc ⟶  Will convert a bitcoin to the provided currency equivalent </li>
            <li> create_group ⟶  Will create a group channel with [users...] if they are on your friendslist </li>
            <li> report ⟶  Will send a report to discord Trust & Safety </li>
            <li> commandtimer ⟶  Will use &lt;command&gt; every &lt;interval&gt; seconds &lt;amount&gt; times </li>
            <li> timer ⟶  Will count down from &lt;_time&gt; and update in an embed every &lt;interval&gt; seconds </li>
            <li> tinyurl ⟶  Will generate a tinyurl link from &lt;link&gt; </li>
            <li> charinfo ⟶  Will send info about your &lt;message&gt; unicode </li>
            <li> urban ⟶  Will search your &lt;query&gt; on urban dictionary and send definition </li>
            <li> reload ⟶  Will reload all the cogs </li>
            <li> exportchat ⟶  Will backup the latest &lt;limit&gt; messages in the current channel to a txt file </li>
            <li> viewbot ⟶  Will have &lt;amount&gt; bots viewing &lt;link&gt; </li>
            <li> google ⟶  Will search google by &lt;query&gt; and return results as links </li>
            <li> purge ⟶  Will delete &lt;amount&gt; of messages send by you (cap 300), filtering with [keywords...] </li>
            <li> q ⟶  Will quickly delete [amount] messages send by you </li>
            <li> rand ⟶  Will send a random number between &lt;num1&gt; and &lt;num2&gt; </li>
            <li> passgen ⟶  Will generate a &lt;length&gt; long password </li>
            <li> logout ⟶  Will log out the selfbot </li>
            <li> reboot ⟶  Will restart the selfbot </li>
            <li> reverse_search ⟶  Will reverse image search the &lt;user&gt; profile picture </li>
            <li> loop ⟶  Base command for looping messages </li>
            <ul>
                <li> stop ⟶  Will stop the currently playing loop function </li>
                <li> start ⟶  Will start the loop function with the given &lt;delay&gt; and &lt;message&gt; </li>
            </ul>
            <li> dstatus ⟶  Base command for changing your discord status </li>
            <ul>
                <li> listening ⟶  Will change your status to listening to &lt;message&gt; </li>
                <li> watching ⟶  Will change your status to watching &lt;message&gt; </li>
                <li> streaming ⟶  Will change your status to streaming &lt;message&gt; with link &lt;stream_url&gt; </li>
                <li> playing ⟶  Will change your status playing &lt;message&gt; </li>
            </ul>
            <li> autodel ⟶  Base command for automatically deleting messages over a limit </li>
            <ul>
                <li> start ⟶  Will delete any messages send by you over the provided &lt;limit&gt; </li>
                <li> stop ⟶  Will stop the autodelete messages </li>
            </ul>
            <li> clistener ⟶  Base command for adding custom listeners for words, that are logged in a separate wh </li>
            <ul>
                <li> start ⟶  Will start a custom listener for specified words </li>
                <li> stop ⟶  Will stop all custom listeners </li>
            </ul>
            <li> afkmode ⟶  Base command for on/off afkmode which will auto reply to mentions </li>
            <ul>
                <li> start ⟶  Will start the afkmode, autoreplying to mentions with &lt;message&gt; </li>
                <li> stop ⟶  Will stop the afkmode </li>
            </ul>
            <li> invisible ⟶  Base command for making your username/pfp blank, and reverting that </li>
            <ul>
                <li> start ⟶  Will change your username and pfp to be blank </li>
                <li> stop ⟶  Will change your username and pfp back to original </li>
            </ul>
        </ul>
        </details>
    </ul>
</details>

### Events
<details open>
<summary>open/close</summary>
    <ul>
        <details>
            <summary>Nitro sniper</summary>
            <ul>
                <li> The nitro sniper has build in anti-spam methods, this means you won't ever be banned by using this!
                The speed (depending on your internetspeed, discords server load and the distance) is around <a target="_blank" title="Snipe speeds" href="https://i.imgur.com/GZ8uR5W.png">0.15s</a>, but could drop to 0.12s from beginning to end. </li>
            </ul>
        </details>
        <details>
            <summary>Privnote sniper</summary>
            <ul>
                <li> The privnotes snipe speed are about the same as the nitro snipe speeds. The contents of these privnotes
                are saved in a folder in .txt files. </li>
            </ul>
        </details>
        <details>
            <summary>Token sniper</summary>
            <ul>
                <li> If someone pastes a bot or user token, it will instantly be logged to the logging channel. </li>
            </ul>
        </details>
        <details>
            <summary>Giveaway sniper</summary>
            <ul>
                <li> If a giveaway is started from one of the 4 recognized bots, it will attempt to join it by reacting
                with the emote after a random delay. </li>
            </ul>
        </details>
        <details>
            <summary>Auto delete</summary>
            <ul>
                <li> Every sentence/word starting with your custom prefix will instantly be deleted. </li>
            </ul>
        </details>
    </ul>
</details>

### Other
<details open>
<summary>open/close</summary>
    <ul>
        <details>
            <summary>Customizability</summary>
            <ul>
                <li> The embed colour, footer icon and text and autodelete time are customizable </li>
                <li> The prefix is custamizable </li>
                <li> Enabling/disabling sniping is optional </li>
            </ul>
        </details>
        <details>
            <summary>Extensions</summary>
            <ul>
                <li> I have made 2 optional extensions. This includes the Moderation (8 commands) and the NSFW extension (2 commands).
                They can be downloaded in our guild upon buying the selfbot. </li>
            </ul>
        </details>
        <details>
            <summary>Logging</summary>
            <ul>
                <li> All logging is done discretely in a by you chosen guilds sytem channel. A webhook is created that will
                send what actions are being done, or some command output and more. </li>
            </ul>
        </details>
        <details>
            <summary>Support</summary>
            <ul>
                <li> You can create a ticket in <a target="_blank" href="https://discord.gg/ZGrYnNB">our discord</a> where we will provide great support
                ASAP. The discord server also contains a FAQ page, where most of your questions will be answered. So make sure to check that out! </li>
            </ul>
        </details>
    </ul>
</details>

<button class="button button"><a style="color: black;" href="#top">Back to top</a></button>

<p align="center">
    <img alt="Geazer Selfbot Logo" src="https://i.imgur.com/UsrLN7k.gif" width="150" height="150" />
</p>
