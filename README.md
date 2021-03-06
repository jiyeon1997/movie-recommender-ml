# movie-recommender-ml


It is a system that recommends movies to users by using Kaggle movie dataset.

### Preview

<img src="https://t1.daumcdn.net/cfile/tistory/9921884C5C6E6E861A">

### Algorithm

+ [TF-IDF](https://ko.wikipedia.org/wiki/Tf-idf) 
+ [cosine similarity](https://ko.wikipedia.org/wiki/%EC%BD%94%EC%82%AC%EC%9D%B8_%EC%9C%A0%EC%82%AC%EB%8F%84)


### Flowchart

1. Vectorize the overview of the movie using tf-idf.
2. The user selects a movie.
3. Obtain the similarity of selected movies and all documents using the cosine similarity.
4. Sort the similarities in descending order.
5. Extract only 10 of the sorted values.
6. Output the extracted data.

### Author

+ Ji Yeon, Cheon 

+ email : somos3993@gmail.com

+ Let me know what features you'd like to add or error.

+ Thank you!
