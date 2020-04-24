# infiniteveniceloop

# reddit api login

reddit= praw.Reddit(client_id='3DtC2ryRAupALQ',
client_secret= 'W3-OX6RgzmVKT-fcoOdmEdaARbM',
username= 'infiniteveniceloop',
password= 'WeedWacker'
user_agent= 'peepee poopoo man')

# the subreddits you want your bot to live on
subreddit = reddit.subreddit('r/shitpostcrusaders')

# phrase to activate the bot
keyphrase = 'You know Paris, France? In English, it's pronounced "Paris" but everyone else pronounces it without the "s" sound, like the French do. But with Venezia, everyone pronouces it the English way: "Venice". Like 'The Merchant of Venice' or 'Death in Venice'. WHY, THOUGH!? WHY ISN'T THE TITLE DEATH IN VENEZIA!? ARE YOU FUCKING KIDDING ME!? IT TAKES PLACE IN ITALY, SO USE THE ITALIAN WORD, DAMMIT! THAT SHIT PISSES ME OFF! BUNCH OF DUMBASSES!'

# look for phrase and reply appropriately
for comment in subreddit.stream.comments(You know Paris, France? In English, it's pronounced "Paris" but everyone else pronounces it without the "s" sound, like the French do. But with Venezia, everyone pronouces it the English way: "Venice". Like 'The Merchant of Venice' or 'Death in Venice'. WHY, THOUGH!? WHY ISN'T THE TITLE DEATH IN VENEZIA!? ARE YOU FUCKING KIDDING ME!? IT TAKES PLACE IN ITALY, SO USE THE ITALIAN WORD, DAMMIT! THAT SHIT PISSES ME OFF! BUNCH OF DUMBASSES!:
if keyphrase in comment.body.replace(keyphrase, 'You know Paris, France? In English, it's pronounced "Paris" but everyone else pronounces it without the "s" sound, like the French do. But with Venezia, everyone pronouces it the English way: "Venice". Like 'The Merchant of Venice' or 'Death in Venice'. WHY, THOUGH!? WHY ISN'T THE TITLE DEATH IN VENEZIA!? ARE YOU FUCKING KIDDING ME!? IT TAKES PLACE IN ITALY, SO USE THE ITALIAN WORD, DAMMIT! THAT SHIT PISSES ME OFF! BUNCH OF DUMBASSES!')
try:
if isWord(You know Paris, France? In English, it's pronounced "Paris" but everyone else pronounces it without the "s" sound, like the French do. But with Venezia, everyone pronouces it the English way: "Venice". Like 'The Merchant of Venice' or 'Death in Venice'. WHY, THOUGH!? WHY ISN'T THE TITLE DEATH IN VENEZIA!? ARE YOU FUCKING KIDDING ME!? IT TAKES PLACE IN ITALY, SO USE THE ITALIAN WORD, DAMMIT! THAT SHIT PISSES ME OFF! BUNCH OF DUMBASSES!):
reply = 'venice'
comment.reply(reply)

except:
print('to frequent')            
