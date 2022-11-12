# Hack2Educate-GenZ

# Team GenZ

### The Team Members of GenZ are:
    - Harsh Raj
    - Raj Vardhan Tomar
    - Arpita Kesharwani
    - Rahul Kumar Mishra
## We are working on an AI/ML theme.
    - We will be given a Youtube video and then our tasks are following :-
    - Determine if it is an educational video or not.
    - Determine which category or subcategory of BE it would belong to.
    - Accuracy: 90%+ on a custom dataset that will be provided after proof of concept.
    - Should be able to run in near-real-time on a server.
## Problem solving approach:-
    -Used Natural Language Programming to solve this problem
    -First step was to create a dataset of educational and non-educational words, for that description
    and title of several YouTube videos from different channels were extracted and punctuations, emoji
    and links were removed and then remaining keywords were classified into the categories mentioned
    above.
    -Now to check whether the video is educational or not, the video is first imported and then its title
    and description is extracted. Further punctuations, emoji, links and non-educational words are
    removed and from the remaining words it is checked that how many words are educational and
    percentage of educational word is calculated using the dataset. If the percentage is above certain
    number then the video is declared to be non-educational.
## Final demo
    -The final outcome of the project is a website where link of any YouTube video can be pasted and a
    result will be displayed on the page to show if the video is educational or not.
## Index
    - Project 1
        - To learn how to use Application Programming Interface (API) to extract some data of YouTube
        channels and videos.
        - To extract data from Educational, Entertainment, Technology and Motivational channels.
    - Creation of Dataset
        - Data was extracted from approximately 1.5 Lakh YouTube videos from 45 different
        channels.
        - Separation of educational and non-educational keyword was done so that it can be checked if the video is educational or not.
    - Algorithm
        1. To classifying the video as educational or non-educational.
            - We extracted the title and description of a YouTube video using its link.
            - Removed the punctuations, links and emojis from the extracted data.
            - Created a dictionary of keywords by splitting the data word by word.
            - Removed all the non-educational keywords from the video's keywords.
            - Compared the remaining keywords from our educational keyword dataset and using the algorithm it is calculated that what is the percentage of the video to be educational.
            - And if the percentage calculated is above certain number then the video is declared to be educational.
        2. To predict from which category or subcategory of Beyond Exams the video belongs.
            - Defined a list of keywords for each of the subcategory
            - Used the same procedure as first algorithm to check which subcategory of BE the video may belongs to.