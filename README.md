OVERVIEW

This Anki deck covers bird species common to the Netherlands. While the species were selected with the Netherlands in mind, the overlap to other European countries is very large, so users not from the Netherlands will likely also get some use out of it.

It contains names in various languages, as well as images, songs and calls to learn to recognize them. Furthermore, it includes extra information like taxonomy and notes to help distinguish between species that are difficult to tell apart, or with extra information that is just interesting.

The default card types do not include some of the information that is included in the deck. There are no questions to translate the names of birds from one language to another, no questions about the taxonomy, and no questions about silhouettes of birds of prey. Questions for other call types (alarm calls, flight calls) and for images of juvenile birds are enabled, but these fields have not currently been filled, so you will not see these questions either. However, since the relevant fields for all these things are included, it is easy for any user to include these card types or fill these fields, should they be interested in them—see the section Customization for this. I hope to add specific call types and juvenile images later.

The deck uses multiple images for any given species, so that the user does not end up learning the peculiarities of the images rather than the characteristics of the bird. As a result, the deck ended up becoming too big for AnkiWeb, which is why it is now here on GitHub. An added benefit of course is that it is made easier for users to point out errors and make suggestions—please do feel free to do so using the issues tab on the repository.

Thank you, and good luck with your upcoming ornithological developments!



INSTALLATION

First, make sure you have Anki for desktop downloaded from apps.ankiweb.net. There are options for 32bit and 64bit for Windows, Mac and Linux. Choose the version that is relevant for you and download and install it—usually all the default settings will be fine.

If you do not yet have a free account on Ankiweb, you might want to create one so that you will not lose your progress if your local files get deleted. On the main Anki screen, click the Sync button; if you are logged in, it should sync successfully, but otherwise it will ask you to log in. Use either an existing account, or first create an account from ankiweb.net and then put in your details.

Once your Anki is set up, all you need to do is download the files from this repository that end in .zip.00x (where x is another digit), unzip these files and open the .apkg file that is contained within with Anki (it should already be the default program for this extension, so you just have to open the file). Anki will load if it is not open, and the deck will be added to your list of decks.

There are mobile versions for Anki that many prefer for reviews, although creating new cards tends to be easier on the desktop version. The iPhone version requires a one-time payment, but the Android app AnkiDroid is free. You can also just stick with the desktop version for your reviews. If you use both, be sure to sync before and after each session, so that there are no conflicts between your progress on both platforms.



CUSTOMIZATION

In your Anki desktop app, click Browse on the main screen to go to the browser. On the left, you should see a list of decks, card types and tags that you have saved in your profile. If you select the Dutch birds - sounds and appearance deck, you should see the individual cards listed on the top right, and the selected card shown on the bottom right. You can edit the information for any bird by selecting it in the list, and then changing the contents of any of the fields.

Just above the fields, there is a button labeled "Fields..." and another one labeled "Cards...". These buttons specify the fields (pieces of information) and card types (questions asked about these fields) used in the deck. This is what you will want to edit if you would like to add or remove question types for all birds, like for example adding a question to translate the English into the scientific name, or removing the questions about bird sounds (songs and calls). To do this, click "Cards...", and a new window will open up. On the top left you see a drop-down menu for the different card types in the deck. If you want to remove a card type, select it from the menu and in the top right, click Options → Remove Card Type..., and hit "Yes" in the confirmation window that shows up. If you want to add a card type, hit Options → Add Card Type..., hit "Yes" to confirm, and edit the fields near the top left (Front Template) and bottom left (Back Template) to edit what is shown on the front and back of each card. To reference individual fields, use the name of the field enclosed in double curly brackets (for example, "{{Call}}").



CONTRIBUTING

Contributions to the deck are most welcome. The easiest thing to do is to open an issue on the GitHub repository to let me know about any mistake you find or suggest any improvement that you may have for the deck. 



HISTORY

The deck was begun and uploaded to AnkiWeb on 2014-04-23, but after that several updates were made prior to the move to GitHub on 2020-12-03. The update notes for these are given below.

2014-10-28: Thanks to an anonymous reviewer (2014-08-20), I was able to implement a number of improvements to the deck that should make it nicer to use and easier to edit. Here is a list of improvements:

- Sources now only in a hidden field so they don't take up space and distract from the images or sounds;
- Images and/or sounds now shown/played on back of cards with different questions (for extra association opportunities);
- Several under the hood improvements (single card type; extra fields unused for the time being perhaps to be added later or otherwise just for ease of editing).

Some of the new fields include alarm, flight, and courting calls. These are as yet unused, but some of the calls that are already in may overlap with these call types, as I originally did not distinguish between them. The same is true, if to a lesser degree, for juvenile images. Please keep this in mind when adding these on your own.

2016-04-07: Added some new species: marsh tit, willow tit, long-tailed tit, common kingfisher, Eurasian teal.

2017-07-17: Pretty big update. What's new?

- There are nine new birds: common cuckoo, white wagtail, common chiffchaff, willow warbler, hawfinch, common pochard, green sandpiper, European greenfinch, and yellowhammer. I am especially embarrassed that I didn't have the common chiffchaff and the willow warbler in before.
- I have added a small bit of Javascript code to the cards that allows the selection of a (quasi-)random image from several that are put together in a single field, separated by the | symbol. Since I only use the PC version, I am not fully sure this will work on mobile apps, but please let me know if there are any problems. The idea is that if there are different pictures for each species, the user is less likely to learn to recognize the picture, rather than the bird. A result is that the size of the deck has gone up quite a bit; I hope this is not too much of a problem for most users. I would like to thank Reddit user gurple for their help with this code.
- The silhouet questions for the birds of prey have been removed by default, as they are rather difficult and niche. The fields and images still remain, however, so they can be re-added easily, should the user wish to do so.
- Esperanto names have been added in a separate field, and are shown among the other names on the backs of image and sound cards. There are no questions about translation into or from Esperanto names by default so as not to bother those not interested in this, but these can of course be added quite easily.

2017-07-17: added Eurasian siskin, mostly in an attempt to fix a minor problem with the deck.

2020-05-26: added Mediterranean gull. Added French, German and Spanish names. Removed the taxonomy question and any questions about translating from one language (or the scientific name) to another. The relevant fields for these questions are still in, but if you want the actual questions for them, you will have to add them again manually. Sorry for any inconvenience, but I expect the typical user not to be too interested in these questions. Now, the only questions asked go from images or sounds (calls, songs) to the name. All languages are shown on the back side of these cards, so you can choose on your own which language(s) you want to test on. Also, added notes for various species, mostly to help distinguish between similar species (corvine species, larine species, ducks, that sort of thing).

2020-12-03: Thanks to Sebastiaan's review, I became aware that some common Dutch species were still missing. So, I have added ten more: the common whitethroat, garden warbler, marsh warbler, meadow pipit, tree pipit, Eurasian skylark, western yellow wagtail, goldcrest, common linnet and common swift. I have a few more in mind, but I think I am just about at the maximum size for a deck on AnkiWeb. I have therefore decided to copy the deck onto GitHub, which will allow me to expand on it further in the future.



ACKNOWLEDGMENT

I would like to thank my old friend Roeland for helping me on my first steps to becoming a bird enthusiast, and the teachers of the bird course at Utrecht University for helping lay further foundations.
The deck was created by me, Vincent Oostelbos, starting on 2014-04-23, but has gotten reviews from several users on AnkiWeb over the years, without whose ideas and contributions the deck would be much less good. In particular, I would like to thank the anonymous 2014-08-20 reviewer for many ideas on how to both simplify and expand the deck, an anonymous reviewer on 2020-05-11 for giving me the idea of simplifying the default card types for the deck, and Sebastiaan for further suggestions on 2020-09-02, most noticeably to add several common species I had missed before. Of course, a big thank you also goes out to everyone who has used this deck over the years, and continues to do so.