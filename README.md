# U.S.A-Presidential-Speech-Analysis
Text Analytics project using Python's NLTK library.

## Problem Statement:

In this particular project, we are going to work on the inaugural corpora from the nltk in Python. 
We will be looking at the following speeches of the Presidents of the United States of America:

* President Franklin D. Roosevelt in 1941
* President John F. Kennedy in 1961
* President Richard Nixon in 1973

Code Snippet to extract the three speeches:

        
        import nltk
        nltk.download('inaugural')
        from nltk.corpus import inaugural
        inaugural.fileids()
        inaugural.raw('1941-Roosevelt.txt')
        inaugural.raw('1961-Kennedy.txt')
        inaugural.raw('1973-Nixon.txt')

## Steps involved:
### 1. Finding the number of characters, words and sentences for the mentioned documents.
#### a) Roosevelt speech:
<img width="501" alt="Screenshot 2024-01-01 at 8 16 24 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/5294517c-6285-41aa-bd1a-d85458ce93eb">

#### b) Kennedy speech:
<img width="501" alt="Screenshot 2024-01-01 at 8 16 44 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/a8fb87cd-0f8b-4483-b6ef-bbb781f52740">

#### c) Nixon speech:
<img width="501" alt="Screenshot 2024-01-01 at 8 17 00 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/8aa9e768-7ceb-413f-a91e-e7c57d2f4243">

### 2. Removing all the stopwords from the three speeches & showing the word count before and after the removal of stopwords.
#### a) Roosevelt speech:
<img width="590" alt="Screenshot 2024-01-01 at 8 17 24 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/a8e004cf-f7d4-4dd6-9c23-9dbf418217a4">

#### A sample sentence after removal of stop-words :
<img width="508" alt="Screenshot 2024-01-01 at 8 17 50 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/b8c977ff-e8bb-44ce-9c3b-b48e51c525ac">

#### b) Kennedy speech:
<img width="588" alt="Screenshot 2024-01-01 at 8 19 57 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/24e81e46-8e9c-42f0-ace6-791b8ab348b9">

#### A sample sentence after removal of stop-words :
<img width="588" alt="Screenshot 2024-01-01 at 8 19 03 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/7ea74fcb-c8aa-4ac8-8dc6-b719293a8979">

#### c) Nixon speech:
<img width="588" alt="Screenshot 2024-01-01 at 8 19 39 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/64f8d282-a450-4a34-9633-657ae458030f">

#### A sample sentence after removal of stop-words :
<img width="588" alt="Screenshot 2024-01-01 at 8 19 21 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/b5c5a40e-f305-4fe0-ad0b-042a68c8c41c">

### 3. Most frequently used words in the inaugural address for each president (after removing the stopwords)
#### a) Roosevelt speech:
<img width="588" alt="Screenshot 2024-01-01 at 8 20 29 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/d2f692b5-9435-465f-88b5-8033ba8ad1dd">

• The word that occurs the most number of times in the 1941 inaugural address for
president Roosvelt is "nation".

• While the top three words based on frequency of repitition were 'nation': 17 times,
'know': 10 times and 'peopl': 9 times.

• Here we should also note that the words 'spirit': 9 times, 'life': 9 times, 'democraci': 9
times and 'becaus': 9 times were repeated the same 9 number of times as the word
'peopl'. But only top three words were asked so we could not fit these words.

• As 'peopl' was the word which came first on the list among the words having
frequency as 9, it was included in the top three words. But in real sense any of these
words can replace the word 'peopl' among the top three words.

#### b) Kennedy speech:
<img width="588" alt="Screenshot 2024-01-01 at 8 20 50 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/62957f91-2b22-4227-9b17-1c70766618e0">

• The word that occurs the most number of times in the 1961 inaugural address for
president Kennedy is "let".

• While the top three words based on frequency of repetition were 'let': 16 times, 'us':
12 times and 'power': 9 times.

#### c) Nixon speech:
<img width="588" alt="Screenshot 2024-01-01 at 8 21 06 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/4e966f56-5d4b-4e43-89a7-cad79de2d560">

• The word that occurs the most number of times in the 1973 inaugural address for
president Nixon is "us".

• While the top three words based on frequency of repitition were 'us': 26 times, 'let':
22 times and 'america': 21 times.

### 4. Plotting the word cloud for each of the three speeches (after removal of stopwords).

#### a) Roosevelt speech:
<img width="585" alt="Screenshot 2024-01-01 at 8 21 53 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/cf5319d4-b460-48af-a7d9-998313e735e5">


#### b) Kennedy speech:
<img width="585" alt="Screenshot 2024-01-01 at 8 22 24 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/8938169d-2498-437a-87ba-7f88b8627380">

#### c) Nixon speech:
<img width="585" alt="Screenshot 2024-01-01 at 8 23 12 PM" src="https://github.com/VivekSagarSingh/U.S.A-Presidential-Speech-Analysis/assets/153344691/fc43ae42-4fad-415a-acac-471be4a7d8e4">

