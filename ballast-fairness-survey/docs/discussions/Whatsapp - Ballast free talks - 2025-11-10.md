10.11.2025, 00:29 - ‎+33 6 89 93 36 22 dołączył(a) ze społeczności
10.11.2025, 11:58 - ‎+1 (657) 500-9272 dołączył(a) ze społeczności
10.11.2025, 12:13 - Dodano: +33 6 49 73 82 71
10.11.2025, 12:12 - ‎+33 6 49 73 82 71 dołączył(a) ze społeczności
10.11.2025, 12:35 - Dodano: Stephane Drouin
10.11.2025, 12:35 - ‎Stephane Drouin dołączył(a) ze społeczności
10.11.2025, 16:07 - +36 30 500 2958: Lukas, you seem to be an expert in this topic. Can you tell me the following: if Baptiste and Yassen both fly Enzo M at the same weight, but with Sub S and L, how much difference is between them? My theory is that the difference is significant, between 0.5-1.0 glider size. Can you confirm this on your model?
Also one big difference is the head: Baptise's head is almost hidden in the "tunnel" of the harness, while a tall pilot's head very much sticks out. I don't know if your model takes this into account <Ta wiadomość była edytowana>
10.11.2025, 16:16 - +49 1573 4866279: To give some context: Lukas' model currently uses a norm to determine some body measurements from a given height. It then constructs a body made up of recangles, calculates the area by giving them different angles compared to the airflow and then assumes some drag factors for different parts of this simple body (1 for arms, 0.23 for legs+torso+protector, etc.) 
imho this doesn't reclect what is going on with current comp harnesses, as the diameter of the main "tube" stays the same through all sizes. 
I tried making some rough adjustments by replacing the torso and protector area by a constand circle and adding some factor of the torso area on top (~1/3), but it still needs some work
10.11.2025, 16:18 - +33 6 15 67 83 97: @Zsolt, find here again in that file, my estimation of harness drag for the various sizes. It's done considering bigger body for bigger sizes.
10.11.2025, 16:19 - +33 6 15 67 83 97: <Pominięto multimedia>
10.11.2025, 16:21 - +33 6 15 67 83 97: The difference of drag between harnesses sizes is small. That's due to the fact that the frontal of the harness itself stays the same, the neck cannot extend out of the envellope, so the main difference comes from the arms and the helmet (helmet is almost nothing).
10.11.2025, 16:28 - +33 6 15 67 83 97: And for those wandering: the difference of drag between harness sizes is also small for another pod harness. <Ta wiadomość była edytowana>
10.11.2025, 16:31 - +36 30 500 2958: Luc, thanks! I don't yet understand the XLS, can you calculate the following?

* Enzo M @ 115 kg. Full speed. Both pilots.
* Pilot 1: Baptiste
* Pilot 2: 200 cm

How much difference is between them? <Ta wiadomość była edytowana>
10.11.2025, 16:31 - +33 6 15 67 83 97: this xls is doing it
10.11.2025, 16:32 - +36 30 500 2958: I just don't understand how to use it
10.11.2025, 16:32 - +33 6 15 67 83 97: ok, 1 minute
10.11.2025, 16:36 - +33 6 15 67 83 97: You can expect about 1cm/s variation of sink rate at full speed between extreme pilot sizes. The difference of sink rate at full speed from Enzo3 M to Enzo3 S is about 3cm/s.
10.11.2025, 16:44 - +36 30 500 2958: OK, so more or less 1/3 of a glider size step for pilot sizes on the extremes?
10.11.2025, 16:44 - +36 30 500 2958: And we could test this in practice by putting X cm of equalizers on Baptiste vs Yassen or someone tall and check if they glide equally?
10.11.2025, 16:45 - +33 6 15 67 83 97: no. We don't have accurate enough instruments.
10.11.2025, 16:49 - +36 30 500 2958: I mean by going on a glide at sunset, just like you how tested your original hypothesis of equalizers workings. A short and a tall pilot goes on a lot of glide tests with identical equipment, and they keep putting equalizers on the shorter pilot's glider until they believe the glide is identical.
As I understand you did the same testing for the original equalizer concept.
10.11.2025, 16:51 - +33 6 15 67 83 97: in the most ideal atmopheric conditions and the best possible measurement tool (developed in conjonction by Ozone and Vector Vario) the resultion is about 1cm/s at full speed.
10.11.2025, 16:52 - +33 6 15 67 83 97: So we would not really conclude on the comparison you are asking for <Ta wiadomość była edytowana>
10.11.2025, 16:52 - +36 30 500 2958: But we need to test the whole idea that equalizers are working. Pilot size is just one parameter.
10.11.2025, 16:53 - +33 6 15 67 83 97: Pilot size is a minor parameter that we don't need to fix. <Ta wiadomość była edytowana>
10.11.2025, 16:54 - +33 6 15 67 83 97: The major parameter, which is also th major issue, is total weight.
10.11.2025, 16:55 - +36 30 500 2958: I mean we need to test the full picture in the real-world. If we cannot test this, then it won't be a fair adjustment.
Maybe we need to analyse tracklogs on events with equalizers but we need to find a way to make sure the compensation is fair. <Ta wiadomość była edytowana>
10.11.2025, 16:57 - +33 6 15 67 83 97: The compensation on that xls file is the minimum undiscussable theoritical amount between glider sizes.
10.11.2025, 16:58 - +33 6 15 67 83 97: it can only be much fairer than nothing.
10.11.2025, 17:00 - +33 6 15 67 83 97: after two seasons, if you still see a lot of pilot ballasting, then you know for sure that the compensation is not enough. Because the pilots will have made a very well informed decision from hundreds of glide in real conditions. Something no-one can afford doing otherwise.
10.11.2025, 17:01 - +36 30 500 2958: I'm worried about the other direction. Small pilots will have advantage on an S size Enzo.
We'd need to find a way to take real-world results into equalizer sizes.
10.11.2025, 17:01 - +36 30 500 2958: For example analyse long glides on comps, which are not final-glides. <Ta wiadomość była edytowana>
10.11.2025, 17:01 - +41 76 465 96 05: Why do you think so?
10.11.2025, 17:02 - +36 30 500 2958: Because shorter arms, smaller harnesses, head in a more aerodynamic position.
10.11.2025, 17:02 - Julien Garcia: The point of Equalizer is to offer a compensation for Glider size.
10.11.2025, 17:03 - Julien Garcia: As I understood it.
10.11.2025, 17:03 - +33 6 15 67 83 97: there would still remains enaqualized parameters. and this would be one of them.
10.11.2025, 17:03 - +36 30 500 2958: But right now it's just a theoretical calculation, we haven't tested if it compensates enough or compensates too much.
10.11.2025, 17:04 - Julien Garcia: We can have statistical one too
10.11.2025, 17:04 - +33 6 15 67 83 97: We know it's not too much. And we would know if it's too little by doing it. <Ta wiadomość była edytowana>
10.11.2025, 17:05 - +33 6 62 51 67 03: The more we overthink, try to found every little points to say it's not good, the more we delay the test ! Let's stop to think, discuss and now we test !
10.11.2025, 17:06 - +36 30 500 2958: I'm also saying that we should start racing with them, I'm just saying that we need to be open minded to compensating for harness size and pilot size.
10.11.2025, 17:06 - +36 30 500 2958: The only way to figure out is race them and analyse the tracklogs. Or maybe you can tell me a better way.
10.11.2025, 17:07 - Julien Garcia: We hardly agree at all to compensate on 2 decade long lasting problem. <Ta wiadomość była edytowana>
10.11.2025, 17:07 - +33 6 15 67 83 97: I think stats on tracklogs, even with numerous data will not get you a good neough answer on pilot size matter (I mean for a given wing size)
10.11.2025, 17:09 - +33 6 15 67 83 97: Let's call Equalizer, Size Equalizer. Any other parameters is another subject. If you want to include all parameters (wing brand, wing model, harness model, arms, size, speedArm, tight or loose speed arm, cyclist race speed arm, etc.) you'll just make the whole thing unpractible.
10.11.2025, 17:10 - +33 6 62 51 67 03: we already know that we have performances differences in between size in a direction, this is the first ever realistic option to try to compensate this thing. we need to try this !
perhaps it's not perfect ?Yes maybe, but at least it's worth to try
10.11.2025, 17:12 - +32 486 31 34 36: Exactly. Step by step. Don’t try to eat the mammoth in one piece. Bit by bit. Start with what can be done in the near future. See how the system adapts….. rinse and repeat
10.11.2025, 17:13 - +36 30 500 2958: I think currently most pilots would agree that there is:

* minimal difference in glide between current CCC gliders of the same size
* big difference in one glider size step
* almost a glider size difference between flying with a GR5 and Submarine

Maybe we cannot measure it, but there are hundreds of tasks where the best pilots have raced each other and most of them concluded the same <Ta wiadomość była edytowana>
10.11.2025, 17:22 - +36 30 500 2958: I am supporting this idea, but currently I think a large percent of the pilots are against it.
If you try to push it through in the current form, I believe so many pilots will be against it, that they'll simply vote it out on races, like PWCA.
This is not something we can push through by force, I believe.
10.11.2025, 17:24 - +33 6 15 67 83 97: Maybe a poll in gagglereport will tell ?
10.11.2025, 17:27 - +36 30 500 2958: I think gagglereport is already a filter for pilots with more empathy/understanding, those who contribute here probably care about the direction of the sport. But sure, a poll is a good idea.
10.11.2025, 17:31 - +33 6 62 51 67 03: We know how it is ! most of the light pilots want to follow this proposal to compensate one lack, most of the heavy and tall pilots are against because they don't want to loose the performance and small advantage they have in glide
10.11.2025, 17:32 - +33 6 62 51 67 03: Everyone wants to defend his own interrest. In a way it's natural and understandable
But we need to think to the global system
10.11.2025, 17:35 - +33 6 62 51 67 03: I'm light and fly a 105kg max glider. If this is applayed, i will most probably change and use a smaller glider. 
I can used less ballast (one problem solved)
I can still have competitive performances (second probleme solved)
10.11.2025, 17:37 - +33 6 89 93 36 22: Différence is bigger between Baptiste and Mr 200cm because of training & time involved / accurate technics / accurate positioning & tactics in many race configurations / talent. Than 1cm/s.
Funny that we totally evacuate all sporting aspects
10.11.2025, 17:37 - +36 30 500 2958: I don't think it's as simple as that, there are many heavy pilots who understand why it's important and are in favour of equalizer. All I'm proposing is that if there was a "bonus cm" for harness size/pilot size, the heavier pilots would feel more understood and would be more in favour.
10.11.2025, 17:37 - +33 6 62 51 67 03: I'm defending my interrests in a way, but globally we can solve or compensate 2 problems in one
10.11.2025, 17:38 - +33 6 15 67 83 97: I think you should forget about this bonus cm idea. <Ta wiadomość była edytowana>
10.11.2025, 17:39 - +33 6 15 67 83 97: it does not help anything
10.11.2025, 17:41 - +36 30 500 2958: OK, I'm just saying by numbers, currently 80+ kg pilots are dominating the field. Lightweight pilots might be the champions, but the average male comp pilot is not lightweight.
If you make a proposal that penalises them, they'll not support your proposal and it'll be voted out after a season or so.
10.11.2025, 17:42 - +36 30 500 2958: I'm totally for making an equal playing field, but the sport has developed into what it is currently and you need to be understanding with the guys who will be penalized.
10.11.2025, 17:43 - +33 6 15 67 83 97: there is nothing less we can do Zsolt.
10.11.2025, 17:43 - +54 9 11 4417-7923: Humour hat on 😉
The problem here is Luc´s lack of political acumen
He should have proposed exaggerated equalizers at the start, so after bargaining a little bit, we would end up accepting the calculated equalizers and everyone happy (well not everyone for sure)
10.11.2025, 18:11 - +41 76 465 96 05: The 80 kg pilots should understand that it’s actually fairer for them when the 65 kg pilots fly the 95 kg wings with an equalizer setup, rather than the current situation where they fly the same 115 kg size with 40 kg of ballast. Just look at the results…

My concern is that some pilots will still decide to fly larger wings with maximum ballast to squeeze out the best possible performance by combining small arms with bigger gliders. And if we try to fix this by shifting even more performance toward the smaller wings in the hope that the heavy-ballast guys will carry less weight, it would end up disadvantaging the 80 kg pilots who fly without ballast.

That’s why I propose adding extra equalizer length for pilots using more than 25 kg of ballast, and again for those using more than 35 kg of ballast. For now, this shouldn’t apply to pilots who are struggling to even reach 95 kg.
10.11.2025, 18:13 - +49 1573 4866279: 25kg will still easily happen if you happen to be in between sizes and want to properly load on a good day <Ta wiadomość była edytowana>
10.11.2025, 18:15 - +33 6 15 67 83 97: what's your weight L ?  (and your name).
10.11.2025, 18:17 - +41 76 465 96 05: The point we need to emphasize now, in order to win this vote, is that the situation is already crooked — it favors the big guys and the small guys who load up with a lot of ballast.
10.11.2025, 18:18 - +44 7446 445157: Equalising for pilot size is a separate topic and should be spun up through "What we want" to see if there is sufficient support for the idea.  (In the same way as suggested for the aero/ non-aero harness equalisation suggested by Mark Hayman)
10.11.2025, 18:19 - +41 76 465 96 05: I told it before. Lukas Gantenbein I'm on a XL.
What is your weight Luc?
10.11.2025, 18:19 - +33 6 15 67 83 97: 80kg.
10.11.2025, 18:19 - +41 76 465 96 05: I am in favour of the equalizer solution
10.11.2025, 18:20 - +41 76 465 96 05: The point we need to emphasize now, in order to win this vote, is that the situation is already crooked — it favors the big guys and the small guys who load up with a lot of ballast.

Tell me this is not true!
10.11.2025, 18:22 - +33 6 15 67 83 97: but I know what it takes to carry and fly with very heavy bags. I've done it in the past to fly with Large size. there is no question, no-one would want to suffer this just to for few mm/s regarding arm size.
10.11.2025, 18:23 - +386 31 404 688: There is a test event being planned for next year specifically to use them. From that there will hopefully be some good data that will enable PWCA to commit to using them, or a modified version of the method. Thereafter a CAT1 can adopt it once it is proven and suitable tweaked.

At the Superfinal earlier this year the informal vote by they pilots was overwhelmingly in favour of using them. That included the XL/200cm pilots 😊
10.11.2025, 18:25 - +36 30 500 2958: I don't think the current situation favours the small guys, the situation is extremely against the small guys. The current champions are the best pilots _despite_ having to carry 45 kg equipment.
For those pilots one bad step on takeoff or landing might put them out of flying for half a season.

It clearly favours the big guys.

I just think that removing protectors from harnesses to make them aerodynamical and then putting it on the glider lines to make them less aerodynamical is a totally stupid development in our sport.
10.11.2025, 18:25 - +36 30 500 2958: To be clear I want to accept drag on the harnesses as equalizer.
10.11.2025, 18:27 - +33 6 15 67 83 97: you just bring another subject.
10.11.2025, 18:28 - +33 6 15 67 83 97: Equalizer would exist whatever is the protection.
10.11.2025, 18:28 - +36 30 500 2958: No, I think it's the same subject, equalizers and ballast free talks.
10.11.2025, 18:28 - +36 30 500 2958: Yes, but large pilots would have 14 cm protectors and super short equalizers on their lines
10.11.2025, 18:29 - +33 6 15 67 83 97: Well. call it Size Equalizer and ballast free talks.
10.11.2025, 18:29 - +33 6 15 67 83 97: if you want to open a subject about harness protection Equalizer, do it.
10.11.2025, 18:29 - +33 6 15 67 83 97: Josh already had a good idea about it.
10.11.2025, 18:32 - ‎+34 677 74 19 08 dołączył(a) ze społeczności
10.11.2025, 18:51 - +64 27 202 2996: Ta wiadomość została usunięta
10.11.2025, 19:14 - +44 7815 693738: Hi guys, I have put together a document to invoke more detailed discussion. Instead of choosing one idea, I thought about a multi system approach, that can be run in parallel that focuses on; how quickly we could start to address the issue, maximum pilot satisfaction and addressing some “cons” that get repeated about each subject. There are over 170 pilots in this group but very few get involved, please read, and comment, together we can come up with a solution!
10.11.2025, 19:14 - +44 7815 693738: <Pominięto multimedia>
10.11.2025, 22:54 - Julien Garcia: Thanks Malin. Interesting parrallel proposal.