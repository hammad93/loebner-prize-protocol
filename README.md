# loebner-prize-protocol
The protocol for the Loebner Prize

Loebner Prize Protocol (LPP)
http://www.aisb.org.uk/events/loebner-prize
https://github.com/jhudsy/LoebnerPrizeProtocol


Personal Assistance Machine (P.A.M.)
by Hammad Usmani

Requirements:
- Microsoft C++ 2008 Redistributable (https://www.microsoft.com/en-us/download/details.aspx?id=29)
- IE Explorer with ActiveX Enabled. Please "Allow Blocked Content" for ai-PAM.html

Features:
- Replies uniquely to every input
- Replies to any Unicode input
- Learns based on any input
- Can respond in the following input languages:
    * English
    * Chinese
    * Spanish
    * Hindi
    * Arabic
    * Portugese
    * Russian
    * Japanese
    * Punjabi
    * French

Loebner Prize Protocol (LPP) Instructions:
1. Start PAM API by clicking the `PAM` shortcut or navigating to `dist\PAM.exe`
    - This will start a server on localhost port 1337
2. Use `ai-PAM.html` for A.I. Chatbot client using PAM
    - The file `demo LPP` stages the `ai-PAM.html` file according the the git repository


Method:
This chatbot is not based on a rule based engine but uses a statistical inference model. The model is based on
a Markov-Chain approach which is simliar to a Recurrent Neural Network (RNN) in Machine Learning. The advantage of
using this kind of model is the ability to respond uniquely to every input, learning on every input, and responses
on any input. This type of model can be more conversational to some people. The disadvantage a pure RNN based approach
is the absense of any knowledge or logical memory capabilities. The chatbot lacks any induction based logic or
the ability to make inferences.

The Chatbot was able to learn the most popular languages around the world by analyzing Twitter profiles using the
Twitter API. This allows conversational output of the Markov-Chain model. The list of Twitter users and their respective
target languages are listed below.

Referenes:
https://github.com/pteichman/cobe

Twitter Profiles:
French: @nightinkstains
@paulinhoMAP4
@_cocof
@maxime_minard
@byoussoufa

Japanese: @FF_DIALOVER
@yuki_kaze_178
@ayaka4817
@soltcaramel
@_kataomoi_bot

Russian: @LokiStilinski
@echeneidae
@PERFECT_GIRL_1D
@rrr17firss
@_guildenstern

Protugese: @MinaDoPovo_
@sandraselmader
@CheZeGuevara
@SargentoFAHUR
@dixangelo

Arabic: @2m__38
@a_o__o7
@Kaoor322
@iffvdde
@Saedhalwa1

Hindi: @1stIndiaNews
@zeerajasthan_
@aapyamunanagar
@sanjay_vyas
@asimRmathur

Spanish: @LuleMartinez
@AlfoSema
@ernes_caceres
@HugoEscudero06
@adrianlozano29

Chinese: @8964_Tank_Man
@Orzzai
@nicolesi10
@kanzhongguolife
@kuma980122

English: @realDonaldTrump
@CNN
@ArianaGrande
@KimKardashian ‏
@BarackObama

Punjabi: @DrTayyabFarooq
@PTVNewsOfficial
@shanegujrat
@city42
@DostHuApka
