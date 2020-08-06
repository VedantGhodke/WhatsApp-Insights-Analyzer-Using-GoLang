# Insights
> Generates insights for a whatsapp chat.
 
## Usage
```bash
   # you can clone the repository and make the binary yourself
   λ git clone git@github.com:VEDANTGHODKE/WhatsApp-Insights-Analyzer-Using-GoLang
   λ cd insights
   λ make
   λ ./bin/insights ./path/to/chat/file.txt
   # for different timezones you can use -timezone flag
   λ insights -pretty -timezone=Asia/Kolkata ./path/to/chat/file.txt
```
Or you can just download prebuilt binaries from here: [Link](https://github.com/VEDANTGHODKE/WhatsApp-Insights-Analyzer-Using-GoLang/releases/latest)
 
## Metrics

- First Message
- Last Message
- Duration
- Frequency (how many messages in every hour of day) 
- Total Messages
- Total Words
- Total Letters
- Average Words Per Message
- Average Letters Per Message
- Average Messages Per Day
- Average Words Per Day
- Average Letters Per Day
- Participants
- Contribution Per Participant
- Contribution Count Per Participant
- Contribution Words Per Participant
- Contribution Letters Per Participant
- Contribution Frequency Per Participant
- Timeline (how many messages per day/week/month/year)
- Timeline Count
- Timeline Words
- Timeline Letters
- Most Active Day
- Most Active Count
- Least Active Day
- Least Active Count
- Emoji Used

## Graphs

It also comes with a server that would represent the data extracted from the chat in graphical format it would require `-server` argument during execution, it would look like this:

![](Example.png)

## Implementations

This is a very crude implementation that I coded within a single day, hence there are lots of potential improvements that could be done. In any case, please feel free to send a PR or raise an issue if you find anything interesting.


