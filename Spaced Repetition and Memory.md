* Spaced Math Repetition http://mathgradblog.williams.edu/?p=1506
* To Really Learn, Quit Studying and Take a Test http://www.nytimes.com/2011/01/21/science/21memory.html
* Recalling memories while asleep helps lock them in place http://arstechnica.com/science/news/2011/01/recalling-memories-while-asleep-helps-lock-them-in-place.ars
* [Heisig Method]()

## Adventure into SRS studying

There’s been some research into the effectiveness of spaced repetition (see the references on the wikipedia article) as a study technique.  Both myself and my roommate use it with our respective foreign languages (French and Chinese) as a means to memorize vocabulary and practice writing/pronunciation.  Spaced repetition (SRS) seems uniquely qualified to assist in language learning, and indeed there have been notable SRS programs such as Anki which are geared towards learning languages.  It’s been about a week since I started using Anki for my introductory French class, and I already have a solid grasp on the first chapter vocabulary which wouldn’t have been possible with my high school study techniques (ie, repeating a list of words over and over right before a quiz).  The idea behind SRS is to space the repetition of flashcards so the ones you know well appear less often and the harder cards are shown more frequently.  Ideally, you will be presented with the card just as its contents are starting to slip from your memory.  The makers of SuperMemo have extensively documented their algorithm, which involves a fair bit of math but seems to work nicely.  All of this seems good for studying material which requires rote memorization (dates, vocabulary, etc.), but how well does it translate to classes which require a deeper understanding of methods and rationale?  Can SRS be applied to situations which require critical thinking?  We are currently developing a web-based application which hopefully will do just that.


Part of my goal this semester is to investigate this question: Does SRS work for technical classes which involve difficult problem solving skills?  I have decided to try it for my three technical classes (theoretical mechanics, statistical mechanics, and Fourier series/BVP), and will record my thoughts and observations here.  I don’t have a well-developed plan of attack, but rather will try to play things by ear and learn as I go along.  But here are my initial thoughts:

### Note Taking

For formulas, etc., SRS seems like an obviously good idea.  Not that knowing the formulas ensures success, but fluency in the tools available to solve a problem is always helpful.  It really slows down the studying process to have to look up Gauss’ law every time you want to do an E&M problem.  Also, knowing which formulas are useful for what types of problems (for example, in Stat. Mech. knowing when to apply certain thermodynamic identities) can greatly expedite problem solving.  SRS (I’m hoping) will help keep the house in order so I don’t spend 15 minutes searching for the right formula every time I start a new problem.

Additionally, SRS could help review key facts or observations from the readings.  Instead of cramming a semester’s worth of notes right before the final, I plan on continually reviewing the material throughout the semester.  We’ll see if it pays off!

### Problem Solving

The unproven frontier of SRS seems to be enhancing problem solving skills.  However, with the library of formulas built up by SRS throughout the semester, I should be able to focus more on problem solving techniques.  Maybe identifying certain problems that are similar and require similar approaches?  Knowing a variety of ways to approach a certain problem depending on the conditions you are given?  As to how this will translate to SRS flashcards, it remains to be seen.

### Forming Connections

Forming connections with other material is also important.  Hopefully I’ll be able to develop some techniques, maybe not entirely SRS, that allow me to see the connections between what I’m studying and what I’ve studied before.

More than anything, this will be an adventure.  But hopefully one that will have real impacts on my understanding of the material in these classes!  Stay tuned for updates, both to my own experiences and to the project which will incorporate my findings.

## Applying the AJATT method to Chinese class

This summer I raved about the All Japanese All the Time blog in another post.To summarize, his idea is to learn to speak a language fluently in minimal time by attempting to surround yourself as entirely as possibly with input material in that language. Sticking with fun source material like movies and music and attempting to remove English crutches both help invoke the childlike language learning state that many claim to be unattainable after a certain age. Additionally, memorization occurs by studying sentences in the target language with a spaced repetition system (see any other post here for a description). If any of this appeals to you, I highly recommend reading the AJATT blog.

While this approach appeals to me intuitively, I have the competing goal of making a good grade in Chinese class, which differs from just being good at Chinese. Certain words and phrases, the vocab of the lesson, occur on tests with far greater probability, requiring the student to know exact pinyin and tones and particular wordings of English translation at certain times. So allowing yourself to stumble across things by watching movies won’t cut it.

Like Neal has been saying about French, I’ve had a lot of success last year in intro Chinese using spaced repetition on the vocab for each lesson. However, there’s always room for improvement. For one, I suffered very long, dull review sessions every week. I also felt behind in overall comprehension, and I had to study grammar separately.

So here is my plan to incorporate the AJATT method into my studying for intermediate Chinese (using the textbook Integrated Chinese Level 2). I imagine this plan should work as well for any language, ignoring the Chinese nerd stuff (hanzi = writing, pinyin = pronunciation)

Work through Remember the Hanzi this summer to memorize a large number of characters. I made it about 90% through 1500 characters in a month before quitting when school started. RTH deserves its own blog post, but the gist is to break down characters into their components, assign a definite meaning to each component, then create stories that tie in the components with the definition of the word.

Use a modification of the Pinyin Toolkit in Anki to add the lesson’s vocab. The Pinyin Toolkit is very snazzy and a huge time-saver for entering vocab. By entering the hanzi, the toolkit generates the pinyin (colored by tone), audio for pronuncation, English translations, and measure words. It automatically generates a bunch of cards for each vocab item, but I modified it so that I only study listening, reading, and writing.

Find difficult or interesting sentences from the lesson’s text. Use mp3splt on the textbook audio files for the text to split up everything into sentences. Make a new model in Pinyin Toolkit that generate one card for reading the characters and one for listening to the audio and transcribing to Chinese character. Add each of the sentences to the same deck as vocab.

Watch fun stuff in Chinese — Mandarin audio, no subtitles (or Chinese subtitles). Don’t worry about full comprehension, just enjoy the pictures. I’ve been watching Pixar movies, Dexter’s Lab, Powerpuff Girls, etc. Look for a future post on how find video and watch it conveniently. Sadly I haven’t really had enough time to watch enough and start adding sentences from the movies to the deck.

So the big difference here is the addition of studying sentences from the textbook. I see this as a huge advantage: all at the same time I get to study vocab in context, grammatical constructs, and fairly natural sounding Chinese sentences. The main issue to work out right now is the balance between sentences and vocab. Currently using all of the vocab with three cards each and every interesting sentence is a little overwhelming. The listening for single characters can be ambiguous, and there are various other kinks and annoyances. I’ll try tweaking some of the parameters and see how my weekly quiz grades are affected, then post conclusions closer to the end of the semester.

Let me know if you want elaboration on anything here or have ideas of your own. Good luck language learning!

## Update: SRS for everything

Although I’ve been regularly swamped with school work, I’ve had a bit of time to try out new ideas for my “SRS for everything” experiment.  Here is the update.

To refresh your memory (What? You aren’t using SRS for the blog?), I wanted to try using spaced repetition techniques to study things other than foreign language vocabulary.  Despite some hurdles involving  (i.e. LaTeX parsing) that have yet to be completely overcome, I decided to summarize my initial impressions of the project.

### Forming good questions

For my Philosophy of Language and Mind class, I planned to take notes on the reading (either typing notes directly, or adding notes to imported digital copies of the readings I could find online) and then make flashcards which cover the big ideas and definitions from each reading to use with the SM-2 algorithm .   When reviewing the flashcards, I would try to lecture out loud to myself about each idea, explaining the author’s argument and any objections I might have considered.  However, in practice I found that the effectiveness of this technique was limited by my ability to write well-framed questions.  Especially for articles that progress through a variety of working theses before coming to the author’s actual thoughts, I found it hard to match up my notes with effective questions that addressed the real key ideas.

This would seem to present several problems for our project.  Because the project is centered around SRS studying, good flashcards are critical.  However, there may be a better way to construct these flashcards.  Instead of asking a question such as “What was so-and-so’s opinion of X?” the flashcard could present some original source material and ask the student to explain the significance.  This way, the student is re-presented with the original text and is forced to construct a higher synthesis of what they have read.  Because not all of my readings are available online, I will try this with the ones that are and report back later.  With any luck, it will negate the need to come up with well-formed questions!

## My update: Chinese sentence experiment

A few weeks ago, I gave an overview of my Chinese studying method and left you with the question of maintaining a balance between sentences and vocab. Rather than fudging with careful independent variables and whatnot, I decided to just go all out and attempt to study one of my Chinese lessons using only sentence cards, completely covering every sentence in the lesson. That is, I never once studied the vocab item “实习” but rather the sentence “也许你可以先找个地方实习一下”.

The results? Not very viable in this extreme, but I learned a thing or two about more effectively studying sentences along the way.


To reiterate, for each sentence (from my Chinese textbook lessons) I generate two cards:

For one card, I try to read the sentence in Chinese characters. The other side contains pinyin and audio extracted from the textbook audio.
For other card,  I listen to the audio and attempt to write all of the characters.
I quickly realized that writing out every audio card would take way too long. Instead, I tried just writing out characters that didn’t seem obvious. However, even this was taking forever to get through. Having to focus on new characters AND decipher the audio was too much to handle for one card. So what exactly do I do with a sentence card? Luckily, AJATT’s ever-thoughtful Khatzumoto answered exactly that in a recent post. He addressed my first type of card: Attempt to read the sentence aloud and understand it. If not, write the sentence out. As for the other type of card, I imagine something similar is effective: if you comprehend the sentence by listening, you’re good to go. Otherwise, only then write it out, but write the whole thing. Ultimately, not worrying about writing at all for most cards makes things much smoother and quicker. Again, my goals are slightly different since I’m studying to ace tests and not just learn Chinese, so I have to worry about characters that slip under the cracks — ones I can read or hear but not write from memory. That’s why I think the vocab cards are essential, at least, outside of the ideal world where I’ve memorized every character Heisig-style (well worth reading — in fact, I just might have to switch back to that system).

Of course, Khatz would also never suggest holding on to every one of those boring sentences. There were some things I liked about this method though. I set new cards to appear in order at the beginning of the review session, so I can read through them as if it were my book, but at the same time, I’m assigning SRS data to every single sentence. Whereas the more I study outside the system, the more I feel like its model of my memory is off. It’s also kind of beautiful to look back on the text and have the textbook audio nearly playing in my head as I read it. So SRS everything! is a major goal of our project, but we are still thinking hard about keeping that process from being an untamable beast, hopefully by finding a way to tap into what’s actually fun and engaging as well as what’s important.
