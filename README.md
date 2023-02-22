# E-Redial
E-ReDial is a conversational recommender system dataset with high-quality explanations. It consists of 756 dialogues with 12,003 utterances, each with 15.9 turns on average.  2,058 high-quality explanations are included, each with 79.2 tokens on average. The dataset is under the folder "dataset/". An example of dialogue in E-ReDial is as follows:

```json
{
        "messages": [
            {
                "text": "Annnnd hello",
                "movies": [],
                "knowledge": [],
                "role": 1,
                "rewrite": 0,
                "reason": "",
                "description": "",
                "encourage": ""
            },
            {
                "text": "hello how are you",
                "role": 0
            },
            {
                "text": "I am doing pretty good. You?",
                "movies": [],
                "knowledge": [],
                "role": 1,
                "rewrite": 0,
                "reason": "",
                "description": "",
                "encourage": ""
            },
            {
                "text": "I am great thanks for asking",
                "role": 0
            },
            {
                "text": "What kinda movies do you like?",
                "movies": [],
                "knowledge": [],
                "role": 1,
                "rewrite": 0,
                "reason": "",
                "description": "",
                "encourage": ""
            },
            {
                "text": "Can you find me a movie like [Pretty Woman (1990)]",
                "role": 0
            },
            {
                "text": "An all time favorite",
                "role": 0
            },
            {
                "text": "Since you want a movie like Pretty Woman (1990), I recommend [Bridget Jones's Diary (2001)], it’s also a romance comedy. It tells a story that Bridget Jones is determined to improve herself while she looks for love in a year in which she keeps a personal diary. I think it’s one of the most charming romantic comedies in a while! I believe this movie will give you an unprecedented experience.",
                "movies": [
                    "[Bridget Jones's Diary (2001)]"
                ],
                "knowledge": [
                    {
                        "wiki": "Bridget Jones's Diary is a 2001 romantic comedy film directed by Sharon Maguire and written by Richard Curtis, Andrew Davies, and Helen Fielding. A co-production of the United Kingdom, United States and France, it is based on Fielding's 1996 novel of the same name, which is a reinterpretation of Jane Austen's 1813 novel Pride and Prejudice. The adaptation stars Renée Zellweger as Bridget Jones, a 32-year-old British single woman, who writes a diary which focuses on the things she wishes to happen in her life. However, her life changes when two men vie for her affection, portrayed by Colin Firth and Hugh Grant. Jim Broadbent and Gemma Jones appear in supporting roles. Production began in August 2000 and ended in November 2000, and took place largely on location in London and the home counties.\r\nBridget Jones's Diary premiered on 4 April 2001 in the United Kingdom and was released to theatres on 13 April 2001 simultaneously in the United Kingdom and in the United States. It grossed over $280 million worldwide and received positive reviews, with critics highlighting Zellweger's titular performance, which garnered her a nomination for the Academy Award for Best Actress. Over the years, it has been hailed as part of the English pop culture, with Bridget Jones being cited as a British cultural icon.\r\nThe success of the film spawned a Bridget Jones franchise with two equally successful sequels being released, Bridget Jones: The Edge of Reason (2004) and Bridget Jones's Baby (2016).",
                        "plot": "Bridget Jones is determined to improve herself while she looks for love in a year in which she keeps a personal diary.",
                        "review": "As a huge fan of the books, I had incredibly high expectations of the movie. In order for the movie to work for me, it had to capture Bridget's plucky-heroine character and the hilarious-poignant emotions that are in the book. Needless to say, `Bridget Jones's Diary' the movie worked very, very, very well. Although Helen Fielding also wrote the screenplay (w/ Richard Curtis, very skilled with romantic comedies) and keeps the laughs coming, this movie could have fallen flat on its face. But it doesn't because one, the casting is absolutely divine and two, smartly builds on some elements the book downplays. Renee Zellweger is absolutely perfect as Bridget Jones. She has always been one of my favorite actresses and here, she totally displays Bridget's pathetic cuteness. Zellweger gained weight for this role, too, so she looks adorably plump. It's very, very hard to not fall in love with her the moment you see her at her family's Christmas party or drinking alone at home or listening to sad, Celine Dion music. (You have a heart of stone if you aren't moved to laughs or tears or pity for her.) I can't imagine anyone else playing Bridget Jones. Zellweger fits the role because she is very much normal and approachable we can relate to her. As Daniel Cleaver (her caddish Cassanova lover/boss), Hugh Grant is smoldering and hilarious. (Ok, I might be a little biased because I've been in love with him for ages and ages, but you can't deny he is a great comedic actor.) There's no trace of his stuttering that we saw (and I loved) in `Four Weddings and a Funeral' or `Sense and Sensibility.' Grant morphs effortlessly into a cad that we all love to hate and all love to love. Yes, it's a paradox, but that is what Grant brings to his role. He makes being `bad' look so sexy. You can't take your eyes off him; he brings his own humor to his role. It's lovely, smoldering, and incredibly sexy. Colin Firth is also a delight to watch onscreen as Mark Darcy (I think I might be in love with him, too). He is also sexy and smoldering, but not in the same wild, fiery way as Daniel Cleaver. Firth brings a very cute sweetness to his role. I don't know if it is his adorable face or his hair or the way he dresses or just the fact that he is a major sex symbol, but you can't help but fall in love with him the MOMENT you see him onscreen. There is also one very beautiful moment where he tells Bridget, `I like you very much just the way you are.' It's incredibly romantic and, for me, ranks right up there with Tom Cruise's `You complete me' in `Jerry Maguire.' He also has rather explosive chemistry with Renee Zellweger, which is moving and sexy all at the same time. (And, of course, the author Helen Fielding used Colin Firth as the basis for Mark Darcy, so it all works out marvelously.) I also mentioned that the movie smartly builds on some elements that the book downplays. Yes, there are certain parts of the movie that cannot be found in the book, but I'm still glad they put them in the movie. Most of what they added doesn't necessarily build on plot but it does add to the characters. I don't want to give anything away because it's rather hilarious what unfolds onscreen. The movie is filmed in an almost Ally McBeal type of way but it remains true to the sincerity, cuteness, and pathetic naivete that Bridget Jones embodies. There are no pretensions. It's an entirely wonderful film. 10/10",
                        "movieid": "tt0243155"
                    }
                ],
                "role": 1,
                "rewrite": 1,
                "reason": "Since you want a movie like Pretty Woman (1990), I recommend [Bridget Jones's Diary (2001)], it’s also a romance comedy.",
                "description": "It tells a story that Bridget Jones is determined to improve herself while she looks for love in a year in which she keeps a personal diary. I think it’s one of the most charming romantic comedies in a while!",
                "encourage": "I believe this movie will give you an unprecedented experience."
            },
            {
                "text": "I have seen that i was good",
                "role": 0
            },
            {
                "text": "Since you like movies like Pretty Woman (1990), you may like [Notting Hill] and Bridget Jones's Diary (2001) similar movies.[Notting Hill] is a romantic comedy film released in 1999, directed by Roger Michell and written by Richard Curtis. Bridget Jones's Diary (2001) is a romantic comedy film released in 2001, directed by Sharon Maguire and based on the novel of the same name by Helen Fielding.I suggest you try these two films, you will be satisfied.",
                "movies": [
                    "[Notting Hill]"
                ],
                "knowledge": [
                    {
                        "wiki": "Notting Hill is a 1999 romantic comedy film directed by Roger Michell. The screenplay was written by Richard Curtis, and the film was produced by Duncan Kenworthy. It stars Julia Roberts and Hugh Grant, with Rhys Ifans, Emma Chambers, Tim McInnerny, Gina McKee, and Hugh Bonneville in supporting roles. The story is of a romance between a London bookseller (Grant) and a famous American actress (Roberts) who happens to walk into his shop.\r\nReleased on 21 May 1999, Notting Hill was well-received by critics and became the highest-grossing British film of all time. It was nominated for the Golden Globe Award for Best Motion Picture – Musical or Comedy, with Roberts and Grant also receiving nominations for their performances. It also earned two BAFTA nominations, and won a British Comedy Award and a Brit Award for its soundtrack.",
                        "plot": "The life of a simple bookshop owner changes when he meets the most famous film star in the world.",
                        "review": "I'm not a fan of either Hugh Grant or Julia Roberts. So why did I watch this film in the first place? I guess I'm always looking for the best in everyone. What a surprise. I was not disappointed. Hugh Grant's jittery, bumbling charm has never been more endearing. The vulnerability Grant infuses into his character is definitely his best quality, and it's perfectly understandable that he might decline the opportunity to date a megastar actress out of trepidation.Julia Roberts' legions of fans will not be let down by her character. It's dead-on Julia. But those who are not among her fans will be slowly but surely won over by the honesty and directness of the character. I don't care what your testosterone quotient is, there won't be a dry eye in the house when she almost whispers, nervous smile masking the hurt, that she's \"just a girl, standing in front of a boy, asking him to love her.\"The story is by the writer of Four Weddings and a Funeral and Bridget Jones' Diary, so it's a sure bet from the start. But Grant and Roberts take what might have been a slightly weak treatment and make it sparkle. I get so sick of everyone who pooh-pooh's a happy ending because it's somehow so unbelievable that things ever work out right. Instead we demand tear jerker disappointment at every turn and end up with Kevin Costner drowning like a sacrificial lamb at the end of Message in a Bottle to satisfy our lust for tragedy. I love it when things work out well in my life, and sometimes I like to see films about things working out. If a bookstore owner in London can actually end up with the top actress in Hollywood, then maybe I'll get that promotion, or that beautiful new associate might actually talk to me. Is that so bad?",
                        "movieid": "tt0125439"
                    }
                ],
                "role": 1,
                "rewrite": 1,
                "reason": "Since you like movies like Pretty Woman (1990), you may like [Notting Hill] and Bridget Jones's Diary (2001) similar movies.",
                "description": "[Notting Hill] is a romantic comedy film released in 1999, directed by Roger Michell and written by Richard Curtis. Bridget Jones's Diary (2001) is a romantic comedy film released in 2001, directed by Sharon Maguire and based on the novel of the same name by Helen Fielding.",
                "encourage": "I suggest you try these two films, you will be satisfied."
            },
            {
                "text": "I have seen that one too lol also good",
                "role": 0
            },
            {
                "text": "I talked to someone who liked rom-coms",
                "movies": [],
                "knowledge": [],
                "role": 1,
                "rewrite": 0,
                "reason": "",
                "description": "",
                "encourage": ""
            },
            {
                "text": "They liked classics.",
                "movies": [],
                "knowledge": [],
                "role": 1,
                "rewrite": 0,
                "reason": "",
                "description": "",
                "encourage": ""
            },
            {
                "text": "How about something like [Save the Last Dance (2001)]",
                "role": 0
            },
            {
                "text": "Oh ok great",
                "role": 0
            },
            {
                "text": "As you want a movie like Pretty Woman (1990)，what about [Dirty Dancing]?Spending the summer at a Catskills resort with her family,Frances\"Baby\"Houseman falls in love with the camp''s dance instructor Johnny Castle.Hope you can like it.",
                "movies": [
                    "[Dirty Dancing]"
                ],
                "knowledge": [
                    {
                        "wiki": "Dirty Dancing is a 1987 American romantic drama dance film written by Eleanor Bergstein, produced by Linda Gottlieb, and directed by Emile Ardolino. Starring Patrick Swayze and Jennifer Grey, it tells the story of Frances \"Baby\" Houseman, a young woman who falls in love with dance instructor Johnny Castle (Swayze) at a vacation resort.\r\nThe film was based on screenwriter Bergstein's own childhood. She originally wrote a screenplay for the Michael Douglas film It's My Turn, but ultimately ended up conceiving a story for a film which became Dirty Dancing. She finished the script in 1985, but management changes at Metro-Goldwyn-Mayer put the film in development hell. The production company was changed to Vestron Pictures with Emile Ardolino as director and Linda Gottlieb as producer. Filming took place in Lake Lure, North Carolina, and Mountain Lake, Virginia, with the film's score composed by John Morris and dance choreography by Kenny Ortega.\r\nDirty Dancing premiered at the 1987 Cannes Film Festival on May 12, 1987, and was released on August 21, 1987, in the United States, earning over $214 million worldwide, and was the first film to sell more than a million copies for home video. It earned positive reviews from critics, who particularly praised the performances of Grey and Swayze, and its soundtrack, created by Jimmy Ienner, generated two multi-platinum albums and multiple singles. \"(I've Had) The Time of My Life\", performed by Bill Medley and Jennifer Warnes, won the Academy Award for Best Original Song, the Golden Globe Award for Best Original Song, and the Grammy Award for Best Pop Performance by a Duo or Group with Vocals.\r\nThe film's popularity led to a 2004 prequel, Dirty Dancing: Havana Nights, and a stage version which has had sellout performances in Australia, Europe, and North America. A made-for-TV remake was also released in 2017. A sequel is scheduled to be released in 2024, with Grey reprising her role.",
                        "plot": "Spending the summer at a Catskills resort with her family, Frances \"Baby\" Houseman falls in love with the camp's dance instructor, Johnny Castle.",
                        "review": "Dirty Dancing follows the story of Frances 'Baby' Houseman (Jennifer Grey)and her family as they spend the summer at Kellerman's Family Summer Camp. We get to see her discover herself as she falls in love with the dance instructor, Johnny Castle (Patrick Swayze).The movie is full of wonderful dancing (hence the title!) some great music, and terrific scenery. It handles some tough issues with dignity and grace, and, of course, has (shocking spoiler here!) a happy, wonderful, feel good ending! You know how it's going to end from the beginning, but that's really not the point here. The point is the journey, a journey that touches every member of the family.It's one of the movies I need to see whenever it comes on TV...never mind the fact that I already have it memorized!",
                        "movieid": "tt0092890"
                    }
                ],
                "role": 1,
                "rewrite": 1,
                "reason": "As you want a movie like Pretty Woman (1990)，what about [Dirty Dancing]?",
                "description": "Spending the summer at a Catskills resort with her family,Frances\"Baby\"Houseman falls in love with the camp''s dance instructor Johnny Castle.",
                "encourage": "Hope you can like it."
            },
            {
                "text": "ooooh yes that was an all time favorit",
                "role": 0
            },
            {
                "text": "favorite",
                "role": 0
            },
            {
                "text": "well thank you for the suggestions I will just throw in [Titanic (2012)]",
                "role": 0
            },
            {
                "text": "A great one!",
                "movies": [],
                "knowledge": [],
                "role": 1,
                "rewrite": 0,
                "reason": "",
                "description": "",
                "encourage": ""
            }
        ],
        "conversationId": "17177"
    }
```

